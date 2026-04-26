---
title: "MismatchedTokenException Class"
---

## MismatchedTokenException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [RecognitionException](RecognitionException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MismatchedTokenException**() |  |
| **MismatchedTokenException**(string message) |  |
| **MismatchedTokenException**(string message, Exception innerException) |  |
| **MismatchedTokenException**(int expecting, [IIntStream](IIntStream.md) input) |  |
| **MismatchedTokenException**(SerializationInfo info, StreamingContext context) |  |
| **MismatchedTokenException**(int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames) |  |
| **MismatchedTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames) |  |
| **MismatchedTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames, Exception innerException) |  |

**MismatchedTokenException**()

---

**MismatchedTokenException**(**message**: string)

**Parameters**

- **message** (string)  

---

**MismatchedTokenException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**MismatchedTokenException**(**expecting**: int, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  

---

**MismatchedTokenException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**MismatchedTokenException**(**expecting**: int, **input**: [IIntStream](IIntStream.md), **tokenNames**: IList<string>)

**Parameters**

- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **tokenNames** (IList<string>)  

---

**MismatchedTokenException**(**message**: string, **expecting**: int, **input**: [IIntStream](IIntStream.md), **tokenNames**: IList<string>)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **tokenNames** (IList<string>)  

---

**MismatchedTokenException**(**message**: string, **expecting**: int, **input**: [IIntStream](IIntStream.md), **tokenNames**: IList<string>, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **tokenNames** (IList<string>)  
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

