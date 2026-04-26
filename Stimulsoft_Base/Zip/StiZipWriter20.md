---
title: "StiZipWriter20 Class"
---

## StiZipWriter20 Class

**Namespace:** `Stimulsoft.Base.Zip`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiZipWriter20**() |  |

**StiZipWriter20**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddFile** *(+4 overloads)* | void |  |
| **Begin** | void |  |
| **Close** *(+1 overloads)* | void |  |
| **CloseEntry** | void | Close current entry |
| **End** | void |  |
| **Finish** *(+1 overloads)* | void |  |
| **Flush** | void |  |
| **PutNextEntry** | void | Put next entry into Zip file |
| **Read** | int |  |
| **ReadByte** | int |  |
| **Reset** | void |  |
| **Seek** | long |  |
| **SetLength** | void |  |
| **Write** *(+1 overloads)* | void |  |
| **WriteByte** | void |  |

---

### Method Details

#### AddFile

**AddFile**(**fileName**: string, **dataStream**: MemoryStream): void

**Parameters**

- **fileName** (string)  
- **dataStream** (MemoryStream)  

---

**AddFile**(**fileName**: string, **sourceFileName**: string): void

**Parameters**

- **fileName** (string)  
- **sourceFileName** (string)  

---

**AddFile**(**fileName**: string, **sourceFileName**: string, **useUnicodeFileName**: bool): void

**Parameters**

- **fileName** (string)  
- **sourceFileName** (string)  
- **useUnicodeFileName** (bool)  

---

**AddFile**(**fileName**: string, **dataStream**: MemoryStream, **closeDataStream**: bool): void

**Parameters**

- **fileName** (string)  
- **dataStream** (MemoryStream)  
- **closeDataStream** (bool)  

---

**AddFile**(**fileName**: string, **dataStream**: MemoryStream, **closeDataStream**: bool, **useUnicodeFileName**: bool): void

**Parameters**

- **fileName** (string)  
- **dataStream** (MemoryStream)  
- **closeDataStream** (bool)  
- **useUnicodeFileName** (bool)  


---

#### Begin

**Begin**(**stream**: Stream, **leaveOpen**: bool): void

**Parameters**

- **stream** (Stream)  
- **leaveOpen** (bool)  


---

#### Close

**Close**(): void

---

**Close**(): void


---

#### CloseEntry

**CloseEntry**(): void

Close current entry


---

#### End

**End**(): void


---

#### Finish

**Finish**(): void

---

**Finish**(): void


---

#### Flush

**Flush**(): void


---

#### PutNextEntry

**PutNextEntry**(**entry**: ZipEntry): void

Put next entry into Zip file

**Parameters**

- **entry** (ZipEntry) — Entry to put into zip file  


---

#### Read

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

#### Reset

**Reset**(): void


---

#### Seek

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

#### Write

**Write**(****: bytebuffer, **offset**: int, **count**: int): void

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  

---

**Write**(****: bytebuffer, **offset**: int, **count**: int): void

Write data to the current entry

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  


---

#### WriteByte

**WriteByte**(**value**: byte): void

**Parameters**

- **value** (byte)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CentralHeaderBaseSize** | int |  |
| **CentralHeaderSignature** | int |  |
| **DataDescriptorSignature** | int |  |
| **DataDescriptorSize** | int |  |
| **DefaultEncoding** | Encoding |  |
| **EndOfCentralDirectorySignature** | int |  |
| **LocalHeaderBaseSize** | int |  |
| **LocalHeaderSignature** | int |  |
| **TotalOut** | int |  |
| **Version** | int |  |
| **baseOutputStream** | Stream |  |
