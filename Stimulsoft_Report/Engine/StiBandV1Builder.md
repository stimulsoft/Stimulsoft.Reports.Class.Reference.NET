---
title: "StiBandV1Builder Class"
---

## StiBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiBandV1Builder
```

### Inheritance

Inherits from: [StiContainerV1Builder](StiContainerV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetChildBands** `static` | StiComponentsCollection | Returns child bands. |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **RenderChilds** `static` | bool | Render childs bands. |
