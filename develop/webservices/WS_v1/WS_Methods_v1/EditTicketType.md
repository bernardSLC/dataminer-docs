---
uid: EditTicketType
---

# EditTicketType

Use this method to edit a specific ticket type (called “domain” in the Ticketing app).

> [!NOTE]
> DataMiner Ticketing requires a Cassandra database as well as a specific license. From DataMiner 10.0.13 onwards, it also requires an Elasticsearch database. For more information on acquiring a Ticketing license, contact the Skyline Sales department.

## Input

| Item           | Format | Description                                          |
|----------------|--------|------------------------------------------------------|
| Connection     | String | The connection ID. See [ConnectApp](xref:ConnectApp). |
| TicketTypeID   | GUID   | The GUID of the ticket type.                         |
| TicketTypeName | String | The name of the ticket type.                         |

## Output

| Item                 | Format | Description                  |
|----------------------|--------|------------------------------|
| EditTicketTypeResult | GUID   | The GUID of the ticket type. |
