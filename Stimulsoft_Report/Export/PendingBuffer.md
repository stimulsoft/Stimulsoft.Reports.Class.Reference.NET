---
title: "PendingBuffer Class"
---

## PendingBuffer Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **PendingBuffer**() |  |
| **PendingBuffer**(int bufsize) |  |

**PendingBuffer**()

---

**PendingBuffer**(**bufsize**: int)

**Parameters**

- **bufsize** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlignToByte** | void |  |
| **Flush** | int |  |
| **Reset** | void |  |
| **ToByteArray** | byte[] |  |
| **WriteBits** | void |  |
| **WriteBlock** | void |  |
| **WriteByte** | void |  |
| **WriteInt** | void |  |
| **WriteShort** | void |  |
| **WriteShortMSB** | void |  |

---

### Method Details

#### AlignToByte

**AlignToByte**(): void


---

#### Flush

**Flush**(****: byteoutput, **offset**: int, **length**: int): int

**Parameters**

- **** (byteoutput)  
- **offset** (int)  
- **length** (int)  

**Returns** int


---

#### Reset

**Reset**(): void


---

#### ToByteArray

**ToByteArray**(): byte[]

**Returns** byte[]


---

#### WriteBits

**WriteBits**(**b**: int, **count**: int): void

**Parameters**

- **b** (int)  
- **count** (int)  


---

#### WriteBlock

**WriteBlock**(****: byteblock, **offset**: int, **len**: int): void

**Parameters**

- **** (byteblock)  
- **offset** (int)  
- **len** (int)  


---

#### WriteByte

**WriteByte**(**b**: int): void

**Parameters**

- **b** (int)  


---

#### WriteInt

**WriteInt**(**s**: int): void

**Parameters**

- **s** (int)  


---

#### WriteShort

**WriteShort**(**s**: int): void

**Parameters**

- **s** (int)  


---

#### WriteShortMSB

**WriteShortMSB**(**s**: int): void

**Parameters**

- **s** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **buf** | byte[] |  |
