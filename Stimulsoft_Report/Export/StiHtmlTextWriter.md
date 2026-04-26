---
title: "StiHtmlTextWriter Class"
---

## StiHtmlTextWriter Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHtmlTextWriter**(TextWriter baseStream) |  |

**StiHtmlTextWriter**(**baseStream**: TextWriter)

**Parameters**

- **baseStream** (TextWriter)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Flush** | void |  |
| **Write** | void |  |
| **WriteAttribute** | void |  |
| **WriteBeginTag** | void |  |
| **WriteEndTag** | void |  |
| **WriteFullBeginTag** | void |  |
| **WriteFullEndTag** | void |  |
| **WriteLine** *(+1 overloads)* | void |  |
| **WriteStyleAttribute** | void |  |

---

### Method Details

#### Flush

**Flush**(): void


---

#### Write

**Write**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### WriteAttribute

**WriteAttribute**(**attr**: string, **value**: string): void

**Parameters**

- **attr** (string)  
- **value** (string)  


---

#### WriteBeginTag

**WriteBeginTag**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### WriteEndTag

**WriteEndTag**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### WriteFullBeginTag

**WriteFullBeginTag**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### WriteFullEndTag

**WriteFullEndTag**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### WriteLine

**WriteLine**(): void

---

**WriteLine**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### WriteStyleAttribute

**WriteStyleAttribute**(**attr**: string, **value**: string): void

**Parameters**

- **attr** (string)  
- **value** (string)  

