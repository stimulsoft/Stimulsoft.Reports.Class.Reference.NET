---
title: "StiControlColorCollection Class"
---

## StiControlColorCollection Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiControlColorCollection**(Control control) |  |

**StiControlColorCollection**(**control**: Control)

**Parameters**

- **control** (Control)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BackColor** | Color |  |
| **ForeColor** | Color |  |
| **GlyphColor** | Color |  |
| **HotBackColor** | Color |  |
| **HotForeColor** | Color |  |
| **HotGlyphColor** | Color |  |
| **HotSelectedBackColor** | Color |  |
| **HotSelectedForeColor** | Color |  |
| **HotSelectedGlyphColor** | Color |  |
| **IconSet** | [StiDashboardViewerUIIconSet](../../Stimulsoft_Base/Drawing/StiDashboardViewerUIIconSet.md) |  |
| **IsDarkMode** | bool |  |
| **SelectedBackColor** | Color |  |
| **SelectedForeColor** | Color |  |
| **SelectedGlyphColor** | Color |  |
| **SeparatorColor** | Color |  |
| **StyleIdent** | [StiElementStyleIdent](../../Stimulsoft_Report/Dashboard/StiElementStyleIdent.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetActionColors** `static` | [StiControlColorCollection](StiControlColorCollection.md) |  |
| **GetBackColor** | Color |  |
| **GetElementColors** `static` | [StiControlColorCollection](StiControlColorCollection.md) |  |
| **GetForeColor** | Color |  |
| **GetGlyphColor** | Color |  |
| **GetSeparatorColor** | Color |  |

---

### Method Details

#### GetActionColors `static`

**GetActionColors**(**element**: IStiElement, **isDarkMode**: bool?): [StiControlColorCollection](StiControlColorCollection.md)

**Parameters**

- **element** (IStiElement)  
- **isDarkMode** (bool?)  

**Returns** [StiControlColorCollection](StiControlColorCollection.md)


---

#### GetBackColor

**GetBackColor**(**isSelected**: bool, **isHot**: bool): Color

**Parameters**

- **isSelected** (bool)  
- **isHot** (bool)  

**Returns** Color


---

#### GetElementColors `static`

**GetElementColors**(**element**: IStiElement): [StiControlColorCollection](StiControlColorCollection.md)

**Parameters**

- **element** (IStiElement)  

**Returns** [StiControlColorCollection](StiControlColorCollection.md)


---

#### GetForeColor

**GetForeColor**(**isSelected**: bool, **isHot**: bool): Color

**Parameters**

- **isSelected** (bool)  
- **isHot** (bool)  

**Returns** Color


---

#### GetGlyphColor

**GetGlyphColor**(**isSelected**: bool, **isHot**: bool): Color

**Parameters**

- **isSelected** (bool)  
- **isHot** (bool)  

**Returns** Color


---

#### GetSeparatorColor

**GetSeparatorColor**(): Color

**Returns** Color

