---
title: "StiSumDistinctDecimalFunctionService Class"
---

## StiSumDistinctDecimalFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the class for work with SumDistinct aggregate function. To calculate the type Decimal is used.

### Inheritance

Inherits from: [StiTwoArgumentAggregateFunctionService](StiTwoArgumentAggregateFunctionService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSumDistinctDecimalFunctionService**() |  |
| **StiSumDistinctDecimalFunctionService**(bool runningTotal) |  |

**StiSumDistinctDecimalFunctionService**()

---

**StiSumDistinctDecimalFunctionService**(**runningTotal**: bool)

**Parameters**

- **runningTotal** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalcItem** *(+1 overloads)* | void | A value calculation. |
| **GetResultType** | Type | Returns the type of the result. |
| **GetValue** | object | Returns the calculation result. |
| **Init** | void | First initialization. |
| **RestoreState** | void | Restores the earlier saved object state. |
| **SaveState** | void | Saves the current state of an object. |
| **SetValue** | void | Sets the calculation result. |

---

### Method Details

#### CalcItem

**CalcItem**(**value**: object): void

A value calculation.

**Parameters**

- **value** (object) — Value.  

---

**CalcItem**(**value**: object, **valueToSum**: object): void

**Parameters**

- **value** (object)  
- **valueToSum** (object)  


---

#### GetResultType

**GetResultType**(): Type

Returns the type of the result.

**Returns** Type


---

#### GetValue

**GetValue**(): object

Returns the calculation result.

**Returns** object — Calculation result.


---

#### Init

**Init**(): void

First initialization.


---

#### RestoreState

**RestoreState**(**stateName**: string): void

Restores the earlier saved object state.

**Parameters**

- **stateName** (string) — A name of the state being restored.  


---

#### SaveState

**SaveState**(**stateName**: string): void

Saves the current state of an object.

**Parameters**

- **stateName** (string) — A name of the state being saved.  


---

#### SetValue

**SetValue**(**value**: object): void

Sets the calculation result.

**Parameters**

- **value** (object)  

