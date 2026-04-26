---
title: "FontV Class"
---

## FontV Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **FontV**(string name, bytecontent , string path, string extension, bool allowFileCache, string hash, [PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md) masterFontCollection) |  |

**FontV**(**name**: string, ****: bytecontent, **path**: string, **extension**: string, **allowFileCache**: bool, **hash**: string, **masterFontCollection**: [PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md))

**Parameters**

- **name** (string)  
- **** (bytecontent)  
- **path** (string)  
- **extension** (string)  
- **allowFileCache** (bool)  
- **hash** (string)  
- **masterFontCollection** ([PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FilePath** | string |  |
| **IsCachePath** | bool |  |
| **Name** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetFontFamily** | [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md) |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### GetFontFamily

**GetFontFamily**(**name**: string): [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)

**Parameters**

- **name** (string)  

**Returns** [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Content** | byte[] |  |
