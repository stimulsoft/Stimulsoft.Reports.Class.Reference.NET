---
title: "StiServerException Class"
---

## StiServerException Class

**Namespace:** `Stimulsoft.Base`

This class describes base class of Stimulsoft Server exceptions.

### Inheritance

Inherits from: Exception  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiServerException**(Exception innerException) |  |
| **StiServerException**(string message, Exception innerException) |  |
| **StiServerException**([StiNoticeIdent](StiNoticeIdent.md) noticeIdent, Exception innerException) |  |
| **StiServerException**([StiNotice](StiNotice.md) notice, Exception innerException) |  |

**StiServerException**(**innerException**: Exception)

**Parameters**

- **innerException** (Exception)  

---

**StiServerException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**StiServerException**(**noticeIdent**: [StiNoticeIdent](StiNoticeIdent.md), **innerException**: Exception)

**Parameters**

- **noticeIdent** ([StiNoticeIdent](StiNoticeIdent.md))  
- **innerException** (Exception)  

---

**StiServerException**(**notice**: [StiNotice](StiNotice.md), **innerException**: Exception)

**Parameters**

- **notice** ([StiNotice](StiNotice.md))  
- **innerException** (Exception)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Notice** | [StiNotice](StiNotice.md) |  |
