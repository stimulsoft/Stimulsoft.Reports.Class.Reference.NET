---
title: "StiSubReport Class"
---

## StiSubReport Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiContainer  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSubReport**() | Creates a new component of the type StiSubReport. |
| **StiSubReport**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new component of the type StiSubReport. |

**StiSubReport**()

Creates a new component of the type StiSubReport.

---

**StiSubReport**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new component of the type StiSubReport.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **KeepSubReportTogether** | bool |  |
| **Parameters** | StiParametersCollection |  |
| **SubReportPageGuid** | string |  |
| **SubReportUrl** | string |  |
| **ToolboxCategory** | [StiToolboxCategory](StiToolboxCategory.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanContainIn** | bool | May this container be located in the specified component. |
| **Clone** *(+1 overloads)* | object |  |
| **Convert** | void | Converts a component out of one unit into another. |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Returns events collection of this component. |
| **GetExternalSubReport** | [StiReport](../root/StiReport.md) | Returns the SubReport template for rendering. |
| **GetSubReportForPage** `static` | [StiSubReport](StiSubReport.md) |  |
| **GetSubReportFromFile** | [StiReport](../root/StiReport.md) | Returns the SubReport from specified path. |
| **GetSubReportFromUrl** | [StiReport](../root/StiReport.md) | Returns the SubReport from specified url. |
| **InvokeFillParameters** | void | Raises the FillParameters event. |
| **LoadFromJsonObject** | void |  |
| **OnFillParameters** | void | Raises the FillParameters event. |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### CanContainIn

**CanContainIn**(**component**: StiComponent): bool

May this container be located in the specified component.

**Parameters**

- **component** (StiComponent) — Component for checking.  

**Returns** bool — true, if this container may is located in the specified component.


---

#### Clone

**Clone**(**cloneProperties**: bool): object

**Parameters**

- **cloneProperties** (bool)  

**Returns** object

---

**Clone**(**cloneProperties**: bool, **cloneComponents**: bool): object

Creates a new object that is a copy of the current instance.

**Parameters**

- **cloneProperties** (bool)  
- **cloneComponents** (bool)  

**Returns** object — A new object that is a copy of this instance.


---

#### Convert

**Convert**(**oldUnit**: [StiUnit](../Units/StiUnit.md), **newUnit**: [StiUnit](../Units/StiUnit.md), **isReportSnapshot**: bool): void

Converts a component out of one unit into another.

**Parameters**

- **oldUnit** ([StiUnit](../Units/StiUnit.md)) — Old units.  
- **newUnit** ([StiUnit](../Units/StiUnit.md)) — New units.  
- **isReportSnapshot** (bool)  


---

#### GetEvents

**GetEvents**(): [StiEventsCollection](../Events/StiEventsCollection.md)

Returns events collection of this component.

**Returns** [StiEventsCollection](../Events/StiEventsCollection.md)


---

#### GetExternalSubReport

**GetExternalSubReport**(): [StiReport](../root/StiReport.md)

Returns the SubReport template for rendering.

**Returns** [StiReport](../root/StiReport.md)


---

#### GetSubReportForPage `static`

**GetSubReportForPage**(**page**: StiPage): [StiSubReport](StiSubReport.md)

**Parameters**

- **page** (StiPage)  

**Returns** [StiSubReport](StiSubReport.md)


---

#### GetSubReportFromFile

**GetSubReportFromFile**(**url**: string): [StiReport](../root/StiReport.md)

Returns the SubReport from specified path.

**Parameters**

- **url** (string)  

**Returns** [StiReport](../root/StiReport.md)


---

#### GetSubReportFromUrl

**GetSubReportFromUrl**(**url**: string): [StiReport](../root/StiReport.md)

Returns the SubReport from specified url.

**Parameters**

- **url** (string)  

**Returns** [StiReport](../root/StiReport.md)


---

#### InvokeFillParameters

**InvokeFillParameters**(**sender**: StiComponent, **e**: StiFillParametersEventArgs): void

Raises the FillParameters event.

**Parameters**

- **sender** (StiComponent)  
- **e** (StiFillParametersEventArgs)  


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### OnFillParameters

**OnFillParameters**(**e**: StiFillParametersEventArgs): void

Raises the FillParameters event.

**Parameters**

- **e** (StiFillParametersEventArgs)  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

