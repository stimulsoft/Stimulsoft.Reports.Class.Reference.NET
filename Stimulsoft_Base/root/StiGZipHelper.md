---
title: "StiGZipHelper Class"
---

## StiGZipHelper Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertByteArrayToString** `static` | string |  |
| **ConvertStringToByteArray** `static` | byte[] |  |
| **Pack** `static` *(+2 overloads)* | string |  |
| **Unpack** `static` *(+3 overloads)* | string |  |

---

### Method Details

#### ConvertByteArrayToString `static`

**ConvertByteArrayToString**(****: bytebytes): string

**Parameters**

- **** (bytebytes)  

**Returns** string


---

#### ConvertStringToByteArray `static`

**ConvertStringToByteArray**(**str**: string): byte[]

**Parameters**

- **str** (string)  

**Returns** byte[]


---

#### Pack `static`

**Pack**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string

---

**Pack**(****: bytebytes): byte[]

**Parameters**

- **** (bytebytes)  

**Returns** byte[]

---

**Pack**(**stream**: Stream): Stream

**Parameters**

- **stream** (Stream)  

**Returns** Stream


---

#### Unpack `static`

**Unpack**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string

---

**Unpack**(****: bytebytes): byte[]

**Parameters**

- **** (bytebytes)  

**Returns** byte[]

---

**Unpack**(**stream**: Stream): Stream

**Parameters**

- **stream** (Stream)  

**Returns** Stream

---

**Unpack**(**stream**: Stream, **resultStream**: Stream): void

**Parameters**

- **stream** (Stream)  
- **resultStream** (Stream)  

