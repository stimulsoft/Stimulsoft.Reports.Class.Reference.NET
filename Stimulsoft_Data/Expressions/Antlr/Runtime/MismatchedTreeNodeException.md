---
title: "MismatchedTreeNodeException Class"
---

## MismatchedTreeNodeException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [RecognitionException](RecognitionException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MismatchedTreeNodeException**() |  |
| **MismatchedTreeNodeException**(string message) |  |
| **MismatchedTreeNodeException**(string message, Exception innerException) |  |
| **MismatchedTreeNodeException**(int expecting, Tree.ITreeNodeStream input) |  |
| **MismatchedTreeNodeException**(SerializationInfo info, StreamingContext context) |  |
| **MismatchedTreeNodeException**(string message, int expecting, Tree.ITreeNodeStream input) |  |
| **MismatchedTreeNodeException**(string message, int expecting, Tree.ITreeNodeStream input, Exception innerException) |  |

**MismatchedTreeNodeException**()

---

**MismatchedTreeNodeException**(**message**: string)

**Parameters**

- **message** (string)  

---

**MismatchedTreeNodeException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**MismatchedTreeNodeException**(**expecting**: int, **input**: Tree.ITreeNodeStream)

**Parameters**

- **expecting** (int)  
- **input** (Tree.ITreeNodeStream)  

---

**MismatchedTreeNodeException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**MismatchedTreeNodeException**(**message**: string, **expecting**: int, **input**: Tree.ITreeNodeStream)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** (Tree.ITreeNodeStream)  

---

**MismatchedTreeNodeException**(**message**: string, **expecting**: int, **input**: Tree.ITreeNodeStream, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** (Tree.ITreeNodeStream)  
- **innerException** (Exception)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetObjectData** | void |  |
| **ToString** | string |  |

---

### Method Details

#### GetObjectData

**GetObjectData**(**info**: SerializationInfo, **context**: StreamingContext): void

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  


---

#### ToString

**ToString**(): string

**Returns** string

