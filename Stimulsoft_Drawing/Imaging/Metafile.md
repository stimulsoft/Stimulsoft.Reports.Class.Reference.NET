---
title: "Metafile Class"
---

## Metafile Class

**Namespace:** `Stimulsoft.Drawing.Imaging`  
**Assembly:** `Stimulsoft.Drawing`

```csharp
public sealed class Metafile
```

### Inheritance

Implements: [Image](../Image.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `Metafile(IntPtr referenceHdc, System.Drawing.Imaging.EmfType emfType)` |  |
| `Metafile(Stream stream, IntPtr referenceHdc)` |  |
| `Metafile(IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit, System.Drawing.Imaging.EmfType type)` |  |
| `Metafile(Stream stream, IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit)` |  |
| `Metafile(Stream stream, IntPtr referenceHdc, object p, System.Drawing.Imaging.MetafileFrameUnit pixel)` |  |
| `Metafile(IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit, System.Drawing.Imaging.EmfType type, string description)` |  |
| `Metafile(Stream stream, IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit, System.Drawing.Imaging.EmfType type, string description)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBounds** | RectangleF |  |
| **GetHenhmetafile** | IntPtr |  |
| **GetMetafileHeader** | [MetafileHeader](MetafileHeader.md) |  |
