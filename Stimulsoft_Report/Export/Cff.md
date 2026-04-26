---
title: "Cff Class"
---

## Cff Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CutUnusedSubr** | void |  |
| **GetBaseTablesString** | string |  |
| **GetNewTablesString** | string |  |
| **GetSize** | int |  |
| **Read** | void |  |
| **Save** | byte[] |  |

---

### Method Details

#### CutUnusedSubr

**CutUnusedSubr**(): void


---

#### GetBaseTablesString

**GetBaseTablesString**(): string

**Returns** string


---

#### GetNewTablesString

**GetNewTablesString**(): string

**Returns** string


---

#### GetSize

**GetSize**(): int

**Returns** int


---

#### Read

**Read**(****: bytefontBytes, **offset**: int, **length**: int): void

**Parameters**

- **** (bytefontBytes)  
- **offset** (int)  
- **length** (int)  


---

#### Save

**Save**(): byte[]

**Returns** byte[]


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **GlobalSubrIndex** | Index |  |
| **GlyphsNeed** | bool[] |  |
| **Header** | Cff_Header |  |
| **NameIndex** | Index |  |
| **Offset** | Int32 |  |
| **StringIndex** | StiStringIndex |  |
| **TablesList** | List<Block> |  |
| **TopDictIndex** | DictIndex |  |
