---
title: "StiFunctionsMath Class"
---

## StiFunctionsMath Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Ceiling** `static` *(+3 overloads)* | decimal | Returns the smallest integer greater than or equal to the specified decimal number. |
| **Clamp** `static` *(+2 overloads)* | double | Clamps a double-precision floating-point value to a specified range. |
| **Div** `static` *(+11 overloads)* | long | Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0. |
| **Frac** `static` *(+1 overloads)* | decimal | Returns the fractional part of the specified decimal number. |
| **Maximum** `static` *(+5 overloads)* | decimal |  |
| **Minimum** `static` *(+5 overloads)* | decimal |  |
| **Round** `static` *(+15 overloads)* | double | Returns result of rounding. |

---

### Method Details

#### Ceiling `static`

**Ceiling**(**value**: decimal): decimal

Returns the smallest integer greater than or equal to the specified decimal number.

**Parameters**

- **value** (decimal) — A decimal number.  

**Returns** decimal — The smallest integer greater than or equal to value.

---

**Ceiling**(**value**: double): double

Returns the smallest integer greater than or equal to the specified double-precision floating-point number.

**Parameters**

- **value** (double) — A double-precision floating-point number.  

**Returns** double — The smallest integer greater than or equal to value.

---

**Ceiling**(**value**: decimal?): decimal?

Returns the smallest integer greater than or equal to the specified decimal number.

**Parameters**

- **value** (decimal?) — A nullable decimal number.  

**Returns** decimal? — The smallest integer greater than or equal to value or null if value is null.

---

**Ceiling**(**value**: double?): double?

Returns the smallest integer greater than or equal to the specified double-precision floating-point number.

**Parameters**

- **value** (double?) — A nullable double-precision floating-point number.  

**Returns** double? — The smallest integer greater than or equal to value or null if value is null.


---

#### Clamp `static`

**Clamp**(**value**: double, **min**: double, **max**: double): double

Clamps a double-precision floating-point value to a specified range.

**Parameters**

- **value** (double) — The value to clamp.  
- **min** (double) — The minimum value of the range.  
- **max** (double) — The maximum value of the range.  

**Returns** double — The clamped value. If the value is less than the minimum, the minimum is returned. If the value is greater than the maximum, the maximum is returned. Otherwise, the original value is returned.

---

**Clamp**(**value**: decimal, **min**: decimal, **max**: decimal): decimal

Clamps a decimal value to a specified range.

**Parameters**

- **value** (decimal) — The value to clamp.  
- **min** (decimal) — The minimum value of the range.  
- **max** (decimal) — The maximum value of the range.  

**Returns** decimal — The clamped value. If the value is less than the minimum, the minimum is returned. If the value is greater than the maximum, the maximum is returned. Otherwise, the original value is returned.

---

**Clamp**(**value**: long, **min**: long, **max**: long): long

Clamps a long value to a specified range.

**Parameters**

- **value** (long) — The value to clamp.  
- **min** (long) — The minimum value of the range.  
- **max** (long) — The maximum value of the range.  

**Returns** long — The clamped value. If the value is less than the minimum, the minimum is returned. If the value is greater than the maximum, the maximum is returned. Otherwise, the original value is returned.


---

#### Div `static`

**Div**(**value1**: long, **value2**: long): long

Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0.

**Parameters**

- **value1** (long)  
- **value2** (long)  

**Returns** long

---

**Div**(**value1**: long, **value2**: long, **zeroResult**: long): long

Returns result of dividing value1 and value2. If value2 is zero, then result is zeroResult (third argument).

**Parameters**

- **value1** (long)  
- **value2** (long)  
- **zeroResult** (long)  

**Returns** long

---

**Div**(**value1**: double, **value2**: double): double

Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0.

**Parameters**

- **value1** (double)  
- **value2** (double)  

**Returns** double

---

**Div**(**value1**: double, **value2**: double, **zeroResult**: double): double

Returns result of dividing value1 and value2. If value2 is zero, then result is zeroResult (third argument).

**Parameters**

- **value1** (double)  
- **value2** (double)  
- **zeroResult** (double)  

**Returns** double

---

**Div**(**value1**: decimal, **value2**: decimal): decimal

Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0.

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  

**Returns** decimal

---

**Div**(**value1**: decimal, **value2**: decimal, **zeroResult**: decimal): decimal

Returns result of dividing value1 and value2. If value2 is zero, then result is zeroResult (third argument).

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  
- **zeroResult** (decimal)  

**Returns** decimal

---

**Div**(**value1**: long?, **value2**: long?): long?

Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0.

**Parameters**

- **value1** (long?)  
- **value2** (long?)  

**Returns** long?

---

**Div**(**value1**: long?, **value2**: long?, **zeroResult**: long?): long?

Returns result of dividing value1 and value2. If value2 is zero, then result is zeroResult (third argument).

**Parameters**

- **value1** (long?)  
- **value2** (long?)  
- **zeroResult** (long?)  

**Returns** long?

---

**Div**(**value1**: double?, **value2**: double?): double?

Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0.

**Parameters**

- **value1** (double?)  
- **value2** (double?)  

**Returns** double?

---

**Div**(**value1**: double?, **value2**: double?, **zeroResult**: double?): double?

Returns result of dividing value1 and value2. If value2 is zero, then result is zeroResult (third argument).

**Parameters**

- **value1** (double?)  
- **value2** (double?)  
- **zeroResult** (double?)  

**Returns** double?

---

**Div**(**value1**: decimal?, **value2**: decimal?): decimal?

Returns result of dividing value1 and value2. If value2 is zero, then result equal to 0.

**Parameters**

- **value1** (decimal?)  
- **value2** (decimal?)  

**Returns** decimal?

---

**Div**(**value1**: decimal?, **value2**: decimal?, **zeroResult**: decimal?): decimal?

Returns result of dividing value1 and value2. If value2 is zero, then result is zeroResult (third argument).

**Parameters**

- **value1** (decimal?)  
- **value2** (decimal?)  
- **zeroResult** (decimal?)  

**Returns** decimal?


---

#### Frac `static`

**Frac**(**value**: decimal): decimal

Returns the fractional part of the specified decimal number.

**Parameters**

- **value** (decimal) — A decimal number.  

**Returns** decimal — The fractional part of the specified decimal number.

---

**Frac**(**value**: double): double

Returns the fractional part of the specified double-precision floating-point number.

**Parameters**

- **value** (double) — A double-precision floating-point number.  

**Returns** double — The fractional part of the specified double-precision floating-point number.


---

#### Maximum `static`

**Maximum**(**value1**: decimal, **value2**: decimal): decimal

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  

**Returns** decimal

---

**Maximum**(**value1**: decimal?, **value2**: decimal?): decimal?

**Parameters**

- **value1** (decimal?)  
- **value2** (decimal?)  

**Returns** decimal?

---

**Maximum**(**value1**: double, **value2**: double): double

**Parameters**

- **value1** (double)  
- **value2** (double)  

**Returns** double

---

**Maximum**(**value1**: double?, **value2**: double?): double?

**Parameters**

- **value1** (double?)  
- **value2** (double?)  

**Returns** double?

---

**Maximum**(**value1**: long, **value2**: long): long

**Parameters**

- **value1** (long)  
- **value2** (long)  

**Returns** long

---

**Maximum**(**value1**: long?, **value2**: long?): long?

**Parameters**

- **value1** (long?)  
- **value2** (long?)  

**Returns** long?


---

#### Minimum `static`

**Minimum**(**value1**: decimal, **value2**: decimal): decimal

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  

**Returns** decimal

---

**Minimum**(**value1**: decimal?, **value2**: decimal?): decimal?

**Parameters**

- **value1** (decimal?)  
- **value2** (decimal?)  

**Returns** decimal?

---

**Minimum**(**value1**: double, **value2**: double): double

**Parameters**

- **value1** (double)  
- **value2** (double)  

**Returns** double

---

**Minimum**(**value1**: double?, **value2**: double?): double?

**Parameters**

- **value1** (double?)  
- **value2** (double?)  

**Returns** double?

---

**Minimum**(**value1**: long, **value2**: long): long

**Parameters**

- **value1** (long)  
- **value2** (long)  

**Returns** long

---

**Minimum**(**value1**: long?, **value2**: long?): long?

**Parameters**

- **value1** (long?)  
- **value2** (long?)  

**Returns** long?


---

#### Round `static`

**Round**(**value**: double): double

Returns result of rounding.

**Parameters**

- **value** (double)  

**Returns** double

---

**Round**(**value**: decimal): decimal

**Parameters**

- **value** (decimal)  

**Returns** decimal

---

**Round**(**value**: double, **decimals**: int): double

**Parameters**

- **value** (double)  
- **decimals** (int)  

**Returns** double

---

**Round**(**value**: decimal, **decimals**: int): decimal

**Parameters**

- **value** (decimal)  
- **decimals** (int)  

**Returns** decimal

---

**Round**(**value**: double, **midpointRounding**: MidpointRounding): double

**Parameters**

- **value** (double)  
- **midpointRounding** (MidpointRounding)  

**Returns** double

---

**Round**(**value**: decimal, **midpointRounding**: MidpointRounding): decimal

**Parameters**

- **value** (decimal)  
- **midpointRounding** (MidpointRounding)  

**Returns** decimal

---

**Round**(**value**: double, **decimals**: int, **midpointRounding**: MidpointRounding): double

**Parameters**

- **value** (double)  
- **decimals** (int)  
- **midpointRounding** (MidpointRounding)  

**Returns** double

---

**Round**(**value**: decimal, **decimals**: int, **midpointRounding**: MidpointRounding): decimal

**Parameters**

- **value** (decimal)  
- **decimals** (int)  
- **midpointRounding** (MidpointRounding)  

**Returns** decimal

---

**Round**(**value**: double?): double?

**Parameters**

- **value** (double?)  

**Returns** double?

---

**Round**(**value**: decimal?): decimal?

**Parameters**

- **value** (decimal?)  

**Returns** decimal?

---

**Round**(**value**: double?, **decimals**: int): double?

**Parameters**

- **value** (double?)  
- **decimals** (int)  

**Returns** double?

---

**Round**(**value**: decimal?, **decimals**: int): decimal?

**Parameters**

- **value** (decimal?)  
- **decimals** (int)  

**Returns** decimal?

---

**Round**(**value**: double?, **midpointRounding**: MidpointRounding): double?

**Parameters**

- **value** (double?)  
- **midpointRounding** (MidpointRounding)  

**Returns** double?

---

**Round**(**value**: decimal?, **midpointRounding**: MidpointRounding): decimal?

**Parameters**

- **value** (decimal?)  
- **midpointRounding** (MidpointRounding)  

**Returns** decimal?

---

**Round**(**value**: double?, **decimals**: int, **midpointRounding**: MidpointRounding): double?

**Parameters**

- **value** (double?)  
- **decimals** (int)  
- **midpointRounding** (MidpointRounding)  

**Returns** double?

---

**Round**(**value**: decimal?, **decimals**: int, **midpointRounding**: MidpointRounding): decimal?

**Parameters**

- **value** (decimal?)  
- **decimals** (int)  
- **midpointRounding** (MidpointRounding)  

**Returns** decimal?

