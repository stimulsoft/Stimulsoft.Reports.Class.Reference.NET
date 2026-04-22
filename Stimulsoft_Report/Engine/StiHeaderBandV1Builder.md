---
title: "StiHeaderBandV1Builder Class"
---

## StiHeaderBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiHeaderBandV1Builder
```

### Inheritance

Inherits from: [StiBandV1Builder](StiBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMaster** `static` | StiComponent | Returns Master component of this component. |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. The rendered component is returned in the renderedComponent. |
| **Prepare** | void | Prepares a component for rendering. |
| **PrintOddEven** `static` | bool |  |
| **Render** | bool | Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument. |
