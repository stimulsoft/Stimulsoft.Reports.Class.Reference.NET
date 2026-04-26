---
title: "StiFunctionsDrawing Class"
---

## StiFunctionsDrawing Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ARGB** `static` | Color | Creates a Color from the four ARGB component (alpha, red, green, and blue) values. |
| **ColorFade** `static` | Color | Makes a color darker or lighter on a specified fade value. For example: ColorFade(Color.Red, -0.5), ColorFade(Color.Green, 0.3). |
| **ColorValue** `static` | Color | Translates a string representation to a color. For example: ColorValue("Red"), ColorValue("#FF0000"), ColorValue("#55009900"). |
| **FontValue** `static` *(+1 overloads)* | [Font](../../Stimulsoft_Drawing/root/Font.md) | Makes a new font using a specified name and size. For example: FontValue("Arial", 8). |
| **GlareBrushValue** `static` | [StiGlareBrush](../../Stimulsoft_Base/Drawing/StiGlareBrush.md) | Makes a glare brush. For example: GlareBrushValue("red", "green", 45), GlareBrushValue(Color.Red, Color.Green, 45). |
| **GlassBrushValue** `static` | [StiGlassBrush](../../Stimulsoft_Base/Drawing/StiGlassBrush.md) | Makes a glass brush. For example: GlassBrushValue("#ff0000", 0.2), GlassBrushValue(Color.Red, 0.2). |
| **GradientBrushValue** `static` | [StiGradientBrush](../../Stimulsoft_Base/Drawing/StiGradientBrush.md) | Makes a gradient brush. For example: GradientBrushValue("red", "green", 45), GradientBrushValue(Color.Red, Color.Green, 45). |
| **HatchBrushValue** `static` | [StiHatchBrush](../../Stimulsoft_Base/Drawing/StiHatchBrush.md) | Makes a hatch brush. For example: HatchBrushValue(HatchStyle.Cross, "gray", "white"). |
| **RGB** `static` | Color | Creates a Color from the three RGB component (red, green, and blue) values. |
| **SolidBrushValue** `static` | [StiSolidBrush](../../Stimulsoft_Base/Drawing/StiSolidBrush.md) | Makes a solid brush. For example: SolidBrushValue("red"), SolidBrushValue(Color.Yellow). |

---

### Method Details

#### ARGB `static`

**ARGB**(**alpha**: int, **red**: int, **green**: int, **blue**: int): Color

Creates a Color from the four ARGB component (alpha, red, green, and blue) values.

**Parameters**

- **alpha** (int) — An alpha component, which ranges from 0 (fully transparent) to 255 (fully opaque).  
- **red** (int) — A red component, which ranges from 0 (no saturation) to 255 (full saturation).  
- **green** (int) — A green component, which ranges from 0 (no saturation) to 255 (full saturation).  
- **blue** (int) — A blue component, which ranges from 0 (no saturation) to 255 (full saturation).  

**Returns** Color — A color value.


---

#### ColorFade `static`

**ColorFade**(**color**: object, **fadeAmount**: double): Color

Makes a color darker or lighter on a specified fade value. For example: ColorFade(Color.Red, -0.5), ColorFade(Color.Green, 0.3).

**Parameters**

- **color** (object) — A color value.  
- **fadeAmount** (double) — A number between -1 and 1. -1 fully darkens a color to black, 0 doesn't affect the color, and 1 fully brightens a color to white.  

**Returns** Color — A color value.


---

#### ColorValue `static`

**ColorValue**(**value**: string): Color

Translates a string representation to a color. For example: ColorValue("Red"), ColorValue("#FF0000"), ColorValue("#55009900").

**Parameters**

- **value** (string) — A string representation of a color to translate.  

**Returns** Color — A color value.


---

#### FontValue `static`

**FontValue**(**name**: string, **size**: float): [Font](../../Stimulsoft_Drawing/root/Font.md)

Makes a new font using a specified name and size. For example: FontValue("Arial", 8).

**Parameters**

- **name** (string) — A font name.  
- **size** (float) — A font size.  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md) — A created font.

---

**FontValue**(**name**: string, **size**: float, **style**: FontStyle): [Font](../../Stimulsoft_Drawing/root/Font.md)

Makes a new font using a specified name, size and style.

**Parameters**

- **name** (string) — A font name.  
- **size** (float) — A font size.  
- **style** (FontStyle) — A font style.  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md) — A created font.


---

#### GlareBrushValue `static`

**GlareBrushValue**(**startColor**: object, **endColor**: object, **angle**: double, **focus**: double, **scale**: double): [StiGlareBrush](../../Stimulsoft_Base/Drawing/StiGlareBrush.md)

Makes a glare brush. For example: GlareBrushValue("red", "green", 45), GlareBrushValue(Color.Red, Color.Green, 45).

**Parameters**

- **startColor** (object) — A string representation of a starting color for the gradient.  
- **endColor** (object) — A string representation of a ending color for the gradient.  
- **angle** (double) — An angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line.  
- **focus** (double) — A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color).  
- **scale** (double) — A value from 0 through 1 that specifies how fast the colors falloff from the focus.  

**Returns** [StiGlareBrush](../../Stimulsoft_Base/Drawing/StiGlareBrush.md) — A glare brush.


---

#### GlassBrushValue `static`

**GlassBrushValue**(**color**: object, **drawHatch**: bool, **blendFactor**: double): [StiGlassBrush](../../Stimulsoft_Base/Drawing/StiGlassBrush.md)

Makes a glass brush. For example: GlassBrushValue("#ff0000", 0.2), GlassBrushValue(Color.Red, 0.2).

**Parameters**

- **color** (object) — A color for the glass brush.  
- **drawHatch** (bool) — Draw hatch at background or not.  
- **blendFactor** (double) — A blend factor. The value must be in range between 0 and 1.  

**Returns** [StiGlassBrush](../../Stimulsoft_Base/Drawing/StiGlassBrush.md) — A glass brush.


---

#### GradientBrushValue `static`

**GradientBrushValue**(**startColor**: object, **endColor**: object, **angle**: double): [StiGradientBrush](../../Stimulsoft_Base/Drawing/StiGradientBrush.md)

Makes a gradient brush. For example: GradientBrushValue("red", "green", 45), GradientBrushValue(Color.Red, Color.Green, 45).

**Parameters**

- **startColor** (object) — A starting color for the gradient.  
- **endColor** (object) — An ending color for the gradient.  
- **angle** (double) — An angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line.  

**Returns** [StiGradientBrush](../../Stimulsoft_Base/Drawing/StiGradientBrush.md) — A gradient brush.


---

#### HatchBrushValue `static`

**HatchBrushValue**(**style**: HatchStyle, **foreColor**: object, **backColor**: object): [StiHatchBrush](../../Stimulsoft_Base/Drawing/StiHatchBrush.md)

Makes a hatch brush. For example: HatchBrushValue(HatchStyle.Cross, "gray", "white").

**Parameters**

- **style** (HatchStyle) — A hatch style of the brush.  
- **foreColor** (object) — A foreground color for the hatch brush.  
- **backColor** (object) — A background color for the hatch brush.  

**Returns** [StiHatchBrush](../../Stimulsoft_Base/Drawing/StiHatchBrush.md) — A hatch brush.


---

#### RGB `static`

**RGB**(**red**: int, **green**: int, **blue**: int): Color

Creates a Color from the three RGB component (red, green, and blue) values.

**Parameters**

- **red** (int) — A red component, which ranges from 0 (no saturation) to 255 (full saturation).  
- **green** (int) — A green component, which ranges from 0 (no saturation) to 255 (full saturation).  
- **blue** (int) — A blue component, which ranges from 0 (no saturation) to 255 (full saturation).  

**Returns** Color — A color value.


---

#### SolidBrushValue `static`

**SolidBrushValue**(**color**: object): [StiSolidBrush](../../Stimulsoft_Base/Drawing/StiSolidBrush.md)

Makes a solid brush. For example: SolidBrushValue("red"), SolidBrushValue(Color.Yellow).

**Parameters**

- **color** (object) — A color value for the solid brush.  

**Returns** [StiSolidBrush](../../Stimulsoft_Base/Drawing/StiSolidBrush.md) — A solid brush.

