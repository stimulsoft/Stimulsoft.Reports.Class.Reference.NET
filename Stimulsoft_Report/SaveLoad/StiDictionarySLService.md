---
title: "StiDictionarySLService Class"
---

## StiDictionarySLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

### Inheritance

Inherits from: [StiSLService](StiSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** | void | Loads a dictionary from the stream. |
| **LoadAsync** | Task | Loads asynchronously a dictionary from the stream. |
| **Merge** | void | Merges the dictionary from the stream. |
| **MergeAsync** | Task | Merges asynchronously a dictionary from the stream. |
| **Save** | void | Saves a dictionaryin the stream. |
| **SaveAsync** | Task | Saves asynchronously a dictionary in the stream. |

---

### Method Details

#### Load

**Load**(**dictionary**: StiDictionary, **stream**: Stream): void

Loads a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary in which loading will be done.  
- **stream** (Stream) — The stream to load the dictionary.  


---

#### LoadAsync

**LoadAsync**(**dictionary**: StiDictionary, **stream**: Stream): Task

Loads asynchronously a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary in which loading will be done.  
- **stream** (Stream) — The stream to load the dictionary.  

**Returns** Task


---

#### Merge

**Merge**(**dictionary**: StiDictionary, **stream**: Stream): void

Merges the dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary to merge.  
- **stream** (Stream) — The stream to merge the dictionary.  


---

#### MergeAsync

**MergeAsync**(**dictionary**: StiDictionary, **stream**: Stream): Task

Merges asynchronously a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary to merge.  
- **stream** (Stream) — The stream to merge the dictionary.  

**Returns** Task


---

#### Save

**Save**(**dictionary**: StiDictionary, **stream**: Stream): void

Saves a dictionaryin the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary for saving.  
- **stream** (Stream) — The stream to save the dictionary.  


---

#### SaveAsync

**SaveAsync**(**dictionary**: StiDictionary, **stream**: Stream): Task

Saves asynchronously a dictionary in the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary for saving.  
- **stream** (Stream) — The stream to save the dictionary.  

**Returns** Task

