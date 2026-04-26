---
title: "StiDataLink Class"
---

## StiDataLink Class

**Namespace:** `Stimulsoft.Data.Engine`

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/root/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataLink**() |  |
| **StiDataLink**(string key) |  |
| **StiDataLink**(string parentTable, string childTable, stringparentColumns , stringchildColumns , bool active, [StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md) joinType) |  |
| **StiDataLink**(string parentTable, string childTable, stringparentColumns , stringchildColumns , bool active, [StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md) joinType, string key) |  |

**StiDataLink**()

---

**StiDataLink**(**key**: string)

**Parameters**

- **key** (string)  

---

**StiDataLink**(**parentTable**: string, **childTable**: string, ****: stringparentColumns, ****: stringchildColumns, **active**: bool, **joinType**: [StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md))

**Parameters**

- **parentTable** (string)  
- **childTable** (string)  
- **** (stringparentColumns)  
- **** (stringchildColumns)  
- **active** (bool)  
- **joinType** ([StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md))  

---

**StiDataLink**(**parentTable**: string, **childTable**: string, ****: stringparentColumns, ****: stringchildColumns, **active**: bool, **joinType**: [StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md), **key**: string)

**Parameters**

- **parentTable** (string)  
- **childTable** (string)  
- **** (stringparentColumns)  
- **** (stringchildColumns)  
- **active** (bool)  
- **joinType** ([StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md))  
- **key** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Active** | bool |  |
| **ChildColumns** | string[] |  |
| **ChildTable** | string |  |
| **JoinType** | [StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md) | Specifies the type of data join operation that merges two data sources into one. Used only in Dashboards data. |
| **Key** | string | Gets or sets the key to the data relation in the report dictionary. |
| **ParentColumns** | string[] |  |
| **ParentTable** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJson** `static` | [StiDataLink](StiDataLink.md) |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ToString** | string |  |

---

### Method Details

#### LoadFromJson `static`

**LoadFromJson**(**json**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): [StiDataLink](StiDataLink.md)

**Parameters**

- **json** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  

**Returns** [StiDataLink](StiDataLink.md)


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### ToString

**ToString**(): string

**Returns** string

