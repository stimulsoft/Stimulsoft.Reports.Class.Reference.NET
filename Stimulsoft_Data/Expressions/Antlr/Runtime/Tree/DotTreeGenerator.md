---
title: "DotTreeGenerator Class"
---

## DotTreeGenerator Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DefineEdges** | IEnumerable<string> |  |
| **DefineNodes** | IEnumerable<string> |  |
| **FixString** | string |  |
| **GetNodeNumber** | int |  |
| **GetNodeText** | string |  |
| **ToDot** *(+1 overloads)* | string |  |

---

### Method Details

#### DefineEdges

**DefineEdges**(**tree**: object, **adaptor**: [ITreeAdaptor](ITreeAdaptor.md)): IEnumerable<string>

**Parameters**

- **tree** (object)  
- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  

**Returns** IEnumerable<string>


---

#### DefineNodes

**DefineNodes**(**tree**: object, **adaptor**: [ITreeAdaptor](ITreeAdaptor.md)): IEnumerable<string>

**Parameters**

- **tree** (object)  
- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  

**Returns** IEnumerable<string>


---

#### FixString

**FixString**(**text**: string): string

**Parameters**

- **text** (string)  

**Returns** string


---

#### GetNodeNumber

**GetNodeNumber**(**t**: object): int

**Parameters**

- **t** (object)  

**Returns** int


---

#### GetNodeText

**GetNodeText**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **t**: object): string

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **t** (object)  

**Returns** string


---

#### ToDot

**ToDot**(**tree**: object, **adaptor**: [ITreeAdaptor](ITreeAdaptor.md)): string

**Parameters**

- **tree** (object)  
- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  

**Returns** string

---

**ToDot**(**tree**: [ITree](ITree.md)): string

**Parameters**

- **tree** ([ITree](ITree.md))  

**Returns** string

