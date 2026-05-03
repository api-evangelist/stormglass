# Stormglass (stormglass)
Stormglass provides a global marine and weather API delivering high-resolution forecasts, historical data, and environmental measurements for any coordinate on Earth. The platform aggregates data from multiple authoritative sources including NOAA, ECMWF, DWD, and others to provide weather point forecasts, marine data, tidal information, solar and astronomical data, biological oceanographic data, and elevation/bathymetry data.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Astronomy
- Bio
- Climate
- Elevation
- Forecasting
- Marine
- Ocean
- Solar
- Tides
- Weather
- Wind

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-02

## APIs

### Stormglass API
The Stormglass API provides global weather, marine, tidal, astronomical, solar, biological, and elevation data for any coordinate on Earth. It aggregates data from multiple meteorological and oceanographic sources into a single REST API.

**Human URL:** [https://stormglass.io/](https://stormglass.io/)
**Base URL:** https://api.stormglass.io/v2

#### Tags

- Astronomy, Bio, Elevation, Forecasting, Marine, Solar, Tides, Weather

#### Properties

- [Documentation](https://docs.stormglass.io/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/stormglass/refs/heads/main/openapi/stormglass-openapi.yml)
- [Pricing](https://stormglass.io/pricing)
- [Sign Up](https://stormglass.io/register)
- [Website](https://stormglass.io/)

## Artifacts

### OpenAPI Specs

| File | Description |
|---|---|
| [stormglass-openapi.yml](openapi/stormglass-openapi.yml) | Full Stormglass API v2 OpenAPI specification |

### Capabilities

| File | Description |
|---|---|
| [marine-weather.yaml](capabilities/marine-weather.yaml) | Unified marine and weather intelligence workflow |
| [shared/stormglass.yaml](capabilities/shared/stormglass.yaml) | Stormglass API shared capability definition |

### Rules

| File | Description |
|---|---|
| [stormglass-rules.yml](rules/stormglass-rules.yml) | Spectral ruleset enforcing Stormglass API conventions |

### JSON Schemas

| File | Description |
|---|---|
| [stormglass-weather-point-schema.json](json-schema/stormglass-weather-point-schema.json) | Weather point response schema |
| [stormglass-tide-extremes-schema.json](json-schema/stormglass-tide-extremes-schema.json) | Tide extremes response schema |

### JSON Structure

| File | Description |
|---|---|
| [stormglass-weather-point-structure.json](json-structure/stormglass-weather-point-structure.json) | Weather point response structure documentation |

### JSON-LD

| File | Description |
|---|---|
| [stormglass-context.jsonld](json-ld/stormglass-context.jsonld) | JSON-LD context mapping Stormglass vocabulary to schema.org |

### Examples

| File | Description |
|---|---|
| [stormglass-get-weather-point-example.json](examples/stormglass-get-weather-point-example.json) | Weather point request/response example |
| [stormglass-get-tide-extremes-example.json](examples/stormglass-get-tide-extremes-example.json) | Tide extremes request/response example |
| [stormglass-get-astronomy-point-example.json](examples/stormglass-get-astronomy-point-example.json) | Astronomy point request/response example |

### Vocabulary

| File | Description |
|---|---|
| [stormglass-vocabulary.yml](vocabulary/stormglass-vocabulary.yml) | Domain vocabulary for weather, marine, tidal, and astronomical concepts |

## Common Properties

- [Portal](https://stormglass.io/)
- [Documentation](https://docs.stormglass.io/)
- [Sign Up](https://stormglass.io/register)
- [Pricing](https://stormglass.io/pricing)
- [Website](https://stormglass.io/)
- [Blog](https://stormglass.io/blog)
- [Terms of Service](https://stormglass.io/terms-and-conditions/)
- [Privacy Policy](https://stormglass.io/privacy-policy/)
- [GitHub Org](https://github.com/stormglass)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
