---
title: "FailedPredicateException Class"
---

## FailedPredicateException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [RecognitionException](RecognitionException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **FailedPredicateException**() |  |
| **FailedPredicateException**(string message) |  |
| **FailedPredicateException**(string message, Exception innerException) |  |
| **FailedPredicateException**(SerializationInfo info, StreamingContext context) |  |
| **FailedPredicateException**([IIntStream](IIntStream.md) input, string ruleName, string predicateText) |  |
| **FailedPredicateException**(string message, [IIntStream](IIntStream.md) input, string ruleName, string predicateText) |  |
| **FailedPredicateException**(string message, [IIntStream](IIntStream.md) input, string ruleName, string predicateText, Exception innerException) |  |

**FailedPredicateException**()

---

**FailedPredicateException**(**message**: string)

**Parameters**

- **message** (string)  

---

**FailedPredicateException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**FailedPredicateException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**FailedPredicateException**(**input**: [IIntStream](IIntStream.md), **ruleName**: string, **predicateText**: string)

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **ruleName** (string)  
- **predicateText** (string)  

---

**FailedPredicateException**(**message**: string, **input**: [IIntStream](IIntStream.md), **ruleName**: string, **predicateText**: string)

**Parameters**

- **message** (string)  
- **input** ([IIntStream](IIntStream.md))  
- **ruleName** (string)  
- **predicateText** (string)  

---

**FailedPredicateException**(**message**: string, **input**: [IIntStream](IIntStream.md), **ruleName**: string, **predicateText**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **input** ([IIntStream](IIntStream.md))  
- **ruleName** (string)  
- **predicateText** (string)  
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

