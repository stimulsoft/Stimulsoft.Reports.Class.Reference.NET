---
title: "StiEngine Class"
---

## StiEngine Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

Report engine core.

```csharp
public class StiEngine
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiEngine([StiReport](../StiReport.md) report)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ContainerForRender** | StiContainer | Gets or sets a container in what rendering of bands is done. |
| **CrossFreeSpace** | double | Contains a freespace in a container in what the printing is done. Used to output Cross bands only. |
| **CurrentDataBandOfPageLine** | StiDataBand | Gets or sets the current data band associated with the page line. |
| **FreeSpace** | double | Contains a freespace in a container in what the printing is done. |
| **IgnoreUnlimitedHeightForNewPage** | bool | If true then UnlimitedHeight property is ignored when NewPage method is called. |
| **IsCrossBandsMode** | bool | This property is set to true for printing CrossBands. |
| **IsDynamicBookmarksMode** | bool | If true then it is allowed to add any Bookmarks. If false then add Bookmarks of components which the IsRendered property = false (in other words it is rendered first time). This property allows adding Bookmarks for static components only once (to avoid duplication). |
| **IsFirstDataBandOnPage** | bool | Returns true if the first DataBand is printed on the current page. |
| **IsLastDataBandOnPage** | bool | Returns true if the last DataBand is printed on the current page. |
| **MasterReport** | [StiReport](../StiReport.md) | Gets or sets a master report that is being rendered in the current moment. |
| **Page** | StiPage | Gets or sets a page in what rendering of bands is done. |
| **PageLineRenderingEnabled** | bool | Gets or sets a value indicating whether page line rendering is enabled. |
| **PositionBottomY** | double | Indicates the current position bands output on the Y axis on the bottom of a page. |
| **PositionX** | double | Indicates the current position bands output on the X axis. |
| **PositionY** | double | Indicates the current position bands output on the Y axis. |
| **Report** | [StiReport](../StiReport.md) | Gets or sets a report that is being rendered in the current moment. |
| **TemplateContainer** | StiContainer | Gets or sets a container from a template. This page is being rendered in the current moment. If a page is output then the TemplateContainer property is equal in TemplatePage. |
| **TemplatePage** | StiPage | Gets or sets a page from a template. This page is being rendered in the current moment. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddContainerToDestination** | void | Adds a specified container into the container for output. |
| **AddFooterMarker** | void | Adds a FooterMarker (special container) into the current container of output. A container-marker is used for the engine to know on what place in a container of output FooterBands for PrintOnAllPages should be replaced after their rendering is complete. |
| **AddKeepLevelAtLatestDataBand** | void | Adds a container-marker of the beginning of grouping before the last rendered DataBand. |
| **AddLevel** | void | Adds a container-marker of the beginning of grouping into the current position of output in the stream. |
| **AddPageToRenderedPages** | void | Adds a specified page into the collection of rendered pages. |
| **CheckForDuplicate** | bool |  |
| **ClearCachedTotals** | void |  |
| **ClearPageBreakSkipFirst** | void | Clears a collection of bands which once passed the generation of a new page or column. |
| **FinalClear** | void | A method is called to finalize operations over the output stream. |
| **FinishColumns** | void | Finds all the column containers and finishes them. The finishing procedure includes a call to the FinishColumns method. This method arranges the containers into columns. |
| **FinishContainer** | void | Find all containers and zero the ParentBand property. |
| **FinishResetPageNumberContainer** | void | The method checks the ResetPageNumber property and resets the page number if necessary. |
| **GetComponentByNameFromRenderedPage** | StiComponent |  |
| **GetSumTagsOnPage** | decimal |  |
| **NewColumn** | void | A method forms a new column. |
| **NewDestination** *(+1 overloads)* | void | Forms a new page of a new column (if there are some). |
| **NewList** *(+1 overloads)* | void | A method is called for each new page or column. If the first column is output or thre are no columns then a method outputs statis bands. In addition, it resets the pointer to the last output DataBand. Also a method prints bands which should be output on all pages. |
| **NewPage** | void | A method forms a new page in a report. |
| **RemoveBandFromPageBreakSkipList** | void |  |
| **RemoveLevel** | void | Adds a container-marker of the end of grouping into the current position of output in the stream. |
| **RenderBand** | StiComponentsCollection | Renders a specified band taking Child bands into consideration. |
| **ResetProcessingDuplicates** *(+1 overloads)* | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SpecialContainerHeight** | double |  |
| **SpecialContainerHeight2** | double |  |
