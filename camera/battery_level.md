# Battery Level

### Service

4B445988-CAA0-4DD3-941D-37B4F52ACA86

### Characteristic

875FC41D-4980-434C-A653-FD4A4D4410C4

### Overview

Acquires the battery level of the camera and the source of power being used.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Level | sint8 | Current battery level |
| Used | sint8 | Source of power being used:<br>0 - Battery<br>1 - AcAdapter |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Excluded |
| Notify | Mandatory |