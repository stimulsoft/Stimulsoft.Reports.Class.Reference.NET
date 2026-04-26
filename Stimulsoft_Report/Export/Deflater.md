---
title: "Deflater Class"
---

## Deflater Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **Deflater**() |  |
| **Deflater**(int lvl) |  |
| **Deflater**(int lvl, bool nowrap) |  |

**Deflater**()

---

**Deflater**(**lvl**: int)

**Parameters**

- **lvl** (int)  

---

**Deflater**(**lvl**: int, **nowrap**: bool)

**Parameters**

- **lvl** (int)  
- **nowrap** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Deflate** *(+1 overloads)* | int |  |
| **Finish** | void |  |
| **Flush** | void |  |
| **Reset** | void |  |
| **SetDictionary** *(+1 overloads)* | void |  |
| **SetInput** *(+1 overloads)* | void |  |
| **SetLevel** | void |  |
| **SetStrategy** | void |  |

---

### Method Details

#### Deflate

**Deflate**(****: byteoutput): int

**Parameters**

- **** (byteoutput)  

**Returns** int

---

**Deflate**(****: byteoutput, **offset**: int, **length**: int): int

**Parameters**

- **** (byteoutput)  
- **offset** (int)  
- **length** (int)  

**Returns** int


---

#### Finish

**Finish**(): void


---

#### Flush

**Flush**(): void


---

#### Reset

**Reset**(): void


---

#### SetDictionary

**SetDictionary**(****: bytedict): void

**Parameters**

- **** (bytedict)  

---

**SetDictionary**(****: bytedict, **offset**: int, **length**: int): void

**Parameters**

- **** (bytedict)  
- **offset** (int)  
- **length** (int)  


---

#### SetInput

**SetInput**(****: byteinput): void

**Parameters**

- **** (byteinput)  

---

**SetInput**(****: byteinput, **off**: int, **len**: int): void

**Parameters**

- **** (byteinput)  
- **off** (int)  
- **len** (int)  


---

#### SetLevel

**SetLevel**(**lvl**: int): void

**Parameters**

- **lvl** (int)  


---

#### SetStrategy

**SetStrategy**(**stgy**: [DeflateStrategy](DeflateStrategy.md)): void

**Parameters**

- **stgy** ([DeflateStrategy](DeflateStrategy.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **BEST_COMPRESSION** | int |  |
| **BEST_SPEED** | int |  |
| **DEFAULT_COMPRESSION** | int |  |
| **DEFLATED** | int |  |
| **NO_COMPRESSION** | int |  |
