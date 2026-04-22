---
title: "Font Class"
---

## Font Class

**Namespace:** `Stimulsoft.Drawing`  
**Assembly:** `Stimulsoft.Drawing`

```csharp
public class Font
```

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| `Font([Font](Font.md) prototype, float size)` |  |
| `Font([Font](Font.md) prototype, System.Drawing.FontStyle newStyle)` |  |
| `Font([FontFamily](FontFamily.md) family, float emSize)` |  |
| `Font(string familyName, float emSize)` |  |
| `Font([FontFamily](FontFamily.md) family, float emSize, System.Drawing.GraphicsUnit unit)` |  |
| `Font(string familyName, float emSize, System.Drawing.GraphicsUnit unit)` |  |
| `Font([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style)` |  |
| `Font(string familyName, float emSize, System.Drawing.FontStyle style)` |  |
| `Font([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit)` |  |
| `Font(string familyName, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit)` |  |
| `Font([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet)` |  |
| `Font(string familyName, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet)` |  |
| `Font(string familyName, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont)` |  |
| `Font([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **Dispose** | void |  |
| **FromLogFont** `static` | [Font](Font.md) |  |
| **GetHeight** | float |  |
| **ToHfont** | IntPtr |  |
| **ToString** | String |  |
