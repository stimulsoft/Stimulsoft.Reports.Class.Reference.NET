---
title: "JsonSchema Class"
---

## JsonSchema Class

**Namespace:** `Stimulsoft.Base.Json.Schema`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class JsonSchema
```

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonSchema()` | Initializes a new instance of the JsonSchema class. |

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
