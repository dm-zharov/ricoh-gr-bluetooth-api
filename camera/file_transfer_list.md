# File Transfer List

### Service

4B445988-CAA0-4DD3-941D-37B4F52ACA86

### Characteristic

D9AE1C06-447D-4DEA-8B7D-FC8B19C2CDAE

### Overview

Acquires the information about the file transfer list.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Not empty | sint8 | 0 - No files to transfer<br>1 - Files available for transfer |
| Changed | sint8 | 0 - The list has not changed<br>1 - The list has changed |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Notify | Mandatory |