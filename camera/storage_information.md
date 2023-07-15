# Storage Information

### Service

4B445988-CAA0-4DD3-941D-37B4F52ACA86

### Characteristic

A0C10148-8865-4470-9631-8F36D79A41A5

### Overview

Acquires the information of the camera storage.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Elements | sint8 | |
| Type | sint8 | 0 - Internal Memory<br>1 - SD Slot1<br>2 - SD Slot2 |
| Existence | sint8 | 0 - No storage (card) available<br>1 - Storage (card) available |
| Locked | sint8 | 0 - Unlocked<br>1 - Locked |
| Available | sint8 | 0 - Unavailable (due to error or other issues)<br> 1 - Available |
| Formatted | sint8 | 0 - Not formatted<br>1 - Formatted |
| Remaining Pictures | sint32 | Remaining space for pictures (count) |
| Remaining Videos Seconds | sint32 | Remaining space for video in seconds |
| File Type | sint8 | |
| Active | sint8 | 0 - Write-protected<br>1 - Writable |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Excluded |
| Notify | Mandatory |