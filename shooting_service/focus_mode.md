# Focus Mode

### Service

9F00F387-8345-4BBC-8B92-B87B52E3091A

### Characteristic

89458F80-50A1-42C1-B031-1BC6082179C0

### Overview

Acquires the focus mode.

### Value Fields

| Name | Type |
|:--|:--|
| Focus Mode | sint8 |
| Focus Setting | sint8 |

#### Focus Mode

| Value | Description |
|:--|:--|
| 0 | MF |
| 1 | AF |

#### Focus Setting

| Value | Description |
|:--|:--|
| 0 | MF (Manual Focus) |
| 1 | Auto Area AF |
| 2 | Select AF |
| 3 | Pinpoint AF |
| 4 | Tracking AF |
| 5 | Continuous AF |
| 6 | Snap |
| 7 | Infinity |
| 8 | Movie |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Excluded |
| Notify | Mandatory |