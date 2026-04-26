---
title: "StiExpressionHelper Class"
---

## StiExpressionHelper Class

**Namespace:** `Stimulsoft.Data.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Compile** `static` | [LogicalExpression](../Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **EscapeExpression** `static` | string |  |
| **FetchBlocksFromExpression** `static` | List<string> |  |
| **GetArguments** `static` | List<string> |  |
| **GetFirstArgumentFromExpression** `static` | string |  |
| **GetFunction** `static` | string |  |
| **IsAggregationFunctionPresent** `static` | bool |  |
| **IsExpression** `static` | bool |  |
| **IsFunctionPresent** `static` | bool |  |
| **IsPercentOfGrandTotal** `static` | bool |  |
| **IsThisExpression** `static` | bool |  |
| **IsTimeExpression** `static` | bool |  |
| **NewExpression** `static` | [Expression](../Expressions/NCalc/Expression.md) |  |
| **ParseReportExpression** `static` | string |  |
| **PrepareExpression** `static` | string |  |
| **RemoveFunction** `static` | string |  |
| **RemoveRelations** `static` | string |  |
| **ReplaceExpressionBlocksByValues** `static` | string |  |
| **ReplaceFunction** `static` | string |  |
| **Visit** *(+6 overloads)* | void |  |

---

### Method Details

#### Compile `static`

**Compile**(**expression**: string): [LogicalExpression](../Expressions/NCalc/Domain/LogicalExpression.md)

**Parameters**

- **expression** (string)  

**Returns** [LogicalExpression](../Expressions/NCalc/Domain/LogicalExpression.md)


---

#### EscapeExpression `static`

**EscapeExpression**(**expression**: string): string

**Parameters**

- **expression** (string)  

**Returns** string


---

#### FetchBlocksFromExpression `static`

**FetchBlocksFromExpression**(**inputExpression**: string): List<string>

**Parameters**

- **inputExpression** (string)  

**Returns** List<string>


---

#### GetArguments `static`

**GetArguments**(**expression**: string): List<string>

**Parameters**

- **expression** (string)  

**Returns** List<string>


---

#### GetFirstArgumentFromExpression `static`

**GetFirstArgumentFromExpression**(**expression**: string): string

**Parameters**

- **expression** (string)  

**Returns** string


---

#### GetFunction `static`

**GetFunction**(**expression**: string): string

**Parameters**

- **expression** (string)  

**Returns** string


---

#### IsAggregationFunctionPresent `static`

**IsAggregationFunctionPresent**(**expression**: string): bool

**Parameters**

- **expression** (string)  

**Returns** bool


---

#### IsExpression `static`

**IsExpression**(**str**: string): bool

**Parameters**

- **str** (string)  

**Returns** bool


---

#### IsFunctionPresent `static`

**IsFunctionPresent**(**expression**: string): bool

**Parameters**

- **expression** (string)  

**Returns** bool


---

#### IsPercentOfGrandTotal `static`

**IsPercentOfGrandTotal**(**expression**: string): bool

**Parameters**

- **expression** (string)  

**Returns** bool


---

#### IsThisExpression `static`

**IsThisExpression**(**str**: string): bool

**Parameters**

- **str** (string)  

**Returns** bool


---

#### IsTimeExpression `static`

**IsTimeExpression**(**str**: string): bool

**Parameters**

- **str** (string)  

**Returns** bool


---

#### NewExpression `static`

**NewExpression**(**expression**: string): [Expression](../Expressions/NCalc/Expression.md)

**Parameters**

- **expression** (string)  

**Returns** [Expression](../Expressions/NCalc/Expression.md)


---

#### ParseReportExpression `static`

**ParseReportExpression**(**report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **text**: string, **withBraces**: bool, **allowReturnNull**: bool): string

**Parameters**

- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **text** (string)  
- **withBraces** (bool)  
- **allowReturnNull** (bool)  

**Returns** string


---

#### PrepareExpression `static`

**PrepareExpression**(**expression**: string): string

**Parameters**

- **expression** (string)  

**Returns** string


---

#### RemoveFunction `static`

**RemoveFunction**(**expression**: string): string

**Parameters**

- **expression** (string)  

**Returns** string


---

#### RemoveRelations `static`

**RemoveRelations**(**expression**: string, **dataSources**: IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>): string

**Parameters**

- **expression** (string)  
- **dataSources** (IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>)  

**Returns** string


---

#### ReplaceExpressionBlocksByValues `static`

**ReplaceExpressionBlocksByValues**(**inputExpression**: string, **values**: List<string>): string

**Parameters**

- **inputExpression** (string)  
- **values** (List<string>)  

**Returns** string


---

#### ReplaceFunction `static`

**ReplaceFunction**(**expression**: string, **newFunction**: string): string

**Parameters**

- **expression** (string)  
- **newFunction** (string)  

**Returns** string


---

#### Visit

**Visit**(**function**: [Identifier](../Expressions/NCalc/Domain/Identifier.md)): void

**Parameters**

- **function** ([Identifier](../Expressions/NCalc/Domain/Identifier.md))  

---

**Visit**(**expression**: [UnaryExpression](../Expressions/NCalc/Domain/UnaryExpression.md)): void

**Parameters**

- **expression** ([UnaryExpression](../Expressions/NCalc/Domain/UnaryExpression.md))  

---

**Visit**(**expression**: [BinaryExpression](../Expressions/NCalc/Domain/BinaryExpression.md)): void

**Parameters**

- **expression** ([BinaryExpression](../Expressions/NCalc/Domain/BinaryExpression.md))  

---

**Visit**(**expression**: [TernaryExpression](../Expressions/NCalc/Domain/TernaryExpression.md)): void

**Parameters**

- **expression** ([TernaryExpression](../Expressions/NCalc/Domain/TernaryExpression.md))  

---

**Visit**(**function**: [Function](../Expressions/NCalc/Domain/Function.md)): void

**Parameters**

- **function** ([Function](../Expressions/NCalc/Domain/Function.md))  

---

**Visit**(**expression**: [LogicalExpression](../Expressions/NCalc/Domain/LogicalExpression.md)): void

**Parameters**

- **expression** ([LogicalExpression](../Expressions/NCalc/Domain/LogicalExpression.md))  

---

**Visit**(**expression**: [ValueExpression](../Expressions/NCalc/Domain/ValueExpression.md)): void

**Parameters**

- **expression** ([ValueExpression](../Expressions/NCalc/Domain/ValueExpression.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Parameters** | HashSet<string> |  |
