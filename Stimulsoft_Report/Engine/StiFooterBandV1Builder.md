---
title: "StiFooterBandV1Builder Class"
---

## StiFooterBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFooterBandV1Builder
```

### Inheritance

Inherits from: [StiBandV1Builder](StiBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMaster** `static` | StiComponent | Returns the Master component of an object. |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. Rendered component is returned in the renderedComponent. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** | bool | Renders a component in the specified container with taking generation of events into consideration. A rendered component is returned in the renderedComponent argument. |
