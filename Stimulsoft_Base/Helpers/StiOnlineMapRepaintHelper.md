---
title: "StiOnlineMapRepaintHelper Class"
---

## StiOnlineMapRepaintHelper Class

**Namespace:** `Stimulsoft.Base.Helpers`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiOnlineMapRepaintHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Browser** | WebBrowser |  |
| **Comp** | [IStiAppComponent](../IStiAppComponent.md) |  |
| **ElementKey** | string |  |
| **G** | [Graphics](../../Stimulsoft_Drawing/Graphics.md) |  |
| **IsReady** | bool |  |
| **Key** | int |  |
| **Location** | [RectangleD](../Drawing/RectangleD.md) |  |
| **OrigialSize** | Size |  |
| **Script** | string |  |
| **Script** | String |  |
| **Size** | Size |  |
| **Tick** | long |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` | WebBrowser |  |
| **Clean** `static` | void |  |
| **CopyStream** `static` | byte[] |  |
| **Dispose** `static` | void |  |
| **ExportImage** `static` | void |  |
| **FetchAllComponents** `static` | List<[IStiAppComponent](../IStiAppComponent.md)> |  |
| **Get** `static` | WebBrowser |  |
| **GetDataAsStringAsync** `static` | Task<string> |  |
| **GetPushpins** `static` | List<string> |  |
| **GetTile** `static` | string |  |
| **GetTileBytes** `static` | byte[] |  |
| **Init** `static` | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Tick** | EventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **BrowserLifetime** | int |  |
| **TimerInterval** | int |  |
