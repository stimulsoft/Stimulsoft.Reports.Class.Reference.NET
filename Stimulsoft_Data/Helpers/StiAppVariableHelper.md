---
title: "StiAppVariableHelper Class"
---

## StiAppVariableHelper Class

**Namespace:** `Stimulsoft.Data.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearVariableLabels** `static` | void |  |
| **GetVariableLabel** `static` | string |  |
| **MakeTheSameCache** `static` *(+1 overloads)* | void | Makes the same cache for the app2 as for app1. |
| **SetVariableLabel** `static` | void |  |

---

### Method Details

#### ClearVariableLabels `static`

**ClearVariableLabels**(**app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md)): void

**Parameters**

- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  


---

#### GetVariableLabel `static`

**GetVariableLabel**(**app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md), **variableName**: string): string

**Parameters**

- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  
- **variableName** (string)  

**Returns** string


---

#### MakeTheSameCache `static`

**MakeTheSameCache**(**app1**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md), **app2**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md)): void

Makes the same cache for the app2 as for app1.

**Parameters**

- **app1** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  
- **app2** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  

---

**MakeTheSameCache**(**app1Key**: string, **app2Key**: string): void

**Parameters**

- **app1Key** (string)  
- **app2Key** (string)  


---

#### SetVariableLabel `static`

**SetVariableLabel**(**app**: [IStiApp](../../Stimulsoft_Base/root/IStiApp.md), **variable**: [IStiAppVariable](../../Stimulsoft_Base/root/IStiAppVariable.md), **label**: string): void

**Parameters**

- **app** ([IStiApp](../../Stimulsoft_Base/root/IStiApp.md))  
- **variable** ([IStiAppVariable](../../Stimulsoft_Base/root/IStiAppVariable.md))  
- **label** (string)  

