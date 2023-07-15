# Capture Status

### Service

9F00F387-8345-4BBC-8B92-B87B52E3091A

### Characteristic

B5589C08-B5FD-46F5-BE7D-AB1B8C074CAA

### Overview

Acquires the status of capture operations.

### Value Fields

| Name | Type | Description |
|:--|:--|:--|
| Capturing | sint8 | Status of capturing process:<br>0 - Not capturing<br>1 - Capturing in progress |
| Countdown | sint8 | Status of countdown:<br>0 - Not in countdown<br>1 - Countdown in progress (Self-timer)<br>2 - Waiting for specified time (Time specified) |
| Still | sint8 | State of still captures:<br>0 - Other<br>1 - Continuous shooting in progress<br>2 - Bracket shooting in progress<br>3 - Multiple exposure in progress<br>4 - Interval shooting in progress<br>5 - Interval composite in progress |
| Movie | sint8 | Movie capture status:<br>0 - Other<br>1 - Recording in progress |
| Type3CaptureState | sint8 | Status of Type 3 capture:<br>0 - Waiting for capture<br>1 - Pre-capture in progress<br>2 - Main capture in progress |
| Type3PreCaptureResult | sint8 | Result of Type 3 pre-capture:<br>0 - No error<br>1 - Motion detection failure error<br>2 - Exposure time error |
| AstroTrackingTime | uint16 | Time for astro tracking (unit unspecified) |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Excluded |
| Notify | Mandatory |