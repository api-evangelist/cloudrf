# CloudRF (cloudrf)

CloudRF is a radio frequency (RF) propagation, coverage modeling, and wireless network planning service. The HTTPS REST API at `api.cloudrf.com` covers point-to-multipoint coverage heatmaps, point-to-point path analysis, mesh networks, multisite, HF point-to-multipoint and point-to-point analysis, 3D coverage, satellite modeling, interference detection, geo-location of signals, archive and export of calculations, clutter and noise data management, account metrics, and reusable templates. Authentication is by API key passed as the `key` HTTP header.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudrf/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Company:** CloudRF (Farrant Consulting Ltd.)
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Coverage Modeling, HF Propagation, Mesh Network, Radio Frequency, RF, Satellite, Signal Analysis, Telecommunications, Wireless Planning

## APIs

### CloudRF API
Public REST API for RF propagation, coverage modeling, mesh and multisite analysis, HF analysis, 3D and satellite modeling, interference detection, signal geo-location, archive/export, clutter and noise data, and reusable templates. Authentication is via the `key` HTTP header.

- [Developer Documentation](https://cloudrf.com/documentation/developer/)
- [Swagger UI](https://cloudrf.com/documentation/developer/swagger-ui/)
- [OpenAPI](openapi/cloudrf-openapi.yml)
- [Code Samples](https://github.com/Cloud-RF/CloudRF-API-clients)

### Operations Summary
- **Create:** `/area`, `/path`, `/points`, `/multilink`, `/multisite`, `/hf`, `/hf-path`
- **Analyse:** `/best-site`, `/best-server`, `/merge`, `/interference`, `/locate`
- **3D:** `/3d`, `/3d-upload`
- **Manage:** `/archive`, `/archive/delete`, `/network/delete`, `/export`, `/clutter`, `/clutter/delete`, `/noise`, `/noise-average`, `/noise/map`, `/noise/delete`
- **Account:** `/account/metrics`
- **Template:** `/template` (GET/POST)
- **Satellite:** `/satellite`

## Common Properties

- [Website](https://cloudrf.com/)
- [Documentation](https://cloudrf.com/documentation/)
- [Developer Documentation](https://cloudrf.com/documentation/developer/)
- [API Reference (Swagger UI)](https://cloudrf.com/documentation/developer/swagger-ui/)
- [Code Samples](https://github.com/Cloud-RF/CloudRF-API-clients)
- [OpenAPI](openapi/cloudrf-openapi.yml)
- [JSON-LD](json-ld/cloudrf-context.jsonld)
- [Spectral](rules/cloudrf-rules.yml)
- [Naftiko Capabilities](capabilities/cloudrf-capabilities.yml)

## Maintainers

- **FN:** Kin Lane
- **Email:** kinlane@gmail.com
