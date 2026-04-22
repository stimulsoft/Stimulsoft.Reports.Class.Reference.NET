---
title: "StiWordExportSettings Class"
---

## StiWordExportSettings Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

This class describes settings for export to Word format.

```csharp
public class StiWordExportSettings
```

### Inheritance

Inherits from: [StiImageResolutionExportSettings](StiImageResolutionExportSettings.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CompanyString** | string |  |
| **EncryptionPassword** | string |  |
| **ImageFormat** | [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md) |  |
| **LastModifiedString** | string |  |
| **ProtectionPassword** | string |  |
| **RemoveEmptySpaceAtBottom** | bool |  |
| **RestrictEditing** | [StiWord2007RestrictEditing](StiWord2007RestrictEditing.md) |  |
| **UsePageHeadersAndFooters** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetExportFormat** | [StiExportFormat](../StiExportFormat.md) |  |
