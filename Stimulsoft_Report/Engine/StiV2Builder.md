---
title: "StiV2Builder Class"
---

## StiV2Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiV2Builder
```

### Inheritance

Inherits from: [StiBuilder](StiBuilder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBuilder** `static` | [StiV2Builder](StiV2Builder.md) |  |
| **InternalRender** | StiComponent | Renders a component. Does not call events of a component while rendering. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** | StiComponent | Renders a component with calling an event. A method is used with InternalRender for the component rendering. |
| **SetReportVariables** | void | Sets system variables which are specific for the specified component. |
| **UnPrepare** | void | Clears a component for rendering. |
