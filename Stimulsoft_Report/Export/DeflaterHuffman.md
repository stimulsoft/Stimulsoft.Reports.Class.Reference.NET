---
title: "DeflaterHuffman Class"
---

## DeflaterHuffman Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **DeflaterHuffman**([DeflaterPending](DeflaterPending.md) pending) |  |

**DeflaterHuffman**(**pending**: [DeflaterPending](DeflaterPending.md))

**Parameters**

- **pending** ([DeflaterPending](DeflaterPending.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BitReverse** `static` | short |  |
| **CompressBlock** | void |  |
| **FlushBlock** | void |  |
| **FlushStoredBlock** | void |  |
| **IsFull** | bool |  |
| **Reset** | void |  |
| **SendAllTrees** | void |  |
| **TallyDist** | bool |  |
| **TallyLit** | bool |  |

---

### Method Details

#### BitReverse `static`

**BitReverse**(**value**: int): short

**Parameters**

- **value** (int)  

**Returns** short


---

#### CompressBlock

**CompressBlock**(): void


---

#### FlushBlock

**FlushBlock**(****: bytestored, **stored_offset**: int, **stored_len**: int, **lastBlock**: bool): void

**Parameters**

- **** (bytestored)  
- **stored_offset** (int)  
- **stored_len** (int)  
- **lastBlock** (bool)  


---

#### FlushStoredBlock

**FlushStoredBlock**(****: bytestored, **stored_offset**: int, **stored_len**: int, **lastBlock**: bool): void

**Parameters**

- **** (bytestored)  
- **stored_offset** (int)  
- **stored_len** (int)  
- **lastBlock** (bool)  


---

#### IsFull

**IsFull**(): bool

**Returns** bool


---

#### Reset

**Reset**(): void


---

#### SendAllTrees

**SendAllTrees**(**blTreeCodes**: int): void

**Parameters**

- **blTreeCodes** (int)  


---

#### TallyDist

**TallyDist**(**dist**: int, **len**: int): bool

**Parameters**

- **dist** (int)  
- **len** (int)  

**Returns** bool


---

#### TallyLit

**TallyLit**(**lit**: int): bool

**Parameters**

- **lit** (int)  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **pending** | [DeflaterPending](DeflaterPending.md) |  |
