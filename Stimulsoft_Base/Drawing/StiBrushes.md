---
title: "StiBrushes Class"
---

## StiBrushes Class

**Namespace:** `Stimulsoft.Base.Drawing`

Brushes for StimulControls colors.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Content** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Gets a defined Brush object with a Content color. |
| **ContentDark** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Gets a defined Brush object with a Dark Content color. |
| **Focus** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Gets a defined Brush object with a Focus color. |
| **HatchStyles** `static` | HatchStyle[] | Array contains all elements of HatchStyle enumeration. |
| **Selected** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Gets a defined Brush object with the Selected color. |
| **SelectedText** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Gets a defined Brush object with the SelectedText color. |
| **Window** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Gets a defined Brush object with the SelectedText color. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetActiveCaptionBrush** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Creates the ActiveCaption from the specified Rectangle and Angle. |
| **GetActiveCaptionLightBrush** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Creates an ActiveCaptionLight from the specified Rectangle and Angle. |
| **GetControlBrush** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Creates a ControlBrush from the specified Rectangle and Angle. |
| **GetControlDarkBrush** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Creates a ControlDark Brush from the specified Rectangle and Angle. |
| **GetControlLightBrush** `static` | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Creates a ControlLight Brush from the specified Rectangle and Angle. |
| **HatchStyleFromName** `static` | HatchStyle | Creates a HatchStyle from the specified name of a HatchStyle object. |

---

### Method Details

#### GetActiveCaptionBrush `static`

**GetActiveCaptionBrush**(**rectangle**: Rectangle, **angle**: float): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Creates the ActiveCaption from the specified Rectangle and Angle.

**Parameters**

- **rectangle** (Rectangle) — Rectangle that defines the starting and ending points of the gradient.  
- **angle** (float) — The angle, measured in degrees clockwise from the x-axis, of the gradient orientation line.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — This method creates The LinearGradientBrush object.


---

#### GetActiveCaptionLightBrush `static`

**GetActiveCaptionLightBrush**(**rectangle**: Rectangle, **angle**: float): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Creates an ActiveCaptionLight from the specified Rectangle and Angle.

**Parameters**

- **rectangle** (Rectangle) — Rectangle that defines the starting and ending points of the gradient.  
- **angle** (float) — The angle, measured in degrees clockwise from the x-axis, of the gradient orientation line.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — This method creates The LinearGradientBrush object.


---

#### GetControlBrush `static`

**GetControlBrush**(**rectangle**: Rectangle, **angle**: float): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Creates a ControlBrush from the specified Rectangle and Angle.

**Parameters**

- **rectangle** (Rectangle) — Rectangle that defines the starting and ending points of the gradient.  
- **angle** (float) — The angle, measured in degrees clockwise from the x-axis, of the gradient orientation line.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — This method creates The LinearGradientBrush object.


---

#### GetControlDarkBrush `static`

**GetControlDarkBrush**(**rectangle**: Rectangle, **angle**: float): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Creates a ControlDark Brush from the specified Rectangle and Angle.

**Parameters**

- **rectangle** (Rectangle) — Rectangle that defines the starting and ending points of the gradient.  
- **angle** (float) — The angle, measured in degrees clockwise from the x-axis, of the gradient orientation line.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — This method creates The LinearGradientBrush object.


---

#### GetControlLightBrush `static`

**GetControlLightBrush**(**rectangle**: Rectangle, **angle**: float): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Creates a ControlLight Brush from the specified Rectangle and Angle.

**Parameters**

- **rectangle** (Rectangle) — Rectangle that defines the starting and ending points of the gradient.  
- **angle** (float) — The angle, measured in degrees clockwise from the x-axis, of the gradient orientation line.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — This method creates The LinearGradientBrush object.


---

#### HatchStyleFromName `static`

**HatchStyleFromName**(**name**: string): HatchStyle

Creates a HatchStyle from the specified name of a HatchStyle object.

**Parameters**

- **name** (string) — A string that is the name of a HatchStyle object.  

**Returns** HatchStyle — This method creates The HatchStyle object.

