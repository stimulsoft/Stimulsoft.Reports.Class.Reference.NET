---
title: "StiDataRetrieval Class"
---

## StiDataRetrieval Class

**Namespace:** `Stimulsoft.Report.Dictionary`

The service allows to find all data sources, columns, relations, which are used in the report.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UsedColumns** | Hashtable | Gets columns to use. |
| **UsedDataSources** | Hashtable | Gets Data Sources used. |
| **UsedRelations** | Hashtable | Gets relations to use. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Build** | void | Processes a dictionary. |
| **Dispose** | void |  |
| **Retrieval** | void | Builds hashtables with elements being used. |

---

### Method Details

#### Build

**Build**(**elements**: Hashtable, **dictionary**: StiDictionary): void

Processes a dictionary.

**Parameters**

- **elements** (Hashtable) — Hashtable for filling.  
- **dictionary** (StiDictionary) — Dictionary.  


---

#### Dispose

**Dispose**(): void


---

#### Retrieval

**Retrieval**(**report**: [StiReport](../root/StiReport.md)): void

Builds hashtables with elements being used.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

