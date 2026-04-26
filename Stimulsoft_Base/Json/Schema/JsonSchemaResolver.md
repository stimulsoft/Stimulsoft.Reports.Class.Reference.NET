---
title: "JsonSchemaResolver Class"
---

## JsonSchemaResolver Class

**Namespace:** `Stimulsoft.Base.Json.Schema`

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonSchemaResolver**() | Initializes a new instance of the JsonSchemaResolver class. |

**JsonSchemaResolver**()

Initializes a new instance of the JsonSchemaResolver class.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LoadedSchemas** | IList<[JsonSchema](JsonSchema.md)> | Gets or sets the loaded schemas. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetSchema** | [JsonSchema](JsonSchema.md) | Gets a JsonSchema for the specified reference. |

---

### Method Details

#### GetSchema

**GetSchema**(**reference**: string): [JsonSchema](JsonSchema.md)

Gets a JsonSchema for the specified reference.

**Parameters**

- **reference** (string) — The id.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema for the specified reference.

