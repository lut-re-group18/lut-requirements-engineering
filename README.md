# Requirements Engineering (Group18)

> This is the repository for school project of Group18 in Requirement Engineering course [@LUT](https://www.lut.fi).

## Documents

- [Requirements Management Plan](docs/requirements-management-plan.md)
- [Vision & Scope](docs/vision-and-scope.md)
- [Home of this project](README.md)


## How to contribute

How can I contribute to this project?

- [Open issues](https://github.com/joniturunen/lut-requirements-engineering/issues) to notify of errors in project, propose new features, or other improvements.
- Fork the project, make changes, and submit a pull request!
  - *This is the way.*

## Test MD to PDF conversion (localy)

You need Docker installed on your machine. Then run the following command:

```bash
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/latex:2.19 --output=result.pdf \
       "/data/docs/requirements-management-plan.md"
```