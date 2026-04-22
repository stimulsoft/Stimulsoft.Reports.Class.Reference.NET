---
title: "StiFindHelper Class"
---

## StiFindHelper Class

**Namespace:** `Stimulsoft.Report.Viewer`  
**Assembly:** `Stimulsoft.Report`

This class helps in search components in report

```csharp
public class StiFindHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowLoop** | bool |  |
| **AlwaysFindAgain** | bool |  |
| **CurrentComponent** | int |  |
| **FindActivated** | bool |  |
| **FindedComponents** | List<StiComponent> |  |
| **HashOfFindedPages** | Hashtable |  |
| **IsBof** | bool |  |
| **IsEof** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearFind** *(+1 overloads)* | void |  |
| **CloseFind** | void |  |
| **InvokeProgressChanged** | void |  |
| **ResetFind** | void |  |
| **StartFind** *(+1 overloads)* | void |  |
| **StartFindPrevious** *(+1 overloads)* | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **ProgressChanged** | StiProgressChangedEventHandler |  |
