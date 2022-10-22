# Test MD to PDF conversion

You need Docker installed on your machine. Then run the following command:

```bash
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/latex:2.19 \
        -V geometry:"top=3cm, bottom=3cm, left=2.5cm, right=2.5cm" \
        --output=result.pdf \
        "/data/docs/requirements-management-plan.md"
```

---

Return to [main document](README.md).