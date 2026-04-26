---
title: "MismatchedRangeException Class"
---

## MismatchedRangeException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [RecognitionException](RecognitionException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MismatchedRangeException**() |  |
| **MismatchedRangeException**(string message) |  |
| **MismatchedRangeException**(string message, Exception innerException) |  |
| **MismatchedRangeException**(SerializationInfo info, StreamingContext context) |  |
| **MismatchedRangeException**(int a, int b, [IIntStream](IIntStream.md) input) |  |
| **MismatchedRangeException**(string message, int a, int b, [IIntStream](IIntStream.md) input) |  |
| **MismatchedRangeException**(string message, int a, int b, [IIntStream](IIntStream.md) input, Exception innerException) |  |

**MismatchedRangeException**()

---

**MismatchedRangeException**(**message**: string)

**Parameters**

- **message** (string)  

---

**MismatchedRangeException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**MismatchedRangeException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**MismatchedRangeException**(**a**: int, **b**: int, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **a** (int)  
- **b** (int)  
- **input** ([IIntStream](IIntStream.md))  

---

**MismatchedRangeException**(**message**: string, **a**: int, **b**: int, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **message** (string)  
- **a** (int)  
- **b** (int)  
- **input** ([IIntStream](IIntStream.md))  

---

**MismatchedRangeException**(**message**: string, **a**: int, **b**: int, **input**: [IIntStream](IIntStream.md), **innerException**: Exception)

**Parameters**

- **message** (string)  
- **a** (int)  
- **b** (int)  
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

