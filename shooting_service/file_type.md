# File Type

### Service

9F00F387-8345-4BBC-8B92-B87B52E3091A

### Characteristic

95BFA8CA-4680-424D-B27C-AAC20D86E48B

### Format

uint8

### Overview

Acquires and sets the output file type.

### Value Fields

| Name | Type |
|:--|:--|
| File Type | sint8 |
| Raw Type | sint8 |
| CardSlot | sint8 |
| SlotMode | sint8 |

#### File Type

| Value | Description |
|:--|:--|
| 0 | JPEG |
| 1 | PEF |
| 2 | DNG |
| 3 | JPEG + PEF |
| 4 | JPEG + DNG |

#### Raw Type

| Value | Description |
|:--|:--|
| 0 | PEF |
| 1 | DNG |

#### Card Slot

| Value | Description |
|:--|:--|
| 0 | sd1 |
| 1 | sd2 |

#### Slot Mode

| Value | Description |
|:--|:--|
| 0 | Sequential |
| 1 | Duplicate |
| 2 | RAW/JPEG Separation |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Mandatory |
| Notify | Mandatory |