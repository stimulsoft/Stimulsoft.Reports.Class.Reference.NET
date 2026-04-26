---
title: "StiDataBandV1Builder Class"
---

## StiDataBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

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

---

### Method Details

#### CheckFreeSpace

**CheckFreeSpace**(**masterDataBand**: StiDataBand, **outContainer**: StiContainer): bool

Checks availability of free space in the container. And adds it, if it may check availability of free space in the container.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **outContainer** (StiContainer) — Container to check free space.  

**Returns** bool — Result: if true then no free space.


---

#### DecFreeSpace

**DecFreeSpace**(**masterDataBand**: StiDataBand, **component**: StiComponent): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **component** (StiComponent)  


---

#### FirstDetail

**FirstDetail**(**masterDataBand**: StiDataBand): void

Comes on the first detail component. If there are no such components then sets the current detail component to null.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### FirstPassBreak

**FirstPassBreak**(**masterDataBand**: StiDataBand, **renderedComponent**: StiComponent, **masterComponent**: StiComponent, **freeSpace**: double): bool

**Parameters**

- **masterDataBand** (StiDataBand)  
- **renderedComponent** (StiComponent)  
- **masterComponent** (StiComponent)  
- **freeSpace** (double)  

**Returns** bool


---

#### GetDataDetails

**GetDataDetails**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of data childs components.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection — Components collection.


---

#### GetDataIsPrepared

**GetDataIsPrepared**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### GetDetails

**GetDetails**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of childs components.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection — Components collection.


---

#### GetFooters

**GetFooters**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of footers of an object.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection


---

#### GetFreeSpaceFromComponent

**GetFreeSpaceFromComponent**(**component**: StiComponent): double

**Parameters**

- **component** (StiComponent)  

**Returns** double


---

#### GetFreeSpaceFromRectangle

**GetFreeSpaceFromRectangle**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): double

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** double


---

#### GetGroupFooters

**GetGroupFooters**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of group footers.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection — Components collection.


---

#### GetGroupHeaders

**GetGroupHeaders**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of group headers.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection — Components collection.


---

#### GetGroupLinesCount

**GetGroupLinesCount**(**masterDataBand**: StiDataBand, **band**: StiGroupHeaderBand): int

Returns count of rows in current groups.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **band** (StiGroupHeaderBand)  

**Returns** int


---

#### GetHeaders

**GetHeaders**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of headers for the object.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection


---

#### GetSubReports

**GetSubReports**(**masterDataBand**: StiDataBand): StiComponentsCollection

Returns a collection of SubReport components.

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** StiComponentsCollection — Components collection.


---

#### GroupsComparison

**GroupsComparison**(**masterDataBand**: StiDataBand): void

All GroupFooters are placed on their GroupHeader(is set property - Header).

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### IncFreeSpace

**IncFreeSpace**(**masterDataBand**: StiDataBand, **component**: StiComponent): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **component** (StiComponent)  


---

#### InternalRender

**InternalRender**(**masterDataBand**: StiDataBand, **renderedComponent**: StiComponent, **outContainer**: StiContainer, **value**: bool): bool

Band rendering without event.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **renderedComponent** (StiComponent) — Rendered component.  
- **outContainer** (StiContainer) — The panel in which rendering will be done.  
- **value** (bool)  

**Returns** bool — Is rendering finished or not?

---

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A rendered component.  
- **outContainer** (StiContainer) — A panel in what rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### IsDetailDataSourcesEmpty `static`

**IsDetailDataSourcesEmpty**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### IsPrintIfDetailEmpty

**IsPrintIfDetailEmpty**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### MoveNext

**MoveNext**(**masterDataBand**: StiDataBand): void

Moves on the next row.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### NextDetail

**NextDetail**(**masterDataBand**: StiDataBand): void

Comes on the first detail component. If there are no such components then sets the current subordinate component to null.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### ProcessRenderedContainer

**ProcessRenderedContainer**(**masterDataBand**: StiDataBand, **container**: StiContainer): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **container** (StiContainer)  


---

#### RemoveRenderedHeaders

**RemoveRenderedHeaders**(**masterDataBand**: StiDataBand, **outContainer**: StiContainer): void

Removes rendered headers.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **outContainer** (StiContainer)  


---

#### Render

**Render**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container with taking events generation into consideration. The rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A component which is being rendered.  
- **outContainer** (StiContainer) — A container in which rendering will be done.  

**Returns** bool — A value which indicates whether rendering of the component is finished or not.


---

#### RenderDetails

**RenderDetails**(**masterDataBand**: StiDataBand, **outContainer**: StiContainer): void

Render detail components.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **outContainer** (StiContainer)  


---

#### RenderFootersSecond

**RenderFootersSecond**(**masterDataBand**: StiDataBand, **renderedFooters**: ArrayList, **outContainer**: StiContainer, **newPageStarted**: bool, **isBreaked**: bool): bool

Print footers with the specified option [PrintOnAllPages](second pass) for to take them their own place.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **renderedFooters** (ArrayList)  
- **outContainer** (StiContainer)  
- **newPageStarted** (bool)  
- **isBreaked** (bool)  

**Returns** bool


---

#### RenderGroupHeaders

**RenderGroupHeaders**(**masterDataBand**: StiDataBand, **outContainer**: StiContainer, **startNewPage**: bool): bool

Render group headers.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **outContainer** (StiContainer)  
- **startNewPage** (bool)  

**Returns** bool


---

#### RenderHeaders

**RenderHeaders**(**masterDataBand**: StiDataBand, **outContainer**: StiContainer): bool

Render headers.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **outContainer** (StiContainer)  

**Returns** bool


---

#### RenderItem

**RenderItem**(**masterDataBand**: StiDataBand, **breaked**: bool, **outContainer**: StiContainer): bool

Renders one row with all details.

**Parameters**

- **masterDataBand** (StiDataBand)  
- **breaked** (bool)  
- **outContainer** (StiContainer)  

**Returns** bool


---

#### ResetStartNewPageProcessed

**ResetStartNewPageProcessed**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### SecondPassBreak

**SecondPassBreak**(**masterDataBand**: StiDataBand, **renderedComponent**: StiComponent, **masterComponent**: StiComponent, **freeSpace**: double): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **renderedComponent** (StiComponent)  
- **masterComponent** (StiComponent)  
- **freeSpace** (double)  


---

#### SetData

**SetData**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### SetDataIsPrepared

**SetDataIsPrepared**(**masterDataBand**: StiDataBand, **value**: bool): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **value** (bool)  


---

#### SetDetails `static`

**SetDetails**(**masterDataBand**: StiDataBand): void

Sets detail.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### SetReportVariables

**SetReportVariables**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

Cleans up the component after rendering.

**Parameters**

- **masterComp** (StiComponent)  

