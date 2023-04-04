# Requirements

- Java 11+

# How to Use

```shell
git clone --recurse-submodules git@github.com:40CoderPlus/openai-java-sdk.git
```

Use [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) to generation client SDKs.

```shell
gradle clean
gradle openApiGenerate
gradle build -x test
```

# Specification

- [OpenAI API Docs](https://platform.openai.com/docs/api-reference)
- [OpenAI OpenAPI](openai-openapi/openapi.yaml)