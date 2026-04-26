---
title: "RecognitionException Class"
---

## RecognitionException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: Exception  

### Constructors

| Constructor | Description |
| --- | --- |
| **RecognitionException**() |  |
| **RecognitionException**([IIntStream](IIntStream.md) input) |  |
| **RecognitionException**(string message) |  |
| **RecognitionException**([IIntStream](IIntStream.md) input, int k) |  |
| **RecognitionException**(string message, [IIntStream](IIntStream.md) input) |  |
| **RecognitionException**(string message, Exception innerException) |  |
| **RecognitionException**(SerializationInfo info, StreamingContext context) |  |
| **RecognitionException**(string message, [IIntStream](IIntStream.md) input, int k) |  |
| **RecognitionException**(string message, [IIntStream](IIntStream.md) input, Exception innerException) |  |
| **RecognitionException**(string message, [IIntStream](IIntStream.md) input, int k, Exception innerException) |  |

**RecognitionException**()

---

**RecognitionException**(**input**: [IIntStream](IIntStream.md))

**Parameters**

- **input** ([IIntStream](IIntStream.md))  

---

**RecognitionException**(**message**: string)

**Parameters**

- **message** (string)  

---

**RecognitionException**(**input**: [IIntStream](IIntStream.md), **k**: int)

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **k** (int)  

---

**RecognitionException**(**message**: string, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **message** (string)  
- **input** ([IIntStream](IIntStream.md))  

---

**RecognitionException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**RecognitionException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**RecognitionException**(**message**: string, **input**: [IIntStream](IIntStream.md), **k**: int)

**Parameters**

- **message** (string)  
- **input** ([IIntStream](IIntStream.md))  
- **k** (int)  

---

**RecognitionException**(**message**: string, **input**: [IIntStream](IIntStream.md), **innerException**: Exception)

**Parameters**

- **message** (string)  
- **input** ([IIntStream](IIntStream.md))  
- **innerException** (Exception)  

---

**RecognitionException**(**message**: string, **input**: [IIntStream](IIntStream.md), **k**: int, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **input** ([IIntStream](IIntStream.md))  
- **k** (int)  
- **innerException** (Exception)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ExtractInformationFromTreeNodeStream** *(+1 overloads)* | void |  |
| **GetObjectData** | void |  |

---

### Method Details

#### ExtractInformationFromTreeNodeStream

**ExtractInformationFromTreeNodeStream**(**input**: Tree.ITreeNodeStream): void

**Parameters**

- **input** (Tree.ITreeNodeStream)  

---

**ExtractInformationFromTreeNodeStream**(**input**: Tree.ITreeNodeStream, **k**: int): void

**Parameters**

- **input** (Tree.ITreeNodeStream)  
- **k** (int)  


---

#### GetObjectData

**GetObjectData**(**info**: SerializationInfo, **context**: StreamingContext): void

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

