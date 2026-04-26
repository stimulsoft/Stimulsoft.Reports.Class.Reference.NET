---
title: "StiAIAssistantCreator Class"
---

## StiAIAssistantCreator Class

**Namespace:** `Stimulsoft.Base.StimulAI`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseAI** `static` | void |  |
| **GetBlocklySession** `static` | [IStiBlocklyAIChatSession](IStiBlocklyAIChatSession.md) |  |
| **GetCalcColumnExpressionSession** `static` | [IStiTypedExpressionAIChatSession](IStiTypedExpressionAIChatSession.md) |  |
| **GetDataExceptionSession** `static` | [IStiDataExceptionSession](IStiDataExceptionSession.md) |  |
| **GetDatabaseQuerySession** `static` | [IStiDatabaseQueryAIChatSession](IStiDatabaseQueryAIChatSession.md) |  |
| **GetEventScriptSession** `static` | [IStiEventScriptAIChatSession](IStiEventScriptAIChatSession.md) |  |
| **GetGenerateOneTableDataExampleSession** `static` | [IStiGenerateOneTableDataExampleSession](IStiGenerateOneTableDataExampleSession.md) |  |
| **GetGlobalizationChatSession** `static` | [IStiGlobalizationSession](IStiGlobalizationSession.md) |  |
| **GetIntTextAndExpressionSession** `static` | [IStiIntTextAndExpressionAIChatSession](IStiIntTextAndExpressionAIChatSession.md) |  |
| **GetOnlyExpressionSession** `static` | [IStiOnlyExpressionAIChatSession](IStiOnlyExpressionAIChatSession.md) |  |
| **GetReportEditingSession** `static` | [IStiReportEditingSession](IStiReportEditingSession.md) |  |
| **GetSqlConnectionSession** `static` | [IStiSqlConnectionAIChatSession](IStiSqlConnectionAIChatSession.md) |  |
| **GetTextAndExpressionSession** `static` | [IStiTextAndExpressionAIChatSession](IStiTextAndExpressionAIChatSession.md) |  |
| **GetTextFormatAIChatSession** `static` | [IStiTextFormatAIChatSession](IStiTextFormatAIChatSession.md) |  |
| **GetUserFunctionSession** `static` | [IStiUserFunctionSession](IStiUserFunctionSession.md) |  |
| **IsAIChatEnabled** `static` | bool |  |
| **ShowAI** `static` | void |  |

---

### Method Details

#### CloseAI `static`

**CloseAI**(): void


---

#### GetBlocklySession `static`

**GetBlocklySession**(**editor**: [IStiBlocklyEditorStimulAI](IStiBlocklyEditorStimulAI.md)): [IStiBlocklyAIChatSession](IStiBlocklyAIChatSession.md)

**Parameters**

- **editor** ([IStiBlocklyEditorStimulAI](IStiBlocklyEditorStimulAI.md))  

**Returns** [IStiBlocklyAIChatSession](IStiBlocklyAIChatSession.md)


---

#### GetCalcColumnExpressionSession `static`

**GetCalcColumnExpressionSession**(**editor**: [IStiTypedExpressionEditorStimulAI](IStiTypedExpressionEditorStimulAI.md)): [IStiTypedExpressionAIChatSession](IStiTypedExpressionAIChatSession.md)

**Parameters**

- **editor** ([IStiTypedExpressionEditorStimulAI](IStiTypedExpressionEditorStimulAI.md))  

**Returns** [IStiTypedExpressionAIChatSession](IStiTypedExpressionAIChatSession.md)


---

#### GetDataExceptionSession `static`

**GetDataExceptionSession**(): [IStiDataExceptionSession](IStiDataExceptionSession.md)

**Returns** [IStiDataExceptionSession](IStiDataExceptionSession.md)


---

#### GetDatabaseQuerySession `static`

**GetDatabaseQuerySession**(**editor**: [IStiDatabaseQueryEditorStimulAI](IStiDatabaseQueryEditorStimulAI.md)): [IStiDatabaseQueryAIChatSession](IStiDatabaseQueryAIChatSession.md)

**Parameters**

- **editor** ([IStiDatabaseQueryEditorStimulAI](IStiDatabaseQueryEditorStimulAI.md))  

**Returns** [IStiDatabaseQueryAIChatSession](IStiDatabaseQueryAIChatSession.md)


---

#### GetEventScriptSession `static`

**GetEventScriptSession**(**editor**: [IStiEventScriptEditorStimulAI](IStiEventScriptEditorStimulAI.md)): [IStiEventScriptAIChatSession](IStiEventScriptAIChatSession.md)

**Parameters**

- **editor** ([IStiEventScriptEditorStimulAI](IStiEventScriptEditorStimulAI.md))  

**Returns** [IStiEventScriptAIChatSession](IStiEventScriptAIChatSession.md)


---

#### GetGenerateOneTableDataExampleSession `static`

**GetGenerateOneTableDataExampleSession**(**showCreateDataManually**: bool): [IStiGenerateOneTableDataExampleSession](IStiGenerateOneTableDataExampleSession.md)

**Parameters**

- **showCreateDataManually** (bool)  

**Returns** [IStiGenerateOneTableDataExampleSession](IStiGenerateOneTableDataExampleSession.md)


---

#### GetGlobalizationChatSession `static`

**GetGlobalizationChatSession**(): [IStiGlobalizationSession](IStiGlobalizationSession.md)

**Returns** [IStiGlobalizationSession](IStiGlobalizationSession.md)


---

#### GetIntTextAndExpressionSession `static`

**GetIntTextAndExpressionSession**(**editor**: [IStiIntTextAndExpressionEditorStimulAI](IStiIntTextAndExpressionEditorStimulAI.md)): [IStiIntTextAndExpressionAIChatSession](IStiIntTextAndExpressionAIChatSession.md)

**Parameters**

- **editor** ([IStiIntTextAndExpressionEditorStimulAI](IStiIntTextAndExpressionEditorStimulAI.md))  

**Returns** [IStiIntTextAndExpressionAIChatSession](IStiIntTextAndExpressionAIChatSession.md)


---

#### GetOnlyExpressionSession `static`

**GetOnlyExpressionSession**(**editor**: [IStiOnlyExpressionEditorStimulAI](IStiOnlyExpressionEditorStimulAI.md)): [IStiOnlyExpressionAIChatSession](IStiOnlyExpressionAIChatSession.md)

**Parameters**

- **editor** ([IStiOnlyExpressionEditorStimulAI](IStiOnlyExpressionEditorStimulAI.md))  

**Returns** [IStiOnlyExpressionAIChatSession](IStiOnlyExpressionAIChatSession.md)


---

#### GetReportEditingSession `static`

**GetReportEditingSession**(**designer**: object): [IStiReportEditingSession](IStiReportEditingSession.md)

**Parameters**

- **designer** (object)  

**Returns** [IStiReportEditingSession](IStiReportEditingSession.md)


---

#### GetSqlConnectionSession `static`

**GetSqlConnectionSession**(**editor**: [IStiSqlConnectionEditorStimulAI](IStiSqlConnectionEditorStimulAI.md)): [IStiSqlConnectionAIChatSession](IStiSqlConnectionAIChatSession.md)

**Parameters**

- **editor** ([IStiSqlConnectionEditorStimulAI](IStiSqlConnectionEditorStimulAI.md))  

**Returns** [IStiSqlConnectionAIChatSession](IStiSqlConnectionAIChatSession.md)


---

#### GetTextAndExpressionSession `static`

**GetTextAndExpressionSession**(**editor**: [IStiTextAndExpressionEditorStimulAI](IStiTextAndExpressionEditorStimulAI.md)): [IStiTextAndExpressionAIChatSession](IStiTextAndExpressionAIChatSession.md)

**Parameters**

- **editor** ([IStiTextAndExpressionEditorStimulAI](IStiTextAndExpressionEditorStimulAI.md))  

**Returns** [IStiTextAndExpressionAIChatSession](IStiTextAndExpressionAIChatSession.md)


---

#### GetTextFormatAIChatSession `static`

**GetTextFormatAIChatSession**(**editor**: [IStiTextFormatEditorStimulAI](IStiTextFormatEditorStimulAI.md)): [IStiTextFormatAIChatSession](IStiTextFormatAIChatSession.md)

**Parameters**

- **editor** ([IStiTextFormatEditorStimulAI](IStiTextFormatEditorStimulAI.md))  

**Returns** [IStiTextFormatAIChatSession](IStiTextFormatAIChatSession.md)


---

#### GetUserFunctionSession `static`

**GetUserFunctionSession**(**editor**: [IStiUserFunctionEditorStimulAI](IStiUserFunctionEditorStimulAI.md)): [IStiUserFunctionSession](IStiUserFunctionSession.md)

**Parameters**

- **editor** ([IStiUserFunctionEditorStimulAI](IStiUserFunctionEditorStimulAI.md))  

**Returns** [IStiUserFunctionSession](IStiUserFunctionSession.md)


---

#### IsAIChatEnabled `static`

**IsAIChatEnabled**(): bool

**Returns** bool


---

#### ShowAI `static`

**ShowAI**(**session**: [IStiAIChatSession](IStiAIChatSession.md), **window**: IWin32Window): void

**Parameters**

- **session** ([IStiAIChatSession](IStiAIChatSession.md))  
- **window** (IWin32Window)  

