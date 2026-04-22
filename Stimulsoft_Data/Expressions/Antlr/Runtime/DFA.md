---
title: "DFA Class"
---

## DFA Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class DFA
```

### Constructors

| Constructor | Description |
| --- | --- |
| **DFA**() |  |
| **DFA**(SpecialStateTransitionHandler specialStateTransition) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DebugRecognitionException** | void |  |
| **Error** | void |  |
| **NoViableAlt** | void |  |
| **Predict** | int |  |
| **UnpackEncodedString** `static` | short[] |  |
| **UnpackEncodedStringToUnsignedChars** `static` | char[] |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **accept** | short[] |  |
| **debug** | bool |  |
| **decisionNumber** | int |  |
| **eof** | short[] |  |
| **eot** | short[] |  |
| **max** | char[] |  |
| **min** | char[] |  |
| **recognizer** | [BaseRecognizer](BaseRecognizer.md) |  |
| **special** | short[] |  |
| **transition** | short[][] |  |
