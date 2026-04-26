---
title: "Lexer Class"
---

## Lexer Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [BaseRecognizer](BaseRecognizer.md)  
Implements: [ITokenSource](ITokenSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **Lexer**() |  |
| **Lexer**([ICharStream](ICharStream.md) input) |  |
| **Lexer**([ICharStream](ICharStream.md) input, [RecognizerSharedState](RecognizerSharedState.md) state) |  |

**Lexer**()

---

**Lexer**(**input**: [ICharStream](ICharStream.md))

**Parameters**

- **input** ([ICharStream](ICharStream.md))  

---

**Lexer**(**input**: [ICharStream](ICharStream.md), **state**: [RecognizerSharedState](RecognizerSharedState.md))

**Parameters**

- **input** ([ICharStream](ICharStream.md))  
- **state** ([RecognizerSharedState](RecognizerSharedState.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Emit** *(+1 overloads)* | void |  |
| **GetCharErrorDisplay** | string |  |
| **GetEndOfFileToken** | [IToken](IToken.md) |  |
| **GetErrorMessage** | string |  |
| **Match** *(+1 overloads)* | void |  |
| **MatchAny** | void |  |
| **MatchRange** | void |  |
| **NextToken** | [IToken](IToken.md) |  |
| **ParseNextToken** | void |  |
| **Recover** | void |  |
| **ReportError** | void |  |
| **Reset** | void |  |
| **Skip** | void |  |
| **TraceIn** | void |  |
| **TraceOut** | void |  |
| **mTokens** | void |  |

---

### Method Details

#### Emit

**Emit**(**token**: [IToken](IToken.md)): void

**Parameters**

- **token** ([IToken](IToken.md))  

---

**Emit**(): [IToken](IToken.md)

**Returns** [IToken](IToken.md)


---

#### GetCharErrorDisplay

**GetCharErrorDisplay**(**c**: int): string

**Parameters**

- **c** (int)  

**Returns** string


---

#### GetEndOfFileToken

**GetEndOfFileToken**(): [IToken](IToken.md)

**Returns** [IToken](IToken.md)


---

#### GetErrorMessage

**GetErrorMessage**(**e**: [RecognitionException](RecognitionException.md), ****: stringtokenNames): string

**Parameters**

- **e** ([RecognitionException](RecognitionException.md))  
- **** (stringtokenNames)  

**Returns** string


---

#### Match

**Match**(**s**: string): void

**Parameters**

- **s** (string)  

---

**Match**(**c**: int): void

**Parameters**

- **c** (int)  


---

#### MatchAny

**MatchAny**(): void


---

#### MatchRange

**MatchRange**(**a**: int, **b**: int): void

**Parameters**

- **a** (int)  
- **b** (int)  


---

#### NextToken

**NextToken**(): [IToken](IToken.md)

**Returns** [IToken](IToken.md)


---

#### ParseNextToken

**ParseNextToken**(): void


---

#### Recover

**Recover**(**re**: [RecognitionException](RecognitionException.md)): void

**Parameters**

- **re** ([RecognitionException](RecognitionException.md))  


---

#### ReportError

**ReportError**(**e**: [RecognitionException](RecognitionException.md)): void

**Parameters**

- **e** ([RecognitionException](RecognitionException.md))  


---

#### Reset

**Reset**(): void


---

#### Skip

**Skip**(): void


---

#### TraceIn

**TraceIn**(**ruleName**: string, **ruleIndex**: int): void

**Parameters**

- **ruleName** (string)  
- **ruleIndex** (int)  


---

#### TraceOut

**TraceOut**(**ruleName**: string, **ruleIndex**: int): void

**Parameters**

- **ruleName** (string)  
- **ruleIndex** (int)  


---

#### mTokens

**mTokens**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **input** | [ICharStream](ICharStream.md) |  |
