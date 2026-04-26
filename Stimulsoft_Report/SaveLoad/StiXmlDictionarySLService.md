---
title: "StiXmlDictionarySLService Class"
---

## StiXmlDictionarySLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

Describes the class that allows to save / load dictionaries of data.

### Inheritance

Inherits from: [StiDictionarySLService](StiDictionarySLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a dictionary from the stream. |
| **LoadAsync** | Task | Loads asynchronously a dictionary from the stream. |
| **Merge** | void | Merge a dictionary from the stream. |
| **MergeAsync** | Task | Merge asynchronously a dictionary from the stream. |
| **Save** | void | Saves a dictionary in the stream. |
| **SaveAsync** | Task | Saves asynchronously a dictionary in the stream. |

---

### Method Details

#### GetAction

**GetAction**(): [StiSLActions](StiSLActions.md)

Returns actions available for the provider.

**Returns** [StiSLActions](StiSLActions.md) — Available actions.


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the provider.

**Returns** string — String with filter.


---

#### Load

**Load**(**dictionary**: StiDictionary, **stream**: Stream): void

Loads a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The Dictionary in which loading will be done.  
- **stream** (Stream) — The Stream to load the dictionary.  


---

#### LoadAsync

**LoadAsync**(**dictionary**: StiDictionary, **stream**: Stream): Task

Loads asynchronously a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The Dictionary in which loading will be done.  
- **stream** (Stream) — The Stream to load the dictionary.  

**Returns** Task


---

#### Merge

**Merge**(**dictionary**: StiDictionary, **stream**: Stream): void

Merge a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary to merge.  
- **stream** (Stream) — The stream to merge the dictionary of data.  


---

#### MergeAsync

**MergeAsync**(**dictionary**: StiDictionary, **stream**: Stream): Task

Merge asynchronously a dictionary from the stream.

**Parameters**

- **dictionary** (StiDictionary) — The dictionary to merge.  
- **stream** (Stream) — The stream to merge the dictionary of data.  

**Returns** Task


---

#### Save

**Save**(**dictionary**: StiDictionary, **stream**: Stream): void

Saves a dictionary in the stream.

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

