---
title: "FontsInfoStore Class"
---

## FontsInfoStore Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **FontsInfoStore**() |  |

**FontsInfoStore**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearFontsInfoStore** `static` | void |  |
| **LoadFontInfoToStore** `static` *(+2 overloads)* | void |  |
| **SetIndex** | void |  |

---

### Method Details

#### ClearFontsInfoStore `static`

**ClearFontsInfoStore**(): void


---

#### LoadFontInfoToStore `static`

**LoadFontInfoToStore**(**fontName**: string, ****: bytedata): void

**Parameters**

- **fontName** (string)  
- **** (bytedata)  

---

**LoadFontInfoToStore**(**fontName**: string, **stream**: Stream): void

**Parameters**

- **fontName** (string)  
- **stream** (Stream)  

---

**LoadFontInfoToStore**(**fontName**: string, **path**: string): void

**Parameters**

- **fontName** (string)  
- **path** (string)  


---

#### SetIndex

**SetIndex**(**index**: int): void

**Parameters**

- **index** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Data** | byte[] |  |
| **Data** | byte[] |  |
| **Glyphs** | ushort[] |  |
| **Glyphs** | ushort[] |  |
| **NeedSyntBold** | bool |  |
| **NeedSyntBold** | bool |  |
| **NeedSyntItalic** | bool |  |
| **NeedSyntItalic** | bool |  |
| **OTM** | byte[] |  |
| **OTM** | byte[] |  |
| **StylesInfo** | FontStyleInfo[] |  |
| **Widths** | ushort[] |  |
| **Widths** | ushort[] |  |
