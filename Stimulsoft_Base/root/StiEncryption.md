---
title: "StiEncryption Class"
---

## StiEncryption Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Decrypt** `static` *(+2 overloads)* | byte[] |  |
| **Encrypt** `static` *(+2 overloads)* | byte[] |  |
| **GenerateRandomKey** `static` | byte[] |  |

---

### Method Details

#### Decrypt `static`

**Decrypt**(****: bytesrc, ****: bytekey): byte[]

**Parameters**

- **** (bytesrc)  
- **** (bytekey)  

**Returns** byte[]

---

**Decrypt**(****: bytesrc, **password**: string, **reuseSrcBuffer**: bool): byte[]

**Parameters**

- **** (bytesrc)  
- **password** (string)  
- **reuseSrcBuffer** (bool)  

**Returns** byte[]

---

**Decrypt**(**src**: string, **password**: string): string

**Parameters**

- **src** (string)  
- **password** (string)  

**Returns** string


---

#### Encrypt `static`

**Encrypt**(****: bytesrc, ****: bytekey): byte[]

**Parameters**

- **** (bytesrc)  
- **** (bytekey)  

**Returns** byte[]

---

**Encrypt**(****: bytesrc, **password**: string): byte[]

**Parameters**

- **** (bytesrc)  
- **password** (string)  

**Returns** byte[]

---

**Encrypt**(**src**: string, **password**: string): string

**Parameters**

- **src** (string)  
- **password** (string)  

**Returns** string


---

#### GenerateRandomKey `static`

**GenerateRandomKey**(): byte[]

**Returns** byte[]

