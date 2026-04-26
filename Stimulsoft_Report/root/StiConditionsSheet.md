---
title: "StiConditionsSheet Class"
---

## StiConditionsSheet Class

**Namespace:** `Stimulsoft.Report`

This class describes a list of conditions.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiConditionsSheet**(StiConditionsCollection conditions) | Creates a new object of the type StiConditionsSheet. |

**StiConditionsSheet**(**conditions**: StiConditionsCollection)

Creates a new object of the type StiConditionsSheet.

**Parameters**

- **conditions** (StiConditionsCollection) — A conditions collection.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Conditions** | StiConditionsCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** *(+1 overloads)* | void | Loads a list of conditionss from the stream. |
| **LoadFromJsonFile** | void | Loads a list of conditions from a json file. |
| **LoadFromString** | void | Loads conditions from a string. |
| **Save** *(+1 overloads)* | void | Saves a list of conditions in the stream. |
| **SaveToString** | string | Saves to a string this conditions. |

---

### Method Details

#### Load

**Load**(**stream**: Stream): void

Loads a list of conditionss from the stream.

**Parameters**

- **stream** (Stream) — A stream for list of conditions loading.  

---

**Load**(**file**: string): void

Loads a list of conditions from the file.

**Parameters**

- **file** (string) — A file for list of conditions loading.  


---

#### LoadFromJsonFile

**LoadFromJsonFile**(**file**: string): void

Loads a list of conditions from a json file.

**Parameters**

- **file** (string)  


---

#### LoadFromString

**LoadFromString**(**str**: string): void

Loads conditions from a string.

**Parameters**

- **str** (string)  


---

#### Save

**Save**(**stream**: Stream): void

Saves a list of conditions in the stream.

**Parameters**

- **stream** (Stream) — A stream for saving the conditions list.  

---

**Save**(**file**: string): void

Saves a list of conditionss to the file.

**Parameters**

- **file** (string) — File for list of styles saving.  


---

#### SaveToString

**SaveToString**(): string

Saves to a string this conditions.

**Returns** string

