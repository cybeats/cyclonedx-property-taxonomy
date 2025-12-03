# CyBeats CycloneDX Property Taxonomy
---

# `cybeats` Namespace Taxonomy

This is the namespace for official CyBeats sub-namespaces and properties.
Unofficial sub-namespaces and names MUST NOT be used under the `cybeats` top-level namespace.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC2119](http://www.ietf.org/rfc/rfc2119.txt).

For more information about CycloneDX property taxonomies, see [CycloneDX documentation](https://github.com/CycloneDX/cyclonedx-property-taxonomy).

----

## `cybeats` Namespace Taxonomy
| Namespace                      | Description                                                                                                                                                                                                            |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **`cybeats:quality_analysis`** | Namespace for properties associated with the SBOM quality. An SBOM SHOULD have valid data, SHOULD have the correct structure and SHOULD contain enough information to be ingested by software like CyBeats SBOM Studio |


## `cybeats:quality_analysis` Namespace Taxonomy

| Property                             | Description                                                                              |
| ------------------------------------ | ---------------------------------------------------------------------------------------- |
| **`cybeats:quality_analysis:score`** | A percentage representing the quality score of the SBOM. From 0 to 100. Higher is better |
| **`cybeats:quality_analysis:grade`** | A grade A to D representing the quality                                                  |

## `cybeats:maintenance` Namespace Taxonomy

| Property                             | Description                                                                              |
| ------------------------------------ | ---------------------------------------------------------------------------------------- |
| **`cybeats:maintenance:status`** | Maintenance status of the component. Possible values are `maintained`, `not-maintained`, `abandoned` and `unknown` |

© Copyright 2025 CyBeats
