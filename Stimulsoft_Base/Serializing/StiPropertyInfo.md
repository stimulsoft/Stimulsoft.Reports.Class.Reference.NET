---
title: "StiPropertyInfo Class"
---

## StiPropertyInfo Class

**Namespace:** `Stimulsoft.Base.Serializing`

Class keep an object properties information.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPropertyInfo**(string name, object value, bool isKey, bool isReference, bool isList, string typeName) | Creates a new instance of the StiPropertyInfo class. |

**StiPropertyInfo**(**name**: string, **value**: object, **isKey**: bool, **isReference**: bool, **isList**: bool, **typeName**: string)

Creates a new instance of the StiPropertyInfo class.

**Parameters**

- **name** (string) — Name of an object properties  
- **value** (object) — Value of an object property.  
- **isKey** (bool) — Value indicates that this property describes an object.  
- **isReference** (bool) — Value indicates that this is a reference to an object.  
- **isList** (bool) — Value indicates that this is a collection.  
- **typeName** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Count** | int | Gets or sets the number of elements in the collection. |
| **DefaultValue** | object | Gets or sets the value of an object property by default. |
| **IsDefaultValueSpecified** | bool | Gets or sets the value which indicates that default value specified. |
| **IsKey** | bool | Gets or sets value indicates that this property describes an object. |
| **IsList** | bool | Gets or sets value indicates that this is a collection. |
| **IsReference** | bool | Gets or sets value indicates that this is a reference to an object. |
| **IsSerializable** | bool | Gets or sets value indicates that this object realizes the interface IStiSerializable. |
| **Name** | string | Gets or sets the name of an object property. |
| **Parent** | [StiPropertyInfo](StiPropertyInfo.md) | Gets or sets an object property that is the main for this object property. |
| **Properties** | [StiPropertyInfoCollection](StiPropertyInfoCollection.md) | Gets or sets the collection of subordinated properties. |
| **ReferenceCode** | int | Gets or sets the reference code. |
| **TypeName** | string |  |
| **Value** | object | Gets or sets the value of an object property. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string |  |

---

### Method Details

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Type** | Type | Gets an object type. |
