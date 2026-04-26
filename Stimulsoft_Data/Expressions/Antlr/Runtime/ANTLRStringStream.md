---
title: "ANTLRStringStream Class"
---

## ANTLRStringStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Implements: [ICharStream](ICharStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ANTLRStringStream**() |  |
| **ANTLRStringStream**(string input) |  |
| **ANTLRStringStream**(string input, string sourceName) |  |
| **ANTLRStringStream**(chardata , int numberOfActualCharsInArray) |  |
| **ANTLRStringStream**(chardata , int numberOfActualCharsInArray, string sourceName) |  |

**ANTLRStringStream**()

---

**ANTLRStringStream**(**input**: string)

**Parameters**

- **input** (string)  

---

**ANTLRStringStream**(**input**: string, **sourceName**: string)

**Parameters**

- **input** (string)  
- **sourceName** (string)  

---

**ANTLRStringStream**(****: chardata, **numberOfActualCharsInArray**: int)

**Parameters**

- **** (chardata)  
- **numberOfActualCharsInArray** (int)  

---

**ANTLRStringStream**(****: chardata, **numberOfActualCharsInArray**: int, **sourceName**: string)

**Parameters**

- **** (chardata)  
- **numberOfActualCharsInArray** (int)  
- **sourceName** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Consume** | void |  |
| **LA** | int |  |
| **LT** | int |  |
| **Mark** | int |  |
| **Release** | void |  |
| **Reset** | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **Substring** | string |  |
| **ToString** | string |  |

---

### Method Details

#### Consume

**Consume**(): void


---

#### LA

**LA**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### LT

**LT**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### Mark

**Mark**(): int

**Returns** int


---

#### Release

**Release**(**marker**: int): void

**Parameters**

- **marker** (int)  


---

#### Reset

**Reset**(): void


---

#### Rewind

**Rewind**(**m**: int): void

**Parameters**

- **m** (int)  

---

**Rewind**(): void


---

#### Seek

**Seek**(**index**: int): void

**Parameters**

- **index** (int)  


---

#### Substring

**Substring**(**start**: int, **length**: int): string

**Parameters**

- **start** (int)  
- **length** (int)  

**Returns** string


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **data** | char[] |  |
| **lastMarker** | int |  |
| **markDepth** | int |  |
| **markers** | IList<[CharStreamState](CharStreamState.md)> |  |
| **n** | int |  |
| **name** | string |  |
| **p** | int |  |
