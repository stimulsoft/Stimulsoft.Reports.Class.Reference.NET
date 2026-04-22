---
title: "StiDataBandV2Builder Class"
---

## StiDataBandV2Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDataBandV2Builder
```

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
