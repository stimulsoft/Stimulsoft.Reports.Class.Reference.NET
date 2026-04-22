---
title: "StiCodeGenerator Class"
---

## StiCodeGenerator Class

**Namespace:** `Stimulsoft.Report.CodeDom`  
**Assembly:** `Stimulsoft.Report`

Class describes CodeGenerator for a report.

```csharp
public abstract class StiCodeGenerator
```

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
