---
title: "StiDataStoreAdapterService Class"
---

## StiDataStoreAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the base adapter of data for access to data in the store.

### Inheritance

Inherits from: [StiDataAdapterService](StiDataAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** | StiDataSource | Creates a new Data Source and adds it to the dictionary. |
| **Edit** | bool | Calls the form for Data Source edition. |
| **New** | bool | Calls the form for a new Data Source edition. |
| **SetDataSourceNames** | void | Fills a name and alias of the Data Source relying on data. |

---

### Method Details

#### Create

**Create**(**dictionary**: StiDictionary, **addToDictionary**: bool): StiDataSource

Creates a new Data Source and adds it to the dictionary.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary to add Data Source.  
- **addToDictionary** (bool)  

**Returns** StiDataSource — Created Data Source.


---

#### Edit

**Edit**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): bool

Calls the form for Data Source edition.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which Data Source is located.  
- **dataSource** (StiDataSource) — Data Source.  

**Returns** bool — Result of gialog form.


---

#### New

**New**(**dictionary**: StiDictionary, **dataSource**: StiDataSource): bool

Calls the form for a new Data Source edition.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which Data Source is located.  
- **dataSource** (StiDataSource) — Data Source.  

**Returns** bool — Result of gialog form.


---

#### SetDataSourceNames

**SetDataSourceNames**(**data**: [StiData](StiData.md), **dataSource**: StiDataSource): void

Fills a name and alias of the Data Source relying on data.

**Parameters**

- **data** ([StiData](StiData.md)) — Data relying on which names will be filled.  
- **dataSource** (StiDataSource) — Data Source in which names will be filled.  

