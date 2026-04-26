---
title: "StiDataConnector Class"
---

## StiDataConnector Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AdvancedRetrievalModeOfDatabaseSchema** `static` | bool | If true then database information will be required from database with help of DataAdapter (instead Connection.GetSchema). |
| **ConnectionIdent** | [StiConnectionIdent](StiConnectionIdent.md) | Gets a type of the connector. |
| **ConnectionOrder** | [StiConnectionOrder](../../Stimulsoft_Report/Dictionary/StiConnectionOrder.md) | Gets an order of the connector. |
| **GetSchemaColumnsMode** `static` | bool | If true then in GetSchema method, column reference by index else by name. |
| **IsAvailable** | bool | Get a value which indicates that this data connector can be used now. |
| **Name** | string | The name of this connector. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetFamilyConnectors** | [StiDataConnector](StiDataConnector.md)[] | Return an array of the data connectors which can be used also to access data for this type of the connector. |
| **ResetSettings** | void |  |

---

### Method Details

#### GetFamilyConnectors

**GetFamilyConnectors**(): [StiDataConnector](StiDataConnector.md)[]

Return an array of the data connectors which can be used also to access data for this type of the connector.

**Returns** [StiDataConnector](StiDataConnector.md)[]


---

#### ResetSettings

**ResetSettings**(): void

