---
title: "WriteState Enum"
---

## WriteState Enum

**Namespace:** `Stimulsoft.Base.Json`

Specifies the state of the JsonWriter.

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Error** | 0 | An exception has been thrown, which has left the JsonWriter in an invalid state. You may call the Close method to put the JsonWriter in the `Closed` state. Any other JsonWriter method calls results in an InvalidOperationException being thrown. |
| **Closed** | 1 | The Close method has been called. |
| **Object** | 2 | An object is being written. |
| **Array** | 3 | A array is being written. |
| **Constructor** | 4 | A constructor is being written. |
| **Property** | 5 | A property is being written. |
| **Start** | 6 | A write method has not been called. |
