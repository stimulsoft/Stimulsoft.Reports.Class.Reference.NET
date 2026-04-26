---
title: "StiLastFunctionService Class"
---

## StiLastFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the class for work with Last aggregate function. To calculate the type Object is used.

### Inheritance

Inherits from: StiAggregateFunctionService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLastFunctionService**() |  |
| **StiLastFunctionService**(bool runningTotal) |  |

**StiLastFunctionService**()

---

**StiLastFunctionService**(**runningTotal**: bool)

**Parameters**

- **runningTotal** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalcItem** | void | A value calculation. |
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

