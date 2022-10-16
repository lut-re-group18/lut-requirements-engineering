# How to extract issues using GitHub Cli (gh)

Check out gh from their site: [https://cli.github.com](https://cli.github.com)


Lets create ; delimited file with the following columns:

```bash
❯ gh issue list --limit 1000 --state all | tr '\t' ';' > All_issues.csv
❯ gh issue list --limit 1000 --state all --label Functional | tr '\t' ';' > functional.csv
❯ gh issue list --limit 1000 --state all --label Non-functional | tr '\t' ';' > non-functional.csv
❯ gh issue list --limit 1000 --state all --label ASR | tr '\t' ';' > asr.csv
```