# Requirements Engineering (Group18)

> This is the repository for school project of Group18 in Requirement Engineering course [@LUT](https://www.lut.fi).

## Documents

- [Requirements Management Plan](docs/requirements-management-plan.md)
- [Vision & Scope](docs/vision-and-scope.md)
- [Use Case Docs](docs/use-cases.md)
- [GitHub Repository of the Project](https://github.com/lut-re-group18/lut-requirements-engineering)


## How to contribute

How can I contribute to this project?

- [Open issues](https://github.com/lut-re-group18/lut-requirements-engineering/issues) to notify of errors in project, propose new features, or other improvements.
- Fork the project, make changes, and submit a pull request!
  - *This is the way.*

### Links to GitHub repositgory and the GitHub Pages

- [GitHub Repository of the Project](https://github.com/lut-re-group18/lut-requirements-engineering/)
- [GitHub Pages](https://lut-re-group18.github.io/lut-requirements-engineering/)
### Test MD to PDF conversion (localy)

You need Docker installed on your machine. Then run the following command:

```bash
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/latex:2.19 --output=result.pdf \
       "/data/docs/requirements-management-plan.md"
```