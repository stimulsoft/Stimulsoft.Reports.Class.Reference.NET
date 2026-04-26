---
title: "StiServiceContainer Class"
---

## StiServiceContainer Class

**Namespace:** `Stimulsoft.Base.Services`

Describes class for access to container of services.

### Inheritance

Inherits from: CollectionBase  
Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiServiceContainer**() | Creates a new object of the type StiServiceContainer. |

**StiServiceContainer**()

Creates a new object of the type StiServiceContainer.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **StandardAssemblies** `static` | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** *(+1 overloads)* | void | Adds service to the container. |
| **AddRange** | void | Adds services to the container. |
| **Clear** | void | Clears all collection from service container. |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Contains** *(+1 overloads)* | bool |  |
| **CreateService** `static` | [StiService](StiService.md) | Creates service. |
| **GetService** *(+2 overloads)* | [StiService](StiService.md) | Gets a service type. |
| **GetServices** *(+3 overloads)* | [StiServiceContainer](StiServiceContainer.md) | Gets all services of the type from the container. |
| **GetServicesFromAssembly** `static` *(+1 overloads)* | [StiServiceContainer](StiServiceContainer.md) | Returns services which are in the specified assembly. |
| **GetServicesNamesFromAssembly** `static` | ArrayList |  |
| **GetStandardServices** `static` | [StiServiceContainer](StiServiceContainer.md) | Gets a service container that contains all standard services. |
| **GetStandardServicesNames** `static` | ArrayList |  |
| **GetStringFromService** `static` *(+1 overloads)* | string | Returns string presentation of the service. |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Load** *(+2 overloads)* | void | Loads container of services. |
| **Remove** *(+2 overloads)* | void | Removes services of the type from the container. |
| **Save** *(+2 overloads)* | void | Saves container of services. |
| **ToArray** | [StiService](StiService.md)[] | Gets array of services, that contains in this service container. |
| **ToList** *(+1 overloads)* | List<T> |  |

---

### Method Details

#### Add

**Add**(**service**: [StiService](StiService.md)): void

Adds service to the container.

**Parameters**

- **service** ([StiService](StiService.md)) — Service.  

---

**Add**(**service**: [StiService](StiService.md), **callBeforeGetService**: bool): void

Adds service to the container.

**Parameters**

- **service** ([StiService](StiService.md)) — Service.  
- **callBeforeGetService** (bool)  


---

#### AddRange

**AddRange**(**services**: [StiServiceContainer](StiServiceContainer.md)): void

Adds services to the container.

**Parameters**

- **services** ([StiServiceContainer](StiServiceContainer.md)) — Services.  


---

#### Clear

**Clear**(): void

Clears all collection from service container.


---

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Contains

**Contains**(**service**: [StiService](StiService.md)): bool

**Parameters**

- **service** ([StiService](StiService.md))  

**Returns** bool

---

**Contains**(**service**: string): bool

**Parameters**

- **service** (string)  

**Returns** bool


---

#### CreateService `static`

**CreateService**(**assemblyName**: string, **type**: string): [StiService](StiService.md)

Creates service.

**Parameters**

- **assemblyName** (string) — Assembly where the service is.  
- **type** (string) — Service type.  

**Returns** [StiService](StiService.md) — Created service.


---

#### GetService

**GetService**(**serviceType**: Type): [StiService](StiService.md)

Gets a service type.

**Parameters**

- **serviceType** (Type)  

**Returns** [StiService](StiService.md)

---

**GetService**(**serviceType**: Type, **getEnabled**: bool): [StiService](StiService.md)

**Parameters**

- **serviceType** (Type)  
- **getEnabled** (bool)  

**Returns** [StiService](StiService.md)

---

**GetService**(**serviceType**: Type, **getEnabled**: bool, **callBeforeGetService**: bool): [StiService](StiService.md)

Gets first service of the type from the container.

**Parameters**

- **serviceType** (Type) — Service type.  
- **getEnabled** (bool)  
- **callBeforeGetService** (bool)  

**Returns** [StiService](StiService.md) — Service.


---

#### GetServices

**GetServices**(**serviceType**: Type): [StiServiceContainer](StiServiceContainer.md)

Gets all services of the type from the container.

**Parameters**

- **serviceType** (Type) — Type of the returnable services.  

**Returns** [StiServiceContainer](StiServiceContainer.md) — Collection of services.

---

**GetServices**(): List<T>

**Returns** List<T>

---

**GetServices**(**serviceType**: Type, **getEnabled**: bool): [StiServiceContainer](StiServiceContainer.md)

**Parameters**

- **serviceType** (Type)  
- **getEnabled** (bool)  

**Returns** [StiServiceContainer](StiServiceContainer.md)

---

**GetServices**(**serviceType**: Type, **getEnabled**: bool, **callBeforeGetService**: bool): [StiServiceContainer](StiServiceContainer.md)

Returns all services of the type from the container.

**Parameters**

- **serviceType** (Type) — Type of the returnable services.  
- **getEnabled** (bool) — If true then returns only enabled services.  
- **callBeforeGetService** (bool)  

**Returns** [StiServiceContainer](StiServiceContainer.md) — Collection of services.


---

#### GetServicesFromAssembly `static`

**GetServicesFromAssembly**(**assemblyName**: string): [StiServiceContainer](StiServiceContainer.md)

Returns services which are in the specified assembly.

**Parameters**

- **assemblyName** (string) — Assembly.  

**Returns** [StiServiceContainer](StiServiceContainer.md) — Services.

---

**GetServicesFromAssembly**(**a**: Assembly): [StiServiceContainer](StiServiceContainer.md)

Returns services which are in the specified assembly.

**Parameters**

- **a** (Assembly) — Assembly.  

**Returns** [StiServiceContainer](StiServiceContainer.md) — Services.


---

#### GetServicesNamesFromAssembly `static`

**GetServicesNamesFromAssembly**(**a**: Assembly): ArrayList

**Parameters**

- **a** (Assembly)  

**Returns** ArrayList


---

#### GetStandardServices `static`

**GetStandardServices**(): [StiServiceContainer](StiServiceContainer.md)

Gets a service container that contains all standard services.

**Returns** [StiServiceContainer](StiServiceContainer.md) — Service container that contains all standard services.


---

#### GetStandardServicesNames `static`

**GetStandardServicesNames**(): ArrayList

**Returns** ArrayList


---

#### GetStringFromService `static`

**GetStringFromService**(**service**: [StiService](StiService.md)): string

Returns string presentation of the service.

**Parameters**

- **service** ([StiService](StiService.md)) — Service.  

**Returns** string — String.

---

**GetStringFromService**(**serviceType**: Type): string

**Parameters**

- **serviceType** (Type)  

**Returns** string


---

#### IndexOf

**IndexOf**(**service**: [StiService](StiService.md)): int

**Parameters**

- **service** ([StiService](StiService.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **service**: [StiService](StiService.md)): void

**Parameters**

- **index** (int)  
- **service** ([StiService](StiService.md))  


---

#### Load

**Load**(**tr**: XmlReader): void

Loads container of services.

**Parameters**

- **tr** (XmlReader) — XmlReader.  

---

**Load**(**stream**: Stream): void

Loads container of services.

**Parameters**

- **stream** (Stream) — Stream.  

---

**Load**(**fileName**: string): void

Loads container of services.

**Parameters**

- **fileName** (string) — File.  


---

#### Remove

**Remove**(**serviceType**: Type): void

Removes services of the type from the container.

**Parameters**

- **serviceType** (Type) — Service type.  

---

**Remove**(**service**: [StiService](StiService.md)): void

Removes service from the container.

**Parameters**

- **service** ([StiService](StiService.md)) — Service.  

---

**Remove**(**services**: [StiServiceContainer](StiServiceContainer.md)): void

Removes service from the container.

**Parameters**

- **services** ([StiServiceContainer](StiServiceContainer.md)) — Services.  


---

#### Save

**Save**(**tw**: XmlWriter): void

Saves container of services.

**Parameters**

- **tw** (XmlWriter) — XmlWriter.  

---

**Save**(**stream**: Stream): void

Saves container of services.

**Parameters**

- **stream** (Stream) — Stream.  

---

**Save**(**fileName**: string): void

Saves container of services.

**Parameters**

- **fileName** (string) — File.  


---

#### ToArray

**ToArray**(): [StiService](StiService.md)[]

Gets array of services, that contains in this service container.

**Returns** [StiService](StiService.md)[]


---

#### ToList

**ToList**(): List<T>

**Returns** List<T>

---

**ToList**(): List<[StiService](StiService.md)>

**Returns** List<[StiService](StiService.md)>


### Events

| Event | Type | Description |
| --- | --- | --- |
| **BeforeGetService** | StiServiceActionHandler |  |
