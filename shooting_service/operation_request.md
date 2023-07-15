# Drive Mode

### Service

9F00F387-8345-4BBC-8B92-B87B52E3091A

### Characteristic

559644B8-E0BC-4011-929B-5CF9199851E7

### Format

uint8

### Overview

Sets the operation request.

### Value Fields

| Name | Type |
|:--|:--|
| Drive Mode | sint8 |
| User Mode | sint8 |
| Shooting Mode Option | sint8 |

#### Operation Code

| Value | Description |
|:--|:--|
| 0 | Single Frame Shooting |
| 1 | Single Frame Shooting (Self 10 seconds) |
| 2 | Single Frame Shooting (Self 2 seconds) |

#### Parameter

| Value | Description |
|:--|:--|
| 0 | NOP |
| 1 | Start Shooting/Recording |
| 2 | Stop Shooting/Recording |

#### Shooting Mode Option

| Value | Description |
|:--|:--|
| 0 | No AF |
| 1 | AF |
| 2 | Green Button Function |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Excluded |
| Write | Mandatory |
| Notify | Excluded |