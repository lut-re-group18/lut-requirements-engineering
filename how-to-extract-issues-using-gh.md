# How to extract issues using GitHub Cli (gh)

Check out gh from their site: [https://cli.github.com](https://cli.github.com)

---

## Info

All this could be done using GitHub Actions but since we do it once or twice for the assignment it is done locally. 

---
## Howto
Lets create ; delimited file with the following columns:

> Be at the local repo directory you want to extract issues from

```bash
❯ gh issue list --limit 1000 --state all | tr '\t' ';' > All_issues.csv
❯ gh issue list --limit 1000 --state all --label Functional | tr '\t' ';' > functional.csv
❯ gh issue list --limit 1000 --state all --label Non-functional | tr '\t' ';' > non-functional.csv
❯ gh issue list --limit 1000 --state all --label ASR | tr '\t' ';' > asr.csv
```

## Deliverables

Created CSV files ignored from git. Deliverables copied to Teams files.

For the heading a csv file is created with the following columns:

```csv
#;status;title;type;timestamp
```

## CSV to Markdown table

Header and all issues files are merged to one file used to create the markdown table.

```bash
cat header.csv All_issues.csv > temp-all.csv
```

Use [https://www.tablesgenerator.com/markdown_tables](https://www.tablesgenerator.com/markdown_tables) to generate markdown table from `temp-all.csv` file.

## Update deliverables in repo

After generating the markdown table, copy the table to the `docs/requirements.md` file.

> You might want to remove the last timestamp column from the table since it is not needed in the requirements.md file.