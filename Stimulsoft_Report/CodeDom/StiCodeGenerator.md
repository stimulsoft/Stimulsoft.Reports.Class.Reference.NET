---
title: "StiCodeGenerator Class"
---

## StiCodeGenerator Class

**Namespace:** `Stimulsoft.Report.CodeDom`

Class describes CodeGenerator for a report.

### Inheritance

Implements: ICodeGenerator  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NullToken** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ContinueOnNewLine** | void |  |
| **CreateEscapedIdentifier** | string |  |
| **CreateValidIdentifier** | string |  |
| **GenerateArgumentReferenceExpression** | void |  |
| **GenerateArrayCreateExpression** | void |  |
| **GenerateArrayIndexerExpression** | void |  |
| **GenerateAssignStatement** | void |  |
| **GenerateAttachEventStatement** | void |  |
| **GenerateAttributeDeclarationsEnd** | void |  |
| **GenerateAttributeDeclarationsStart** | void |  |
| **GenerateBaseReferenceExpression** | void |  |
| **GenerateBinaryOperatorExpression** | void |  |
| **GenerateCastExpression** | void |  |
| **GenerateCodeFromCompileUnit** | void |  |
| **GenerateCodeFromExpression** | void |  |
| **GenerateCodeFromNamespace** | void |  |
| **GenerateCodeFromStatement** | void |  |
| **GenerateCodeFromType** | void |  |
| **GenerateComment** | void |  |
| **GenerateCommentStatement** | void |  |
| **GenerateCompileUnit** | void |  |
| **GenerateCompileUnitEnd** | void |  |
| **GenerateCompileUnitStart** | void |  |
| **GenerateConditionStatement** | void |  |
| **GenerateConstructor** | void |  |
| **GenerateDecimalValue** | void |  |
| **GenerateDelegateCreateExpression** | void |  |
| **GenerateDelegateInvokeExpression** | void |  |
| **GenerateDirectionExpression** | void |  |
| **GenerateDoubleValue** | void |  |
| **GenerateEntryPointMethod** | void |  |
| **GenerateEvent** | void |  |
| **GenerateEventReferenceExpression** | void |  |
| **GenerateExpression** | void |  |
| **GenerateExpressionStatement** | void |  |
| **GenerateField** | void |  |
| **GenerateFieldReferenceExpression** | void |  |
| **GenerateGotoStatement** | void |  |
| **GenerateIndexerExpression** | void |  |
| **GenerateIterationStatement** | void |  |
| **GenerateLabeledStatement** | void |  |
| **GenerateLinePragmaEnd** | void |  |
| **GenerateLinePragmaStart** | void |  |
| **GenerateMethod** | void |  |
| **GenerateMethodInvokeExpression** | void |  |
| **GenerateMethodReferenceExpression** | void |  |
| **GenerateMethodReturnStatement** | void |  |
| **GenerateMethods** | void |  |
| **GenerateNamespace** | void |  |
| **GenerateNamespaceEnd** | void |  |
| **GenerateNamespaceImport** | void |  |
| **GenerateNamespaceImports** | void |  |
| **GenerateNamespaceStart** | void |  |
| **GenerateNamespaces** | void |  |
| **GenerateObjectCreateExpression** | void |  |
| **GenerateParameterDeclarationExpression** | void |  |
| **GeneratePrimitiveExpression** | void |  |
| **GenerateProperty** | void |  |
| **GeneratePropertyReferenceExpression** | void |  |
| **GeneratePropertySetValueReferenceExpression** | void |  |
| **GenerateRegionEnd** | void |  |
| **GenerateRegionEnds** | void |  |
| **GenerateRegionStart** | void |  |
| **GenerateRegionStarts** | void |  |
| **GenerateRemoveEventStatement** | void |  |
| **GenerateSingleFloatValue** | void |  |
| **GenerateSnippetCompileUnit** | void |  |
| **GenerateSnippetExpression** | void |  |
| **GenerateSnippetMember** | void |  |
| **GenerateSnippetStatement** | void |  |
| **GenerateStatement** | void |  |
| **GenerateStatements** | void |  |
| **GenerateThisReferenceExpression** | void |  |
| **GenerateThrowExceptionStatement** | void |  |
| **GenerateTryCatchFinallyStatement** | void |  |
| **GenerateTypeConstructor** | void |  |
| **GenerateTypeEnd** | void |  |
| **GenerateTypeOfExpression** | void |  |
| **GenerateTypeReferenceExpression** | void |  |
| **GenerateTypeStart** | void |  |
| **GenerateTypes** | void |  |
| **GenerateVariableDeclarationStatement** | void |  |
| **GenerateVariableReferenceExpression** | void |  |
| **GetBaseTypeOutput** | string |  |
| **GetClassKeyword** | string |  |
| **GetRegionEnd** | string |  |
| **GetRegionEndWord** | string |  |
| **GetRegionStart** | string |  |
| **GetRegionStartWord** | string |  |
| **GetTypeOutput** | string |  |
| **IsKeyword** | bool |  |
| **IsValidIdentifier** | bool |  |
| **IsValidLanguageIndependentIdentifier** `static` | bool |  |
| **OutputAttributeArgument** | void |  |
| **OutputAttributeDeclarations** | void |  |
| **OutputDirection** | void |  |
| **OutputExpressionList** *(+1 overloads)* | void |  |
| **OutputFieldScopeModifier** | void |  |
| **OutputIdentifier** | void |  |
| **OutputMemberAccessModifier** | void |  |
| **OutputMemberScopeModifier** | void |  |
| **OutputOperator** | void |  |
| **OutputParameters** | void |  |
| **OutputType** | void |  |
| **OutputTypeAttributes** | void |  |
| **OutputTypeNamePair** | void |  |
| **QuoteSnippetString** | string |  |
| **Supports** | bool |  |
| **ValidateIdentifier** | void |  |

---

### Method Details

#### ContinueOnNewLine

**ContinueOnNewLine**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### CreateEscapedIdentifier

**CreateEscapedIdentifier**(**value**: string): string

**Parameters**

- **value** (string)  

**Returns** string


---

#### CreateValidIdentifier

**CreateValidIdentifier**(**value**: string): string

**Parameters**

- **value** (string)  

**Returns** string


---

#### GenerateArgumentReferenceExpression

**GenerateArgumentReferenceExpression**(**e**: CodeArgumentReferenceExpression): void

**Parameters**

- **e** (CodeArgumentReferenceExpression)  


---

#### GenerateArrayCreateExpression

**GenerateArrayCreateExpression**(**e**: CodeArrayCreateExpression): void

**Parameters**

- **e** (CodeArrayCreateExpression)  


---

#### GenerateArrayIndexerExpression

**GenerateArrayIndexerExpression**(**e**: CodeArrayIndexerExpression): void

**Parameters**

- **e** (CodeArrayIndexerExpression)  


---

#### GenerateAssignStatement

**GenerateAssignStatement**(**e**: CodeAssignStatement): void

**Parameters**

- **e** (CodeAssignStatement)  


---

#### GenerateAttachEventStatement

**GenerateAttachEventStatement**(**e**: CodeAttachEventStatement): void

**Parameters**

- **e** (CodeAttachEventStatement)  


---

#### GenerateAttributeDeclarationsEnd

**GenerateAttributeDeclarationsEnd**(**attributes**: CodeAttributeDeclarationCollection): void

**Parameters**

- **attributes** (CodeAttributeDeclarationCollection)  


---

#### GenerateAttributeDeclarationsStart

**GenerateAttributeDeclarationsStart**(**attributes**: CodeAttributeDeclarationCollection): void

**Parameters**

- **attributes** (CodeAttributeDeclarationCollection)  


---

#### GenerateBaseReferenceExpression

**GenerateBaseReferenceExpression**(**e**: CodeBaseReferenceExpression): void

**Parameters**

- **e** (CodeBaseReferenceExpression)  


---

#### GenerateBinaryOperatorExpression

**GenerateBinaryOperatorExpression**(**e**: CodeBinaryOperatorExpression): void

**Parameters**

- **e** (CodeBinaryOperatorExpression)  


---

#### GenerateCastExpression

**GenerateCastExpression**(**e**: CodeCastExpression): void

**Parameters**

- **e** (CodeCastExpression)  


---

#### GenerateCodeFromCompileUnit

**GenerateCodeFromCompileUnit**(**e**: CodeCompileUnit, **w**: TextWriter, **o**: CodeGeneratorOptions): void

**Parameters**

- **e** (CodeCompileUnit)  
- **w** (TextWriter)  
- **o** (CodeGeneratorOptions)  


---

#### GenerateCodeFromExpression

**GenerateCodeFromExpression**(**e**: CodeExpression, **w**: TextWriter, **o**: CodeGeneratorOptions): void

**Parameters**

- **e** (CodeExpression)  
- **w** (TextWriter)  
- **o** (CodeGeneratorOptions)  


---

#### GenerateCodeFromNamespace

**GenerateCodeFromNamespace**(**e**: CodeNamespace, **w**: TextWriter, **o**: CodeGeneratorOptions): void

**Parameters**

- **e** (CodeNamespace)  
- **w** (TextWriter)  
- **o** (CodeGeneratorOptions)  


---

#### GenerateCodeFromStatement

**GenerateCodeFromStatement**(**e**: CodeStatement, **w**: TextWriter, **o**: CodeGeneratorOptions): void

**Parameters**

- **e** (CodeStatement)  
- **w** (TextWriter)  
- **o** (CodeGeneratorOptions)  


---

#### GenerateCodeFromType

**GenerateCodeFromType**(**e**: CodeTypeDeclaration, **w**: TextWriter, **o**: CodeGeneratorOptions): void

**Parameters**

- **e** (CodeTypeDeclaration)  
- **w** (TextWriter)  
- **o** (CodeGeneratorOptions)  


---

#### GenerateComment

**GenerateComment**(**e**: CodeComment): void

**Parameters**

- **e** (CodeComment)  


---

#### GenerateCommentStatement

**GenerateCommentStatement**(**e**: CodeCommentStatement): void

**Parameters**

- **e** (CodeCommentStatement)  


---

#### GenerateCompileUnit

**GenerateCompileUnit**(**e**: CodeCompileUnit): void

**Parameters**

- **e** (CodeCompileUnit)  


---

#### GenerateCompileUnitEnd

**GenerateCompileUnitEnd**(**e**: CodeCompileUnit): void

**Parameters**

- **e** (CodeCompileUnit)  


---

#### GenerateCompileUnitStart

**GenerateCompileUnitStart**(**e**: CodeCompileUnit): void

**Parameters**

- **e** (CodeCompileUnit)  


---

#### GenerateConditionStatement

**GenerateConditionStatement**(**e**: CodeConditionStatement): void

**Parameters**

- **e** (CodeConditionStatement)  


---

#### GenerateConstructor

**GenerateConstructor**(**e**: CodeConstructor, **c**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeConstructor)  
- **c** (CodeTypeDeclaration)  


---

#### GenerateDecimalValue

**GenerateDecimalValue**(**d**: Decimal): void

**Parameters**

- **d** (Decimal)  


---

#### GenerateDelegateCreateExpression

**GenerateDelegateCreateExpression**(**e**: CodeDelegateCreateExpression): void

**Parameters**

- **e** (CodeDelegateCreateExpression)  


---

#### GenerateDelegateInvokeExpression

**GenerateDelegateInvokeExpression**(**e**: CodeDelegateInvokeExpression): void

**Parameters**

- **e** (CodeDelegateInvokeExpression)  


---

#### GenerateDirectionExpression

**GenerateDirectionExpression**(**e**: CodeDirectionExpression): void

**Parameters**

- **e** (CodeDirectionExpression)  


---

#### GenerateDoubleValue

**GenerateDoubleValue**(**d**: Double): void

**Parameters**

- **d** (Double)  


---

#### GenerateEntryPointMethod

**GenerateEntryPointMethod**(**e**: CodeEntryPointMethod, **c**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeEntryPointMethod)  
- **c** (CodeTypeDeclaration)  


---

#### GenerateEvent

**GenerateEvent**(**e**: CodeMemberEvent, **c**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeMemberEvent)  
- **c** (CodeTypeDeclaration)  


---

#### GenerateEventReferenceExpression

**GenerateEventReferenceExpression**(**e**: CodeEventReferenceExpression): void

**Parameters**

- **e** (CodeEventReferenceExpression)  


---

#### GenerateExpression

**GenerateExpression**(**e**: CodeExpression): void

**Parameters**

- **e** (CodeExpression)  


---

#### GenerateExpressionStatement

**GenerateExpressionStatement**(**e**: CodeExpressionStatement): void

**Parameters**

- **e** (CodeExpressionStatement)  


---

#### GenerateField

**GenerateField**(**e**: CodeMemberField): void

**Parameters**

- **e** (CodeMemberField)  


---

#### GenerateFieldReferenceExpression

**GenerateFieldReferenceExpression**(**e**: CodeFieldReferenceExpression): void

**Parameters**

- **e** (CodeFieldReferenceExpression)  


---

#### GenerateGotoStatement

**GenerateGotoStatement**(**e**: CodeGotoStatement): void

**Parameters**

- **e** (CodeGotoStatement)  


---

#### GenerateIndexerExpression

**GenerateIndexerExpression**(**e**: CodeIndexerExpression): void

**Parameters**

- **e** (CodeIndexerExpression)  


---

#### GenerateIterationStatement

**GenerateIterationStatement**(**e**: CodeIterationStatement): void

**Parameters**

- **e** (CodeIterationStatement)  


---

#### GenerateLabeledStatement

**GenerateLabeledStatement**(**e**: CodeLabeledStatement): void

**Parameters**

- **e** (CodeLabeledStatement)  


---

#### GenerateLinePragmaEnd

**GenerateLinePragmaEnd**(**e**: CodeLinePragma): void

**Parameters**

- **e** (CodeLinePragma)  


---

#### GenerateLinePragmaStart

**GenerateLinePragmaStart**(**e**: CodeLinePragma): void

**Parameters**

- **e** (CodeLinePragma)  


---

#### GenerateMethod

**GenerateMethod**(**e**: CodeMemberMethod, **c**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeMemberMethod)  
- **c** (CodeTypeDeclaration)  


---

#### GenerateMethodInvokeExpression

**GenerateMethodInvokeExpression**(**e**: CodeMethodInvokeExpression): void

**Parameters**

- **e** (CodeMethodInvokeExpression)  


---

#### GenerateMethodReferenceExpression

**GenerateMethodReferenceExpression**(**e**: CodeMethodReferenceExpression): void

**Parameters**

- **e** (CodeMethodReferenceExpression)  


---

#### GenerateMethodReturnStatement

**GenerateMethodReturnStatement**(**e**: CodeMethodReturnStatement): void

**Parameters**

- **e** (CodeMethodReturnStatement)  


---

#### GenerateMethods

**GenerateMethods**(**e**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeTypeDeclaration)  


---

#### GenerateNamespace

**GenerateNamespace**(**e**: CodeNamespace): void

**Parameters**

- **e** (CodeNamespace)  


---

#### GenerateNamespaceEnd

**GenerateNamespaceEnd**(**e**: CodeNamespace): void

**Parameters**

- **e** (CodeNamespace)  


---

#### GenerateNamespaceImport

**GenerateNamespaceImport**(**e**: CodeNamespaceImport): void

**Parameters**

- **e** (CodeNamespaceImport)  


---

#### GenerateNamespaceImports

**GenerateNamespaceImports**(**e**: CodeNamespace): void

**Parameters**

- **e** (CodeNamespace)  


---

#### GenerateNamespaceStart

**GenerateNamespaceStart**(**e**: CodeNamespace): void

**Parameters**

- **e** (CodeNamespace)  


---

#### GenerateNamespaces

**GenerateNamespaces**(**e**: CodeCompileUnit): void

**Parameters**

- **e** (CodeCompileUnit)  


---

#### GenerateObjectCreateExpression

**GenerateObjectCreateExpression**(**e**: CodeObjectCreateExpression): void

**Parameters**

- **e** (CodeObjectCreateExpression)  


---

#### GenerateParameterDeclarationExpression

**GenerateParameterDeclarationExpression**(**e**: CodeParameterDeclarationExpression): void

**Parameters**

- **e** (CodeParameterDeclarationExpression)  


---

#### GeneratePrimitiveExpression

**GeneratePrimitiveExpression**(**e**: CodePrimitiveExpression): void

**Parameters**

- **e** (CodePrimitiveExpression)  


---

#### GenerateProperty

**GenerateProperty**(**e**: CodeMemberProperty, **c**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeMemberProperty)  
- **c** (CodeTypeDeclaration)  


---

#### GeneratePropertyReferenceExpression

**GeneratePropertyReferenceExpression**(**e**: CodePropertyReferenceExpression): void

**Parameters**

- **e** (CodePropertyReferenceExpression)  


---

#### GeneratePropertySetValueReferenceExpression

**GeneratePropertySetValueReferenceExpression**(**e**: CodePropertySetValueReferenceExpression): void

**Parameters**

- **e** (CodePropertySetValueReferenceExpression)  


---

#### GenerateRegionEnd

**GenerateRegionEnd**(**e**: [StiCodeRegionEnd](StiCodeRegionEnd.md)): void

**Parameters**

- **e** ([StiCodeRegionEnd](StiCodeRegionEnd.md))  


---

#### GenerateRegionEnds

**GenerateRegionEnds**(**e**: CodeCommentStatementCollection): void

**Parameters**

- **e** (CodeCommentStatementCollection)  


---

#### GenerateRegionStart

**GenerateRegionStart**(**e**: [StiCodeRegionStart](StiCodeRegionStart.md)): void

**Parameters**

- **e** ([StiCodeRegionStart](StiCodeRegionStart.md))  


---

#### GenerateRegionStarts

**GenerateRegionStarts**(**e**: CodeCommentStatementCollection): void

**Parameters**

- **e** (CodeCommentStatementCollection)  


---

#### GenerateRemoveEventStatement

**GenerateRemoveEventStatement**(**e**: CodeRemoveEventStatement): void

**Parameters**

- **e** (CodeRemoveEventStatement)  


---

#### GenerateSingleFloatValue

**GenerateSingleFloatValue**(**s**: Single): void

**Parameters**

- **s** (Single)  


---

#### GenerateSnippetCompileUnit

**GenerateSnippetCompileUnit**(**e**: CodeSnippetCompileUnit): void

**Parameters**

- **e** (CodeSnippetCompileUnit)  


---

#### GenerateSnippetExpression

**GenerateSnippetExpression**(**e**: CodeSnippetExpression): void

**Parameters**

- **e** (CodeSnippetExpression)  


---

#### GenerateSnippetMember

**GenerateSnippetMember**(**e**: CodeSnippetTypeMember): void

**Parameters**

- **e** (CodeSnippetTypeMember)  


---

#### GenerateSnippetStatement

**GenerateSnippetStatement**(**e**: CodeSnippetStatement): void

**Parameters**

- **e** (CodeSnippetStatement)  


---

#### GenerateStatement

**GenerateStatement**(**e**: CodeStatement): void

**Parameters**

- **e** (CodeStatement)  


---

#### GenerateStatements

**GenerateStatements**(**stms**: CodeStatementCollection): void

**Parameters**

- **stms** (CodeStatementCollection)  


---

#### GenerateThisReferenceExpression

**GenerateThisReferenceExpression**(**e**: CodeThisReferenceExpression): void

**Parameters**

- **e** (CodeThisReferenceExpression)  


---

#### GenerateThrowExceptionStatement

**GenerateThrowExceptionStatement**(**e**: CodeThrowExceptionStatement): void

**Parameters**

- **e** (CodeThrowExceptionStatement)  


---

#### GenerateTryCatchFinallyStatement

**GenerateTryCatchFinallyStatement**(**e**: CodeTryCatchFinallyStatement): void

**Parameters**

- **e** (CodeTryCatchFinallyStatement)  


---

#### GenerateTypeConstructor

**GenerateTypeConstructor**(**e**: CodeTypeConstructor): void

**Parameters**

- **e** (CodeTypeConstructor)  


---

#### GenerateTypeEnd

**GenerateTypeEnd**(**e**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeTypeDeclaration)  


---

#### GenerateTypeOfExpression

**GenerateTypeOfExpression**(**e**: CodeTypeOfExpression): void

**Parameters**

- **e** (CodeTypeOfExpression)  


---

#### GenerateTypeReferenceExpression

**GenerateTypeReferenceExpression**(**e**: CodeTypeReferenceExpression): void

**Parameters**

- **e** (CodeTypeReferenceExpression)  


---

#### GenerateTypeStart

**GenerateTypeStart**(**e**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeTypeDeclaration)  


---

#### GenerateTypes

**GenerateTypes**(**e**: CodeNamespace): void

**Parameters**

- **e** (CodeNamespace)  


---

#### GenerateVariableDeclarationStatement

**GenerateVariableDeclarationStatement**(**e**: CodeVariableDeclarationStatement): void

**Parameters**

- **e** (CodeVariableDeclarationStatement)  


---

#### GenerateVariableReferenceExpression

**GenerateVariableReferenceExpression**(**e**: CodeVariableReferenceExpression): void

**Parameters**

- **e** (CodeVariableReferenceExpression)  


---

#### GetBaseTypeOutput

**GetBaseTypeOutput**(**baseType**: string): string

**Parameters**

- **baseType** (string)  

**Returns** string


---

#### GetClassKeyword

**GetClassKeyword**(): string

**Returns** string


---

#### GetRegionEnd

**GetRegionEnd**(**s**: string): string

**Parameters**

- **s** (string)  

**Returns** string


---

#### GetRegionEndWord

**GetRegionEndWord**(): string

**Returns** string


---

#### GetRegionStart

**GetRegionStart**(**s**: string): string

**Parameters**

- **s** (string)  

**Returns** string


---

#### GetRegionStartWord

**GetRegionStartWord**(): string

**Returns** string


---

#### GetTypeOutput

**GetTypeOutput**(**value**: CodeTypeReference): string

**Parameters**

- **value** (CodeTypeReference)  

**Returns** string


---

#### IsKeyword

**IsKeyword**(**value**: string): bool

**Parameters**

- **value** (string)  

**Returns** bool


---

#### IsValidIdentifier

**IsValidIdentifier**(**value**: string): bool

**Parameters**

- **value** (string)  

**Returns** bool


---

#### IsValidLanguageIndependentIdentifier `static`

**IsValidLanguageIndependentIdentifier**(**value**: string): bool

**Parameters**

- **value** (string)  

**Returns** bool


---

#### OutputAttributeArgument

**OutputAttributeArgument**(**arg**: CodeAttributeArgument): void

**Parameters**

- **arg** (CodeAttributeArgument)  


---

#### OutputAttributeDeclarations

**OutputAttributeDeclarations**(**attributes**: CodeAttributeDeclarationCollection): void

**Parameters**

- **attributes** (CodeAttributeDeclarationCollection)  


---

#### OutputDirection

**OutputDirection**(**dir**: FieldDirection): void

**Parameters**

- **dir** (FieldDirection)  


---

#### OutputExpressionList

**OutputExpressionList**(**expressions**: CodeExpressionCollection): void

**Parameters**

- **expressions** (CodeExpressionCollection)  

---

**OutputExpressionList**(**expressions**: CodeExpressionCollection, **newlineBetweenItems**: bool): void

**Parameters**

- **expressions** (CodeExpressionCollection)  
- **newlineBetweenItems** (bool)  


---

#### OutputFieldScopeModifier

**OutputFieldScopeModifier**(**attributes**: MemberAttributes): void

**Parameters**

- **attributes** (MemberAttributes)  


---

#### OutputIdentifier

**OutputIdentifier**(**ident**: string): void

**Parameters**

- **ident** (string)  


---

#### OutputMemberAccessModifier

**OutputMemberAccessModifier**(**attributes**: MemberAttributes): void

**Parameters**

- **attributes** (MemberAttributes)  


---

#### OutputMemberScopeModifier

**OutputMemberScopeModifier**(**attributes**: MemberAttributes): void

**Parameters**

- **attributes** (MemberAttributes)  


---

#### OutputOperator

**OutputOperator**(**op**: CodeBinaryOperatorType): void

**Parameters**

- **op** (CodeBinaryOperatorType)  


---

#### OutputParameters

**OutputParameters**(**parameters**: CodeParameterDeclarationExpressionCollection): void

**Parameters**

- **parameters** (CodeParameterDeclarationExpressionCollection)  


---

#### OutputType

**OutputType**(**typeRef**: CodeTypeReference): void

**Parameters**

- **typeRef** (CodeTypeReference)  


---

#### OutputTypeAttributes

**OutputTypeAttributes**(**attributes**: TypeAttributes, **isStruct**: bool, **isEnum**: bool): void

**Parameters**

- **attributes** (TypeAttributes)  
- **isStruct** (bool)  
- **isEnum** (bool)  


---

#### OutputTypeNamePair

**OutputTypeNamePair**(**typeRef**: CodeTypeReference, **name**: string): void

**Parameters**

- **typeRef** (CodeTypeReference)  
- **name** (string)  


---

#### QuoteSnippetString

**QuoteSnippetString**(**value**: string): string

**Parameters**

- **value** (string)  

**Returns** string


---

#### Supports

**Supports**(**support**: GeneratorSupport): bool

**Parameters**

- **support** (GeneratorSupport)  

**Returns** bool


---

#### ValidateIdentifier

**ValidateIdentifier**(**value**: string): void

**Parameters**

- **value** (string)  

