---
title: "Reflection Class"
---

## Reflection Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** `static` | object |  |
| **GetPropertyValue** `static` *(+1 overloads)* | T |  |
| **InvokeMethod** `static` *(+1 overloads)* | T |  |
| **SetPropertyValue** `static` | void |  |

---

### Method Details

#### Create `static`

**Create**(**assembly**: Assembly, **type**: string, ****: objectargs): object

**Parameters**

- **assembly** (Assembly)  
- **type** (string)  
- **** (objectargs)  

**Returns** object


---

#### GetPropertyValue `static`

**GetPropertyValue**(**value**: object, **propertyName**: string): T

**Parameters**

- **value** (object)  
- **propertyName** (string)  

**Returns** T

---

**GetPropertyValue**(**value**: object, **propertyName**: string): object

**Parameters**

- **value** (object)  
- **propertyName** (string)  

**Returns** object


---

#### InvokeMethod `static`

**InvokeMethod**(**value**: object, **methodName**: string, ****: objectargs): T

**Parameters**

- **value** (object)  
- **methodName** (string)  
- **** (objectargs)  

**Returns** T

---

**InvokeMethod**(**value**: object, **methodName**: string, ****: objectargs): object

**Parameters**

- **value** (object)  
- **methodName** (string)  
- **** (objectargs)  

**Returns** object


---

#### SetPropertyValue `static`

**SetPropertyValue**(**value**: object, **propertyName**: string, **propValue**: object): void

**Parameters**

- **value** (object)  
- **propertyName** (string)  
- **propValue** (object)  

