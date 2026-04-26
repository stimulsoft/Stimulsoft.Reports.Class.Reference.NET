---
title: "StiFunctions Class"
---

## StiFunctions Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddFunction** `static` | StiFunction | Adds new function with specified parameters. |
| **GetAssebliesOfFunctions** `static` | string[] | Returns array of asseblies which contains functions. |
| **GetCategories** `static` | List<string> |  |
| **GetFunctions** `static` *(+2 overloads)* | List<StiFunction> |  |
| **GetFunctionsGrouppedInCategories** `static` | Hashtable |  |
| **GetFunctionsList** `static` | List<StiFunction> |  |
| **RemoveFunction** `static` | void | Removes all functions from report dictionary with specified name. |

---

### Method Details

#### AddFunction `static`

**AddFunction**(**category**: string, **functionName**: string, **typeOfFunction**: Type, **returnType**: Type): StiFunction

Adds new function with specified parameters.

**Parameters**

- **category** (string) — Category of function.  
- **functionName** (string) — Name of function.  
- **typeOfFunction** (Type) — Type which contain method of function.  
- **returnType** (Type) — Return type of function.  

**Returns** StiFunction


---

#### GetAssebliesOfFunctions `static`

**GetAssebliesOfFunctions**(): string[]

Returns array of asseblies which contains functions.

**Returns** string[]


---

#### GetCategories `static`

**GetCategories**(): List<string>

**Returns** List<string>


---

#### GetFunctions `static`

**GetFunctions**(**category**: string): List<StiFunction>

**Parameters**

- **category** (string)  

**Returns** List<StiFunction>

---

**GetFunctions**(**isCompile**: bool): StiFunction[]

Returns array of all functions.

**Parameters**

- **isCompile** (bool)  

**Returns** StiFunction[]

---

**GetFunctions**(**report**: [StiReport](../root/StiReport.md), **functionName**: string, **isCompile**: bool): StiFunction[]

Returns array of functions with spefified name.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **functionName** (string)  
- **isCompile** (bool)  

**Returns** StiFunction[]


---

#### GetFunctionsGrouppedInCategories `static`

**GetFunctionsGrouppedInCategories**(): Hashtable

**Returns** Hashtable


---

#### GetFunctionsList `static`

**GetFunctionsList**(**functionName**: string): List<StiFunction>

**Parameters**

- **functionName** (string)  

**Returns** List<StiFunction>


---

#### RemoveFunction `static`

**RemoveFunction**(**functionName**: string): void

Removes all functions from report dictionary with specified name.

**Parameters**

- **functionName** (string)  

