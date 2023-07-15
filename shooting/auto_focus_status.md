# Auto Focus Status

### Service

9F00F387-8345-4BBC-8B92-B87B52E3091A

### Characteristic

CDFC734E-EA21-427D-A69F-C1A0F7F1E9A3

### Overview

Acquires the auto focus status.

### Value Fields

| Name | Type |
|:--|:--|
| Running | sint8 |
| InFocus | sint8 |

#### Running

| Value | Description |
|:--|:--|
| 0 | Stopped |
| 1 | Operating |

#### InFocus

| Value | Description |
|:--|:--|
| 0 | Not Focused |
| 1 | Focused |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Excluded |
| Notify | Mandatory |