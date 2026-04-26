---
title: "DeflaterEngine Class"
---

## DeflaterEngine Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [DeflaterConstants](DeflaterConstants.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **DeflaterEngine**([DeflaterPending](DeflaterPending.md) pending) |  |

**DeflaterEngine**(**pending**: [DeflaterPending](DeflaterPending.md))

**Parameters**

- **pending** ([DeflaterPending](DeflaterPending.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Deflate** | bool |  |
| **FillWindow** | void |  |
| **NeedsInput** | bool |  |
| **Reset** | void |  |
| **ResetAdler** | void |  |
| **SetDictionary** | void |  |
| **SetInput** | void |  |
| **SetLevel** | void |  |

---

### Method Details

#### Deflate

**Deflate**(**flush**: bool, **finish**: bool): bool

**Parameters**

- **flush** (bool)  
- **finish** (bool)  

**Returns** bool


---

#### FillWindow

**FillWindow**(): void


---

#### NeedsInput

**NeedsInput**(): bool

**Returns** bool


---

#### Reset

**Reset**(): void


---

#### ResetAdler

**ResetAdler**(): void


---

#### SetDictionary

**SetDictionary**(****: bytebuffer, **offset**: int, **length**: int): void

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **length** (int)  


---

#### SetInput

**SetInput**(****: bytebuf, **off**: int, **len**: int): void

**Parameters**

- **** (bytebuf)  
- **off** (int)  
- **len** (int)  


---

#### SetLevel

**SetLevel**(**lvl**: int): void

**Parameters**

- **lvl** (int)  

