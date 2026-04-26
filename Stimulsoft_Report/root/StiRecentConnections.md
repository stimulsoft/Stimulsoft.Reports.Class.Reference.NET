---
title: "StiRecentConnections Class"
---

## StiRecentConnections Class

**Namespace:** `Stimulsoft.Report`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRecentConnections**() |  |

**StiRecentConnections**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **RecentConnections** `static` | [StiRecentConnections](StiRecentConnections.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddAndSave** | void |  |
| **GetDatabase** | StiDatabase |  |
| **GetRecentConnections** | List<Item> |  |
| **Remove** | void |  |
| **Save** | void |  |
| **SetPin** | void |  |

---

### Method Details

#### AddAndSave

**AddAndSave**(**dataBase**: StiDatabase): void

**Parameters**

- **dataBase** (StiDatabase)  


---

#### GetDatabase

**GetDatabase**(**recentConnection**: Connection): StiDatabase

**Parameters**

- **recentConnection** (Connection)  

**Returns** StiDatabase


---

#### GetRecentConnections

**GetRecentConnections**(): List<Item>

**Returns** List<Item>


---

#### Remove

**Remove**(**recentConn**: Connection): void

**Parameters**

- **recentConn** (Connection)  


---

#### Save

**Save**(): void


---

#### SetPin

**SetPin**(**ID**: int, **pinValue**: bool): void

**Parameters**

- **ID** (int)  
- **pinValue** (bool)  

