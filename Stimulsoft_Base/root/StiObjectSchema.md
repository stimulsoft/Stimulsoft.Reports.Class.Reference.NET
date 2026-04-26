---
title: "StiObjectSchema Class"
---

## StiObjectSchema Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Name** | string | A name of the schema object. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromBytes** | void | Loads element from byte array. |
| **LoadFromString** | void | Loads element from string. |
| **SaveToBytes** | byte[] | Saves element to byte array. |
| **SaveToString** | string | Saves element to string. |
| **SaveToXml** | XDocument | Saves specified schema to XDocument object. |

---

### Method Details

#### LoadFromBytes

**LoadFromBytes**(****: bytebytes): void

Loads element from byte array.

**Parameters**

- **** (bytebytes)  


---

#### LoadFromString

**LoadFromString**(**str**: string): void

Loads element from string.

**Parameters**

- **str** (string) — String representation which contain item description.  


---

#### SaveToBytes

**SaveToBytes**(): byte[]

Saves element to byte array.

**Returns** byte[] — String representation which contain item description.


---

#### SaveToString

**SaveToString**(): string

Saves element to string.

**Returns** string — String representation which contains schema.


---

#### SaveToXml

**SaveToXml**(): XDocument

Saves specified schema to XDocument object.

**Returns** XDocument — XElement object which contains xml description of saved schema.

