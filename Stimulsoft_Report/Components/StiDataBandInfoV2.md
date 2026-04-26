---
title: "StiDataBandInfoV2 Class"
---

## StiDataBandInfoV2 Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiComponentInfo](../Engine/StiComponentInfo.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DetailDataBands** | StiComponentsCollection | The collection contains all subordinate DataBand's of the current DataBand. To fill the collection it is necessary to call the FindDetailDataBands method. |
| **Details** | StiComponentsCollection | The collection contains all subordinate components of the current DataBand. To fill the collection it is necessary to call the FindDetails method. |
| **EmptyBands** | StiComponentsCollection | The collection contains all subordinate EmptyBand's of the current DataBand. To fill the collection it is necessary to call the FindEmptyBands method. |
| **FootersOnAllPages** | StiComponentsCollection | The collection contains all subordinate Footer's that are displayed on all pages, of the current DataBand.To populate the collection, call the FindFootersOnAllPages method. |
| **FootersOnLastPage** | StiComponentsCollection | The collection contains all subordinate Footer's that are displayed at the end of the list, of the current DataBand.To populate the collection, call the FindFootersOnLastPage method. |
| **GroupFooterCachedResults** | bool[][] |  |
| **GroupFooterResults** | bool[] | An array of grouping calculation results for GroupFooterBand's. |
| **GroupFooters** | StiComponentsCollection | The collection contains all subordinate GroupFooterBand's of the current DataBand. To populate the collection it is necessary to call the FindGroupFooters method. |
| **GroupHeaderCachedResults** | bool[][] |  |
| **GroupHeaderResults** | bool[] | An array of grouping calculation results for GroupHeaderBand's. |
| **GroupHeaders** | StiComponentsCollection | The collection contains all the subordinate GroupHeaderBand's of the current DataBand. To fill the collection it is necessary to call FindGroupHeaders method. |
| **Headers** | StiComponentsCollection | The collection contains all subordinate HeaderBand's of the current DataBand. To fill collection it is necessary to call the FindHeaders method. |
| **HierarchicalFooters** | StiComponentsCollection | The collection contains all subordinate Footer's that are displayed at the end of the current HierarchicalDataBand list. To populate the collection, the FindHierarchicalFooters method must be called.The method should be called after the FindFooters method is called. |
| **HierarchicalHeaders** | StiComponentsCollection | The collection contains all subordinate HeaderBand's of the current HierarchicalDataBand. To populate the collection it is necessary to call the FindHierarchicalHeaders method. The method should be called after calling the FindHeaders method. |
| **ReportSummaries** | List<StiReportSummaryBand> |  |
| **ReportTitles** | List<StiReportTitleBand> |  |
| **StoredParentBookmark** | [StiBookmark](StiBookmark.md) | The field contains a backup copy of ParentBookmark. The copy is used to populate the ParentBookmark field in output bends because ParentBookmark can be corrupted by the group. |
| **StoredParentPointer** | [StiBookmark](StiBookmark.md) |  |
| **SubReports** | StiComponentsCollection | The collection contains all subordinate SubReport's of the current DataBand. To fill collection it is necessary to call FindSubReports method. |
