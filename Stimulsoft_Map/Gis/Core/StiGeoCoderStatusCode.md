---
title: "StiGeoCoderStatusCode Enum"
---

## StiGeoCoderStatusCode Enum

**Namespace:** `Stimulsoft.Map.Gis.Core`  
**Assembly:** `Stimulsoft.Map`

```csharp
public enum StiGeoCoderStatusCode
```

### Inheritance

Implements: int  

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Unknow** | -1 | unknow response |
| **G_GEO_SUCCESS** | 200 | No errors occurred; the address was successfully parsed and its geocode has been returned. |
| **G_GEO_BAD_REQUEST** | 400 | A directions request could not be successfully parsed. For example, the request may have been rejected if it contained more than the maximum number of waypoints allowed. |
| **G_GEO_SERVER_ERROR** | 500 | A geocoding or directions request could not be successfully processed, yet the exact reason for the failure is not known. |
| **G_GEO_MISSING_QUERY** | 601 | The HTTP q parameter was either missing or had no value. For geocoding requests, this means that an empty address was specified as input. For directions requests, this means that no query was specified in the input. |
| **G_GEO_MISSING_ADDRESS** | 601 | Synonym for G_GEO_MISSING_QUERY. |
| **G_GEO_UNKNOWN_ADDRESS** | 602 | No corresponding geographic location could be found for the specified address. This may be due to the fact that the address is relatively new, or it may be incorrect. |
| **G_GEO_UNAVAILABLE_ADDRESS** | 603 | The geocode for the given address or the route for the given directions query cannot be returned due to legal or contractual reasons. |
| **G_GEO_UNKNOWN_DIRECTIONS** | 604 | The GDirections object could not compute directions between the points mentioned in the query. This is usually because there is no route available between the two points, or because we do not have data for routing in that region. |
| **G_GEO_BAD_KEY** | 610 | The given key is either invalid or does not match the domain for which it was given. |
| **G_GEO_TOO_MANY_QUERIES** | 620 | The given key has gone over the requests limit in the 24 hour period or has submitted too many requests in too short a period of time. If you're sending multiple requests in parallel or in a tight loop, use a timer or pause in your code to make sure you don't send the requests too quickly. |
| **ExceptionInCode** |  | indicates that exception occured during execution |
