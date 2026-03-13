# Google Knowledge Graph Search API

The Google Knowledge Graph Search API allows developers to search for entities (people, places, things) in the Google Knowledge Graph and retrieve structured data about them in JSON-LD format conforming to schema.org standards.

## APIs

- **Google Knowledge Graph Search API** - Search for entities and retrieve structured data from the Knowledge Graph.

## Base URL

```
https://kgsearch.googleapis.com/v1
```

## Key Endpoints

- **Search Entities** - `GET /entities:search` - Search for entities matching query, type, or ID constraints

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/Entity.json) - JSON Schema (draft 2020-12) for Entity
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://developers.google.com/knowledge-graph/how-tos/search-widget)
- [API Reference](https://developers.google.com/knowledge-graph/reference/rest/v1)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
