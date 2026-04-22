---
title: "StiV1Builder Class"
---

## StiV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiV1Builder
```

### Inheritance

Inherits from: [StiBuilder](StiBuilder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBuilder** `static` | [StiV1Builder](StiV1Builder.md) |  |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. The rendered component is returned in the renderedComponent. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** *(+1 overloads)* | bool | Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument. |
| **UnPrepare** | void | Clears a component after rendering. |
