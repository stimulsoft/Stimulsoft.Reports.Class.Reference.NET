---
title: "StiDataBandV2Builder Class"
---

## StiDataBandV2Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiBandV2Builder](StiBandV2Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddFooterMarker** | void | Adds the Footer Marker to the end of a list, if before the list FooterBands were output on all pages. |
| **AddKeepDetails** | void |  |
| **AddKeepLevel** | void |  |
| **AddKeepLevelAtLatestDataBand** | void |  |
| **AllowDetailDataBands** | bool |  |
| **AllowKeepDetails** | bool |  |
| **Block** | void |  |
| **CheckHierarchicalFooters** | void |  |
| **CheckHierarchicalHeaders** | void |  |
| **CheckKeepFooterTogether** | bool |  |
| **CheckKeepReportSummaryTogether** | bool |  |
| **EndBands** | void | Ends monitoring of band OnAllPages. |
| **FindDetailDataBands** | void |  |
| **FindDetails** | void |  |
| **FindEmptyBands** | void |  |
| **FindFooters** | void |  |
| **FindGroupFooters** | void |  |
| **FindGroupHeaders** | void |  |
| **FindHeaders** | void |  |
| **FindHierarchicalFooters** | void |  |
| **FindHierarchicalHeaders** | void |  |
| **FindSubReports** | void |  |
| **GetGroupFooterResult** | bool |  |
| **GetGroupHeaderResult** | bool |  |
| **IsCollapsed** `static` | bool |  |
| **IsDenyDetailsOnFirstPage** | bool |  |
| **IsDetailDataSourcesEmpty** `static` | bool | Gets value indicates that all detail components are empty. |
| **IsPrintIfDetailEmpty** `static` | bool |  |
| **LinkGroupHeadersAndGroupFooters** | void |  |
| **Prepare** | void |  |
| **PrepareGroupResults** `static` | void | Prepares a groups result for each group for the current line. |
| **RegisterEmptyBands** | void |  |
| **RemoveKeepDetails** | void |  |
| **RemoveKeepDetailsRow** | void |  |
| **RemoveKeepGroupHeaders** | void |  |
| **RemoveKeepHeaders** | void |  |
| **RemoveKeepLevel** | void |  |
| **Render** | StiComponent |  |
| **RenderBand** *(+1 overloads)* | void |  |
| **RenderColumns** | void |  |
| **RenderDetailDataBands** | void |  |
| **RenderFootersOnAllPages** | void |  |
| **RenderFootersOnLastPage** | void |  |
| **RenderGroupFooters** | void | Renders all group footers of this databand. |
| **RenderGroupHeaders** | void | Renders all group headers of this databand. |
| **RenderHeaders** | void |  |
| **RenderHierarchicalFooters** | void |  |
| **RenderHierarchicalHeaders** | void |  |
| **RenderMarkerFootersOnAllPages** | void |  |
| **RenderMaster** | void |  |
| **RenderReportSummaries** | void |  |
| **RenderReportTitles** | void |  |
| **ResetDetailDataBands** | void |  |
| **ResetDetails** | void |  |
| **ResetEmptyBands** | void |  |
| **ResetFooters** | void |  |
| **ResetGroupFooters** | void |  |
| **ResetGroupHeaders** | void |  |
| **ResetHeaders** | void |  |
| **ResetHierarchicalFooters** | void |  |
| **ResetHierarchicalHeaders** | void |  |
| **ResetLinkGroupHeadersAndGroupFooters** | void |  |
| **SetDetails** `static` | void | Sets detail. |
| **SetReportVariables** | void | Sets system variables which are specific for the specified component. |
| **StartBand** | void | Starts monitoring of specified band OnAllPages. |
| **StartBands** | void | Starts monitoring of specified collection of bands OnAllPages. |
| **UnBlock** | void |  |
| **UnPrepare** | void | Clears a component after rendering. |

---

### Method Details

#### AddFooterMarker

**AddFooterMarker**(**masterDataBand**: StiDataBand, **footerMaster**: StiFooterBand): void

Adds the Footer Marker to the end of a list, if before the list FooterBands were output on all pages.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **footerMaster** (StiFooterBand)  


---

#### AddKeepDetails

**AddKeepDetails**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### AddKeepLevel

**AddKeepLevel**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### AddKeepLevelAtLatestDataBand

**AddKeepLevelAtLatestDataBand**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### AllowDetailDataBands

**AllowDetailDataBands**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### AllowKeepDetails

**AllowKeepDetails**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### Block

**Block**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### CheckHierarchicalFooters

**CheckHierarchicalFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### CheckHierarchicalHeaders

**CheckHierarchicalHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### CheckKeepFooterTogether

**CheckKeepFooterTogether**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### CheckKeepReportSummaryTogether

**CheckKeepReportSummaryTogether**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### EndBands

**EndBands**(**masterDataBand**: StiDataBand): void

Ends monitoring of band OnAllPages.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindDetailDataBands

**FindDetailDataBands**(**masterDataBand**: StiDataBand, **loops**: List<StiDataBand>): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **loops** (List<StiDataBand>)  


---

#### FindDetails

**FindDetails**(**masterDataBand**: StiDataBand, **loops**: List<StiDataBand>): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **loops** (List<StiDataBand>)  


---

#### FindEmptyBands

**FindEmptyBands**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindFooters

**FindFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindGroupFooters

**FindGroupFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindGroupHeaders

**FindGroupHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindHeaders

**FindHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindHierarchicalFooters

**FindHierarchicalFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindHierarchicalHeaders

**FindHierarchicalHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FindSubReports

**FindSubReports**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### GetGroupFooterResult

**GetGroupFooterResult**(**masterDataBand**: StiDataBand, **groupHeaderBand**: StiGroupHeaderBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  
- **groupHeaderBand** (StiGroupHeaderBand)  

**Returns** bool


---

#### GetGroupHeaderResult

**GetGroupHeaderResult**(**masterDataBand**: StiDataBand, **groupHeaderBand**: StiGroupHeaderBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  
- **groupHeaderBand** (StiGroupHeaderBand)  

**Returns** bool


---

#### IsCollapsed `static`

**IsCollapsed**(**masterDataBand**: StiContainer, **isRendering**: bool): bool

**Parameters**

- **masterDataBand** (StiContainer)  
- **isRendering** (bool)  

**Returns** bool


---

#### IsDenyDetailsOnFirstPage

**IsDenyDetailsOnFirstPage**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### IsDetailDataSourcesEmpty `static`

**IsDetailDataSourcesEmpty**(**masterDataBand**: StiDataBand): bool

Gets value indicates that all detail components are empty.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### IsPrintIfDetailEmpty `static`

**IsPrintIfDetailEmpty**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### LinkGroupHeadersAndGroupFooters

**LinkGroupHeadersAndGroupFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

**Parameters**

- **masterComp** (StiComponent)  


---

#### PrepareGroupResults `static`

**PrepareGroupResults**(**masterDataBand**: StiDataBand): void

Prepares a groups result for each group for the current line.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RegisterEmptyBands

**RegisterEmptyBands**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RemoveKeepDetails

**RemoveKeepDetails**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RemoveKeepDetailsRow

**RemoveKeepDetailsRow**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RemoveKeepGroupHeaders

**RemoveKeepGroupHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RemoveKeepHeaders

**RemoveKeepHeaders**(**masterDataBand**: StiDataBand, ****: boolkeepHeaders): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **** (boolkeepHeaders)  


---

#### RemoveKeepLevel

**RemoveKeepLevel**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### Render

**Render**(**masterComp**: StiComponent): StiComponent

**Parameters**

- **masterComp** (StiComponent)  

**Returns** StiComponent


---

#### RenderBand

**RenderBand**(**masterDataBand**: StiDataBand, **band**: StiBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **band** (StiBand)  

---

**RenderBand**(**masterDataBand**: StiDataBand, **band**: StiBand, **ignorePageBreaks**: bool, **allowRenderingEvents**: bool): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **band** (StiBand)  
- **ignorePageBreaks** (bool)  
- **allowRenderingEvents** (bool)  


---

#### RenderColumns

**RenderColumns**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderDetailDataBands

**RenderDetailDataBands**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderFootersOnAllPages

**RenderFootersOnAllPages**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderFootersOnLastPage

**RenderFootersOnLastPage**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderGroupFooters

**RenderGroupFooters**(**masterDataBand**: StiDataBand): void

Renders all group footers of this databand.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderGroupHeaders

**RenderGroupHeaders**(**masterDataBand**: StiDataBand): void

Renders all group headers of this databand.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderHeaders

**RenderHeaders**(**masterDataBand**: StiDataBand, ****: boolkeepHeaders): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **** (boolkeepHeaders)  


---

#### RenderHierarchicalFooters

**RenderHierarchicalFooters**(**masterDataBand**: StiDataBand, **allowIndent**: bool, **level**: int): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **allowIndent** (bool)  
- **level** (int)  


---

#### RenderHierarchicalHeaders

**RenderHierarchicalHeaders**(**masterDataBand**: StiDataBand, **allowIndent**: bool, **level**: int): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **allowIndent** (bool)  
- **level** (int)  


---

#### RenderMarkerFootersOnAllPages

**RenderMarkerFootersOnAllPages**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderMaster

**RenderMaster**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderReportSummaries

**RenderReportSummaries**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### RenderReportTitles

**RenderReportTitles**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetDetailDataBands

**ResetDetailDataBands**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetDetails

**ResetDetails**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetEmptyBands

**ResetEmptyBands**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetFooters

**ResetFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetGroupFooters

**ResetGroupFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetGroupHeaders

**ResetGroupHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetHeaders

**ResetHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetHierarchicalFooters

**ResetHierarchicalFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetHierarchicalHeaders

**ResetHierarchicalHeaders**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### ResetLinkGroupHeadersAndGroupFooters

**ResetLinkGroupHeadersAndGroupFooters**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### SetDetails `static`

**SetDetails**(**masterDataBand**: StiDataBand): void

Sets detail.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### SetReportVariables

**SetReportVariables**(**masterComp**: StiComponent): void

Sets system variables which are specific for the specified component.

**Parameters**

- **masterComp** (StiComponent)  


---

#### StartBand

**StartBand**(**masterDataBand**: StiDataBand, **band**: StiBand): void

Starts monitoring of specified band OnAllPages.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **band** (StiBand)  


---

#### StartBands

**StartBands**(**masterDataBand**: StiDataBand, **bands**: StiComponentsCollection): void

Starts monitoring of specified collection of bands OnAllPages.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **bands** (StiComponentsCollection)  


---

#### UnBlock

**UnBlock**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

Clears a component after rendering.

**Parameters**

- **masterComp** (StiComponent)  

