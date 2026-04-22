---
title: "StiReference Class"
---

## StiReference Class

**Namespace:** `Stimulsoft.Base.Serializing`  
**Assembly:** `Stimulsoft.Base`

Class for delayed processing references (references which allude to the unprocessed objects).

```csharp
public class StiReference
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiReference**([StiPropertyInfo](StiPropertyInfo.md) propInfo) | Creates a new instance of the StiReference class. |
| **StiReference**([StiPropertyInfo](StiPropertyInfo.md) propInfo, object obj, PropertyInfo propertyInfo) | Creates a new instance of the StiReference class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Object** | object | Gets or sets the object where a property is located. |
| **PropInfo** | [StiPropertyInfo](StiPropertyInfo.md) | Gets or sets the adapted property. |
| **PropertyInfo** | PropertyInfo | Gets or sets standard property. |
