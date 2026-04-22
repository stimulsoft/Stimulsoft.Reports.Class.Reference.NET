---
title: "StiCSharpScriptParser Class"
---

## StiCSharpScriptParser Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

Parses and executes C# scripts.

```csharp
public class StiCSharpScriptParser
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCSharpScriptParser**(string scriptText, [StiCSharpScriptParserOptions](Parser/StiCSharpScriptParserOptions.md) options) | Initializes a new instance of the StiParser class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowUsingDirective** `static` | bool | Gets or sets a value indicating whether the 'using' directive is allowed in the script. |
| **AllowUsingSecurityMode** `static` | bool | Gets or sets a value indicating whether type creation should be restricted to whitelist. When true, only types from the whitelist can be instantiated. Default value is true for maximum security. |
| **BlockStart** | TokenState |  |
| **CatchType** | Type |  |
| **Index** | int |  |
| **MaxArraySize** `static` | int | Gets or sets the maximum allowed size for array creation. This limit prevents potential denial-of-service attacks through excessive memory allocation. Default value is 1,000,000 elements. Set to 0 to disable the limit (not recommended for security). |
| **MaxLoopIterations** `static` | int | Gets or sets the maximum allowed number of iterations for loops (for, while, do-while, foreach). This limit prevents potential denial-of-service attacks through infinite or very long loops. Default value is 1,000,000 iterations. Set to 0 to disable the limit (not recommended for security). |
| **MaxRecursionDepth** `static` | int | Gets or sets the maximum allowed depth for recursion in method calls and expressions. This limit prevents potential stack overflow attacks through deep recursion. Default value is 100 levels. Set to 0 to disable the limit (not recommended for security). |
| **Result** | object | The result of the last executed expression. |
| **Token** | [StiToken](StiToken.md) |  |
| **VariableName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddAllowedNamespace** `static` | void | Adds a namespace to the whitelist. |
| **AddAllowedType** `static` *(+1 overloads)* | void | Adds a type to the whitelist. |
| **AddBlockedNamespace** `static` | void | Adds a namespace to the blacklist. |
| **AddBlockedType** `static` *(+1 overloads)* | void | Adds a type to the blacklist. |
| **Execute** `static` *(+1 overloads)* | object | Initializes a new instance of the StiParser class with the specified script text. |
| **GetTokenPositions** | List<TokenPosition> |  |
| **GetTokens** | List<[StiToken](StiToken.md)> |  |
| **GetVariable** | object | Gets a variable value from the script or external variable provider. |
| **GetVariableAsBool** | bool? | Gets a variable value as a string from the script or external variable provider. |
| **GetVariableAsDecimal** | decimal? | Gets a variable value as a string from the script or external variable provider. |
| **GetVariableAsDouble** | double? | Gets a variable value as a string from the script or external variable provider. |
| **GetVariableAsFloat** | float? | Gets a variable value as a string from the script or external variable provider. |
| **GetVariableAsInt** | int? | Gets a variable value as a string from the script or external variable provider. |
| **GetVariableAsLong** | long? | Gets a variable value as a string from the script or external variable provider. |
| **RegisterFunction** | void | Registers a custom function that can be called from the script. |
| **RegisterNamespace** | void | Registers a namespace that can be used from the script. |
| **RemoveAllowedNamespace** `static` | void | Removes a namespace from the whitelist. |
| **RemoveAllowedType** `static` *(+1 overloads)* | void | Removes a type from the whitelist. |
| **RemoveBlockedNamespace** `static` | void | Removes a namespace from the blacklist. |
| **RemoveBlockedType** `static` *(+1 overloads)* | void | Removes a type from the blacklist. |
| **SetExternalObjectsProvider** | void | Sets an external objects provider that can be used in the script. |
| **SetScriptSecurity** `static` | void |  |
| **SetThisObject** | void |  |
| **SetVariable** | void | Sets a variable value that can be used in the script. |
