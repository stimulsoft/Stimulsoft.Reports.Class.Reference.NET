---
title: "StiPdfSecurity Class"
---

## StiPdfSecurity Class

**Namespace:** `Stimulsoft.Report.Export.Tools`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPdfSecurity
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfSecurity**([StiPdfExportService](../StiPdfExportService.md) service) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ComputingCryptoValues** | bool |  |
| **CreateSignature** | byte[] |  |
| **EncryptData** | byte[] |  |
| **GetCertificateThumbprintFromCryptoUI** `static` | string |  |
| **GetCertificatesList** `static` | List<StiCertificateInfo> |  |
| **MakeSignedByString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CERT_CLOSE_STORE_CHECK_FLAG** | uint |  |
| **CERT_FIND_SUBJECT_NAME** | uint |  |
| **CERT_FIND_SUBJECT_STR** | uint |  |
| **CERT_STORE_PROV_SYSTEM** | int |  |
| **CERT_STORE_READONLY_FLAG** | uint |  |
| **CERT_SYSTEM_STORE_CURRENT_USER** | uint |  |
| **CERT_SYSTEM_STORE_LOCAL_MACHINE** | uint |  |
| **CRYPTUI_SELECT_EXPIRATION_COLUMN** | uint |  |
| **CRYPTUI_SELECT_FRIENDLYNAME_COLUMN** | uint |  |
| **CRYPTUI_SELECT_INTENDEDUSE_COLUMN** | uint |  |
| **CRYPTUI_SELECT_ISSUEDBY_COLUMN** | uint |  |
| **CRYPTUI_SELECT_ISSUEDTO_COLUMN** | uint |  |
| **CRYPTUI_SELECT_LOCATION_COLUMN** | uint |  |
| **PKCS_7_ASN_ENCODING** | uint |  |
| **X509_ASN_ENCODING** | uint |  |
| **szOID_CP_GOST_R3411** | string |  |
| **szOID_CP_GOST_R3411_12_256** | string |  |
| **szOID_CP_GOST_R3411_12_256_R3410** | string |  |
| **szOID_CP_GOST_R3411_12_512** | string |  |
| **szOID_CP_GOST_R3411_12_512_R3410** | string |  |
| **szOID_CP_GOST_R3411_R3410** | string |  |
| **szOID_CP_GOST_R3411_R3410EL** | string |  |
| **szOID_RSA_SHA1RSA** | string |  |
| **szOID_sha256NoSign** | string |  |
