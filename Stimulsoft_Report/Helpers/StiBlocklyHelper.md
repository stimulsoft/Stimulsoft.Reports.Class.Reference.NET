---
title: "StiBlocklyHelper Class"
---

## StiBlocklyHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InvokeBlockly** `static` | void |  |
| **InvokeUserFunctionBlockly** `static` | object |  |
| **InvokeUserFunctionBlocklyInCompilationMode** `static` | object |  |

---

### Method Details

#### InvokeBlockly `static`

**InvokeBlockly**(**report**: [StiReport](../root/StiReport.md), **sender**: object, **stiEvent**: StiEvent, **e**: EventArgs): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **sender** (object)  
- **stiEvent** (StiEvent)  
- **e** (EventArgs)  


---

#### InvokeUserFunctionBlockly `static`

**InvokeUserFunctionBlockly**(**report**: [StiReport](../root/StiReport.md), **function**: [StiUserFunction](../Dictionary/StiUserFunction.md), **arguments**: IDictionary<string, object>): object

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **function** ([StiUserFunction](../Dictionary/StiUserFunction.md))  
- **arguments** (IDictionary<string, object>)  

**Returns** object


---

#### InvokeUserFunctionBlocklyInCompilationMode `static`

**InvokeUserFunctionBlocklyInCompilationMode**(**report**: [StiReport](../root/StiReport.md), **script**: string, **arguments**: IDictionary<string, object>): object

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **script** (string)  
- **arguments** (IDictionary<string, object>)  

**Returns** object

