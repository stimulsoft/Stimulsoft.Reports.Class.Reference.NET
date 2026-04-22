---
title: "StiDataLink Class"
---

## StiDataLink Class

**Namespace:** `Stimulsoft.Data.Engine`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class StiDataLink
```

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiDataLink()` |  |
| `StiDataLink(string key)` |  |
| `StiDataLink(string parentTable, string childTable, stringparentColumns , stringchildColumns , bool active, [StiDataJoinType](../../Stimulsoft_Base/StiDataJoinType.md) joinType)` |  |
| `StiDataLink(string parentTable, string childTable, stringparentColumns , stringchildColumns , bool active, [StiDataJoinType](../../Stimulsoft_Base/StiDataJoinType.md) joinType, string key)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Active** | bool |  |
| **ChildColumns** | string[] |  |
| **ChildTable** | string |  |
| **JoinType** | [StiDataJoinType](../../Stimulsoft_Base/StiDataJoinType.md) | Specifies the type of data join operation that merges two data sources into one. Used only in Dashboards data. |
| **Key** | string | Gets or sets the key to the data relation in the report dictionary. |
| **ParentColumns** | string[] |  |
| **ParentTable** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJson** `static` | [StiDataLink](StiDataLink.md) |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ToString** | string |  |
