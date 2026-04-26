---
title: "StiFunctionsProgramming Class"
---

## StiFunctionsProgramming Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Choose** `static` *(+1 overloads)* | object | Chooses and returns a value from a list of arguments based on the specified index. |
| **Eval** `static` | string | Evaluates the specified expression in the context of the given report. |
| **EvalDecimal** `static` | decimal | Evaluates the specified expression in the context of the given report and returns the result as a decimal. |
| **EvalDouble** `static` | double | Evaluates the specified expression in the context of the given report and returns the result as a double. |
| **EvalLong** `static` | long | Evaluates the specified expression in the context of the given report and returns the result as a long integer. |
| **Rand** `static` *(+1 overloads)* | object | Generates a random double-precision floating-point number between 0.0 and 1.0. |
| **RuntimeIdentifier** `static` | string | Returns a simplified runtime identifier built from the current runtime version. |
| **RuntimeName** `static` | string | Returns the runtime product name for the current environment. |
| **RuntimeOS** `static` | string | Returns operating system family information for the current environment. |
| **RuntimeType** `static` | string | Returns the runtime type name for the current environment. |
| **RuntimeVersion** `static` | string | Returns the runtime version for the current environment. |
| **Switch** `static` | object | Evaluates a series of conditions and returns a corresponding value for the first condition that is true. |

---

### Method Details

#### Choose `static`

**Choose**(**index**: long, ****: objectargs): object

Chooses and returns a value from a list of arguments based on the specified index.

**Parameters**

- **index** (long) — The 1-based index of the value to return.  
- **** (objectargs)  

**Returns** object — The value at the specified index, or null if the index is out of range or the list is empty.

---

**Choose**(**index**: long?, ****: objectargs): object

Chooses and returns a value from a list of arguments based on the specified nullable index.

**Parameters**

- **index** (long?) — The nullable 1-based index of the value to return.  
- **** (objectargs)  

**Returns** object — The value at the specified index, or null if the index is out of range, the list is empty, or the index is null.


---

#### Eval `static`

**Eval**(**report**: object, **expression**: string): string

Evaluates the specified expression in the context of the given report.

**Parameters**

- **report** (object) — The report object in which context the expression will be evaluated.  
- **expression** (string) — The expression to be evaluated.  

**Returns** string — The result of the evaluated expression as a string.


---

#### EvalDecimal `static`

**EvalDecimal**(**report**: object, **expression**: string): decimal

Evaluates the specified expression in the context of the given report and returns the result as a decimal.

**Parameters**

- **report** (object) — The report object in which context the expression will be evaluated.  
- **expression** (string) — The expression to be evaluated.  

**Returns** decimal — The result of the evaluated expression as a decimal.


---

#### EvalDouble `static`

**EvalDouble**(**report**: object, **expression**: string): double

Evaluates the specified expression in the context of the given report and returns the result as a double.

**Parameters**

- **report** (object) — The report object in which context the expression will be evaluated.  
- **expression** (string) — The expression to be evaluated.  

**Returns** double — The result of the evaluated expression as a double.


---

#### EvalLong `static`

**EvalLong**(**report**: object, **expression**: string): long

Evaluates the specified expression in the context of the given report and returns the result as a long integer.

**Parameters**

- **report** (object) — The report object in which context the expression will be evaluated.  
- **expression** (string) — The expression to be evaluated.  

**Returns** long — The result of the evaluated expression as a long integer.


---

#### Rand `static`

**Rand**(): object

Generates a random double-precision floating-point number between 0.0 and 1.0.

**Returns** object — A double-precision floating-point number greater than or equal to 0.0 and less than 1.0.

---

**Rand**(**seed**: int): object

Generates a random double-precision floating-point number between 0.0 and 1.0 using a specified seed.

**Parameters**

- **seed** (int) — The seed value for the random number generator.  

**Returns** object — A double-precision floating-point number greater than or equal to 0.0 and less than 1.0.


---

#### RuntimeIdentifier `static`

**RuntimeIdentifier**(): string

Returns a simplified runtime identifier built from the current runtime version.

**Returns** string — The runtime identifier string.


---

#### RuntimeName `static`

**RuntimeName**(): string

Returns the runtime product name for the current environment.

**Returns** string — The runtime product name.


---

#### RuntimeOS `static`

**RuntimeOS**(): string

Returns operating system family information for the current environment.

**Returns** string — The operating system family name.


---

#### RuntimeType `static`

**RuntimeType**(): string

Returns the runtime type name for the current environment.

**Returns** string — The runtime type name.


---

#### RuntimeVersion `static`

**RuntimeVersion**(): string

Returns the runtime version for the current environment.

**Returns** string — The runtime version.


---

#### Switch `static`

**Switch**(****: objectargs): object

Evaluates a series of conditions and returns a corresponding value for the first condition that is true.

**Parameters**

- **** (objectargs)  

**Returns** object — The value corresponding to the first condition that evaluates to true, or null if no conditions are true.

