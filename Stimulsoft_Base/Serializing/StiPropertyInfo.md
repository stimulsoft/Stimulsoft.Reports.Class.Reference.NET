---
title: "StiPropertyInfo Class"
---

## StiPropertyInfo Class

**Namespace:** `Stimulsoft.Base.Serializing`  
**Assembly:** `Stimulsoft.Base`

Class keep an object properties information.

```csharp
public class StiPropertyInfo
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPropertyInfo(string name, object value, bool isKey, bool isReference, bool isList, string typeName)` | Creates a new instance of the StiPropertyInfo class. |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Type** | Type | Gets an object type. |
