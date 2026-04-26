---
title: "StiDashboardExportTools Class"
---

## StiDashboardExportTools Class

**Namespace:** `Stimulsoft.Dashboard.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ExportToBytes** `static` *(+3 overloads)* | byte[] |  |
| **ExportToFile** `static` *(+3 overloads)* | bool |  |
| **ExportToStream** `static` *(+3 overloads)* | Stream |  |
| **RenderElement** `static` | StiComponent |  |

---

### Method Details

#### ExportToBytes `static`

**ExportToBytes**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **settings**: StiDashboardExportSettings): byte[]

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **settings** (StiDashboardExportSettings)  

**Returns** byte[]

---

**ExportToBytes**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **settings**: StiDashboardExportSettings, **showProgress**: bool): byte[]

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **settings** (StiDashboardExportSettings)  
- **showProgress** (bool)  

**Returns** byte[]

---

**ExportToBytes**(**element**: IStiElement, **settings**: StiDashboardExportSettings): byte[]

**Parameters**

- **element** (IStiElement)  
- **settings** (StiDashboardExportSettings)  

**Returns** byte[]

---

**ExportToBytes**(**element**: IStiElement, **settings**: StiDashboardExportSettings, **showProgress**: bool): byte[]

**Parameters**

- **element** (IStiElement)  
- **settings** (StiDashboardExportSettings)  
- **showProgress** (bool)  

**Returns** byte[]


---

#### ExportToFile `static`

**ExportToFile**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **path**: string, **settings**: StiDashboardExportSettings): bool

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **path** (string)  
- **settings** (StiDashboardExportSettings)  

**Returns** bool

---

**ExportToFile**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **path**: string, **settings**: StiDashboardExportSettings, **showProgress**: bool): bool

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **path** (string)  
- **settings** (StiDashboardExportSettings)  
- **showProgress** (bool)  

**Returns** bool

---

**ExportToFile**(**element**: IStiElement, **path**: string, **settings**: StiDashboardExportSettings): bool

**Parameters**

- **element** (IStiElement)  
- **path** (string)  
- **settings** (StiDashboardExportSettings)  

**Returns** bool

---

**ExportToFile**(**element**: IStiElement, **path**: string, **settings**: StiDashboardExportSettings, **showProgress**: bool): bool

**Parameters**

- **element** (IStiElement)  
- **path** (string)  
- **settings** (StiDashboardExportSettings)  
- **showProgress** (bool)  

**Returns** bool


---

#### ExportToStream `static`

**ExportToStream**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **settings**: StiDashboardExportSettings): Stream

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **settings** (StiDashboardExportSettings)  

**Returns** Stream

---

**ExportToStream**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **settings**: StiDashboardExportSettings, **showProgress**: bool): Stream

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **settings** (StiDashboardExportSettings)  
- **showProgress** (bool)  

**Returns** Stream

---

**ExportToStream**(**element**: IStiElement, **settings**: StiDashboardExportSettings): Stream

**Parameters**

- **element** (IStiElement)  
- **settings** (StiDashboardExportSettings)  

**Returns** Stream

---

**ExportToStream**(**element**: IStiElement, **settings**: StiDashboardExportSettings, **showProgress**: bool): Stream

**Parameters**

- **element** (IStiElement)  
- **settings** (StiDashboardExportSettings)  
- **showProgress** (bool)  

**Returns** Stream


---

#### RenderElement `static`

**RenderElement**(**parent**: StiContainer, **element**: IStiElement, **scaleX**: double, **scaleY**: double, **settings**: StiDashboardExportSettings): StiComponent

**Parameters**

- **parent** (StiContainer)  
- **element** (IStiElement)  
- **scaleX** (double)  
- **scaleY** (double)  
- **settings** (StiDashboardExportSettings)  

**Returns** StiComponent

