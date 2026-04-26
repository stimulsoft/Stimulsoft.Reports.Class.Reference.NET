---
title: "StiControlPaint Class"
---

## StiControlPaint Class

**Namespace:** `Stimulsoft.Base.Drawing`

Provides methods used to paint controls and their elements.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawBorder** `static` | void | Draws a border. |
| **DrawCheck** `static` | void | Draws a check. |
| **DrawFocus** `static` *(+1 overloads)* | void | Draws a focus rectangle with button. |
| **DrawImageBackground** `static` | void |  |
| **DrawImageDisabled** `static` *(+2 overloads)* | void | Draws the specified image in a disabled state. |
| **DrawItemBackground** `static` | void | Draws an item background. |
| **GetButtonRect** `static` *(+1 overloads)* | Rectangle |  |
| **GetContentRect** `static` | Rectangle |  |
| **GetItemBackground** `static` | Color |  |
| **GetItemForeground** `static` *(+2 overloads)* | Color |  |
| **ScrollWindow** `static` | bool | Scrolls the contents of the specified window's client area. |

---

### Method Details

#### DrawBorder `static`

**DrawBorder**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **bounds**: Rectangle, **isMouseOver**: bool, **isFocused**: bool, **isEnabled**: bool): void

Draws a border.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **bounds** (Rectangle) — The bounds that represents the dimensions of the border rectangle.  
- **isMouseOver** (bool)  
- **isFocused** (bool) — The Border is focused.  
- **isEnabled** (bool)  


---

#### DrawCheck `static`

**DrawCheck**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **x**: int, **y**: int, **enabled**: bool): void

Draws a check.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **x** (int) — The X coordinate of the top left of the check.  
- **y** (int) — The Y coordinate of the top left of the check.  
- **enabled** (bool)  


---

#### DrawFocus `static`

**DrawFocus**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **bounds**: Rectangle, **buttonBounds**: Rectangle): void

Draws a focus rectangle with button.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **bounds** (Rectangle) — The bounds that represents the dimensions of the focus rectangle.  
- **buttonBounds** (Rectangle) — The bounds that represents the dimensions of the button rectangle.  

---

**DrawFocus**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **bounds**: Rectangle): void

Draws a focus rectangle.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **bounds** (Rectangle) — The bounds that represents the dimensions of the focus rectangle.  


---

#### DrawImageBackground `static`

**DrawImageBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **rect**: Rectangle): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **rect** (Rectangle)  


---

#### DrawImageDisabled `static`

**DrawImageDisabled**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **x**: int, **y**: int): void

Draws the specified image in a disabled state.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md)) — The Image to draw.  
- **x** (int) — The X coordinate of the top left of the border image.  
- **y** (int) — The Y coordinate of the top left of the border image.  

---

**DrawImageDisabled**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **bmp**: [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md), **x**: int, **y**: int): void

Draws the specified image in a disabled state.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **bmp** ([Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)) — The Bitmap to draw.  
- **x** (int) — The X coordinate of the top left of the border bitmap.  
- **y** (int) — The Y coordinate of the top left of the border bitmap.  

---

**DrawImageDisabled**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **bmp**: [Image](../../Stimulsoft_Drawing/root/Image.md), **rect**: Rectangle): void

Draws the specified image in a disabled state.

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **bmp** ([Image](../../Stimulsoft_Drawing/root/Image.md)) — The Bitmap to draw.  
- **rect** (Rectangle)  


---

#### DrawItemBackground `static`

**DrawItemBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **bounds**: Rectangle, **state**: DrawItemState, **backColor**: Color?): void

Draws an item background.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics object to draw on.  
- **bounds** (Rectangle) — The bounds that represents the dimensions of the item rectangle.  
- **state** (DrawItemState) — Specifies the state of an item that is being drawn.  
- **backColor** (Color?)  


---

#### GetButtonRect `static`

**GetButtonRect**(**bounds**: Rectangle, **flat**: bool, **rightToLeft**: RightToLeft): Rectangle

**Parameters**

- **bounds** (Rectangle)  
- **flat** (bool)  
- **rightToLeft** (RightToLeft)  

**Returns** Rectangle

---

**GetButtonRect**(**bounds**: Rectangle, **flat**: bool, **buttonWidth**: int, **rightToLeft**: RightToLeft): Rectangle

**Parameters**

- **bounds** (Rectangle)  
- **flat** (bool)  
- **buttonWidth** (int)  
- **rightToLeft** (RightToLeft)  

**Returns** Rectangle


---

#### GetContentRect `static`

**GetContentRect**(**bounds**: Rectangle, **flat**: bool, **rightToLeft**: RightToLeft): Rectangle

**Parameters**

- **bounds** (Rectangle)  
- **flat** (bool)  
- **rightToLeft** (RightToLeft)  

**Returns** Rectangle


---

#### GetItemBackground `static`

**GetItemBackground**(**isItemSelected**: bool, **isMouseOver**: bool, **isBoxFocused**: bool): Color

**Parameters**

- **isItemSelected** (bool)  
- **isMouseOver** (bool)  
- **isBoxFocused** (bool)  

**Returns** Color


---

#### GetItemForeground `static`

**GetItemForeground**(**state**: DrawItemState, **baseColor**: Color?): Color

**Parameters**

- **state** (DrawItemState)  
- **baseColor** (Color?)  

**Returns** Color

---

**GetItemForeground**(**isItemSelected**: bool, **isItemMouseOver**: bool, **isBoxFocused**: bool, **baseColor**: Color?): Color

**Parameters**

- **isItemSelected** (bool)  
- **isItemMouseOver** (bool)  
- **isBoxFocused** (bool)  
- **baseColor** (Color?)  

**Returns** Color

---

**GetItemForeground**(**isItemSelected**: bool, **isItemMouseOver**: bool, **isBoxFocused**: bool, **isBoxDisabled**: bool, **baseColor**: Color?): Color

**Parameters**

- **isItemSelected** (bool)  
- **isItemMouseOver** (bool)  
- **isBoxFocused** (bool)  
- **isBoxDisabled** (bool)  
- **baseColor** (Color?)  

**Returns** Color


---

#### ScrollWindow `static`

**ScrollWindow**(**hWnd**: IntPtr, **xAmount**: int, **yAmount**: int): bool

Scrolls the contents of the specified window's client area.

**Parameters**

- **hWnd** (IntPtr) — Handle to the window where the client area is to be scrolled.  
- **xAmount** (int) — Specifies the amount, in device units, of horizontal scrolling.  
- **yAmount** (int) — Specifies the amount, in device units, of vertical scrolling.  

**Returns** bool — If the function succeeds, the return value is true.

