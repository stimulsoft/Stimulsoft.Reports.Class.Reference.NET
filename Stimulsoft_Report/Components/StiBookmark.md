---
title: "StiBookmark Class"
---

## StiBookmark Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

The class describes a base bookmark class.

```csharp
public class StiBookmark
```

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBookmark**() | Creates a new bookmark. |
| **StiBookmark**(string text, object parentComponent) | Creates a new bookmark. |
| **StiBookmark**(string text, string bookmarkText, object parentComponent) | Creates a new bookmark. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BookmarkText** | string |  |
| **ComponentGuid** | string |  |
| **Engine** | [StiEngineVersion](../../Stimulsoft_Base/Stimulsoft/Report/Engine/StiEngineVersion.md) |  |
| **IsManualBookmark** | bool |  |
| **PageIndex** | int |  |
| **ParentComponent** | object |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
