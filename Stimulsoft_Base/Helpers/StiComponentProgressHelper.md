---
title: "StiComponentProgressHelper Class"
---

## StiComponentProgressHelper Class

**Namespace:** `Stimulsoft.Base.Helpers`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CurrentValue** `static` | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` | void |  |
| **Contains** `static` | [StiProgressStatus](StiProgressStatus.md) |  |
| **Dispose** `static` | void |  |
| **FetchAllComponents** `static` | List<[IStiAppComponent](../root/IStiAppComponent.md)> |  |
| **Init** `static` | void |  |
| **IsActiveProgress** `static` | bool |  |
| **IsHidenProgress** `static` | bool |  |
| **IsLongProgress** `static` | bool |  |
| **Remove** `static` | void |  |

---

### Method Details

#### Add `static`

**Add**(**comp**: [IStiAppComponent](../root/IStiAppComponent.md)): void

**Parameters**

- **comp** ([IStiAppComponent](../root/IStiAppComponent.md))  


---

#### Contains `static`

**Contains**(**comp**: [IStiAppComponent](../root/IStiAppComponent.md)): [StiProgressStatus](StiProgressStatus.md)

**Parameters**

- **comp** ([IStiAppComponent](../root/IStiAppComponent.md))  

**Returns** [StiProgressStatus](StiProgressStatus.md)


---

#### Dispose `static`

**Dispose**(): void


---

#### FetchAllComponents `static`

**FetchAllComponents**(): List<[IStiAppComponent](../root/IStiAppComponent.md)>

**Returns** List<[IStiAppComponent](../root/IStiAppComponent.md)>


---

#### Init `static`

**Init**(): void


---

#### IsActiveProgress `static`

**IsActiveProgress**(**status**: [StiProgressStatus](StiProgressStatus.md)): bool

**Parameters**

- **status** ([StiProgressStatus](StiProgressStatus.md))  

**Returns** bool


---

#### IsHidenProgress `static`

**IsHidenProgress**(**tick**: long): bool

**Parameters**

- **tick** (long)  

**Returns** bool


---

#### IsLongProgress `static`

**IsLongProgress**(**tick**: long): bool

**Parameters**

- **tick** (long)  

**Returns** bool


---

#### Remove `static`

**Remove**(**comp**: [IStiAppComponent](../root/IStiAppComponent.md), **lockCompledProgressr**: bool): void

**Parameters**

- **comp** ([IStiAppComponent](../root/IStiAppComponent.md))  
- **lockCompledProgressr** (bool)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **CompletedProgress** | EventHandler |  |
| **Tick** | EventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ProgressDelta** | float |  |
| **TimerInterval** | int |  |
