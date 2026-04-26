---
title: "StiMapToolboxInfo Class"
---

## StiMapToolboxInfo Class

**Namespace:** `Stimulsoft.Report.Toolbox`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMapToolboxInfo**([StiMapID](../Maps/StiMapID.md) mapID) |  |
| **StiMapToolboxInfo**([StiMapID](../Maps/StiMapID.md) mapID, stringlocalization ) |  |
| **StiMapToolboxInfo**(string customMapID, byteicon ) |  |
| **StiMapToolboxInfo**([StiMapCategory](../Maps/StiMapCategory.md) category, string locEnName, string locRuName) |  |

**StiMapToolboxInfo**(**mapID**: [StiMapID](../Maps/StiMapID.md))

**Parameters**

- **mapID** ([StiMapID](../Maps/StiMapID.md))  

---

**StiMapToolboxInfo**(**mapID**: [StiMapID](../Maps/StiMapID.md), ****: stringlocalization)

**Parameters**

- **mapID** ([StiMapID](../Maps/StiMapID.md))  
- **** (stringlocalization)  

---

**StiMapToolboxInfo**(**customMapID**: string, ****: byteicon)

**Parameters**

- **customMapID** (string)  
- **** (byteicon)  

---

**StiMapToolboxInfo**(**category**: [StiMapCategory](../Maps/StiMapCategory.md), **locEnName**: string, **locRuName**: string)

**Parameters**

- **category** ([StiMapCategory](../Maps/StiMapCategory.md))  
- **locEnName** (string)  
- **locRuName** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Allow3D** | bool |  |
| **Category** | StiMapCategory? |  |
| **CustomIcon** | byte[] |  |
| **Icon** | string |  |
| **Infos** | List<[StiMapToolboxInfo](StiMapToolboxInfo.md)> |  |
| **Language** | string[] |  |
| **LocEnName** | string |  |
| **LocRuName** | string |  |
| **MapID** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetLangOriginalName** | string |  |
| **ToString** | string |  |

---

### Method Details

#### GetLangOriginalName

**GetLangOriginalName**(**id**: string): string

**Parameters**

- **id** (string)  

**Returns** string


---

#### ToString

**ToString**(): string

**Returns** string

