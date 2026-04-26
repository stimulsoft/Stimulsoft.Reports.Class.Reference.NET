---
title: "JsonProperty Class"
---

## JsonProperty Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Maps a JSON property to a .NET member or constructor parameter.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AttributeProvider** | [IAttributeProvider](IAttributeProvider.md) | Gets or sets the IAttributeProvider for this property. |
| **Converter** | [JsonConverter](../JsonConverter.md) | Gets or sets the JsonConverter for the property. If set this converter takes presidence over the contract converter for the property type. |
| **DeclaringType** | Type | Gets or sets the type that declared this property. |
| **DefaultValueHandling** | DefaultValueHandling? | Gets or sets the property default value handling. |
| **GetIsSpecified** | Predicate<object> | Gets or sets a predicate used to determine whether the property should be serialized. |
| **HasMemberAttribute** | bool | Gets or sets a value indicating whether this JsonProperty has a member attribute. |
| **Ignored** | bool | Gets or sets a value indicating whether this JsonProperty is ignored. |
| **IsReference** | bool? | Gets or sets a value indicating whether this property preserves object references. |
| **ItemConverter** | [JsonConverter](../JsonConverter.md) | Gets or sets the converter used when serializing the property's collection items. |
| **ItemIsReference** | bool? | Gets or sets whether this property's collection items are serialized as a reference. |
| **ItemReferenceLoopHandling** | ReferenceLoopHandling? | Gets or sets the the reference loop handling used when serializing the property's collection items. |
| **ItemTypeNameHandling** | TypeNameHandling? | Gets or sets the the type name handling used when serializing the property's collection items. |
| **MemberConverter** | [JsonConverter](../JsonConverter.md) | Gets or sets the member converter. |
| **NullValueHandling** | NullValueHandling? | Gets or sets the property null value handling. |
| **ObjectCreationHandling** | ObjectCreationHandling? | Gets or sets the property object creation handling. |
| **Order** | int? | Gets or sets the order of serialization and deserialization of a member. |
| **Readable** | bool | Gets or sets a value indicating whether this JsonProperty is readable. |
| **ReferenceLoopHandling** | ReferenceLoopHandling? | Gets or sets the property reference loop handling. |
| **ShouldSerialize** | Predicate<object> | Gets or sets a predicate used to determine whether the property should be serialize. |
| **TypeNameHandling** | TypeNameHandling? | Gets or sets or sets the type name handling. |
| **UnderlyingName** | string | Gets or sets the name of the underlying member or parameter. |
| **ValueProvider** | [IValueProvider](IValueProvider.md) | Gets the IValueProvider that will get and set the JsonProperty during serialization. |
| **Writable** | bool | Gets or sets a value indicating whether this JsonProperty is writable. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string | Returns a String that represents this instance. |

---

### Method Details

#### ToString

**ToString**(): string

Returns a String that represents this instance.

**Returns** string — A String that represents this instance.

