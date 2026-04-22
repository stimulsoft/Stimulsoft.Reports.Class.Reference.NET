---
title: "StiDataBandInfoV1 Class"
---

## StiDataBandInfoV1 Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDataBandInfoV1
```

### Inheritance

Inherits from: [StiComponentInfo](../Engine/StiComponentInfo.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AlwaysKeepChildTogether** | bool |  |
| **BreakableComps** | StiComponentsCollection |  |
| **ColumnIndex** | int |  |
| **CrossTabExistOnDataBand** | bool |  |
| **CurrentDetailComponent** | StiComponent | Gets or sets the current child component. If it equal in null then Master component is printed. |
| **DataIsPrepared** | bool |  |
| **DetailComponents** | StiComponentsCollection | Gets or sets collection of details. |
| **DetailDataComponents** | StiComponentsCollection | Gets or sets collection of data details. |
| **FirstCall** | bool |  |
| **FirstGroupOnPass** | bool |  |
| **FirstRow** | bool | Render first row. |
| **FirstRowInPath** | bool | Render first row in the current pass. |
| **FooterComponents** | StiComponentsCollection | Gets or sets collection of footers. |
| **ForceStartNewPage** | bool | Force start new page when on page exist footers from previus page. |
| **FreeSpace** | double | Gets or sets free space for rendering. |
| **GroupFooterComponents** | StiComponentsCollection |  |
| **GroupHeaderComponents** | StiComponentsCollection |  |
| **HeaderComponents** | StiComponentsCollection | Gets or sets a collection of headers. |
| **IsFirstPassOfBreak** | bool |  |
| **ItemsActive** | bool | Save line to collection? |
| **LastComponent** | StiComponent | Last rendered component. |
| **LastPositionRendering** | int |  |
| **LastRenderBreaked** | bool | Last rendered component was breaked. |
| **LatestDataBandBreaked** | bool |  |
| **ParentColumnContainer** | StiContainer |  |
| **RemmitedCollection** | StiComponentsCollection | Collection of components, which will be render in next pass. |
| **RenderedHeaders** | StiComponentsCollection |  |
| **RenderedItems** | List<StiComponent> | Collection rendered lines. |
| **ResHeightOfContainerBeforeRendering** | double |  |
| **ResParentBookmark** | [StiBookmark](StiBookmark.md) | Parent bookmark of the current component. |
| **ResParentPointer** | [StiBookmark](StiBookmark.md) |  |
| **RuntimeLine** | int |  |
| **SkipStartNewPage** | bool |  |
| **StartGroupIndex** | int | Contains the amount of the typed groups. Begin position the group in container. |
| **StartLine** | int | From what lines is calculation Line. |
| **StartMasterIndex** | int |  |
| **SubReportsComponents** | StiComponentsCollection |  |
