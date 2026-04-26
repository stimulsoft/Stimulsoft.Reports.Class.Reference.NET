---
title: "StiMsAccessConnector Class"
---

## StiMsAccessConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiOleDbConnector](StiOleDbConnector.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiMsAccessConnector](StiMsAccessConnector.md) |  |
| **GetDbType** | Type | Returns the type of the DBType. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **StiMsAccessConnector** | internal |  |

---

### Method Details

#### Get `static`

**Get**(**connectionString**: string): [StiMsAccessConnector](StiMsAccessConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiMsAccessConnector](StiMsAccessConnector.md)


---

#### GetDbType

**GetDbType**(): Type

Returns the type of the DBType.

**Returns** Type


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

Returns sample of the connection string to this connector.

**Returns** string


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### StiMsAccessConnector

**StiMsAccessConnector**(**connectionString**: string): internal

**Parameters**

- **connectionString** (string)  

**Returns** internal

