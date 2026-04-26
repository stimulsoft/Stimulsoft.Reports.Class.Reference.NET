---
title: "StiCachedStream Class"
---

## StiCachedStream Class

**Namespace:** `Stimulsoft.Report.Export.Tools`

### Inheritance

Inherits from: MemoryStream  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCachedStream**() |  |

**StiCachedStream**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **SizeLimitToStartUseCache** `static` | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void |  |
| **Finish** | void |  |
| **Flush** | void |  |
| **Read** | int |  |
| **ReadByte** | int |  |
| **Seek** | long |  |
| **SetLength** | void |  |
| **Write** | void |  |
| **WriteByte** | void |  |
| **WriteTo** | void |  |

---

### Method Details

#### Close

**Close**(): void


---

#### Finish

**Finish**(): void


---

#### Flush

**Flush**(): void


---

#### Read

**Read**(****: byteb, **off**: int, **len**: int): int

**Parameters**

- **** (byteb)  
- **off** (int)  
- **len** (int)  

**Returns** int


---

#### ReadByte

**ReadByte**(): int

**Returns** int


---

#### Seek

**Seek**(**offset**: long, **origin**: SeekOrigin): long

**Parameters**

- **offset** (long)  
- **origin** (SeekOrigin)  

**Returns** long


---

#### SetLength

**SetLength**(**val**: long): void

**Parameters**

- **val** (long)  


---

#### Write

**Write**(****: bytebuf, **off**: int, **len**: int): void

**Parameters**

- **** (bytebuf)  
- **off** (int)  
- **len** (int)  


---

#### WriteByte

**WriteByte**(**bval**: byte): void

**Parameters**

- **bval** (byte)  


---

#### WriteTo

**WriteTo**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  

