---
title: "StiEnumConverter Class"
---

## StiEnumConverter Class

**Namespace:** `Stimulsoft.Base.Localization`  
**Assembly:** `Stimulsoft.Base`

Provides a type converter to convert Enum objects to and from various other representations.

```csharp
public class StiEnumConverter
```

### Inheritance

Inherits from: TypeConverter  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEnumConverter**() |  |
| **StiEnumConverter**(Type type) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | Type |  |
| **Values** | StandardValuesCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvertFrom** | bool |  |
| **CanConvertTo** | bool |  |
| **ConvertFrom** | object |  |
| **GetLocName** | string |  |
| **GetStandardValues** | StandardValuesCollection |  |
| **GetStandardValuesExclusive** | bool |  |
| **GetStandardValuesSupported** | bool |  |
| **IsValid** | bool |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **EnumType** | Type |  |
