---
title: "StiAppBindingHelper Class"
---

## StiAppBindingHelper Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBinding** `static` | StiAppBinding |  |
| **GetBindingFromInstance** `static` *(+1 overloads)* | string | Returns an binded field if specified from the context object. Returns null if the binded field is not specified. |
| **GetBindingValue** `static` | string |  |
| **GetBindings** `static` | IEnumerable<StiAppBinding> |  |
| **IsBindingSpecified** `static` | bool |  |
| **IsDataBindingAllowed** `static` | bool |  |
| **RemoveBinding** `static` | void |  |
| **SetBinding** `static` | void |  |

---

### Method Details

#### GetBinding `static`

**GetBinding**(**component**: object, **propName**: string): StiAppBinding

**Parameters**

- **component** (object)  
- **propName** (string)  

**Returns** StiAppBinding


---

#### GetBindingFromInstance `static`

**GetBindingFromInstance**(**context**: ITypeDescriptorContext): string

Returns an binded field if specified from the context object. Returns null if the binded field is not specified.

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** string

---

**GetBindingFromInstance**(**instance**: object, **propertyName**: string): string

Returns and binded field if specified from the specified instance and the property name. Returns null if the binded field is not specified.

**Parameters**

- **instance** (object)  
- **propertyName** (string)  

**Returns** string


---

#### GetBindingValue `static`

**GetBindingValue**(**component**: object, **propName**: string): string

**Parameters**

- **component** (object)  
- **propName** (string)  

**Returns** string


---

#### GetBindings `static`

**GetBindings**(**component**: object): IEnumerable<StiAppBinding>

**Parameters**

- **component** (object)  

**Returns** IEnumerable<StiAppBinding>


---

#### IsBindingSpecified `static`

**IsBindingSpecified**(**component**: object, **propName**: string): bool

**Parameters**

- **component** (object)  
- **propName** (string)  

**Returns** bool


---

#### IsDataBindingAllowed `static`

**IsDataBindingAllowed**(**descriptor**: PropertyDescriptor): bool

**Parameters**

- **descriptor** (PropertyDescriptor)  

**Returns** bool


---

#### RemoveBinding `static`

**RemoveBinding**(**component**: object, **propName**: string): void

**Parameters**

- **component** (object)  
- **propName** (string)  


---

#### SetBinding `static`

**SetBinding**(**component**: object, **propName**: string, **field**: string): void

**Parameters**

- **component** (object)  
- **propName** (string)  
- **field** (string)  

