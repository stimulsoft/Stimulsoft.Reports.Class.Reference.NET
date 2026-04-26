---
title: "TOuterExt Class"
---

## TOuterExt Class

**Namespace:** `Stimulsoft.Data.Extensions`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FullOuterJoin** `static` | IEnumerable<TResult> |  |

---

### Method Details

#### FullOuterJoin `static`

**FullOuterJoin**(**outer**: IEnumerable<TOuter>, **inner**: IEnumerable<TInner>, **outerKeySelector**: [Func](../../Stimulsoft_Report/root/Func.md)<TOuter, TKey>, **innerKeySelector**: [Func](../../Stimulsoft_Report/root/Func.md)<TInner, TKey>, **resultSelector**: [Func](../../Stimulsoft_Report/root/Func.md)<TOuter, TInner, TResult>): IEnumerable<TResult>

**Parameters**

- **outer** (IEnumerable<TOuter>)  
- **inner** (IEnumerable<TInner>)  
- **outerKeySelector** ([Func](../../Stimulsoft_Report/root/Func.md)<TOuter, TKey>)  
- **innerKeySelector** ([Func](../../Stimulsoft_Report/root/Func.md)<TInner, TKey>)  
- **resultSelector** ([Func](../../Stimulsoft_Report/root/Func.md)<TOuter, TInner, TResult>)  

**Returns** IEnumerable<TResult>

