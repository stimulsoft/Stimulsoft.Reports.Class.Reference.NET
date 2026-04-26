---
title: "StiStylesCreator Class"
---

## StiStylesCreator Class

**Namespace:** `Stimulsoft.Report`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiStylesCreator**([StiReport](StiReport.md) report) |  |
| **StiStylesCreator**(List<StiBaseStyle> hashAllStyles) |  |

**StiStylesCreator**(**report**: [StiReport](StiReport.md))

**Parameters**

- **report** ([StiReport](StiReport.md))  

---

**StiStylesCreator**(**hashAllStyles**: List<StiBaseStyle>)

**Parameters**

- **hashAllStyles** (List<StiBaseStyle>)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **MaxNestedLevel** | int | Gets or sets maximal nested level for created styles. |
| **NestedFactor** | [StiNestedFactor](StiNestedFactor.md) | Gets or sets nested level factor for created styles. |
| **ShowBorders** | bool | Gets or sets a value which indicates that styles creator will create a style showing borders. |
| **ShowDatas** | bool | Gets or sets a value which indicates that styles creator will create a style for DataBands. |
| **ShowFooters** | bool | Gets or sets a value which indicates that styles creator will create a style for FooterBands. |
| **ShowGroupFooters** | bool | Gets or sets a value which indicates that styles creator will create a style for GroupFooterBands. |
| **ShowGroupHeaders** | bool | Gets or sets a value which indicates that styles creator will create a style for GroupHeaderBands. |
| **ShowHeaders** | bool | Gets or sets a value which indicates that styles creator will create a style for HeaderBands. |
| **ShowPageFooters** | bool | Gets or sets a value which indicates that styles creator will create a style for PageFooterBands. |
| **ShowPageHeaders** | bool | Gets or sets a value which indicates that styles creator will create a style for PageHeaderBands. |
| **ShowReportSummaries** | bool | Gets or sets a value which indicates that styles creator will create a style for ReportSummaryBands. |
| **ShowReportTitles** | bool | Gets or sets a value which indicates that styles creator will create a style for ReportTitleBands. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateStyles** | List<StiBaseStyle> |  |

---

### Method Details

#### CreateStyles

**CreateStyles**(**collectionName**: string, **baseColor**: Color): List<StiBaseStyle>

**Parameters**

- **collectionName** (string)  
- **baseColor** (Color)  

**Returns** List<StiBaseStyle>

