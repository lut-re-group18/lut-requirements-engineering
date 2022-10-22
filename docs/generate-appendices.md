# Generating deliverables from GitHub

Generating list of requirements, pull requests etc. from projects GitHub repository is described in this document.

> For more information (How and What) about GitHub Cli please see the official documentation at [https://cli.github.com](https://cli.github.com).

---

- [Generating deliverables from GitHub](#generating-deliverables-from-github)
  - [Process information](#process-information)
  - [Howto to generate deliverables](#howto-to-generate-deliverables)
    - [Requirements](#requirements)
      - [CSV to Markdown table](#csv-to-markdown-table)
      - [Update requirements table](#update-requirements-table)
    - [Pull Requests](#pull-requests)
      - [CSV to Markdown table](#csv-to-markdown-table-1)
      - [Update traceability table](#update-traceability-table)

---

## Process information

Generating the deliverables could be done using GitHub Actions and generated automatically as changes are detected in the repository. Dynamic listing of GitHub Project issues and Pull Requests is seen valueable for the project. How ever these listed items (issues, pull requests) are needed as appendices to the project deliverables. The deliverables are generated using GitHub Cli and the generated files are stored in the repository.

---
## Howto to generate deliverables

How to generate Requirements and Pull Requests from GitHub repository into Markdown files and store them in the repository.

### Requirements
Create ; delimited file with the following columns:

> Be at the local repo directory you want to extract issues from

```bash
❯ gh issue list --limit 1000 --state all | tr '\t' ';' > temp-all-reqs.csv
# Not needed but you could get the issues by a specific label
❯ gh issue list --limit 1000 --state all --label Functional | tr '\t' ';' > functional.csv
❯ gh issue list --limit 1000 --state all --label Non-functional | tr '\t' ';' > non-functional.csv
❯ gh issue list --limit 1000 --state all --label ASR | tr '\t' ';' > asr.csv
```

#### CSV to Markdown table

[Header](../req-header.csv) and all issues files are merged to one file used to create the markdown table.

```bash
cat req-header.csv temp-all-reqs.csv > all-reqs.csv
```

Use [https://www.tablesgenerator.com/markdown_tables](https://www.tablesgenerator.com/markdown_tables) to generate markdown table from `all-reqs.csv` file.

> You might want to remove the last timestamp column from the table since it is not needed in the requirements.md file.

#### Update requirements table

After generating the markdown table, copy the table to the `docs/requirements.md` file.

### Pull Requests

Traceability table is generated from [GitHub Pull Requests](https://github.com/lut-re-group18/lut-requirements-engineering/pulls?q=is%3Apr) containing all the commits to the repository. 

The table is generated using the following command:

```bash
❯ gh pr list --limit 1000 --state all --search "is:merged" | tr '\t' ';' > temp-all-prs.csv
```

#### CSV to Markdown table

[Header](../pr-header.csv) and all issues files are merged to one file used to create the markdown table.

```bash
cat pr-header.csv temp-all-prs.csv > all-prs.csv
```

Use [https://www.tablesgenerator.com/markdown_tables](https://www.tablesgenerator.com/markdown_tables) to generate markdown table from `all-prs.csv` file.

#### Update traceability table

After generating the markdown table, copy the table to the `docs/traceability.md` file.


---

[Back to main documentation](../README.md)