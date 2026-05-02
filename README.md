# RTX Corporation

RTX Corporation is a leading American aerospace and defense company comprising Collins Aerospace, Pratt & Whitney, and Raytheon. Raytheon develops the EAGLE (Enhanced Automated Graphical Logistics Environment) platform for integrated logistics support analysis across defense programs.

**Human URL:** https://www.rtx.com/

## APIs

| API | Description |
|-----|-------------|
| [RTX EAGLE API](openapi/rtx-eagle-api-openapi.yml) | Logistics support analysis platform for defense program lifecycle management |

## OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [rtx-eagle-api-openapi.yml](openapi/rtx-eagle-api-openapi.yml) | EAGLE API covering data sources, analytics jobs, and intelligence reports |

## Rules

| Ruleset | Description |
|---------|-------------|
| [rtx-spectral-rules.yml](rules/rtx-spectral-rules.yml) | Spectral ruleset enforcing RTX API design conventions |

## Capabilities

### Workflow Capabilities

| Capability | Description |
|------------|-------------|
| [logistics-intelligence.yaml](capabilities/logistics-intelligence.yaml) | Defense logistics intelligence workflows for EAGLE platform |

### Shared Definitions

| Shared | Description |
|--------|-------------|
| [eagle-api.yaml](capabilities/shared/eagle-api.yaml) | Per-API consumed definition for the RTX EAGLE API |

## Schemas

| Schema | Description |
|--------|-------------|
| [rtx-data-source-schema.json](json-schema/rtx-data-source-schema.json) | JSON Schema for EAGLE data source records |

## Structures

| Structure | Description |
|-----------|-------------|
| [rtx-eagle-structure.json](json-structure/rtx-eagle-structure.json) | JSON structure documentation for EAGLE data entities |

## JSON-LD

| Context | Description |
|---------|-------------|
| [rtx-context.jsonld](json-ld/rtx-context.jsonld) | JSON-LD context mapping EAGLE vocabulary to schema.org |

## Examples

| Example | Description |
|---------|-------------|
| [rtx-list-data-sources-example.json](examples/rtx-list-data-sources-example.json) | List intelligence data sources from the EAGLE platform |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [rtx-vocabulary.yml](vocabulary/rtx-vocabulary.yml) | Domain vocabulary for RTX EAGLE logistics and defense concepts |

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
