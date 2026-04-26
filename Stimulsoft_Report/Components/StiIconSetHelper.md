---
title: "StiIconSetHelper Class"
---

## StiIconSetHelper Class

**Namespace:** `Stimulsoft.Report.Components`

Class helps in working with Icon Set images.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetIcon** `static` *(+1 overloads)* | [Image](../../Stimulsoft_Drawing/root/Image.md) | Returns image for specified icon key. |
| **GetIconSet** `static` | [StiIcon](StiIcon.md)[] | Returns array of icon keys for specified Icon Set. |
| **GetIcons** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md)[] | Returns aray of icon images for specified Icon Set. |

---

### Method Details

#### GetIcon `static`

**GetIcon**(**icon**: [StiIcon](StiIcon.md)): [Image](../../Stimulsoft_Drawing/root/Image.md)

Returns image for specified icon key.

**Parameters**

- **icon** ([StiIcon](StiIcon.md)) — Specified icon key.  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md) — Image for specified icon key.

---

**GetIcon**(**indicator**: StiIconSetIndicator): [Image](../../Stimulsoft_Drawing/root/Image.md)

Returns image for specified indicator.

**Parameters**

- **indicator** (StiIconSetIndicator)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md) — Image for specified indicator.


---

#### GetIconSet `static`

**GetIconSet**(**iconSet**: [StiIconSet](StiIconSet.md)): [StiIcon](StiIcon.md)[]

Returns array of icon keys for specified Icon Set.

**Parameters**

- **iconSet** ([StiIconSet](StiIconSet.md)) — Specified Icon Set.  

**Returns** [StiIcon](StiIcon.md)[] — Array of icon keys.


---

#### GetIcons `static`

**GetIcons**(**iconSet**: [StiIconSet](StiIconSet.md)): [Image](../../Stimulsoft_Drawing/root/Image.md)[]

Returns aray of icon images for specified Icon Set.

**Parameters**

- **iconSet** ([StiIconSet](StiIconSet.md)) — Specified Icon Set.  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)[] — Array of icon images.

