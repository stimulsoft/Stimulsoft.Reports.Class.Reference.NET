---
title: "JsonSchemaGenerator Class"
---

## JsonSchemaGenerator Class

**Namespace:** `Stimulsoft.Base.Json.Schema`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Schema** | [JsonSchema](JsonSchema.md) |  |
| **Type** | Type |  |
| **UndefinedSchemaIdHandling** | [UndefinedSchemaIdHandling](UndefinedSchemaIdHandling.md) | Gets or sets how undefined schemas are handled by the serializer. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Generate** *(+3 overloads)* | [JsonSchema](JsonSchema.md) | Generate a JsonSchema from the specified type. |

---

### Method Details

#### Generate

**Generate**(**type**: Type): [JsonSchema](JsonSchema.md)

Generate a JsonSchema from the specified type.

**Parameters**

- **type** (Type) — The type to generate a JsonSchema from.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema generated from the specified type.

---

**Generate**(**type**: Type, **resolver**: [JsonSchemaResolver](JsonSchemaResolver.md)): [JsonSchema](JsonSchema.md)

Generate a JsonSchema from the specified type.

**Parameters**

- **type** (Type) — The type to generate a JsonSchema from.  
- **resolver** ([JsonSchemaResolver](JsonSchemaResolver.md)) — The JsonSchemaResolver used to resolve schema references.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema generated from the specified type.

---

**Generate**(**type**: Type, **rootSchemaNullable**: bool): [JsonSchema](JsonSchema.md)

Generate a JsonSchema from the specified type.

**Parameters**

- **type** (Type) — The type to generate a JsonSchema from.  
- **rootSchemaNullable** (bool) — Specify whether the generated root JsonSchema will be nullable.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema generated from the specified type.

---

**Generate**(**type**: Type, **resolver**: [JsonSchemaResolver](JsonSchemaResolver.md), **rootSchemaNullable**: bool): [JsonSchema](JsonSchema.md)

Generate a JsonSchema from the specified type.

**Parameters**

- **type** (Type) — The type to generate a JsonSchema from.  
- **resolver** ([JsonSchemaResolver](JsonSchemaResolver.md)) — The JsonSchemaResolver used to resolve schema references.  
- **rootSchemaNullable** (bool) — Specify whether the generated root JsonSchema will be nullable.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema generated from the specified type.

