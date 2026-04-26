---
title: "DFA Class"
---

## DFA Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Constructors

| Constructor | Description |
| --- | --- |
| **DFA**() |  |
| **DFA**(SpecialStateTransitionHandler specialStateTransition) |  |

**DFA**()

---

**DFA**(**specialStateTransition**: SpecialStateTransitionHandler)

**Parameters**

- **specialStateTransition** (SpecialStateTransitionHandler)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DebugRecognitionException** | void |  |
| **Error** | void |  |
| **NoViableAlt** | void |  |
| **Predict** | int |  |
| **UnpackEncodedString** `static` | short[] |  |
| **UnpackEncodedStringToUnsignedChars** `static` | char[] |  |

---

### Method Details

#### DebugRecognitionException

**DebugRecognitionException**(**ex**: [RecognitionException](RecognitionException.md)): void

**Parameters**

- **ex** ([RecognitionException](RecognitionException.md))  


---

#### Error

**Error**(**nvae**: [NoViableAltException](NoViableAltException.md)): void

**Parameters**

- **nvae** ([NoViableAltException](NoViableAltException.md))  


---

#### NoViableAlt

**NoViableAlt**(**s**: int, **input**: [IIntStream](IIntStream.md)): void

**Parameters**

- **s** (int)  
- **input** ([IIntStream](IIntStream.md))  


---

#### Predict

**Predict**(**input**: [IIntStream](IIntStream.md)): int

**Parameters**

- **input** ([IIntStream](IIntStream.md))  

**Returns** int


---

#### UnpackEncodedString `static`

**UnpackEncodedString**(**encodedString**: string): short[]

**Parameters**

- **encodedString** (string)  

**Returns** short[]


---

#### UnpackEncodedStringToUnsignedChars `static`

**UnpackEncodedStringToUnsignedChars**(**encodedString**: string): char[]

**Parameters**

- **encodedString** (string)  

**Returns** char[]


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
