---
title: "StiCSharpScriptParser Class"
---

## StiCSharpScriptParser Class

**Namespace:** `Stimulsoft.Base`

Parses and executes C# scripts.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCSharpScriptParser**(string scriptText, [StiCSharpScriptParserOptions](../Parser/StiCSharpScriptParserOptions.md) options) | Initializes a new instance of the StiParser class. |

**StiCSharpScriptParser**(**scriptText**: string, **options**: [StiCSharpScriptParserOptions](../Parser/StiCSharpScriptParserOptions.md))

Initializes a new instance of the StiParser class.

**Parameters**

- **scriptText** (string) — The script text to parse and execute.  
- **options** ([StiCSharpScriptParserOptions](../Parser/StiCSharpScriptParserOptions.md))  


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

---

### Method Details

#### AddAllowedNamespace `static`

**AddAllowedNamespace**(**namespaceName**: string): void

Adds a namespace to the whitelist.

**Parameters**

- **namespaceName** (string)  


---

#### AddAllowedType `static`

**AddAllowedType**(**type**: Type): void

Adds a type to the whitelist.

**Parameters**

- **type** (Type)  

---

**AddAllowedType**(**typeName**: string): void

Adds a type to the whitelist by name.

**Parameters**

- **typeName** (string)  


---

#### AddBlockedNamespace `static`

**AddBlockedNamespace**(**namespaceName**: string): void

Adds a namespace to the blacklist.

**Parameters**

- **namespaceName** (string)  


---

#### AddBlockedType `static`

**AddBlockedType**(**type**: Type): void

Adds a type to the blacklist.

**Parameters**

- **type** (Type)  

---

**AddBlockedType**(**typeName**: string): void

Adds a type to the blacklist by name.

**Parameters**

- **typeName** (string)  


---

#### Execute `static`

**Execute**(**script**: string): object

Initializes a new instance of the StiParser class with the specified script text.

**Parameters**

- **script** (string)  

**Returns** object

---

**Execute**(**timeoutMilliseconds**: int): object

Starts the parsing and execution of the script.

**Parameters**

- **timeoutMilliseconds** (int)  

**Returns** object — The result of the script execution.


---

#### GetTokenPositions

**GetTokenPositions**(): List<TokenPosition>

**Returns** List<TokenPosition>


---

#### GetTokens

**GetTokens**(): List<[StiToken](StiToken.md)>

**Returns** List<[StiToken](StiToken.md)>


---

#### GetVariable

**GetVariable**(**name**: string): object

Gets a variable value from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** object


---

#### GetVariableAsBool

**GetVariableAsBool**(**name**: string): bool?

Gets a variable value as a string from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** bool?


---

#### GetVariableAsDecimal

**GetVariableAsDecimal**(**name**: string): decimal?

Gets a variable value as a string from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** decimal?


---

#### GetVariableAsDouble

**GetVariableAsDouble**(**name**: string): double?

Gets a variable value as a string from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** double?


---

#### GetVariableAsFloat

**GetVariableAsFloat**(**name**: string): float?

Gets a variable value as a string from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** float?


---

#### GetVariableAsInt

**GetVariableAsInt**(**name**: string): int?

Gets a variable value as a string from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** int?


---

#### GetVariableAsLong

**GetVariableAsLong**(**name**: string): long?

Gets a variable value as a string from the script or external variable provider.

**Parameters**

- **name** (string)  

**Returns** long?


---

#### RegisterFunction

**RegisterFunction**(**name**: string, **function**: [Func](../../Stimulsoft_Report/root/Func.md)<object, object>): void

Registers a custom function that can be called from the script.

**Parameters**

- **name** (string) — The function name.  
- **function** ([Func](../../Stimulsoft_Report/root/Func.md)<object, object>) — The function implementation.  


---

#### RegisterNamespace

**RegisterNamespace**(**name**: string): void

Registers a namespace that can be used from the script.

**Parameters**

- **name** (string) — The namespace name.  


---

#### RemoveAllowedNamespace `static`

**RemoveAllowedNamespace**(**namespaceName**: string): void

Removes a namespace from the whitelist.

**Parameters**

- **namespaceName** (string)  


---

#### RemoveAllowedType `static`

**RemoveAllowedType**(**type**: Type): void

Removes a type from the whitelist.

**Parameters**

- **type** (Type)  

---

**RemoveAllowedType**(**typeName**: string): void

Removes a type from the whitelist by name.

**Parameters**

- **typeName** (string)  


---

#### RemoveBlockedNamespace `static`

**RemoveBlockedNamespace**(**namespaceName**: string): void

Removes a namespace from the blacklist.

**Parameters**

- **namespaceName** (string)  


---

#### RemoveBlockedType `static`

**RemoveBlockedType**(**type**: Type): void

Removes a type from the blacklist.

**Parameters**

- **type** (Type)  

---

**RemoveBlockedType**(**typeName**: string): void

Removes a type from the blacklist by name.

**Parameters**

- **typeName** (string)  


---

#### SetExternalObjectsProvider

**SetExternalObjectsProvider**(**provider**: IExternalObjectsProvider): void

Sets an external objects provider that can be used in the script.

**Parameters**

- **provider** (IExternalObjectsProvider)  


---

#### SetScriptSecurity `static`

**SetScriptSecurity**(**securityMode**: [StiScriptSecurity](StiScriptSecurity.md)): void

**Parameters**

- **securityMode** ([StiScriptSecurity](StiScriptSecurity.md))  


---

#### SetThisObject

**SetThisObject**(**thisObject**: object): void

**Parameters**

- **thisObject** (object)  


---

#### SetVariable

**SetVariable**(**name**: string, **value**: object): void

Sets a variable value that can be used in the script.

**Parameters**

- **name** (string) — The variable name.  
- **value** (object)  

