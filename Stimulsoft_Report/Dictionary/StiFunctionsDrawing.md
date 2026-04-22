---
title: "StiFunctionsDrawing Class"
---

## StiFunctionsDrawing Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFunctionsDrawing
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ARGB** `static` | Color | Creates a Color from the four ARGB component (alpha, red, green, and blue) values. |
| **ColorFade** `static` | Color | Makes a color darker or lighter on a specified fade value. For example: ColorFade(Color.Red, -0.5), ColorFade(Color.Green, 0.3). |
| **ColorValue** `static` | Color | Translates a string representation to a color. For example: ColorValue("Red"), ColorValue("#FF0000"), ColorValue("#55009900"). |
| **FontValue** `static` *(+1 overloads)* | [Font](../../Stimulsoft_Drawing/Font.md) | Makes a new font using a specified name and size. For example: FontValue("Arial", 8). |
| **GlareBrushValue** `static` | [StiGlareBrush](../../Stimulsoft_Base/Drawing/StiGlareBrush.md) | Makes a glare brush. For example: GlareBrushValue("red", "green", 45), GlareBrushValue(Color.Red, Color.Green, 45). |
| **GlassBrushValue** `static` | [StiGlassBrush](../../Stimulsoft_Base/Drawing/StiGlassBrush.md) | Makes a glass brush. For example: GlassBrushValue("#ff0000", 0.2), GlassBrushValue(Color.Red, 0.2). |
| **GradientBrushValue** `static` | [StiGradientBrush](../../Stimulsoft_Base/Drawing/StiGradientBrush.md) | Makes a gradient brush. For example: GradientBrushValue("red", "green", 45), GradientBrushValue(Color.Red, Color.Green, 45). |
| **HatchBrushValue** `static` | [StiHatchBrush](../../Stimulsoft_Base/Drawing/StiHatchBrush.md) | Makes a hatch brush. For example: HatchBrushValue(HatchStyle.Cross, "gray", "white"). |
| **RGB** `static` | Color | Creates a Color from the three RGB component (red, green, and blue) values. |
| **SolidBrushValue** `static` | [StiSolidBrush](../../Stimulsoft_Base/Drawing/StiSolidBrush.md) | Makes a solid brush. For example: SolidBrushValue("red"), SolidBrushValue(Color.Yellow). |
