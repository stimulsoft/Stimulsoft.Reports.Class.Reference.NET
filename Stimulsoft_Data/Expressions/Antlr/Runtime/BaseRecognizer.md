---
title: "BaseRecognizer Class"
---

## BaseRecognizer Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public abstract class BaseRecognizer
```

### Constructors

| Constructor | Description |
| --- | --- |
| **BaseRecognizer**() |  |
| **BaseRecognizer**([RecognizerSharedState](RecognizerSharedState.md) state) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DefaultTokenChannel** | int |  |
| **Hidden** | int |  |
| **InitialFollowStackSize** | int |  |
| **MemoRuleFailed** | int |  |
| **MemoRuleUnknown** | int |  |
| **NextTokenRuleName** | string |  |
