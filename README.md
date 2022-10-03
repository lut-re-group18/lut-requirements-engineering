# lut-requirements-engineering
Repository foor school project in requirements engineering

## Documents

- [Requirements Management Plan](requirements-management-plan.md)
- [Vision & Scope](vision-and-scope.md)
- [Home of this project](README.md)


## How to contribute


## Testing md to pdf conversion

You need Docker installed on your machine. Then run the following command:

```bash
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/latex:2.19 --output=result.pdf \
       "/data/docs/requirements-management-plan.md"
```