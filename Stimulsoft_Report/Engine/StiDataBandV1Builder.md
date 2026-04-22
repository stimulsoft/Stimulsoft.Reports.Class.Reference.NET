---
title: "StiDataBandV1Builder Class"
---

## StiDataBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDataBandV1Builder
```

### Inheritance

Inherits from: [StiBandV1Builder](StiBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckFreeSpace** | bool | Checks availability of free space in the container. And adds it, if it may check availability of free space in the container. |
| **DecFreeSpace** | void |  |
| **FirstDetail** | void | Comes on the first detail component. If there are no such components then sets the current detail component to null. |
| **FirstPassBreak** | bool |  |
| **GetDataDetails** | StiComponentsCollection | Returns a collection of data childs components. |
| **GetDataIsPrepared** | bool |  |
| **GetDetails** | StiComponentsCollection | Returns a collection of childs components. |
| **GetFooters** | StiComponentsCollection | Returns a collection of footers of an object. |
| **GetFreeSpaceFromComponent** | double |  |
| **GetFreeSpaceFromRectangle** | double |  |
| **GetGroupFooters** | StiComponentsCollection | Returns a collection of group footers. |
| **GetGroupHeaders** | StiComponentsCollection | Returns a collection of group headers. |
| **GetGroupLinesCount** | int | Returns count of rows in current groups. |
| **GetHeaders** | StiComponentsCollection | Returns a collection of headers for the object. |
| **GetSubReports** | StiComponentsCollection | Returns a collection of SubReport components. |
| **GroupsComparison** | void | All GroupFooters are placed on their GroupHeader(is set property - Header). |
| **IncFreeSpace** | void |  |
| **InternalRender** *(+1 overloads)* | bool | Band rendering without event. |
| **IsDetailDataSourcesEmpty** `static` | bool |  |
| **IsPrintIfDetailEmpty** | bool |  |
| **MoveNext** | void | Moves on the next row. |
| **NextDetail** | void | Comes on the first detail component. If there are no such components then sets the current subordinate component to null. |
| **Prepare** | void | Prepares a component for rendering. |
| **ProcessRenderedContainer** | void |  |
| **RemoveRenderedHeaders** | void | Removes rendered headers. |
| **Render** | bool | Renders a component in the specified container with taking events generation into consideration. The rendered component is returned in the renderedComponent argument. |
| **RenderDetails** | void | Render detail components. |
| **RenderFootersSecond** | bool | Print footers with the specified option [PrintOnAllPages](second pass) for to take them their own place. |
| **RenderGroupHeaders** | bool | Render group headers. |
| **RenderHeaders** | bool | Render headers. |
| **RenderItem** | bool | Renders one row with all details. |
| **ResetStartNewPageProcessed** | void |  |
| **SecondPassBreak** | void |  |
| **SetData** | void |  |
| **SetDataIsPrepared** | void |  |
| **SetDetails** `static` | void | Sets detail. |
| **SetReportVariables** | void |  |
| **UnPrepare** | void | Cleans up the component after rendering. |
