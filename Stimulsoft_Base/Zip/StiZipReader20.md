---
title: "StiZipReader20 Class"
---

## StiZipReader20 Class

**Namespace:** `Stimulsoft.Base.Zip`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiZipReader20**(string path) |  |
| **StiZipReader20**(Stream stream) |  |

**StiZipReader20**(**path**: string)

**Parameters**

- **path** (string)  

---

**StiZipReader20**(**stream**: Stream)

**Parameters**

- **stream** (Stream)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Close** *(+1 overloads)* | void |  |
| **ConvertToStringExt** `static` | string |  |
| **Dispose** | void |  |
| **Find** | bool |  |
| **Flush** *(+1 overloads)* | void |  |
| **GetEntryStream** | Stream |  |
| **Read** *(+1 overloads)* | int |  |
| **ReadByte** | int |  |
| **ReadFully** `static` *(+1 overloads)* | void |  |
| **ReadInt** | int |  |
| **ReadLEInt** | int |  |
| **ReadLELong** | long |  |
| **ReadLEShort** | int |  |
| **ReadLong** | long |  |
| **Seek** *(+1 overloads)* | long |  |
| **SetLength** *(+1 overloads)* | void |  |
| **Write** *(+1 overloads)* | void |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### Close

**Close**(): void

---

**Close**(): void


---

#### ConvertToStringExt `static`

**ConvertToStringExt**(**flags**: int, ****: bytedata, **count**: int): string

**Parameters**

- **flags** (int)  
- **** (bytedata)  
- **count** (int)  

**Returns** string


---

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### Find

**Find**(**headerID**: int): bool

**Parameters**

- **headerID** (int)  

**Returns** bool


---

#### Flush

**Flush**(): void

---

**Flush**(): void


---

#### GetEntryStream

**GetEntryStream**(**entry**: StiZipEntry): Stream

**Parameters**

- **entry** (StiZipEntry)  

**Returns** Stream


---

#### Read

**Read**(****: bytebuffer, **offset**: int, **count**: int): int

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  

**Returns** int

---

**Read**(****: bytebuffer, **offset**: int, **count**: int): int

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  

**Returns** int


---

#### ReadByte

**ReadByte**(): int

**Returns** int


---

#### ReadFully `static`

**ReadFully**(**stream**: Stream, ****: bytebuffer): void

**Parameters**

- **stream** (Stream)  
- **** (bytebuffer)  

---

**ReadFully**(**stream**: Stream, ****: bytebuffer, **offset**: int, **count**: int): void

**Parameters**

- **stream** (Stream)  
- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  


---

#### ReadInt

**ReadInt**(): int

**Returns** int


---

#### ReadLEInt

**ReadLEInt**(): int

**Returns** int


---

#### ReadLELong

**ReadLELong**(): long

**Returns** long


---

#### ReadLEShort

**ReadLEShort**(): int

**Returns** int


---

#### ReadLong

**ReadLong**(): long

**Returns** long


---

#### Seek

**Seek**(**offset**: long, **origin**: SeekOrigin): long

**Parameters**

- **offset** (long)  
- **origin** (SeekOrigin)  

**Returns** long

---

**Seek**(**offset**: long, **origin**: SeekOrigin): long

**Parameters**

- **offset** (long)  
- **origin** (SeekOrigin)  

**Returns** long


---

#### SetLength

**SetLength**(**value**: long): void

**Parameters**

- **value** (long)  

---

**SetLength**(**value**: long): void

**Parameters**

- **value** (long)  


---

#### Write

**Write**(****: bytebuffer, **offset**: int, **count**: int): void

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  

---

**Write**(****: bytebuffer, **offset**: int, **count**: int): void

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CentralHeaderSignature** | int |  |
| **EndOfCentralDirectorySignature** | int |  |
| **EndOfCentralRecordBaseSize** | int |  |
| **LocalHeaderBaseSize** | int |  |
| **LocalHeaderSignature** | int |  |
| **VersionMadeBy** | int |  |
| **VersionZip64** | int |  |
| **Zip64CentralDirLocatorSignature** | int |  |
| **Zip64CentralFileHeaderSignature** | int |  |
