# Camera Service Notification

### Service

4B445988-CAA0-4DD3-941D-37B4F52ACA86

### Characteristic

FAA0AEAF-1654-4842-A139-F4E1C1E722AC

### Type

variable

### Overview

Acquires the camera service notification.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Number of Notification | sint8 | |
| Include Changed Value | sint8 | 0--1 |
| UUID | sint128 | |
| Changed Value | variable | |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Excluded |
| Notify | Mandatory |