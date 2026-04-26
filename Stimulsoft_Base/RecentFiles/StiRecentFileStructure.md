---
title: "StiRecentFileStructure Class"
---

## StiRecentFileStructure Class

**Namespace:** `Stimulsoft.Base.RecentFiles`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRecentFileStructure**() |  |

**StiRecentFileStructure**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Levels** | List<StiRecentFileStructureLevel> |  |
| **RootLevel** | StiRecentFileStructureLevel |  |
| **Sort** | [StiRecentFileStructureSort](StiRecentFileStructureSort.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GotoFolder** | bool |  |
| **MoveBack** | void |  |
| **MoveTo** | bool |  |
| **NewFolder** | bool |  |

---

### Method Details

#### GotoFolder

**GotoFolder**(**path**: string, **errorMessage**: string): bool

**Parameters**

- **path** (string)  
- **errorMessage** (string)  

**Returns** bool


---

#### MoveBack

**MoveBack**(): void


---

#### MoveTo

**MoveTo**(**item**: [StiRecentFileStructureItem](StiRecentFileStructureItem.md), **errorMessage**: string): bool

**Parameters**

- **item** ([StiRecentFileStructureItem](StiRecentFileStructureItem.md))  
- **errorMessage** (string)  

**Returns** bool


---

#### NewFolder

**NewFolder**(**name**: string, **errorMessage**: string): bool

**Parameters**

- **name** (string)  
- **errorMessage** (string)  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AllowLevelUp** | bool |  |
| **CurrentLevel** | StiRecentFileStructureLevel |  |
