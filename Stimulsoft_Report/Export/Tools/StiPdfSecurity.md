---
title: "StiPdfSecurity Class"
---

## StiPdfSecurity Class

**Namespace:** `Stimulsoft.Report.Export.Tools`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfSecurity**([StiPdfExportService](../StiPdfExportService.md) service) |  |

**StiPdfSecurity**(**service**: [StiPdfExportService](../StiPdfExportService.md))

**Parameters**

- **service** ([StiPdfExportService](../StiPdfExportService.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ComputingCryptoValues** | bool |  |
| **CreateSignature** | byte[] |  |
| **EncryptData** | byte[] |  |
| **GetCertificateThumbprintFromCryptoUI** `static` | string |  |
| **GetCertificatesList** `static` | List<StiCertificateInfo> |  |
| **MakeSignedByString** | string |  |

---

### Method Details

#### ComputingCryptoValues

**ComputingCryptoValues**(**userAccessPrivileges**: [StiUserAccessPrivileges](../StiUserAccessPrivileges.md), **passwordInputOwner**: string, **passwordInputUser**: string, **keyLength**: [StiPdfEncryptionKeyLength](../StiPdfEncryptionKeyLength.md), ****: byteIDValue): bool

**Parameters**

- **userAccessPrivileges** ([StiUserAccessPrivileges](../StiUserAccessPrivileges.md))  
- **passwordInputOwner** (string)  
- **passwordInputUser** (string)  
- **keyLength** ([StiPdfEncryptionKeyLength](../StiPdfEncryptionKeyLength.md))  
- **** (byteIDValue)  

**Returns** bool


---

#### CreateSignature

**CreateSignature**(****: bytebuf, **isGost**: bool, **signedBy**: string, **offsetFilter**: int, **offsetSignedBy**: int): byte[]

**Parameters**

- **** (bytebuf)  
- **isGost** (bool)  
- **signedBy** (string)  
- **offsetFilter** (int)  
- **offsetSignedBy** (int)  

**Returns** byte[]


---

#### EncryptData

**EncryptData**(****: bytedata, **currentObjectNumber**: int, **currentGenerationNumber**: int): byte[]

**Parameters**

- **** (bytedata)  
- **currentObjectNumber** (int)  
- **currentGenerationNumber** (int)  

**Returns** byte[]


---

#### GetCertificateThumbprintFromCryptoUI `static`

**GetCertificateThumbprintFromCryptoUI**(**useLocalMachineCertificates**: bool, **certificateName**: string, **errorMessage**: string): string

**Parameters**

- **useLocalMachineCertificates** (bool)  
- **certificateName** (string)  
- **errorMessage** (string)  

**Returns** string


---

#### GetCertificatesList `static`

**GetCertificatesList**(**useLocalMachineCertificates**: bool): List<StiCertificateInfo>

**Parameters**

- **useLocalMachineCertificates** (bool)  

**Returns** List<StiCertificateInfo>


---

#### MakeSignedByString

**MakeSignedByString**(**input**: string, **padding**: bool): string

**Parameters**

- **input** (string)  
- **padding** (bool)  

**Returns** string


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
