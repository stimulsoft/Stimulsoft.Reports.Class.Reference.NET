---
title: "StiStylesSheet Class"
---

## StiStylesSheet Class

**Namespace:** `Stimulsoft.Report`

Class describes a list of styles.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiStylesSheet**(StiStylesCollection styles) | Creates a new object of the type StiStylesSheet. |

**StiStylesSheet**(**styles**: StiStylesCollection)

Creates a new object of the type StiStylesSheet.

**Parameters**

- **styles** (StiStylesCollection) — Style collection.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Styles** | StiStylesCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** *(+1 overloads)* | void | Loads a list of styles from the stream. |
| **LoadFromJsonFile** | void | Loads a list of styles from the json file. |
| **Save** *(+1 overloads)* | void | Saves a list of styles in the stream. |

---

### Method Details

#### Load

**Load**(**stream**: Stream): void

Loads a list of styles from the stream.

**Parameters**

- **stream** (Stream) — A stream for list of styles loading.  

---

**Load**(**file**: string): void

Loads a list of styles from the file.

**Parameters**

- **file** (string) — A file for list of styles loading.  


---

#### LoadFromJsonFile

**LoadFromJsonFile**(**file**: string): void

Loads a list of styles from the json file.

**Parameters**

- **file** (string)  


---

#### Save

**Save**(**stream**: Stream): void

Saves a list of styles in the stream.

**Parameters**

- **stream** (Stream) — Stream for saving the style list.  

---

**Save**(**file**: string): void

Saves a list of styles to the file.

**Parameters**

- **file** (string) — A file for list of styles saving.  

