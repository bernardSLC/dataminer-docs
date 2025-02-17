---
uid: GetServicesForFilter
---

# GetServicesForFilter

Use this method to retrieve the services matching a specific property filter. Available from DataMiner 10.0.12 onwards.

## Input

| Item | Format | Description |
|--|--|--|
| Connection | String | The connection ID. See [ConnectApp](xref:ConnectApp). |
| GenericFilter.PropertyFilters | Array of [DMAPropertyFilter](xref:DMAPropertyFilter) | The property filters. |

## Output

| Item | Format | Description |
|--|--|--|
| GetServicesForFilter­Result | Array of [DMAElement](xref:DMAElement) | The services matching the property filter. |
