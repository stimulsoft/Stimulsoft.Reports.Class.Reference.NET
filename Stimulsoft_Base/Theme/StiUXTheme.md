---
title: "StiUXTheme Class"
---

## StiUXTheme Class

**Namespace:** `Stimulsoft.Base.Theme`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AccentColor** `static` | [StiThemeAccentColor](StiThemeAccentColor.md) |  |
| **ActualAppTheme** `static` | [StiAppThemeAppearance](StiAppThemeAppearance.md) |  |
| **Appearance** `static` | [StiThemeAppearance](StiThemeAppearance.md) |  |
| **CustomAccentColor** `static` | Color |  |
| **IconSet** `static` | [StiUIIconSet](../Drawing/StiUIIconSet.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyNewIconSet** `static` | void |  |
| **ApplyNewTheme** `static` *(+5 overloads)* | bool |  |

---

### Method Details

#### ApplyNewIconSet `static`

**ApplyNewIconSet**(**iconSet**: [StiUIIconSet](../Drawing/StiUIIconSet.md), **saveChanged**: bool): void

**Parameters**

- **iconSet** ([StiUIIconSet](../Drawing/StiUIIconSet.md))  
- **saveChanged** (bool)  


---

#### ApplyNewTheme `static`

**ApplyNewTheme**(**appearance**: [StiThemeAppearance](StiThemeAppearance.md), **saveChanged**: bool): bool

**Parameters**

- **appearance** ([StiThemeAppearance](StiThemeAppearance.md))  
- **saveChanged** (bool)  

**Returns** bool

---

**ApplyNewTheme**(**accentColor**: [StiThemeAccentColor](StiThemeAccentColor.md), **saveChanged**: bool): bool

**Parameters**

- **accentColor** ([StiThemeAccentColor](StiThemeAccentColor.md))  
- **saveChanged** (bool)  

**Returns** bool

---

**ApplyNewTheme**(**accentColor**: [StiThemeAccentColor](StiThemeAccentColor.md), **customAccentColor**: Color, **saveChanged**: bool): bool

**Parameters**

- **accentColor** ([StiThemeAccentColor](StiThemeAccentColor.md))  
- **customAccentColor** (Color)  
- **saveChanged** (bool)  

**Returns** bool

---

**ApplyNewTheme**(**appearance**: [StiThemeAppearance](StiThemeAppearance.md), **accentColor**: [StiThemeAccentColor](StiThemeAccentColor.md), **saveChanged**: bool): bool

**Parameters**

- **appearance** ([StiThemeAppearance](StiThemeAppearance.md))  
- **accentColor** ([StiThemeAccentColor](StiThemeAccentColor.md))  
- **saveChanged** (bool)  

**Returns** bool

---

**ApplyNewTheme**(**appearance**: [StiThemeAppearance](StiThemeAppearance.md), **accentColor**: [StiThemeAccentColor](StiThemeAccentColor.md), **customAccentColor**: Color, **saveChanged**: bool): bool

**Parameters**

- **appearance** ([StiThemeAppearance](StiThemeAppearance.md))  
- **accentColor** ([StiThemeAccentColor](StiThemeAccentColor.md))  
- **customAccentColor** (Color)  
- **saveChanged** (bool)  

**Returns** bool

---

**ApplyNewTheme**(**customAccentColor**: Color, **saveChanged**: bool): bool

**Parameters**

- **customAccentColor** (Color)  
- **saveChanged** (bool)  

**Returns** bool


### Events

| Event | Type | Description |
| --- | --- | --- |
| **ActualColorChanged** | EventHandler |  |
| **IconSetChanged** | EventHandler |  |
| **ThemeChanged** | EventHandler |  |
| **ThemeInternalChanged** | EventHandler |  |
| **ViewerIconSetChanged** | EventHandler |  |
