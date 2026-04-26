---
title: "StiReportObjectStringConverter Class"
---

## StiReportObjectStringConverter Class

**Namespace:** `Stimulsoft.Report`

Describes the class that contains methods which serves for conversion of an object into a string and a string into an object.

### Inheritance

Inherits from: [StiObjectStringConverter](../../Stimulsoft_Base/root/StiObjectStringConverter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiReportObjectStringConverter**() |  |
| **StiReportObjectStringConverter**(bool allowLoadOptimization) |  |

**StiReportObjectStringConverter**()

---

**StiReportObjectStringConverter**(**allowLoadOptimization**: bool)

**Parameters**

- **allowLoadOptimization** (bool)  


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
| **ConvertStringToBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) | Converts a string into a brush. |
| **ConvertStringToColor** `static` | Color | Converts a string into a color. |
| **ConvertStringToColorArray** `static` | Color[] | Converts a string into a color. |
| **ConvertStringToExpression** | StiExpression | Converts string into expression. |
| **ConvertStringToFont** `static` | [Font](../../Stimulsoft_Drawing/root/Font.md) | Converts string into font. |
| **ConvertStringToPointF** `static` | PointF | Converts a string into a PointF. |
| **ConvertStringToRectangleD** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) | Converts string into rectangle. |
| **ConvertStringToSimpleBorder** | [StiSimpleBorder](../../Stimulsoft_Base/Drawing/StiSimpleBorder.md) | Converts a string into a simple border. |
| **ConvertStringToSimpleShadow** | StiSimpleShadow | Converts a string into a simple shadow. |
| **ConvertStringToTextOptions** | StiTextOptions | Converts string into StiTextOptions. |
| **ConvertStringToUserFunction** | [StiUserFunction](../Dictionary/StiUserFunction.md) | Converts string into user function. |
| **ConvertStringToVariable** | StiVariable | Converts string into variable. |
| **ConvertTextOptionsToString** | string | Converts StiTextOptions into string. |
| **ConvertUserFunctionToString** | string | Converts user function into string. |
| **ConvertVariableToString** | string | Converts variable into string. |
| **ObjectToString** | string | Converts object into string. |
| **ObjectToString2** | string |  |
| **SetProperty** | void |  |
| **StringToObject** | object | Converts string into object. |
| **StringToObject2** | object |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### ConvertBorderToString

**ConvertBorderToString**(**border**: StiBorder): string

Converts a border into a string.

**Parameters**

- **border** (StiBorder) — Border for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertBrushToString

**ConvertBrushToString**(**brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)): string

Converts brush into string.

**Parameters**

- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)) — Brush for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertColorArrayToString `static`

**ConvertColorArrayToString**(****: Colorcolors): string

Converts a color into a string.

**Parameters**

- **** (Colorcolors)  

**Returns** string — String got as result of conversion.


---

#### ConvertColorToString `static`

**ConvertColorToString**(**color**: Color): string

Converts a color into a string.

**Parameters**

- **color** (Color) — Color for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertEventToString

**ConvertEventToString**(**ev**: StiEvent): string

Converts event into string.

**Parameters**

- **ev** (StiEvent) — Event for conversion.  

**Returns** string — Converted string.


---

#### ConvertExpressionToString

**ConvertExpressionToString**(**expr**: StiExpression): string

Convets expression into string.

**Parameters**

- **expr** (StiExpression) — Expression for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertFontToString `static`

**ConvertFontToString**(**font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): string

Converts font into string.

**Parameters**

- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — Font for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertPointFToString `static`

**ConvertPointFToString**(**point**: PointF): string

Converts PointF into string.

**Parameters**

- **point** (PointF)  

**Returns** string — String got as result of conversion.


---

#### ConvertRectangleDToString

**ConvertRectangleDToString**(**rectangle**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): string

Converts rectangle into string.

**Parameters**

- **rectangle** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — Rectangle for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertSimpleBorderToString

**ConvertSimpleBorderToString**(**border**: [StiSimpleBorder](../../Stimulsoft_Base/Drawing/StiSimpleBorder.md), **ignoreDefault**: bool): string

Converts a simple border into a string.

**Parameters**

- **border** ([StiSimpleBorder](../../Stimulsoft_Base/Drawing/StiSimpleBorder.md)) — Border for conversion.  
- **ignoreDefault** (bool)  

**Returns** string — String got as result of conversion.


---

#### ConvertSimpleShadowToString

**ConvertSimpleShadowToString**(**shadow**: StiSimpleShadow, **ignoreDefault**: bool): string

Converts a simple border into a string.

**Parameters**

- **shadow** (StiSimpleShadow) — Border for conversion.  
- **ignoreDefault** (bool)  

**Returns** string — String got as result of conversion.


---

#### ConvertStringToBorder

**ConvertStringToBorder**(**str**: string): StiBorder

Converts a string into a border.

**Parameters**

- **str** (string) — String that shows border.  

**Returns** StiBorder — Border got as result of conversion.


---

#### ConvertStringToBrush

**ConvertStringToBrush**(**str**: string): [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)

Converts a string into a brush.

**Parameters**

- **str** (string) — String that shows brush.  

**Returns** [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) — Brush got as a result of conversion.


---

#### ConvertStringToColor `static`

**ConvertStringToColor**(**str**: string): Color

Converts a string into a color.

**Parameters**

- **str** (string) — String that shows color.  

**Returns** Color — Color got as result of conversion.


---

#### ConvertStringToColorArray `static`

**ConvertStringToColorArray**(**str**: string): Color[]

Converts a string into a color.

**Parameters**

- **str** (string) — String that shows color.  

**Returns** Color[] — Color got as result of conversion.


---

#### ConvertStringToExpression

**ConvertStringToExpression**(**type**: Type, **str**: string): StiExpression

Converts string into expression.

**Parameters**

- **type** (Type) — Expression type.  
- **str** (string) — String that shows expression.  

**Returns** StiExpression — Expression got as result of conversion.


---

#### ConvertStringToFont `static`

**ConvertStringToFont**(**str**: string): [Font](../../Stimulsoft_Drawing/root/Font.md)

Converts string into font.

**Parameters**

- **str** (string) — String that shows font.  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md) — Font got as result of conversion.


---

#### ConvertStringToPointF `static`

**ConvertStringToPointF**(**str**: string): PointF

Converts a string into a PointF.

**Parameters**

- **str** (string) — String that shows color.  

**Returns** PointF — PointF got as result of conversion.


---

#### ConvertStringToRectangleD

**ConvertStringToRectangleD**(**str**: string): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

Converts string into rectangle.

**Parameters**

- **str** (string) — String that shows rectangle.  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) — Rectangle got as result of conversion.


---

#### ConvertStringToSimpleBorder

**ConvertStringToSimpleBorder**(**str**: string): [StiSimpleBorder](../../Stimulsoft_Base/Drawing/StiSimpleBorder.md)

Converts a string into a simple border.

**Parameters**

- **str** (string) — String that shows border.  

**Returns** [StiSimpleBorder](../../Stimulsoft_Base/Drawing/StiSimpleBorder.md) — Border got as result of conversion.


---

#### ConvertStringToSimpleShadow

**ConvertStringToSimpleShadow**(**str**: string): StiSimpleShadow

Converts a string into a simple shadow.

**Parameters**

- **str** (string) — String that shows border.  

**Returns** StiSimpleShadow — Border got as result of conversion.


---

#### ConvertStringToTextOptions

**ConvertStringToTextOptions**(**str**: string): StiTextOptions

Converts string into StiTextOptions.

**Parameters**

- **str** (string) — String that shows StiTextOptions.  

**Returns** StiTextOptions — StiTextOptions got as result of conversion.


---

#### ConvertStringToUserFunction

**ConvertStringToUserFunction**(**type**: Type, **str**: string): [StiUserFunction](../Dictionary/StiUserFunction.md)

Converts string into user function.

**Parameters**

- **type** (Type) — Type of function.  
- **str** (string) — String that shows user function.  

**Returns** [StiUserFunction](../Dictionary/StiUserFunction.md) — User function got as result of conversion.


---

#### ConvertStringToVariable

**ConvertStringToVariable**(**type**: Type, **str**: string): StiVariable

Converts string into variable.

**Parameters**

- **type** (Type) — Type of variable.  
- **str** (string) — String that shows variable.  

**Returns** StiVariable — Variable got as result of conversion.


---

#### ConvertTextOptionsToString

**ConvertTextOptionsToString**(**textOptions**: StiTextOptions): string

Converts StiTextOptions into string.

**Parameters**

- **textOptions** (StiTextOptions) — StiTextOptions for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertUserFunctionToString

**ConvertUserFunctionToString**(**userFunction**: [StiUserFunction](../Dictionary/StiUserFunction.md)): string

Converts user function into string.

**Parameters**

- **userFunction** ([StiUserFunction](../Dictionary/StiUserFunction.md)) — Variable for conversion.  

**Returns** string — String got as result of conversion.


---

#### ConvertVariableToString

**ConvertVariableToString**(**variable**: StiVariable): string

Converts variable into string.

**Parameters**

- **variable** (StiVariable) — Variable for conversion.  

**Returns** string — String got as result of conversion.


---

#### ObjectToString

**ObjectToString**(**obj**: object): string

Converts object into string.

**Parameters**

- **obj** (object) — Object for converting.  

**Returns** string — String that contains object.


---

#### ObjectToString2

**ObjectToString2**(**obj**: object): string

**Parameters**

- **obj** (object)  

**Returns** string


---

#### SetProperty

**SetProperty**(**p**: PropertyInfo, **parentObject**: object, **obj**: object): void

**Parameters**

- **p** (PropertyInfo)  
- **parentObject** (object)  
- **obj** (object)  


---

#### StringToObject

**StringToObject**(**str**: string, **type**: Type): object

Converts string into object.

**Parameters**

- **str** (string) — String that contains object.  
- **type** (Type) — Object type.  

**Returns** object — Object.


---

#### StringToObject2

**StringToObject2**(**str**: string, **type**: Type): object

**Parameters**

- **str** (string)  
- **type** (Type)  

**Returns** object

