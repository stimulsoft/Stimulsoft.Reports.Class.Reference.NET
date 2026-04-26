---
title: "BaseRecognizer Class"
---

## BaseRecognizer Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Constructors

| Constructor | Description |
| --- | --- |
| **BaseRecognizer**() |  |
| **BaseRecognizer**([RecognizerSharedState](RecognizerSharedState.md) state) |  |

**BaseRecognizer**()

---

**BaseRecognizer**(**state**: [RecognizerSharedState](RecognizerSharedState.md))

**Parameters**

- **state** ([RecognizerSharedState](RecognizerSharedState.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlreadyParsedRule** | bool |  |
| **BeginResync** | void |  |
| **CombineFollows** | [BitSet](BitSet.md) |  |
| **ComputeContextSensitiveRuleFOLLOW** | [BitSet](BitSet.md) |  |
| **ComputeErrorRecoverySet** | [BitSet](BitSet.md) |  |
| **ConsumeUntil** *(+1 overloads)* | void |  |
| **DebugBeginBacktrack** | void |  |
| **DebugEndBacktrack** | void |  |
| **DebugEnterAlt** | void |  |
| **DebugEnterDecision** | void |  |
| **DebugEnterRule** | void |  |
| **DebugEnterSubRule** | void |  |
| **DebugExitDecision** | void |  |
| **DebugExitRule** | void |  |
| **DebugExitSubRule** | void |  |
| **DebugLocation** | void |  |
| **DebugRecognitionException** | void |  |
| **DebugSemanticPredicate** | void |  |
| **EmitErrorMessage** | void |  |
| **EndResync** | void |  |
| **GetCurrentInputSymbol** | object |  |
| **GetErrorHeader** | string |  |
| **GetErrorMessage** | string |  |
| **GetRuleInvocationStack** *(+1 overloads)* | IList<string> |  |
| **GetRuleMemoization** | int |  |
| **GetRuleMemoizationCacheSize** | int |  |
| **GetTokenErrorDisplay** | string |  |
| **InitDFAs** | void |  |
| **Match** | object |  |
| **MatchAny** | void |  |
| **MismatchIsMissingToken** | bool |  |
| **MismatchIsUnwantedToken** | bool |  |
| **PopFollow** | void |  |
| **PushFollow** | void |  |
| **Recover** | void |  |
| **RecoverFromMismatchedToken** | object |  |
| **ReportError** | void |  |
| **Reset** | void |  |
| **SetState** | void |  |
| **ToStrings** | List<string> |  |
| **TraceIn** | void |  |
| **TraceOut** | void |  |

---

### Method Details

#### AlreadyParsedRule

**AlreadyParsedRule**(**input**: [IIntStream](IIntStream.md), **ruleIndex**: int): bool

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **ruleIndex** (int)  

**Returns** bool


---

#### BeginResync

**BeginResync**(): void


---

#### CombineFollows

**CombineFollows**(**exact**: bool): [BitSet](BitSet.md)

**Parameters**

- **exact** (bool)  

**Returns** [BitSet](BitSet.md)


---

#### ComputeContextSensitiveRuleFOLLOW

**ComputeContextSensitiveRuleFOLLOW**(): [BitSet](BitSet.md)

**Returns** [BitSet](BitSet.md)


---

#### ComputeErrorRecoverySet

**ComputeErrorRecoverySet**(): [BitSet](BitSet.md)

**Returns** [BitSet](BitSet.md)


---

#### ConsumeUntil

**ConsumeUntil**(**input**: [IIntStream](IIntStream.md), **tokenType**: int): void

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **tokenType** (int)  

---

**ConsumeUntil**(**input**: [IIntStream](IIntStream.md), **set**: [BitSet](BitSet.md)): void

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **set** ([BitSet](BitSet.md))  


---

#### DebugBeginBacktrack

**DebugBeginBacktrack**(**level**: int): void

**Parameters**

- **level** (int)  


---

#### DebugEndBacktrack

**DebugEndBacktrack**(**level**: int, **successful**: bool): void

**Parameters**

- **level** (int)  
- **successful** (bool)  


---

#### DebugEnterAlt

**DebugEnterAlt**(**alt**: int): void

**Parameters**

- **alt** (int)  


---

#### DebugEnterDecision

**DebugEnterDecision**(**decisionNumber**: int, **couldBacktrack**: bool): void

**Parameters**

- **decisionNumber** (int)  
- **couldBacktrack** (bool)  


---

#### DebugEnterRule

**DebugEnterRule**(**grammarFileName**: string, **ruleName**: string): void

**Parameters**

- **grammarFileName** (string)  
- **ruleName** (string)  


---

#### DebugEnterSubRule

**DebugEnterSubRule**(**decisionNumber**: int): void

**Parameters**

- **decisionNumber** (int)  


---

#### DebugExitDecision

**DebugExitDecision**(**decisionNumber**: int): void

**Parameters**

- **decisionNumber** (int)  


---

#### DebugExitRule

**DebugExitRule**(**grammarFileName**: string, **ruleName**: string): void

**Parameters**

- **grammarFileName** (string)  
- **ruleName** (string)  


---

#### DebugExitSubRule

**DebugExitSubRule**(**decisionNumber**: int): void

**Parameters**

- **decisionNumber** (int)  


---

#### DebugLocation

**DebugLocation**(**line**: int, **charPositionInLine**: int): void

**Parameters**

- **line** (int)  
- **charPositionInLine** (int)  


---

#### DebugRecognitionException

**DebugRecognitionException**(**ex**: [RecognitionException](RecognitionException.md)): void

**Parameters**

- **ex** ([RecognitionException](RecognitionException.md))  


---

#### DebugSemanticPredicate

**DebugSemanticPredicate**(**result**: bool, **predicate**: string): void

**Parameters**

- **result** (bool)  
- **predicate** (string)  


---

#### EmitErrorMessage

**EmitErrorMessage**(**msg**: string): void

**Parameters**

- **msg** (string)  


---

#### EndResync

**EndResync**(): void


---

#### GetCurrentInputSymbol

**GetCurrentInputSymbol**(**input**: [IIntStream](IIntStream.md)): object

**Parameters**

- **input** ([IIntStream](IIntStream.md))  

**Returns** object


---

#### GetErrorHeader

**GetErrorHeader**(**e**: [RecognitionException](RecognitionException.md)): string

**Parameters**

- **e** ([RecognitionException](RecognitionException.md))  

**Returns** string


---

#### GetErrorMessage

**GetErrorMessage**(**e**: [RecognitionException](RecognitionException.md), ****: stringtokenNames): string

**Parameters**

- **e** ([RecognitionException](RecognitionException.md))  
- **** (stringtokenNames)  

**Returns** string


---

#### GetRuleInvocationStack

**GetRuleInvocationStack**(): IList<string>

**Returns** IList<string>

---

**GetRuleInvocationStack**(**trace**: StackTrace): IList<string>

**Parameters**

- **trace** (StackTrace)  

**Returns** IList<string>


---

#### GetRuleMemoization

**GetRuleMemoization**(**ruleIndex**: int, **ruleStartIndex**: int): int

**Parameters**

- **ruleIndex** (int)  
- **ruleStartIndex** (int)  

**Returns** int


---

#### GetRuleMemoizationCacheSize

**GetRuleMemoizationCacheSize**(): int

**Returns** int


---

#### GetTokenErrorDisplay

**GetTokenErrorDisplay**(**t**: [IToken](IToken.md)): string

**Parameters**

- **t** ([IToken](IToken.md))  

**Returns** string


---

#### InitDFAs

**InitDFAs**(): void


---

#### Match

**Match**(**input**: [IIntStream](IIntStream.md), **ttype**: int, **follow**: [BitSet](BitSet.md)): object

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **ttype** (int)  
- **follow** ([BitSet](BitSet.md))  

**Returns** object


---

#### MatchAny

**MatchAny**(**input**: [IIntStream](IIntStream.md)): void

**Parameters**

- **input** ([IIntStream](IIntStream.md))  


---

#### MismatchIsMissingToken

**MismatchIsMissingToken**(**input**: [IIntStream](IIntStream.md), **follow**: [BitSet](BitSet.md)): bool

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **follow** ([BitSet](BitSet.md))  

**Returns** bool


---

#### MismatchIsUnwantedToken

**MismatchIsUnwantedToken**(**input**: [IIntStream](IIntStream.md), **ttype**: int): bool

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **ttype** (int)  

**Returns** bool


---

#### PopFollow

**PopFollow**(): void


---

#### PushFollow

**PushFollow**(**fset**: [BitSet](BitSet.md)): void

**Parameters**

- **fset** ([BitSet](BitSet.md))  


---

#### Recover

**Recover**(**input**: [IIntStream](IIntStream.md), **re**: [RecognitionException](RecognitionException.md)): void

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **re** ([RecognitionException](RecognitionException.md))  


---

#### RecoverFromMismatchedToken

**RecoverFromMismatchedToken**(**input**: [IIntStream](IIntStream.md), **ttype**: int, **follow**: [BitSet](BitSet.md)): object

**Parameters**

- **input** ([IIntStream](IIntStream.md))  
- **ttype** (int)  
- **follow** ([BitSet](BitSet.md))  

**Returns** object


---

#### ReportError

**ReportError**(**e**: [RecognitionException](RecognitionException.md)): void

**Parameters**

- **e** ([RecognitionException](RecognitionException.md))  


---

#### Reset

**Reset**(): void


---

#### SetState

**SetState**(**value**: [RecognizerSharedState](RecognizerSharedState.md)): void

**Parameters**

- **value** ([RecognizerSharedState](RecognizerSharedState.md))  


---

#### ToStrings

**ToStrings**(**tokens**: ICollection<[IToken](IToken.md)>): List<string>

**Parameters**

- **tokens** (ICollection<[IToken](IToken.md)>)  

**Returns** List<string>


---

#### TraceIn

**TraceIn**(**ruleName**: string, **ruleIndex**: int, **inputSymbol**: object): void

**Parameters**

- **ruleName** (string)  
- **ruleIndex** (int)  
- **inputSymbol** (object)  


---

#### TraceOut

**TraceOut**(**ruleName**: string, **ruleIndex**: int, **inputSymbol**: object): void

**Parameters**

- **ruleName** (string)  
- **ruleIndex** (int)  
- **inputSymbol** (object)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DefaultTokenChannel** | int |  |
| **Hidden** | int |  |
| **InitialFollowStackSize** | int |  |
| **MemoRuleFailed** | int |  |
| **MemoRuleUnknown** | int |  |
| **NextTokenRuleName** | string |  |
