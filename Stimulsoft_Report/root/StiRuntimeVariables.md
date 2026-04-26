---
title: "StiRuntimeVariables Class"
---

## StiRuntimeVariables Class

**Namespace:** `Stimulsoft.Report`

Describes the class which allows to save and restore variables of a report.

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRuntimeVariables**([StiReport](StiReport.md) report) | Creates a new instance of the StiRuntimeVariables class. |

**StiRuntimeVariables**(**report**: [StiReport](StiReport.md))

Creates a new instance of the StiRuntimeVariables class.

**Parameters**

- **report** ([StiReport](StiReport.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Column** | int |  |
| **DataSourcesPosition** | Hashtable |  |
| **Line** | int |  |
| **LineThrough** | int |  |
| **Page** | StiPage |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **SetVariables** | void | Sets runtime-variables to the specified report. |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### SetVariables

**SetVariables**(**report**: [StiReport](StiReport.md)): void

Sets runtime-variables to the specified report.

**Parameters**

- **report** ([StiReport](StiReport.md))  

