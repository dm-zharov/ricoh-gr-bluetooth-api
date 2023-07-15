# Power Off During File Transfer

### Service

4B445988-CAA0-4DD3-941D-37B4F52ACA86

### Characteristic

BD6725FC-5D16-496A-A48A-F784594C8ECB

### Overview

Controls the behavior of the device during file transfer.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Behavior | sint8 | 0 - Power off during transfer interruption<br>1 -  Power off after transfer completion |
| Auto Resize | sint8 | 0 - Transfer without resizing<br>1 - Transfer with resizing |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Mandatory |
| Notify | Mandatory |