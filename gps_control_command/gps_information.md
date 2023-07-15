# GPS Information

### Service

84A0DD62-E8AA-4D0F-91DB-819B6724C69E

### Characteristic

97B06384-E704-4907-A5D1-22349D12EE6B

### Overview

Acquires and sets the GPS information of the camera.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Latitude | float64 | Latitude. |
| Longitude | float64 | Longitude. |
| Altitude | float64 | Altitude.<br>-9999 -- 9999 |
| Year | sint16 | 1582 -- 9999 |
| Month | sint8 | 1 -- 12 |
| Day | sint8 | 1 -- 31 |
| Hours | sint8 | 0 -- 23 |
| Minutes | sint8 | 0 -- 59 |
| Seconds | sint8 | 0 -- 59 |
| Time Zone | utf8s | + (-) hh:mm (Fixed to 6 digits) |
| Datum | sint8 | 0（WGS84） |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Mandatory |
| Notify | Excluded |
