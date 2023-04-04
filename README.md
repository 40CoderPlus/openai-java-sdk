# Requirements

- Java 11+

# Build

Use [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) to generation client SDKs.

```shell
gradle clean
gradle openApiGenerate
gradle build -x test
```

# Specification

- [OpenAI API Docs](https://platform.openai.com/docs/api-reference)
- [OpenAI OpenAPI](openai-openapi/openapi.yaml)