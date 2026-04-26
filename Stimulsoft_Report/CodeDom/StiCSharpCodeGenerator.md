---
title: "StiCSharpCodeGenerator Class"
---

## StiCSharpCodeGenerator Class

**Namespace:** `Stimulsoft.Report.CodeDom`

Class describes CSharp CodeGenerator.

### Inheritance

Inherits from: [StiCodeGenerator](StiCodeGenerator.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **MaximizeStringLength** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
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
| **GenerateCastExpression** | void |  |
| **GenerateComment** | void |  |
| **GenerateCompileUnitStart** | void |  |
| **GenerateConditionStatement** | void |  |
| **GenerateConstructor** | void |  |
| **GenerateDecimalValue** | void |  |
| **GenerateDelegateCreateExpression** | void |  |
| **GenerateDelegateInvokeExpression** | void |  |
| **GenerateEntryPointMethod** | void |  |
| **GenerateEvent** | void |  |
| **GenerateEventReferenceExpression** | void |  |
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
| **GenerateNamespaceEnd** | void |  |
| **GenerateNamespaceImport** | void |  |
| **GenerateNamespaceStart** | void |  |
| **GenerateObjectCreateExpression** | void |  |
| **GenerateParameterDeclarationExpression** | void |  |
| **GeneratePrimitiveExpression** | void |  |
| **GenerateProperty** | void |  |
| **GeneratePropertyReferenceExpression** | void |  |
| **GeneratePropertySetValueReferenceExpression** | void |  |
| **GenerateRegionEnd** | void |  |
| **GenerateRegionStart** | void |  |
| **GenerateRemoveEventStatement** | void |  |
| **GenerateSingleFloatValue** | void |  |
| **GenerateSnippetExpression** | void |  |
| **GenerateSnippetMember** | void |  |
| **GenerateSnippetStatement** | void |  |
| **GenerateThisReferenceExpression** | void |  |
| **GenerateThrowExceptionStatement** | void |  |
| **GenerateTryCatchFinallyStatement** | void |  |
| **GenerateTypeConstructor** | void |  |
| **GenerateTypeEnd** | void |  |
| **GenerateTypeStart** | void |  |
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
| **IsKeywordExist** `static` | bool |  |
| **IsValidIdentifier** | bool |  |
| **Main** `static` | void |  |
| **OutputFieldScopeModifier** | void |  |
| **OutputIdentifier** | void |  |
| **OutputMemberScopeModifier** | void |  |
| **OutputStartingBrace** | void |  |
| **OutputType** | void |  |
| **QuoteSnippetString** | string |  |
| **QuoteSnippetStringCStyle** | string |  |
| **Supports** | bool |  |

---

### Method Details

#### CreateEscapedIdentifier

**CreateEscapedIdentifier**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### CreateValidIdentifier

**CreateValidIdentifier**(**name**: string): string

**Parameters**

- **name** (string)  

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

#### GenerateCastExpression

**GenerateCastExpression**(**e**: CodeCastExpression): void

**Parameters**

- **e** (CodeCastExpression)  


---

#### GenerateComment

**GenerateComment**(**e**: CodeComment): void

**Parameters**

- **e** (CodeComment)  


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

#### GenerateNamespaceStart

**GenerateNamespaceStart**(**e**: CodeNamespace): void

**Parameters**

- **e** (CodeNamespace)  


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

#### GenerateRegionStart

**GenerateRegionStart**(**e**: [StiCodeRegionStart](StiCodeRegionStart.md)): void

**Parameters**

- **e** ([StiCodeRegionStart](StiCodeRegionStart.md))  


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

#### GenerateTypeStart

**GenerateTypeStart**(**e**: CodeTypeDeclaration): void

**Parameters**

- **e** (CodeTypeDeclaration)  


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

**GetTypeOutput**(**typeRef**: CodeTypeReference): string

**Parameters**

- **typeRef** (CodeTypeReference)  

**Returns** string


---

#### IsKeyword

**IsKeyword**(**value**: string): bool

**Parameters**

- **value** (string)  

**Returns** bool


---

#### IsKeywordExist `static`

**IsKeywordExist**(**value**: string): bool

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

#### Main `static`

**Main**(): void


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

#### OutputMemberScopeModifier

**OutputMemberScopeModifier**(**attributes**: MemberAttributes): void

**Parameters**

- **attributes** (MemberAttributes)  


---

#### OutputStartingBrace

**OutputStartingBrace**(): void


---

#### OutputType

**OutputType**(**typeRef**: CodeTypeReference): void

**Parameters**

- **typeRef** (CodeTypeReference)  


---

#### QuoteSnippetString

**QuoteSnippetString**(**value**: string): string

**Parameters**

- **value** (string)  

**Returns** string


---

#### QuoteSnippetStringCStyle

**QuoteSnippetStringCStyle**(**value**: string): string

**Parameters**

- **value** (string)  

**Returns** string


---

#### Supports

**Supports**(**support**: GeneratorSupport): bool

**Parameters**

- **support** (GeneratorSupport)  

**Returns** bool

