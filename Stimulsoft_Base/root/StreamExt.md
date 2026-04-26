---
title: "StreamExt Class"
---

## StreamExt Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ReadAllBytes** `static` | byte[] |  |
| **ReadBytesExactly** `static` *(+1 overloads)* | byte[] | Reads exactly the number of bytes from the stream. |

---

### Method Details

#### ReadAllBytes `static`

**ReadAllBytes**(**stream**: Stream): byte[]

**Parameters**

- **stream** (Stream)  

**Returns** byte[]


---

#### ReadBytesExactly `static`

**ReadBytesExactly**(**stream**: Stream, **length**: long): byte[]

Reads exactly the number of bytes from the stream.

**Parameters**

- **stream** (Stream)  
- **length** (long)  

**Returns** byte[]

---

**ReadBytesExactly**(**stream**: Stream, ****: bytebuffer, **length**: int): void

Reads exactly the number of bytes into the buffer.

**Parameters**

- **stream** (Stream)  
- **** (bytebuffer)  
- **length** (int)  

