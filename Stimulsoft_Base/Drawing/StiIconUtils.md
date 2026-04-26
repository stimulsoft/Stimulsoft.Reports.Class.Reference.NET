---
title: "StiIconUtils Class"
---

## StiIconUtils Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetIcon** `static` *(+2 overloads)* | [Icon](../../Stimulsoft_Drawing/root/Icon.md) | Gets the Icon object associated with Type. |
| **GetIconStream** `static` *(+1 overloads)* | Stream | Gets the Icon object placed in assembly. |
| **ResizeIcon** `static` | [Icon](../../Stimulsoft_Drawing/root/Icon.md) | Resizes icon to specified size. |
| **ToIcon** `static` | [Icon](../../Stimulsoft_Drawing/root/Icon.md) | Converts Image to an Icon. |

---

### Method Details

#### GetIcon `static`

**GetIcon**(**type**: Type, **iconName**: string): [Icon](../../Stimulsoft_Drawing/root/Icon.md)

Gets the Icon object associated with Type.

**Parameters**

- **type** (Type) — The type with which the Icon object is associated.  
- **iconName** (string) — The name of the icon file to look for.  

**Returns** [Icon](../../Stimulsoft_Drawing/root/Icon.md) — The Icon object.

---

**GetIcon**(**assemblyName**: string, **iconName**: string): [Icon](../../Stimulsoft_Drawing/root/Icon.md)

Gets the Icon object placed in assembly.

**Parameters**

- **assemblyName** (string) — The name of assembly in which the Icon object is placed.  
- **iconName** (string) — The name of the Icon file to look for.  

**Returns** [Icon](../../Stimulsoft_Drawing/root/Icon.md) — The Icon object.

---

**GetIcon**(**cursorAssembly**: Assembly, **iconName**: string): [Icon](../../Stimulsoft_Drawing/root/Icon.md)

Gets the Icon object placed in assembly.

**Parameters**

- **cursorAssembly** (Assembly) — Assembly in which the Icon object is placed.  
- **iconName** (string) — The name of the Icon file to look for.  

**Returns** [Icon](../../Stimulsoft_Drawing/root/Icon.md) — The Icon object.


---

#### GetIconStream `static`

**GetIconStream**(**assemblyName**: string, **iconName**: string): Stream

Gets the Icon object placed in assembly.

**Parameters**

- **assemblyName** (string) — The name of assembly in which the Icon object is placed.  
- **iconName** (string) — The name of the Icon file to look for.  

**Returns** Stream — The Icon object.

---

**GetIconStream**(**cursorAssembly**: Assembly, **iconName**: string): Stream

Gets the Icon object placed in assembly.

**Parameters**

- **cursorAssembly** (Assembly) — Assembly in which the Icon object is placed.  
- **iconName** (string) — The name of the Icon file to look for.  

**Returns** Stream — The Icon object.


---

#### ResizeIcon `static`

**ResizeIcon**(**icon**: [Icon](../../Stimulsoft_Drawing/root/Icon.md), **width**: int, **height**: int): [Icon](../../Stimulsoft_Drawing/root/Icon.md)

Resizes icon to specified size.

**Parameters**

- **icon** ([Icon](../../Stimulsoft_Drawing/root/Icon.md))  
- **width** (int)  
- **height** (int)  

**Returns** [Icon](../../Stimulsoft_Drawing/root/Icon.md)


---

#### ToIcon `static`

**ToIcon**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md)): [Icon](../../Stimulsoft_Drawing/root/Icon.md)

Converts Image to an Icon.

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  

**Returns** [Icon](../../Stimulsoft_Drawing/root/Icon.md)

