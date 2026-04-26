---
title: "Crc32 Class"
---

## Crc32 Class

**Namespace:** `Stimulsoft.Base.Crypto`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Calculate** `static` | long | Calculate CRC32 checksum of the byte array. |
| **Reset** | void | Resets the CRC32 data checksum as if no update was ever called. |
| **Update** | void | Adds the byte array to the data checksum. |

---

### Method Details

#### Calculate `static`

**Calculate**(****: bytebuffer): long

Calculate CRC32 checksum of the byte array.

**Parameters**

- **** (bytebuffer)  

**Returns** long — The ckecksum


---

#### Reset

**Reset**(): void

Resets the CRC32 data checksum as if no update was ever called.


---

#### Update

**Update**(****: bytebuffer, **offset**: int, **count**: int): void

Adds the byte array to the data checksum.

**Parameters**

- **** (bytebuffer)  
- **offset** (int)  
- **count** (int)  

