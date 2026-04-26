---
title: "StiLexer Class"
---

## StiLexer Class

**Namespace:** `Stimulsoft.Base`

Performs the lexical analysis.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLexer**(string textValue) | Creates a new instance of the StiLexer class. |

**StiLexer**(**textValue**: string)

Creates a new instance of the StiLexer class.

**Parameters**

- **textValue** (string) — The Text for lexical analysis.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsVB** | bool |  |
| **PositionInText** | int | Gets or sets current position in text. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAllTokens** `static` | List<[StiToken](StiToken.md)> |  |
| **GetPosition** | [StiPosition](StiPosition.md) | Gets position of token in text. |
| **GetToken** | [StiToken](StiToken.md) | Gets next token. |
| **IdentExists** `static` | bool |  |
| **ReplaceWithNotEqualPrefix** | void | Replaces all occurrences of a specified String, with another specified string. Before oldValue must not follow specified prefix - string. |
| **ReplaceWithPrefix** `static` *(+1 overloads)* | string | Replaces all occurrences of a specified String, with another specified String. Before oldValue must follow specified prefix - token. Replacing is produced with provision for tokens. |
| **Reset** | void | Reset state. |
| **SavePosToken** | void | Saves position of token in text. |
| **ScanChar** | [StiToken](StiToken.md) | Scans the symbol. |
| **ScanIdent** | [StiToken](StiToken.md) | Scans the identifier. |
| **ScanInterpolatedString** | [StiToken](StiToken.md) | Scans an interpolated string, which begins with $" and can contain expressions in { }. |
| **ScanNumber** | [StiToken](StiToken.md) | Scans the number. |
| **ScanString** | [StiToken](StiToken.md) | Scans the string. |
| **SkipWhitespaceAndComments** | void | Skips all whitespace and comments (both single-line and multi-line). |
| **UngetToken** | void | Returns to previous token. |
| **WaitAssign2** | bool | Wait the assign. |
| **WaitComma2** | bool | Wait the right bracket. |
| **WaitLbrace2** | bool | Wait the left brace. |
| **WaitLparen2** | bool | Wait the left paren. |
| **WaitRbrace2** | bool | Wait the right brace. |
| **WaitRparen2** | bool | Wait the right paren. |
| **WaitSemicolon2** | bool | Wait the semicolon. |

---

### Method Details

#### GetAllTokens `static`

**GetAllTokens**(**str**: string): List<[StiToken](StiToken.md)>

**Parameters**

- **str** (string)  

**Returns** List<[StiToken](StiToken.md)>


---

#### GetPosition

**GetPosition**(**positionInText**: int): [StiPosition](StiPosition.md)

Gets position of token in text.

**Parameters**

- **positionInText** (int) — Position in text.  

**Returns** [StiPosition](StiPosition.md) — Position of token in text.


---

#### GetToken

**GetToken**(): [StiToken](StiToken.md)

Gets next token.

**Returns** [StiToken](StiToken.md) — Next token.


---

#### IdentExists `static`

**IdentExists**(**str**: string, **name**: string, **caseSensitive**: bool): bool

**Parameters**

- **str** (string)  
- **name** (string)  
- **caseSensitive** (bool)  

**Returns** bool


---

#### ReplaceWithNotEqualPrefix

**ReplaceWithNotEqualPrefix**(**prefix**: [StiTokenType](StiTokenType.md), **oldValue**: string, **newValue**: string): void

Replaces all occurrences of a specified String, with another specified string. Before oldValue must not follow specified prefix - string.

**Parameters**

- **prefix** ([StiTokenType](StiTokenType.md)) — Prefix - string.  
- **oldValue** (string) — A String to be replaced.  
- **newValue** (string) — A String to replace all occurrences of oldValue.  


---

#### ReplaceWithPrefix `static`

**ReplaceWithPrefix**(**textValue**: string, **prefix**: string, **oldValue**: string, **newValue**: string): string

Replaces all occurrences of a specified String, with another specified String. Before oldValue must follow specified prefix - token. Replacing is produced with provision for tokens.

**Parameters**

- **textValue** (string) — Text for replace.  
- **prefix** (string) — Prefix - token.  
- **oldValue** (string) — A String to be replaced.  
- **newValue** (string) — A String to replace all occurrences of oldValue.  

**Returns** string — Replaced string.

---

**ReplaceWithPrefix**(**prefix**: string, **oldValue**: string, **newValue**: string): void

Replaces all occurrences of a specified String, with another specified string. Before oldValue must follow specified prefix - string. Replacing is produced with provision for tokens.

**Parameters**

- **prefix** (string) — Prefix - string.  
- **oldValue** (string) — A String to be replaced.  
- **newValue** (string) — A String to replace all occurrences of oldValue.  


---

#### Reset

**Reset**(): void

Reset state.


---

#### SavePosToken

**SavePosToken**(): void

Saves position of token in text.


---

#### ScanChar

**ScanChar**(): [StiToken](StiToken.md)

Scans the symbol.

**Returns** [StiToken](StiToken.md) — Token containing symbol.


---

#### ScanIdent

**ScanIdent**(): [StiToken](StiToken.md)

Scans the identifier.

**Returns** [StiToken](StiToken.md) — Token containing identifier.


---

#### ScanInterpolatedString

**ScanInterpolatedString**(): [StiToken](StiToken.md)

Scans an interpolated string, which begins with $" and can contain expressions in { }.

**Returns** [StiToken](StiToken.md) — Token containing the interpolated string content.


---

#### ScanNumber

**ScanNumber**(): [StiToken](StiToken.md)

Scans the number.

**Returns** [StiToken](StiToken.md) — Token containing number.


---

#### ScanString

**ScanString**(): [StiToken](StiToken.md)

Scans the string.

**Returns** [StiToken](StiToken.md) — Token containing string.


---

#### SkipWhitespaceAndComments

**SkipWhitespaceAndComments**(): void

Skips all whitespace and comments (both single-line and multi-line).


---

#### UngetToken

**UngetToken**(): void

Returns to previous token.


---

#### WaitAssign2

**WaitAssign2**(): bool

Wait the assign.

**Returns** bool


---

#### WaitComma2

**WaitComma2**(): bool

Wait the right bracket.

**Returns** bool


---

#### WaitLbrace2

**WaitLbrace2**(): bool

Wait the left brace.

**Returns** bool


---

#### WaitLparen2

**WaitLparen2**(): bool

Wait the left paren.

**Returns** bool


---

#### WaitRbrace2

**WaitRbrace2**(): bool

Wait the right brace.

**Returns** bool


---

#### WaitRparen2

**WaitRparen2**(): bool

Wait the right paren.

**Returns** bool


---

#### WaitSemicolon2

**WaitSemicolon2**(): bool

Wait the semicolon.

**Returns** bool

