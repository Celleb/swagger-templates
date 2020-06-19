# swagger-templates

Swagger templates for swagger-codegen

Extended templates for swagger-codegen

## Getting started

Please clone or download to use the templates

In your project run

```bash
swagger-codegen generate -t templates-path/typescript-fetch --template-engine mustache -i swagger-file.json -l typescript-fetch -o src/api
```

## Updates

### typescript-fetch

- Alias support for `anyOf` and `oneOf`
