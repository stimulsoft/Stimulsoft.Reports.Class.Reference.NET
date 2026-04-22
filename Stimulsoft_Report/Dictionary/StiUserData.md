---
title: "StiUserData Class"
---

## StiUserData Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiUserData
```

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

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Connect** | EventHandler | Occurs when connect to data. |
| **Disconnent** | EventHandler | Occurs when disconnect from data. |
| **GetData** | StiUserGetDataEventHandler | Occurs when get data from source. |
