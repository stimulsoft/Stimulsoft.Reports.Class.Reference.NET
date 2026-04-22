---
title: "StiReportObjectStringConverter Class"
---

## StiReportObjectStringConverter Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

Describes the class that contains methods which serves for conversion of an object into a string and a string into an object.

```csharp
public class StiReportObjectStringConverter
```

### Inheritance

Inherits from: [StiObjectStringConverter](../Stimulsoft_Base/StiObjectStringConverter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiReportObjectStringConverter()` |  |
| `StiReportObjectStringConverter(bool allowLoadOptimization)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **ConvertBorderToString** | string | Converts a border into a string. |
| **ConvertBrushToString** | string | Converts brush into string. |
| **ConvertColorArrayToString** `static` | string | Converts a color into a string. |
| **ConvertColorToString** `static` | string | Converts a color into a string. |
| **ConvertEventToString** | string | Converts event into string. |
| **ConvertExpressionToString** | string | Convets expression into string. |
| **ConvertFontToString** `static` | string | Converts font into string. |
| **ConvertPointFToString** `static` | string | Converts PointF into string. |
| **ConvertRectangleDToString** | string | Converts rectangle into string. |
| **ConvertSimpleBorderToString** | string | Converts a simple border into a string. |
| **ConvertSimpleShadowToString** | string | Converts a simple border into a string. |
| **ConvertStringToBorder** | StiBorder | Converts a string into a border. |
| **ConvertStringToBrush** | [StiBrush](../Stimulsoft_Base/Drawing/StiBrush.md) | Converts a string into a brush. |
| **ConvertStringToColor** `static` | Color | Converts a string into a color. |
| **ConvertStringToColorArray** `static` | Color[] | Converts a string into a color. |
| **ConvertStringToExpression** | StiExpression | Converts string into expression. |
| **ConvertStringToFont** `static` | [Font](../Stimulsoft_Drawing/Font.md) | Converts string into font. |
| **ConvertStringToPointF** `static` | PointF | Converts a string into a PointF. |
| **ConvertStringToRectangleD** | [RectangleD](../Stimulsoft_Base/Drawing/RectangleD.md) | Converts string into rectangle. |
| **ConvertStringToSimpleBorder** | [StiSimpleBorder](../Stimulsoft_Base/Drawing/StiSimpleBorder.md) | Converts a string into a simple border. |
| **ConvertStringToSimpleShadow** | StiSimpleShadow | Converts a string into a simple shadow. |
| **ConvertStringToTextOptions** | StiTextOptions | Converts string into StiTextOptions. |
| **ConvertStringToUserFunction** | [StiUserFunction](Dictionary/StiUserFunction.md) | Converts string into user function. |
| **ConvertStringToVariable** | StiVariable | Converts string into variable. |
| **ConvertTextOptionsToString** | string | Converts StiTextOptions into string. |
| **ConvertUserFunctionToString** | string | Converts user function into string. |
| **ConvertVariableToString** | string | Converts variable into string. |
| **ObjectToString** | string | Converts object into string. |
| **ObjectToString2** | string |  |
| **SetProperty** | void |  |
| **StringToObject** | object | Converts string into object. |
| **StringToObject2** | object |  |
