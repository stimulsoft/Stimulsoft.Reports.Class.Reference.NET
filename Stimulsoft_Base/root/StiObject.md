---
title: "StiObject Class"
---

## StiObject Class

**Namespace:** `Stimulsoft.Base`

This is a base class for all Stimulsoft Server object.

### Inheritance

Implements: ICloneable  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **LoadFromBytes** | void | Loads element from byte array. |
| **LoadFromString** | void | Loads element from string. |
| **ResetProperties** | void | Resets properties to default values. |
| **SaveToBytes** | byte[] | Saves element to byte array. |
| **SaveToString** | string | Saves element to string. |
| **SaveToXml** | XDocument | Saves element to XDocument object. |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

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

#### ResetProperties

**ResetProperties**(): void

Resets properties to default values.


---

#### SaveToBytes

**SaveToBytes**(**allowPacking**: bool): byte[]

Saves element to byte array.

**Parameters**

- **allowPacking** (bool)  

**Returns** byte[] — String representation which contain item description.


---

#### SaveToString

**SaveToString**(): string

Saves element to string.

**Returns** string — String representation which contains schema.


---

#### SaveToXml

**SaveToXml**(): XDocument

Saves element to XDocument object.

**Returns** XDocument — XElement object which contains xml description of saved schema.

