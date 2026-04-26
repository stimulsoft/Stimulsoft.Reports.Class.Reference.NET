---
title: "StiFindHelper Class"
---

## StiFindHelper Class

**Namespace:** `Stimulsoft.Report.Viewer`

This class helps in search components in report

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

---

### Method Details

#### ClearFind

**ClearFind**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

---

**ClearFind**(**pages**: [StiPagesCollection](../Components/StiPagesCollection.md)): void

**Parameters**

- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  


---

#### CloseFind

**CloseFind**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### InvokeProgressChanged

**InvokeProgressChanged**(**value**: int, **maximum**: int): void

**Parameters**

- **value** (int)  
- **maximum** (int)  


---

#### ResetFind

**ResetFind**(): void


---

#### StartFind

**StartFind**(**value**: string, **report**: [StiReport](../root/StiReport.md), **matchCase**: bool, **matchWholeWord**: bool): void

**Parameters**

- **value** (string)  
- **report** ([StiReport](../root/StiReport.md))  
- **matchCase** (bool)  
- **matchWholeWord** (bool)  

---

**StartFind**(**value**: string, **pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **matchCase**: bool, **matchWholeWord**: bool): void

**Parameters**

- **value** (string)  
- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **matchCase** (bool)  
- **matchWholeWord** (bool)  


---

#### StartFindPrevious

**StartFindPrevious**(**value**: string, **report**: [StiReport](../root/StiReport.md), **matchCase**: bool, **matchWholeWord**: bool): void

**Parameters**

- **value** (string)  
- **report** ([StiReport](../root/StiReport.md))  
- **matchCase** (bool)  
- **matchWholeWord** (bool)  

---

**StartFindPrevious**(**value**: string, **pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **matchCase**: bool, **matchWholeWord**: bool): void

**Parameters**

- **value** (string)  
- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **matchCase** (bool)  
- **matchWholeWord** (bool)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **ProgressChanged** | StiProgressChangedEventHandler |  |
