---
title: "TreeWizard Class"
---

## TreeWizard Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeWizard**([ITreeAdaptor](ITreeAdaptor.md) adaptor) |  |
| **TreeWizard**(stringtokenNames ) |  |
| **TreeWizard**([ITreeAdaptor](ITreeAdaptor.md) adaptor, IDictionary<string, int> tokenNameToTypeMap) |  |
| **TreeWizard**([ITreeAdaptor](ITreeAdaptor.md) adaptor, stringtokenNames ) |  |

**TreeWizard**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md))

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  

---

**TreeWizard**(****: stringtokenNames)

**Parameters**

- **** (stringtokenNames)  

---

**TreeWizard**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **tokenNameToTypeMap**: IDictionary<string, int>)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **tokenNameToTypeMap** (IDictionary<string, int>)  

---

**TreeWizard**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), ****: stringtokenNames)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **** (stringtokenNames)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** | object |  |
| **Equals** `static` *(+1 overloads)* | bool |  |
| **EqualsCore** `static` | bool |  |
| **Find** *(+1 overloads)* | IList |  |
| **FindFirst** *(+1 overloads)* | object |  |
| **GetTokenType** | int |  |
| **IndexCore** | void |  |
| **Parse** *(+1 overloads)* | bool |  |
| **ParseCore** | bool |  |
| **Visit** *(+6 overloads)* | void |  |
| **VisitCore** | void |  |
| **fillReverseIndex** | void |  |
| **getNodeIndex** | int |  |
| **reverseIndex** *(+1 overloads)* | void |  |

---

### Method Details

#### Create

**Create**(**pattern**: string): object

**Parameters**

- **pattern** (string)  

**Returns** object


---

#### Equals `static`

**Equals**(**t1**: object, **t2**: object, **adaptor**: [ITreeAdaptor](ITreeAdaptor.md)): bool

**Parameters**

- **t1** (object)  
- **t2** (object)  
- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  

**Returns** bool

---

**Equals**(**t1**: object, **t2**: object): bool

**Parameters**

- **t1** (object)  
- **t2** (object)  

**Returns** bool


---

#### EqualsCore `static`

**EqualsCore**(**t1**: object, **t2**: object, **adaptor**: [ITreeAdaptor](ITreeAdaptor.md)): bool

**Parameters**

- **t1** (object)  
- **t2** (object)  
- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  

**Returns** bool


---

#### Find

**Find**(**t**: object, **ttype**: int): IList

**Parameters**

- **t** (object)  
- **ttype** (int)  

**Returns** IList

---

**Find**(**t**: object, **pattern**: string): IList

**Parameters**

- **t** (object)  
- **pattern** (string)  

**Returns** IList


---

#### FindFirst

**FindFirst**(**t**: object, **ttype**: int): object

**Parameters**

- **t** (object)  
- **ttype** (int)  

**Returns** object

---

**FindFirst**(**t**: object, **pattern**: string): object

**Parameters**

- **t** (object)  
- **pattern** (string)  

**Returns** object


---

#### GetTokenType

**GetTokenType**(**tokenName**: string): int

**Parameters**

- **tokenName** (string)  

**Returns** int


---

#### IndexCore

**IndexCore**(**t**: object, **m**: IDictionary<int, IList>): void

**Parameters**

- **t** (object)  
- **m** (IDictionary<int, IList>)  


---

#### Parse

**Parse**(**t**: object, **pattern**: string, **labels**: IDictionary<string, object>): bool

**Parameters**

- **t** (object)  
- **pattern** (string)  
- **labels** (IDictionary<string, object>)  

**Returns** bool

---

**Parse**(**t**: object, **pattern**: string): bool

**Parameters**

- **t** (object)  
- **pattern** (string)  

**Returns** bool


---

#### ParseCore

**ParseCore**(**t1**: object, **tpattern**: TreePattern, **labels**: IDictionary<string, object>): bool

**Parameters**

- **t1** (object)  
- **tpattern** (TreePattern)  
- **labels** (IDictionary<string, object>)  

**Returns** bool


---

#### Visit

**Visit**(**t**: object): void

**Parameters**

- **t** (object)  

---

**Visit**(**t**: object): void

**Parameters**

- **t** (object)  

---

**Visit**(**t**: object, **parent**: object, **childIndex**: int, **labels**: IDictionary<string, object>): void

**Parameters**

- **t** (object)  
- **parent** (object)  
- **childIndex** (int)  
- **labels** (IDictionary<string, object>)  

---

**Visit**(**t**: object, **ttype**: int, **visitor**: IContextVisitor): void

**Parameters**

- **t** (object)  
- **ttype** (int)  
- **visitor** (IContextVisitor)  

---

**Visit**(**t**: object, **ttype**: int, **action**: Action<object>): void

**Parameters**

- **t** (object)  
- **ttype** (int)  
- **action** (Action<object>)  

---

**Visit**(**t**: object, **parent**: object, **childIndex**: int, **unusedlabels**: IDictionary<string, object>): void

**Parameters**

- **t** (object)  
- **parent** (object)  
- **childIndex** (int)  
- **unusedlabels** (IDictionary<string, object>)  

---

**Visit**(**t**: object, **pattern**: string, **visitor**: IContextVisitor): void

**Parameters**

- **t** (object)  
- **pattern** (string)  
- **visitor** (IContextVisitor)  


---

#### VisitCore

**VisitCore**(**t**: object, **parent**: object, **childIndex**: int, **ttype**: int, **visitor**: IContextVisitor): void

**Parameters**

- **t** (object)  
- **parent** (object)  
- **childIndex** (int)  
- **ttype** (int)  
- **visitor** (IContextVisitor)  


---

#### fillReverseIndex

**fillReverseIndex**(**node**: object, **streamIndex**: int): void

**Parameters**

- **node** (object)  
- **streamIndex** (int)  


---

#### getNodeIndex

**getNodeIndex**(**node**: object): int

**Parameters**

- **node** (object)  

**Returns** int


---

#### reverseIndex

**reverseIndex**(**tokenType**: int): void

**Parameters**

- **tokenType** (int)  

---

**reverseIndex**(**tokenTypes**: HashSet<int>): void

**Parameters**

- **tokenTypes** (HashSet<int>)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **INDEX_ALL** | HashSet<int> |  |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **tokenTypesToReverseIndex** | HashSet<int> |  |
