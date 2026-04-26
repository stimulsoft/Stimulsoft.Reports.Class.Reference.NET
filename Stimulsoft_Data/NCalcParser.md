---
title: "NCalcParser Class"
---

## NCalcParser Class

**Namespace:** ``

### Inheritance

Inherits from: [Parser](Expressions/Antlr/Runtime/Parser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **NCalcParser**([ITokenStream](Expressions/Antlr/Runtime/ITokenStream.md) input) |  |
| **NCalcParser**([ITokenStream](Expressions/Antlr/Runtime/ITokenStream.md) input, [RecognizerSharedState](Expressions/Antlr/Runtime/RecognizerSharedState.md) state) |  |

**NCalcParser**(**input**: [ITokenStream](Expressions/Antlr/Runtime/ITokenStream.md))

**Parameters**

- **input** ([ITokenStream](Expressions/Antlr/Runtime/ITokenStream.md))  

---

**NCalcParser**(**input**: [ITokenStream](Expressions/Antlr/Runtime/ITokenStream.md), **state**: [RecognizerSharedState](Expressions/Antlr/Runtime/RecognizerSharedState.md))

**Parameters**

- **input** ([ITokenStream](Expressions/Antlr/Runtime/ITokenStream.md))  
- **state** ([RecognizerSharedState](Expressions/Antlr/Runtime/RecognizerSharedState.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Errors** | List<string> |  |
| **GrammarFileName** | string |  |
| **TokenNames** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DisplayRecognitionError** | void |  |
| **ncalcExpression** | NCalcParser.ncalcExpression_return |  |

---

### Method Details

#### DisplayRecognitionError

**DisplayRecognitionError**(****: StringtokenNames, **e**: [RecognitionException](Expressions/Antlr/Runtime/RecognitionException.md)): void

**Parameters**

- **** (StringtokenNames)  
- **e** ([RecognitionException](Expressions/Antlr/Runtime/RecognitionException.md))  


---

#### ncalcExpression

**ncalcExpression**(): NCalcParser.ncalcExpression_return

**Returns** NCalcParser.ncalcExpression_return


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DATETIME** | int |  |
| **DIGIT** | int |  |
| **E** | int |  |
| **EOF** | int |  |
| **EscapeSequence** | int |  |
| **FALSE** | int |  |
| **FLOAT** | int |  |
| **HexDigit** | int |  |
| **ID** | int |  |
| **INTEGER** | int |  |
| **LETTER** | int |  |
| **NAME** | int |  |
| **STRING** | int |  |
| **TRUE** | int |  |
| **T__19** | int |  |
| **T__20** | int |  |
| **T__21** | int |  |
| **T__22** | int |  |
| **T__23** | int |  |
| **T__24** | int |  |
| **T__25** | int |  |
| **T__26** | int |  |
| **T__27** | int |  |
| **T__28** | int |  |
| **T__29** | int |  |
| **T__30** | int |  |
| **T__31** | int |  |
| **T__32** | int |  |
| **T__33** | int |  |
| **T__34** | int |  |
| **T__35** | int |  |
| **T__36** | int |  |
| **T__37** | int |  |
| **T__38** | int |  |
| **T__39** | int |  |
| **T__40** | int |  |
| **T__41** | int |  |
| **T__42** | int |  |
| **T__43** | int |  |
| **T__44** | int |  |
| **T__45** | int |  |
| **T__46** | int |  |
| **T__47** | int |  |
| **T__48** | int |  |
| **UnicodeEscape** | int |  |
| **WS** | int |  |
| **_21_in_multiplicativeExpression717** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_23_in_bitwiseAndExpression346** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_24_in_arguments1002** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_24_in_primaryExpression825** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_25_in_arguments1013** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_25_in_primaryExpression829** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_26_in_multiplicativeExpression697** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_27_in_additiveExpression632** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_28_in_expressionList969** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_29_in_additiveExpression642** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_29_in_unaryExpression801** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_30_in_multiplicativeExpression707** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_31_in_logicalExpression86** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_32_in_relationalExpression481** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_33_in_shiftExpression567** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_34_in_relationalExpression491** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_38_in_relationalExpression502** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_39_in_relationalExpression512** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_40_in_shiftExpression577** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_41_in_logicalExpression80** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_42_in_bitwiseXOrExpression295** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_46_in_bitwiseOrExpression242** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_48_in_unaryExpression787** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_DATETIME_in_value897** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_EOF_in_ncalcExpression54** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_FALSE_in_value912** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_FLOAT_in_value880** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_ID_in_identifier930** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_INTEGER_in_value872** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_NAME_in_identifier938** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_STRING_in_value888** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_TRUE_in_value904** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_additiveExpression_in_shiftExpression556** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_additiveExpression_in_shiftExpression589** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_arguments_in_primaryExpression852** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_bitwiseAndExpression_in_bitwiseXOrExpression286** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_bitwiseAndExpression_in_bitwiseXOrExpression305** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_bitwiseOrExpression_in_bitwiseOrExpression252** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_bitwiseOrExpression_in_booleanAndExpression176** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_bitwiseOrExpression_in_booleanAndExpression201** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_bitwiseXOrExpression_in_bitwiseOrExpression233** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_booleanAndExpression_in_conditionalExpression117** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_conditionalExpression_in_conditionalExpression142** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_conditionalExpression_in_logicalExpression74** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_conditionalExpression_in_logicalExpression84** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_conditionalExpression_in_logicalExpression90** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_equalityExpression_in_bitwiseAndExpression337** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_equalityExpression_in_bitwiseAndExpression356** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_expressionList_in_arguments1006** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_identifier_in_primaryExpression847** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_logicalExpression_in_expressionList962** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_logicalExpression_in_expressionList973** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_logicalExpression_in_ncalcExpression52** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_logicalExpression_in_primaryExpression827** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_multiplicativeExpression_in_additiveExpression621** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_multiplicativeExpression_in_additiveExpression654** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_primaryExpression_in_unaryExpression756** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_primaryExpression_in_unaryExpression775** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_primaryExpression_in_unaryExpression790** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_primaryExpression_in_unaryExpression803** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_relationalExpression_in_equalityExpression390** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_relationalExpression_in_equalityExpression437** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_set_in_booleanAndExpression185** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_set_in_conditionalExpression126** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_set_in_equalityExpression401** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_set_in_equalityExpression418** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_set_in_unaryExpression767** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_shiftExpression_in_relationalExpression470** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_shiftExpression_in_relationalExpression524** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_unaryExpression_in_multiplicativeExpression686** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_unaryExpression_in_multiplicativeExpression729** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **_value_in_primaryExpression839** | [BitSet](Expressions/Antlr/Runtime/BitSet.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **value** | [ValueExpression](Expressions/NCalc/Domain/ValueExpression.md) |  |
| **value** | [Identifier](Expressions/NCalc/Domain/Identifier.md) |  |
| **value** | List<[LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md)> |  |
| **value** | List<[LogicalExpression](Expressions/NCalc/Domain/LogicalExpression.md)> |  |
