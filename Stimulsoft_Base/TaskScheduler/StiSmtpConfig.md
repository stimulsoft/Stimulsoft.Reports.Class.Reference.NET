---
title: "StiSmtpConfig Class"
---

## StiSmtpConfig Class

**Namespace:** `Stimulsoft.Base.TaskScheduler`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EnableSsl** | bool | Encrypt or not the connections to the SMTP server with help of the Secure Sockets Layer protocol. |
| **Host** | string |  |
| **Password** | string | The password for the user name associated with the credentials. |
| **Port** | int | Port used for SMTP transactions. |
| **SenderEmail** | string | The Email of the Server Email agent. |
| **UserName** | string | The user name associated with the credentials. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiSmtpConfig](StiSmtpConfig.md) |  |
| **GetEmpty** `static` | [StiSmtpConfig](StiSmtpConfig.md) |  |
| **IsValid** | bool |  |
| **TrySave** | void |  |

---

### Method Details

#### Get `static`

**Get**(): [StiSmtpConfig](StiSmtpConfig.md)

**Returns** [StiSmtpConfig](StiSmtpConfig.md)


---

#### GetEmpty `static`

**GetEmpty**(): [StiSmtpConfig](StiSmtpConfig.md)

**Returns** [StiSmtpConfig](StiSmtpConfig.md)


---

#### IsValid

**IsValid**(): bool

**Returns** bool


---

#### TrySave

**TrySave**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Timeout** | int | Value that specifies the amount of time after which a synchronous System.Net.Mail.SmtpClient.SendEmail call times out. |
