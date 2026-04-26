---
title: "StiUserData Class"
---

## StiUserData Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: Component  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Alias** | string |  |
| **Columns** | StiDataColumnsCollection |  |
| **Count** | int |  |
| **Name** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InvokeConnect** | void | Raises the Connect event for this component. |
| **InvokeDisconnent** | void | Raises the Disconnent event for this component. |
| **InvokeGetData** | void | Raises the GetData event for this component. |

---

### Method Details

#### InvokeConnect

**InvokeConnect**(**e**: EventArgs): void

Raises the Connect event for this component.

**Parameters**

- **e** (EventArgs) — An EventArgs that contains the event data.  


---

#### InvokeDisconnent

**InvokeDisconnent**(**e**: EventArgs): void

Raises the Disconnent event for this component.

**Parameters**

- **e** (EventArgs) — An EventArgs that contains the event data.  


---

#### InvokeGetData

**InvokeGetData**(**e**: [StiUserGetDataEventArgs](StiUserGetDataEventArgs.md)): void

Raises the GetData event for this component.

**Parameters**

- **e** ([StiUserGetDataEventArgs](StiUserGetDataEventArgs.md)) — An StiUserGetDataEventArgs that contains the event data.  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Connect** | EventHandler | Occurs when connect to data. |
| **Disconnent** | EventHandler | Occurs when disconnect from data. |
| **GetData** | StiUserGetDataEventHandler | Occurs when get data from source. |
