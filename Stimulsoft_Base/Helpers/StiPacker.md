---
title: "StiPacker Class"
---

## StiPacker Class

**Namespace:** `Stimulsoft.Base.Helpers`

This class helps in working with packing/unpacking data.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowPacking** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IsPacked** `static` *(+1 overloads)* | bool | Returns true if the specified stream is packed. |
| **Pack** `static` *(+1 overloads)* | byte[] | Packs the byte array. |
| **PackAndEncrypt** `static` | byte[] | Packs and encrypts the byte array. |
| **PackAndEncryptToString** `static` | string | Packs and encrypts the byte array to the byte64 string. |
| **PackToBytes** `static` *(+1 overloads)* | byte[] | Packs string and convert it to byte array. |
| **PackToString** `static` | string |  |
| **Unpack** `static` *(+1 overloads)* | byte[] | Unpacks byte array. |
| **UnpackAndDecrypt** `static` *(+1 overloads)* | byte[] | Unpacks and uncrypts byte array. |
| **UnpackFromString** `static` | byte[] |  |
| **UnpackToString** `static` | string | Unpacks byte array and convert it to string. |
| **UnpackToXElement** `static` | XElement | Unpacks byte array and convert it to XElement. |

---

### Method Details

#### IsPacked `static`

**IsPacked**(**stream**: Stream): bool

Returns true if the specified stream is packed.

**Parameters**

- **stream** (Stream)  

**Returns** bool

---

**IsPacked**(****: bytebytes): bool

Returns true if the specified byte array is packed.

**Parameters**

- **** (bytebytes)  

**Returns** bool


---

#### Pack `static`

**Pack**(****: bytebytes): byte[]

Packs the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** byte[]

---

**Pack**(**stream**: Stream): Stream

Packs the stream.

**Parameters**

- **stream** (Stream)  

**Returns** Stream


---

#### PackAndEncrypt `static`

**PackAndEncrypt**(****: bytebytes, **encryptedId**: string): byte[]

Packs and encrypts the byte array.

**Parameters**

- **** (bytebytes)  
- **encryptedId** (string)  

**Returns** byte[]


---

#### PackAndEncryptToString `static`

**PackAndEncryptToString**(****: bytebytes): string

Packs and encrypts the byte array to the byte64 string.

**Parameters**

- **** (bytebytes)  

**Returns** string


---

#### PackToBytes `static`

**PackToBytes**(**str**: string, **allowPacking**: bool): byte[]

Packs string and convert it to byte array.

**Parameters**

- **str** (string)  
- **allowPacking** (bool)  

**Returns** byte[]

---

**PackToBytes**(**element**: XElement): byte[]

Packs XElement and convert it to byte array.

**Parameters**

- **element** (XElement)  

**Returns** byte[]


---

#### PackToString `static`

**PackToString**(****: bytebytes): string

**Parameters**

- **** (bytebytes)  

**Returns** string


---

#### Unpack `static`

**Unpack**(****: bytebytes): byte[]

Unpacks byte array.

**Parameters**

- **** (bytebytes)  

**Returns** byte[]

---

**Unpack**(**stream**: Stream): Stream

Unpacks stream.

**Parameters**

- **stream** (Stream)  

**Returns** Stream


---

#### UnpackAndDecrypt `static`

**UnpackAndDecrypt**(****: bytebytes, **encryptedId**: string): byte[]

Unpacks and uncrypts byte array.

**Parameters**

- **** (bytebytes)  
- **encryptedId** (string)  

**Returns** byte[]

---

**UnpackAndDecrypt**(**str**: string): byte[]

Unpacks and uncrypts byte array from base64 string.

**Parameters**

- **str** (string)  

**Returns** byte[]


---

#### UnpackFromString `static`

**UnpackFromString**(**str**: string): byte[]

**Parameters**

- **str** (string)  

**Returns** byte[]


---

#### UnpackToString `static`

**UnpackToString**(****: bytebytes): string

Unpacks byte array and convert it to string.

**Parameters**

- **** (bytebytes)  

**Returns** string


---

#### UnpackToXElement `static`

**UnpackToXElement**(****: bytebytes): XElement

Unpacks byte array and convert it to XElement.

**Parameters**

- **** (bytebytes)  

**Returns** XElement

