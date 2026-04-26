---
title: "JsonSchema Class"
---

## JsonSchema Class

**Namespace:** `Stimulsoft.Base.Json.Schema`

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonSchema**() | Initializes a new instance of the JsonSchema class. |

**JsonSchema**()

Initializes a new instance of the JsonSchema class.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AdditionalItems** | [JsonSchema](JsonSchema.md) | Gets or sets the JsonSchema of additional items. |
| **AdditionalProperties** | [JsonSchema](JsonSchema.md) | Gets or sets the JsonSchema of additional properties. |
| **AllowAdditionalItems** | bool | Gets or sets a value indicating whether additional items are allowed. |
| **AllowAdditionalProperties** | bool | Gets or sets a value indicating whether additional properties are allowed. |
| **Default** | [JToken](../Linq/JToken.md) | Gets or sets the default value. |
| **Description** | string | Gets or sets the description of the object. |
| **Disallow** | JsonSchemaType? | Gets or sets disallowed types. |
| **DivisibleBy** | double? | Gets or sets a number that the value should be divisble by. |
| **Enum** | IList<[JToken](../Linq/JToken.md)> | Gets or sets the a collection of valid enum values allowed. |
| **ExclusiveMaximum** | bool? | Gets or sets a flag indicating whether the value can not equal the number defined by the "maximum" attribute. |
| **ExclusiveMinimum** | bool? | Gets or sets a flag indicating whether the value can not equal the number defined by the "minimum" attribute. |
| **Extends** | IList<[JsonSchema](JsonSchema.md)> | Gets or sets the collection of JsonSchema that this schema extends. |
| **Format** | string | Gets or sets the format. |
| **Hidden** | bool? | Gets or sets whether the object is visible to users. |
| **Id** | string | Gets or sets the id. |
| **Items** | IList<[JsonSchema](JsonSchema.md)> | Gets or sets the JsonSchema of items. |
| **Maximum** | double? | Gets or sets the maximum. |
| **MaximumItems** | int? | Gets or sets the maximum number of items. |
| **MaximumLength** | int? | Gets or sets the maximum length. |
| **Minimum** | double? | Gets or sets the minimum. |
| **MinimumItems** | int? | Gets or sets the minimum number of items. |
| **MinimumLength** | int? | Gets or sets the minimum length. |
| **Pattern** | string | Gets or sets the pattern. |
| **PositionalItemsValidation** | bool | Gets or sets a value indicating whether items in an array are validated using the JsonSchema instance at their array position from Items. |
| **ReadOnly** | bool? | Gets or sets whether the object is read only. |
| **Required** | bool? | Gets or sets whether the object is required. |
| **Requires** | string | Gets or sets the required property if this property is present. |
| **Title** | string | Gets or sets the title. |
| **Transient** | bool? | Gets or sets whether the object is transient. |
| **Type** | JsonSchemaType? | Gets or sets the types of values allowed by the object. |
| **UniqueItems** | bool | Gets or sets whether the array items must be unique. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Parse** `static` *(+1 overloads)* | [JsonSchema](JsonSchema.md) | Load a JsonSchema from a string that contains schema JSON. |
| **Read** `static` *(+1 overloads)* | [JsonSchema](JsonSchema.md) | Reads a JsonSchema from the specified JsonReader. |
| **ToString** | string | Returns a String that represents the current Object. |
| **WriteTo** *(+1 overloads)* | void | Writes this schema to a JsonWriter. |

---

### Method Details

#### Parse `static`

**Parse**(**json**: string): [JsonSchema](JsonSchema.md)

Load a JsonSchema from a string that contains schema JSON.

**Parameters**

- **json** (string) — A String that contains JSON.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema populated from the string that contains JSON.

---

**Parse**(**json**: string, **resolver**: [JsonSchemaResolver](JsonSchemaResolver.md)): [JsonSchema](JsonSchema.md)

Parses the specified json.

**Parameters**

- **json** (string) — The json.  
- **resolver** ([JsonSchemaResolver](JsonSchemaResolver.md)) — The resolver.  

**Returns** [JsonSchema](JsonSchema.md) — A JsonSchema populated from the string that contains JSON.


---

#### Read `static`

**Read**(**reader**: [JsonReader](../JsonReader.md)): [JsonSchema](JsonSchema.md)

Reads a JsonSchema from the specified JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — The JsonReader containing the JSON Schema to read.  

**Returns** [JsonSchema](JsonSchema.md) — The JsonSchema object representing the JSON Schema.

---

**Read**(**reader**: [JsonReader](../JsonReader.md), **resolver**: [JsonSchemaResolver](JsonSchemaResolver.md)): [JsonSchema](JsonSchema.md)

Reads a JsonSchema from the specified JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — The JsonReader containing the JSON Schema to read.  
- **resolver** ([JsonSchemaResolver](JsonSchemaResolver.md)) — The JsonSchemaResolver to use when resolving schema references.  

**Returns** [JsonSchema](JsonSchema.md) — The JsonSchema object representing the JSON Schema.


---

#### ToString

**ToString**(): string

Returns a String that represents the current Object.

**Returns** string — A String that represents the current Object.


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md)): void

Writes this schema to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  

---

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), **resolver**: [JsonSchemaResolver](JsonSchemaResolver.md)): void

Writes this schema to a JsonWriter using the specified JsonSchemaResolver.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **resolver** ([JsonSchemaResolver](JsonSchemaResolver.md)) — The resolver used.  

