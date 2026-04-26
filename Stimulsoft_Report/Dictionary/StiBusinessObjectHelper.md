---
title: "StiBusinessObjectHelper Class"
---

## StiBusinessObjectHelper Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Class which helps work with business objects.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBusinessObjectFromGuid** `static` | StiBusinessObject |  |
| **GetBusinessObjectFullAlias** `static` | string |  |
| **GetBusinessObjectFullName** `static` | string |  |
| **GetBusinessObjectsFromReport** `static` *(+1 overloads)* | List<StiBusinessObject> |  |
| **GetColumnsFromBusinessObject** `static` | StiDataColumnsCollection |  |
| **GetColumnsFromBusinessObjectData** `static` | StiDataColumnsCollection |  |
| **GetColumnsFromData** `static` *(+1 overloads)* | StiDataColumnsCollection |  |
| **GetElementFromEnumerable** `static` | object |  |
| **GetElementFromObject** `static` *(+1 overloads)* | object |  |
| **GetElementType** `static` | Type |  |
| **GetEnumeratorFromClass** `static` | IEnumerator |  |
| **GetEnumeratorFromDataSet** `static` | IEnumerator |  |
| **GetEnumeratorFromDataTable** `static` | IEnumerator |  |
| **GetEnumeratorFromIEnumerable** `static` | IEnumerator |  |
| **GetEnumeratorFromIEnumerator** `static` | IEnumerator |  |
| **GetEnumeratorFromObject** `static` | IEnumerator |  |
| **GetUsedBusinessObjectsNames** `static` *(+1 overloads)* | Hashtable |  |
| **GetUsedBusinessObjectsNamesList** `static` *(+1 overloads)* | List<string> |  |
| **GetValueFromClass** `static` *(+1 overloads)* | object |  |
| **GetValueFromDataRow** `static` | object |  |
| **GetValueFromDataSet** `static` | object |  |
| **GetValueFromDataTable** `static` | object |  |
| **GetValueFromDictionaryEntry** `static` | object |  |
| **GetValueFromICustomTypeDescriptor** `static` | object |  |
| **GetValueFromITypedList** `static` *(+1 overloads)* | object |  |
| **GetValueFromKeyValuePair** `static` | object |  |
| **GetValueFromObject** `static` *(+1 overloads)* | object |  |
| **IsDataColumn** `static` | bool |  |
| **IsTypeImplementICollection** `static` | bool |  |
| **IsValueExistInClass** `static` | bool |  |

---

### Method Details

#### GetBusinessObjectFromGuid `static`

**GetBusinessObjectFromGuid**(**report**: [StiReport](../root/StiReport.md), **guid**: string): StiBusinessObject

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **guid** (string)  

**Returns** StiBusinessObject


---

#### GetBusinessObjectFullAlias `static`

**GetBusinessObjectFullAlias**(**businessObject**: StiBusinessObject): string

**Parameters**

- **businessObject** (StiBusinessObject)  

**Returns** string


---

#### GetBusinessObjectFullName `static`

**GetBusinessObjectFullName**(**businessObject**: StiBusinessObject): string

**Parameters**

- **businessObject** (StiBusinessObject)  

**Returns** string


---

#### GetBusinessObjectsFromReport `static`

**GetBusinessObjectsFromReport**(**businessObjects**: StiBusinessObjectsCollection): List<StiBusinessObject>

**Parameters**

- **businessObjects** (StiBusinessObjectsCollection)  

**Returns** List<StiBusinessObject>

---

**GetBusinessObjectsFromReport**(**report**: [StiReport](../root/StiReport.md)): List<StiBusinessObject>

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** List<StiBusinessObject>


---

#### GetColumnsFromBusinessObject `static`

**GetColumnsFromBusinessObject**(**data**: StiBusinessObject): StiDataColumnsCollection

**Parameters**

- **data** (StiBusinessObject)  

**Returns** StiDataColumnsCollection


---

#### GetColumnsFromBusinessObjectData `static`

**GetColumnsFromBusinessObjectData**(**data**: [StiBusinessObjectData](StiBusinessObjectData.md)): StiDataColumnsCollection

**Parameters**

- **data** ([StiBusinessObjectData](StiBusinessObjectData.md))  

**Returns** StiDataColumnsCollection


---

#### GetColumnsFromData `static`

**GetColumnsFromData**(**data**: object): StiDataColumnsCollection

**Parameters**

- **data** (object)  

**Returns** StiDataColumnsCollection

---

**GetColumnsFromData**(**data**: object, **includeChildDataSources**: bool): StiDataColumnsCollection

**Parameters**

- **data** (object)  
- **includeChildDataSources** (bool)  

**Returns** StiDataColumnsCollection


---

#### GetElementFromEnumerable `static`

**GetElementFromEnumerable**(**enumerable**: IEnumerable): object

**Parameters**

- **enumerable** (IEnumerable)  

**Returns** object


---

#### GetElementFromObject `static`

**GetElementFromObject**(**value**: object, **name**: string): object

**Parameters**

- **value** (object)  
- **name** (string)  

**Returns** object

---

**GetElementFromObject**(**value**: object, **name**: string, **isColumnsRetrieve**: bool): object

**Parameters**

- **value** (object)  
- **name** (string)  
- **isColumnsRetrieve** (bool)  

**Returns** object


---

#### GetElementType `static`

**GetElementType**(**arrayType**: Type): Type

**Parameters**

- **arrayType** (Type)  

**Returns** Type


---

#### GetEnumeratorFromClass `static`

**GetEnumeratorFromClass**(**value**: object): IEnumerator

**Parameters**

- **value** (object)  

**Returns** IEnumerator


---

#### GetEnumeratorFromDataSet `static`

**GetEnumeratorFromDataSet**(**dataSet**: DataSet): IEnumerator

**Parameters**

- **dataSet** (DataSet)  

**Returns** IEnumerator


---

#### GetEnumeratorFromDataTable `static`

**GetEnumeratorFromDataTable**(**dataTable**: DataTable): IEnumerator

**Parameters**

- **dataTable** (DataTable)  

**Returns** IEnumerator


---

#### GetEnumeratorFromIEnumerable `static`

**GetEnumeratorFromIEnumerable**(**enumerable**: IEnumerable): IEnumerator

**Parameters**

- **enumerable** (IEnumerable)  

**Returns** IEnumerator


---

#### GetEnumeratorFromIEnumerator `static`

**GetEnumeratorFromIEnumerator**(**enumerator**: IEnumerator): IEnumerator

**Parameters**

- **enumerator** (IEnumerator)  

**Returns** IEnumerator


---

#### GetEnumeratorFromObject `static`

**GetEnumeratorFromObject**(**value**: object): IEnumerator

**Parameters**

- **value** (object)  

**Returns** IEnumerator


---

#### GetUsedBusinessObjectsNames `static`

**GetUsedBusinessObjectsNames**(**report**: [StiReport](../root/StiReport.md)): Hashtable

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** Hashtable

---

**GetUsedBusinessObjectsNames**(**report**: [StiReport](../root/StiReport.md), **addColumns**: bool): Hashtable

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **addColumns** (bool)  

**Returns** Hashtable


---

#### GetUsedBusinessObjectsNamesList `static`

**GetUsedBusinessObjectsNamesList**(**report**: [StiReport](../root/StiReport.md)): List<string>

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** List<string>

---

**GetUsedBusinessObjectsNamesList**(**report**: [StiReport](../root/StiReport.md), **addColumns**: bool): List<string>

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **addColumns** (bool)  

**Returns** List<string>


---

#### GetValueFromClass `static`

**GetValueFromClass**(**value**: object, **name**: string): object

**Parameters**

- **value** (object)  
- **name** (string)  

**Returns** object

---

**GetValueFromClass**(**value**: object, **name**: string, **isColumnsRetrieve**: bool): object

**Parameters**

- **value** (object)  
- **name** (string)  
- **isColumnsRetrieve** (bool)  

**Returns** object


---

#### GetValueFromDataRow `static`

**GetValueFromDataRow**(**dataRow**: DataRow, **name**: string): object

**Parameters**

- **dataRow** (DataRow)  
- **name** (string)  

**Returns** object


---

#### GetValueFromDataSet `static`

**GetValueFromDataSet**(**dataSet**: DataSet, **name**: string): object

**Parameters**

- **dataSet** (DataSet)  
- **name** (string)  

**Returns** object


---

#### GetValueFromDataTable `static`

**GetValueFromDataTable**(**dataTable**: DataTable, **name**: string): object

**Parameters**

- **dataTable** (DataTable)  
- **name** (string)  

**Returns** object


---

#### GetValueFromDictionaryEntry `static`

**GetValueFromDictionaryEntry**(**entry**: DictionaryEntry, **name**: string): object

**Parameters**

- **entry** (DictionaryEntry)  
- **name** (string)  

**Returns** object


---

#### GetValueFromICustomTypeDescriptor `static`

**GetValueFromICustomTypeDescriptor**(**customTypeDescriptor**: ICustomTypeDescriptor, **name**: string): object

**Parameters**

- **customTypeDescriptor** (ICustomTypeDescriptor)  
- **name** (string)  

**Returns** object


---

#### GetValueFromITypedList `static`

**GetValueFromITypedList**(**typedList**: ITypedList, **name**: string): object

**Parameters**

- **typedList** (ITypedList)  
- **name** (string)  

**Returns** object

---

**GetValueFromITypedList**(**typedList**: ITypedList, **name**: string, **value**: object): object

**Parameters**

- **typedList** (ITypedList)  
- **name** (string)  
- **value** (object)  

**Returns** object


---

#### GetValueFromKeyValuePair `static`

**GetValueFromKeyValuePair**(**item**: object, **name**: string): object

**Parameters**

- **item** (object)  
- **name** (string)  

**Returns** object


---

#### GetValueFromObject `static`

**GetValueFromObject**(**value**: object, **name**: string): object

**Parameters**

- **value** (object)  
- **name** (string)  

**Returns** object

---

**GetValueFromObject**(**value**: object, **name**: string, **isColumnsRetrieve**: bool): object

**Parameters**

- **value** (object)  
- **name** (string)  
- **isColumnsRetrieve** (bool)  

**Returns** object


---

#### IsDataColumn `static`

**IsDataColumn**(**type**: Type): bool

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### IsTypeImplementICollection `static`

**IsTypeImplementICollection**(**type**: Type): bool

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### IsValueExistInClass `static`

**IsValueExistInClass**(**value**: object, **name**: string): bool

**Parameters**

- **value** (object)  
- **name** (string)  

**Returns** bool

