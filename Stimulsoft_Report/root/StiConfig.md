---
title: "StiConfig Class"
---

## StiConfig Class

**Namespace:** `Stimulsoft.Report`

Class which describes the configuration of the report engine.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Services** `static` | [StiServiceContainer](../../Stimulsoft_Base/Services/StiServiceContainer.md) | Gets or sets a collection of services. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultReportConfigPath** `static` | string |  |
| **GetDirectoryLocalization** `static` | string |  |
| **HideProperty** `static` *(+1 overloads)* | void |  |
| **InitWeb** `static` | void |  |
| **IsAllowedProperty** `static` | bool |  |
| **Load** `static` *(+3 overloads)* | void | Loads a configuration of the report engine if it exist. |
| **LoadDefaultLocalization** `static` | void |  |
| **LoadLocalization** `static` *(+1 overloads)* | void |  |
| **Reset** `static` | void |  |
| **Restore** `static` | void |  |
| **Save** `static` *(+3 overloads)* | void | Saves a configuration of the report engine. |
| **ShowProperty** `static` *(+1 overloads)* | void |  |
| **Synchronize** `static` | void |  |

---

### Method Details

#### GetDefaultReportConfigPath `static`

**GetDefaultReportConfigPath**(): string

**Returns** string


---

#### GetDirectoryLocalization `static`

**GetDirectoryLocalization**(): string

**Returns** string


---

#### HideProperty `static`

**HideProperty**(**type**: Type, **propertyName**: string): void

**Parameters**

- **type** (Type)  
- **propertyName** (string)  

---

**HideProperty**(**propertyName**: string): void

**Parameters**

- **propertyName** (string)  


---

#### InitWeb `static`

**InitWeb**(): void


---

#### IsAllowedProperty `static`

**IsAllowedProperty**(**type**: Type, **propertyName**: string): bool

**Parameters**

- **type** (Type)  
- **propertyName** (string)  

**Returns** bool


---

#### Load `static`

**Load**(): void

Loads a configuration of the report engine if it exist.

---

**Load**(**file**: string): void

Loads a configuration of the report engine.

**Parameters**

- **file** (string) — A file for loading a configuration of the report.  

---

**Load**(**stream**: Stream): void

Loads a configuration of the report engine.

**Parameters**

- **stream** (Stream) — A stream for loading configuration of the report engine.  

---

**Load**(**stream**: Stream, **services**: [StiServiceContainer](../../Stimulsoft_Base/Services/StiServiceContainer.md)): void

Loads a configuration of the report engine.

**Parameters**

- **stream** (Stream) — A stream for loading configuration of the report engine.  
- **services** ([StiServiceContainer](../../Stimulsoft_Base/Services/StiServiceContainer.md)) — A container which contains services of the report.  


---

#### LoadDefaultLocalization `static`

**LoadDefaultLocalization**(): void


---

#### LoadLocalization `static`

**LoadLocalization**(**file**: string): void

**Parameters**

- **file** (string)  

---

**LoadLocalization**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  


---

#### Reset `static`

**Reset**(): void


---

#### Restore `static`

**Restore**(): void


---

#### Save `static`

**Save**(): void

Saves a configuration of the report engine.

---

**Save**(**file**: string): void

Saves a configuration of the report engine.

**Parameters**

- **file** (string) — A file for saving a configuration of the report.  

---

**Save**(**stream**: Stream): void

Saves a configuration of the report engine.

**Parameters**

- **stream** (Stream) — A stream for saving configuration of the report engine.  

---

**Save**(**stream**: Stream, **services**: [StiServiceContainer](../../Stimulsoft_Base/Services/StiServiceContainer.md)): void

Saves a configuration of the report engine.

**Parameters**

- **stream** (Stream) — A stream for saving configuration of the report engine.  
- **services** ([StiServiceContainer](../../Stimulsoft_Base/Services/StiServiceContainer.md)) — A container which contains services of the report.  


---

#### ShowProperty `static`

**ShowProperty**(**type**: Type, **propertyName**: string): void

**Parameters**

- **type** (Type)  
- **propertyName** (string)  

---

**ShowProperty**(**propertyName**: string): void

**Parameters**

- **propertyName** (string)  


---

#### Synchronize `static`

**Synchronize**(): void

