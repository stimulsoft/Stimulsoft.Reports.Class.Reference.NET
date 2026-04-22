---
title: "StiComponentV1Builder Class"
---

## StiComponentV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiComponentV1Builder
```

### Inheritance

Inherits from: [StiV1Builder](StiV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** *(+1 overloads)* | bool | Renders a component in the specified container with taking events generation into consideration. A rendered component is returned in the renderedComponent argument. |
| **UnPrepare** | void | Clears a component after rendering. |
