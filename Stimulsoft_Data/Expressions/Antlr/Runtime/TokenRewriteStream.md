---
title: "TokenRewriteStream Class"
---

## TokenRewriteStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [CommonTokenStream](CommonTokenStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **TokenRewriteStream**() |  |
| **TokenRewriteStream**([ITokenSource](ITokenSource.md) tokenSource) |  |
| **TokenRewriteStream**([ITokenSource](ITokenSource.md) tokenSource, int channel) |  |

**TokenRewriteStream**()

---

**TokenRewriteStream**(**tokenSource**: [ITokenSource](ITokenSource.md))

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  

---

**TokenRewriteStream**(**tokenSource**: [ITokenSource](ITokenSource.md), **channel**: int)

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  
- **channel** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CatOpText** | string |  |
| **Delete** *(+5 overloads)* | void |  |
| **DeleteProgram** *(+1 overloads)* | void |  |
| **Execute** *(+2 overloads)* | int |  |
| **GetKindOfOps** *(+1 overloads)* | IList<RewriteOperation> |  |
| **GetLastRewriteTokenIndex** *(+1 overloads)* | int |  |
| **GetProgram** | IList<RewriteOperation> |  |
| **Init** | void |  |
| **InsertAfter** *(+3 overloads)* | void |  |
| **InsertBefore** *(+3 overloads)* | void |  |
| **Replace** *(+5 overloads)* | void |  |
| **Rollback** *(+1 overloads)* | void |  |
| **SetLastRewriteTokenIndex** | void |  |
| **ToDebugString** *(+1 overloads)* | string |  |
| **ToOriginalString** *(+1 overloads)* | string |  |
| **ToString** *(+5 overloads)* | string |  |

---

### Method Details

#### CatOpText

**CatOpText**(**a**: object, **b**: object): string

**Parameters**

- **a** (object)  
- **b** (object)  

**Returns** string


---

#### Delete

**Delete**(**index**: int): void

**Parameters**

- **index** (int)  

---

**Delete**(**from**: int, **to**: int): void

**Parameters**

- **from** (int)  
- **to** (int)  

---

**Delete**(**indexT**: [IToken](IToken.md)): void

**Parameters**

- **indexT** ([IToken](IToken.md))  

---

**Delete**(**from**: [IToken](IToken.md), **to**: [IToken](IToken.md)): void

**Parameters**

- **from** ([IToken](IToken.md))  
- **to** ([IToken](IToken.md))  

---

**Delete**(**programName**: string, **from**: int, **to**: int): void

**Parameters**

- **programName** (string)  
- **from** (int)  
- **to** (int)  

---

**Delete**(**programName**: string, **from**: [IToken](IToken.md), **to**: [IToken](IToken.md)): void

**Parameters**

- **programName** (string)  
- **from** ([IToken](IToken.md))  
- **to** ([IToken](IToken.md))  


---

#### DeleteProgram

**DeleteProgram**(): void

---

**DeleteProgram**(**programName**: string): void

**Parameters**

- **programName** (string)  


---

#### Execute

**Execute**(**buf**: StringBuilder): int

**Parameters**

- **buf** (StringBuilder)  

**Returns** int

---

**Execute**(**buf**: StringBuilder): int

**Parameters**

- **buf** (StringBuilder)  

**Returns** int

---

**Execute**(**buf**: StringBuilder): int

**Parameters**

- **buf** (StringBuilder)  

**Returns** int


---

#### GetKindOfOps

**GetKindOfOps**(**rewrites**: IList<RewriteOperation>, **kind**: Type): IList<RewriteOperation>

**Parameters**

- **rewrites** (IList<RewriteOperation>)  
- **kind** (Type)  

**Returns** IList<RewriteOperation>

---

**GetKindOfOps**(**rewrites**: IList<RewriteOperation>, **kind**: Type, **before**: int): IList<RewriteOperation>

**Parameters**

- **rewrites** (IList<RewriteOperation>)  
- **kind** (Type)  
- **before** (int)  

**Returns** IList<RewriteOperation>


---

#### GetLastRewriteTokenIndex

**GetLastRewriteTokenIndex**(): int

**Returns** int

---

**GetLastRewriteTokenIndex**(**programName**: string): int

**Parameters**

- **programName** (string)  

**Returns** int


---

#### GetProgram

**GetProgram**(**name**: string): IList<RewriteOperation>

**Parameters**

- **name** (string)  

**Returns** IList<RewriteOperation>


---

#### Init

**Init**(): void


---

#### InsertAfter

**InsertAfter**(**t**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **t** ([IToken](IToken.md))  
- **text** (object)  

---

**InsertAfter**(**index**: int, **text**: object): void

**Parameters**

- **index** (int)  
- **text** (object)  

---

**InsertAfter**(**programName**: string, **t**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **programName** (string)  
- **t** ([IToken](IToken.md))  
- **text** (object)  

---

**InsertAfter**(**programName**: string, **index**: int, **text**: object): void

**Parameters**

- **programName** (string)  
- **index** (int)  
- **text** (object)  


---

#### InsertBefore

**InsertBefore**(**t**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **t** ([IToken](IToken.md))  
- **text** (object)  

---

**InsertBefore**(**index**: int, **text**: object): void

**Parameters**

- **index** (int)  
- **text** (object)  

---

**InsertBefore**(**programName**: string, **t**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **programName** (string)  
- **t** ([IToken](IToken.md))  
- **text** (object)  

---

**InsertBefore**(**programName**: string, **index**: int, **text**: object): void

**Parameters**

- **programName** (string)  
- **index** (int)  
- **text** (object)  


---

#### Replace

**Replace**(**index**: int, **text**: object): void

**Parameters**

- **index** (int)  
- **text** (object)  

---

**Replace**(**from**: int, **to**: int, **text**: object): void

**Parameters**

- **from** (int)  
- **to** (int)  
- **text** (object)  

---

**Replace**(**indexT**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **indexT** ([IToken](IToken.md))  
- **text** (object)  

---

**Replace**(**from**: [IToken](IToken.md), **to**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **from** ([IToken](IToken.md))  
- **to** ([IToken](IToken.md))  
- **text** (object)  

---

**Replace**(**programName**: string, **from**: int, **to**: int, **text**: object): void

**Parameters**

- **programName** (string)  
- **from** (int)  
- **to** (int)  
- **text** (object)  

---

**Replace**(**programName**: string, **from**: [IToken](IToken.md), **to**: [IToken](IToken.md), **text**: object): void

**Parameters**

- **programName** (string)  
- **from** ([IToken](IToken.md))  
- **to** ([IToken](IToken.md))  
- **text** (object)  


---

#### Rollback

**Rollback**(**instructionIndex**: int): void

**Parameters**

- **instructionIndex** (int)  

---

**Rollback**(**programName**: string, **instructionIndex**: int): void

**Parameters**

- **programName** (string)  
- **instructionIndex** (int)  


---

#### SetLastRewriteTokenIndex

**SetLastRewriteTokenIndex**(**programName**: string, **i**: int): void

**Parameters**

- **programName** (string)  
- **i** (int)  


---

#### ToDebugString

**ToDebugString**(): string

**Returns** string

---

**ToDebugString**(**start**: int, **end**: int): string

**Parameters**

- **start** (int)  
- **end** (int)  

**Returns** string


---

#### ToOriginalString

**ToOriginalString**(): string

**Returns** string

---

**ToOriginalString**(**start**: int, **end**: int): string

**Parameters**

- **start** (int)  
- **end** (int)  

**Returns** string


---

#### ToString

**ToString**(): string

**Returns** string

---

**ToString**(): string

**Returns** string

---

**ToString**(): string

**Returns** string

---

**ToString**(**programName**: string): string

**Parameters**

- **programName** (string)  

**Returns** string

---

**ToString**(**start**: int, **end**: int): string

**Parameters**

- **start** (int)  
- **end** (int)  

**Returns** string

---

**ToString**(**programName**: string, **start**: int, **end**: int): string

**Parameters**

- **programName** (string)  
- **start** (int)  
- **end** (int)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DEFAULT_PROGRAM_NAME** | string |  |
| **MIN_TOKEN_INDEX** | int |  |
| **PROGRAM_INIT_SIZE** | int |  |
| **index** | int |  |
| **instructionIndex** | int |  |
| **lastIndex** | int |  |
| **stream** | [TokenRewriteStream](TokenRewriteStream.md) |  |
| **text** | object |  |
