---
title: "TtfInfo Class"
---

## TtfInfo Class

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class TtfInfo
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Cmap** | [Cmap](Cmap.md) |  |
| **GSUB** | [GSUB_Header](GSUB_Header.md) |  |
| **Head** | [Head](Head.md) |  |
| **Hhea** | [Hhea](Hhea.md) |  |
| **Hmtx** | [Hmtx](Hmtx.md) |  |
| **Maxp** | [Maxp](Maxp.md) |  |
| **Name** | [Name](Name.md) |  |
| **OS2** | [OS2](OS2.md) |  |
| **Post** | [PostTable](PostTable.md) |  |
| **Vhea** | [Vhea](Vhea.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetFamilyName** | string |  |
| **GetGlyphs** | List<[StiGlyphInfo](StiGlyphInfo.md)> |  |
| **GetStyle** | FontStyle |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **FontReader** | StiFontReader |  |
| **HeaderOffset** | uint |  |
| **NumTables** | ushort |  |
| **SfntVersion** | uint |  |
