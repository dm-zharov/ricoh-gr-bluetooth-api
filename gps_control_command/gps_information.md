# GPS Information

### Service

84A0DD62-E8AA-4D0F-91DB-819B6724C69E

### Characteristic

28F59D60-8B8E-4FCD-A81F-61BDB46595A9

### Overview

Acquires and sets the GPS information to the camera.

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
| Datum | sint8 | 0（WGS84）|

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Mandatory |
| Notify | Excluded |
