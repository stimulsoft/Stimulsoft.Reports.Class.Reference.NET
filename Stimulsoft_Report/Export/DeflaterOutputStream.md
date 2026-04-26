---
title: "DeflaterOutputStream Class"
---

## DeflaterOutputStream Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: Stream  

### Constructors

| Constructor | Description |
| --- | --- |
| **DeflaterOutputStream**(Stream baseOutputStream) |  |
| **DeflaterOutputStream**(Stream baseOutputStream, [Deflater](Deflater.md) defl) |  |
| **DeflaterOutputStream**(Stream baseOutputStream, [Deflater](Deflater.md) defl, int bufsize) |  |

**DeflaterOutputStream**(**baseOutputStream**: Stream)

**Parameters**

- **baseOutputStream** (Stream)  

---

**DeflaterOutputStream**(**baseOutputStream**: Stream, **defl**: [Deflater](Deflater.md))

**Parameters**

- **baseOutputStream** (Stream)  
- **defl** ([Deflater](Deflater.md))  

---

**DeflaterOutputStream**(**baseOutputStream**: Stream, **defl**: [Deflater](Deflater.md), **bufsize**: int)

**Parameters**

- **baseOutputStream** (Stream)  
- **defl** ([Deflater](Deflater.md))  
- **bufsize** (int)  


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
| **deflate** | void |  |

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

#### deflate

**deflate**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **baseOutputStream** | Stream |  |
| **buf** | byte[] |  |
| **def** | [Deflater](Deflater.md) |  |
| **isStreamOwnerValue** | bool |  |
