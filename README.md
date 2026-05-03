# TravelCenters of America

TravelCenters of America is the largest publicly traded full-service travel center network in the United States, operating under the TA, Petro Stopping Centers, and TA Express brands. The company provides REST APIs for truck service work order management, retail location data, fuel codes, pricing, parking availability, and shower availability.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Travel Centers, Truck Service, Retail, Fuel, Locations, Trucking, Fleet Management

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### TravelCenters of America API
REST APIs for TA and Petro travel center operations including truck service, location data, fuel codes, pricing, parking, and shower availability.

**Human URL:** [https://developer.accessta.com/](https://developer.accessta.com/)

**Base URL:** `https://api.accessta.com/v1`

#### Tags

Travel Centers, Truck Service, Retail, Fuel, Locations, Trucking, Fleet Management

#### Properties

- [Documentation](https://developer.accessta.com/)
- [OpenAPI](openapi/travelcenters-of-america-openapi.yml)
- [JSON Schema - Location](json-schema/travelcenters-of-america-location-schema.json)
- [JSON Structure](json-structure/travelcenters-of-america-location-structure.json)
- [JSON-LD Context](json-ld/travelcenters-of-america-context.jsonld)
- [Spectral Rules](rules/travelcenters-of-america-rules.yml)
- [Naftiko Capabilities](capabilities/fleet-and-driver-services.yaml)
- [Vocabulary](vocabulary/travelcenters-of-america-vocabulary.yml)
- [Sign Up](https://services.accessta.com/APIRequest/DevApiRequest)
- [Mobile App](https://apps.apple.com/us/app/trucksmart/id420579235)

## Services

| Service | Description |
|---|---|
| Location and Amenities | Search travel centers by location with full amenity details |
| Parking Availability | Real-time truck parking space counts |
| Shower Availability | Shower facility availability and wait times |
| Work Order Management | Truck service work order creation and tracking |
| Document Search | Service records, invoices, and maintenance documentation |
| Fuel Codes | Fleet fuel authorization codes |
| Fuel Pricing | Live diesel, gasoline, and DEF pricing |

## OpenAPI Specifications

| API | File |
|---|---|
| TravelCenters of America API | [openapi/travelcenters-of-america-openapi.yml](openapi/travelcenters-of-america-openapi.yml) |

## Capabilities

### Workflow Capabilities

| Workflow | Description |
|---|---|
| [Fleet and Driver Services](capabilities/fleet-and-driver-services.yaml) | Location discovery, parking, showers, fuel pricing, work orders, and fuel codes for fleet operators and drivers |

### Shared Definitions

| API | File |
|---|---|
| [TravelCenters of America](capabilities/shared/travelcenters-of-america.yaml) | Core TA API consumed definitions |

## Examples

| Example | Description |
|---|---|
| [List Locations](examples/travelcenters-of-america-list-locations-example.json) | Find travel centers near a location |
| [Get Parking Availability](examples/travelcenters-of-america-get-parking-availability-example.json) | Check truck parking at a location |

## Rules

| Ruleset | Description |
|---|---|
| [travelcenters-of-america-rules.yml](rules/travelcenters-of-america-rules.yml) | Spectral ruleset for TA API conventions |

## JSON Schemas

| Schema | Description |
|---|---|
| [travelcenters-of-america-location-schema.json](json-schema/travelcenters-of-america-location-schema.json) | Travel center location |

## JSON Structures

| Structure | Description |
|---|---|
| [travelcenters-of-america-location-structure.json](json-structure/travelcenters-of-america-location-structure.json) | Location fields |

## JSON-LD

| Context | Description |
|---|---|
| [travelcenters-of-america-context.jsonld](json-ld/travelcenters-of-america-context.jsonld) | Linked data context for travel center data |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [travelcenters-of-america-vocabulary.yml](vocabulary/travelcenters-of-america-vocabulary.yml) | Travel center and trucking domain vocabulary |

## Common Properties

- [Website](https://www.ta-petro.com/)
- [Documentation](https://developer.accessta.com/)
- [Developers](https://www.ta-petro.com/developers/)
- [Sign Up](https://services.accessta.com/APIRequest/DevApiRequest)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
