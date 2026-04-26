---
title: "MismatchedSetException Class"
---

## MismatchedSetException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [RecognitionException](RecognitionException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MismatchedSetException**() |  |
| **MismatchedSetException**(string message) |  |
| **MismatchedSetException**(string message, Exception innerException) |  |
| **MismatchedSetException**([BitSet](BitSet.md) expecting, [IIntStream](IIntStream.md) input) |  |
| **MismatchedSetException**(SerializationInfo info, StreamingContext context) |  |
| **MismatchedSetException**(string message, [BitSet](BitSet.md) expecting, [IIntStream](IIntStream.md) input) |  |
| **MismatchedSetException**(string message, [BitSet](BitSet.md) expecting, [IIntStream](IIntStream.md) input, Exception innerException) |  |

**MismatchedSetException**()

---

**MismatchedSetException**(**message**: string)

**Parameters**

- **message** (string)  

---

**MismatchedSetException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**MismatchedSetException**(**expecting**: [BitSet](BitSet.md), **input**: [IIntStream](IIntStream.md))

**Parameters**

- **expecting** ([BitSet](BitSet.md))  
- **input** ([IIntStream](IIntStream.md))  

---

**MismatchedSetException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**MismatchedSetException**(**message**: string, **expecting**: [BitSet](BitSet.md), **input**: [IIntStream](IIntStream.md))

**Parameters**

- **message** (string)  
- **expecting** ([BitSet](BitSet.md))  
- **input** ([IIntStream](IIntStream.md))  

---

**MismatchedSetException**(**message**: string, **expecting**: [BitSet](BitSet.md), **input**: [IIntStream](IIntStream.md), **innerException**: Exception)

**Parameters**

- **message** (string)  
- **expecting** ([BitSet](BitSet.md))  
- **input** ([IIntStream](IIntStream.md))  
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

