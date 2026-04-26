---
title: "StiOnlineMapRepaintHelper Class"
---

## StiOnlineMapRepaintHelper Class

**Namespace:** `Stimulsoft.Base.Helpers`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Browser** | WebBrowser |  |
| **Comp** | [IStiAppComponent](../root/IStiAppComponent.md) |  |
| **ElementKey** | string |  |
| **G** | [Graphics](../../Stimulsoft_Drawing/root/Graphics.md) |  |
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
| **FetchAllComponents** `static` | List<[IStiAppComponent](../root/IStiAppComponent.md)> |  |
| **Get** `static` | WebBrowser |  |
| **GetDataAsStringAsync** `static` | Task<string> |  |
| **GetPushpins** `static` | List<string> |  |
| **GetTile** `static` | string |  |
| **GetTileBytes** `static` | byte[] |  |
| **Init** `static` | void |  |

---

### Method Details

#### Add `static`

**Add**(**comp**: [IStiAppComponent](../root/IStiAppComponent.md), **key**: int, **script**: String, **size**: Size, **elementKey**: string): WebBrowser

**Parameters**

- **comp** ([IStiAppComponent](../root/IStiAppComponent.md))  
- **key** (int)  
- **script** (String)  
- **size** (Size)  
- **elementKey** (string)  

**Returns** WebBrowser


---

#### Clean `static`

**Clean**(**reportKey**: string): void

**Parameters**

- **reportKey** (string)  


---

#### CopyStream `static`

**CopyStream**(**inputStream**: Stream): byte[]

**Parameters**

- **inputStream** (Stream)  

**Returns** byte[]


---

#### Dispose `static`

**Dispose**(): void


---

#### ExportImage `static`

**ExportImage**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **script**: String, **size**: Size, **origialSize**: Size, **location**: [RectangleD](../Drawing/RectangleD.md)): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **script** (String)  
- **size** (Size)  
- **origialSize** (Size)  
- **location** ([RectangleD](../Drawing/RectangleD.md))  


---

#### FetchAllComponents `static`

**FetchAllComponents**(): List<[IStiAppComponent](../root/IStiAppComponent.md)>

**Returns** List<[IStiAppComponent](../root/IStiAppComponent.md)>


---

#### Get `static`

**Get**(**comp**: [IStiAppComponent](../root/IStiAppComponent.md), **key**: int, **ignoreKey**: bool): WebBrowser

**Parameters**

- **comp** ([IStiAppComponent](../root/IStiAppComponent.md))  
- **key** (int)  
- **ignoreKey** (bool)  

**Returns** WebBrowser


---

#### GetDataAsStringAsync `static`

**GetDataAsStringAsync**(**url**: string, **data**: string): Task<string>

**Parameters**

- **url** (string)  
- **data** (string)  

**Returns** Task<string>


---

#### GetPushpins `static`

**GetPushpins**(**mapData**: Hashtable): List<string>

**Parameters**

- **mapData** (Hashtable)  

**Returns** List<string>


---

#### GetTile `static`

**GetTile**(**url**: String): string

**Parameters**

- **url** (String)  

**Returns** string


---

#### GetTileBytes `static`

**GetTileBytes**(**url**: String): byte[]

**Parameters**

- **url** (String)  

**Returns** byte[]


---

#### Init `static`

**Init**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Tick** | EventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **BrowserLifetime** | int |  |
| **TimerInterval** | int |  |
