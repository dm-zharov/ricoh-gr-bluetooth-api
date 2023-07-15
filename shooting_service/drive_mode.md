# Drive Mode

### Service

9F00F387-8345-4BBC-8B92-B87B52E3091A

### Characteristic

B29E6DE3-1AEC-48C1-9D05-02CEA57CE664

### Format

uint8

### Overview

Acquires and sets the drive mode of the camera.

### Value Fields

| Name | Type |
|:--|:--|
| Drive Mode | sint8 |
| User Mode | sint8 |
| Shooting Mode Option | sint8 |

#### Drive Mode

| Value | Description |
|:--|:--|
| 0 | Single Frame Shooting |
| 1 | Single Frame Shooting (Self 10 seconds) |
| 2 | Single Frame Shooting (Self 2 seconds) |
| 3 | Continuous Shooting |
| 4 | Bracket Shooting |
| 5 | Bracket Shooting (Self 10 seconds) |
| 6 | Bracket Shooting (Self 2 seconds) |
| 7 | Multiple Exposure |
| 8 | Multiple Exposure (Self 10 seconds) |
| 9 | Multiple Exposure (Self 2 seconds) |
| 10 | Interval Shooting |
| 11 | Interval Shooting (Self 10 seconds) |
| 12 | Interval Shooting (Self 2 seconds) |
| 13 | Interval Composite |
| 14 | Interval Composite (Self 10 seconds) |
| 15 | Interval Composite (Self 2 seconds) |
| 16 | Single Frame Shooting (Remote Immediate) |
| 17 | Single Frame Shooting (Remote 3 seconds) |
| 18 | Continuous Shooting H |
| 19 | Continuous Shooting H (Self 12 seconds) |
| 20 | Continuous Shooting H (Self 2 seconds) |
| 21 | Continuous Shooting H (Remote Immediate) |
| 22 | Continuous Shooting H (Remote 3 seconds) |
| 23 | Continuous Shooting M |
| 24 | Continuous Shooting M (Self 12 seconds) |
| 25 | Continuous Shooting M (Self 2 seconds) |
| 26 | Continuous Shooting M (Remote Immediate) |
| 27 | Continuous Shooting M (Remote 3 seconds) |
| 28 | Continuous Shooting L |
| 29 | Continuous Shooting L (Self 12 seconds) |
| 30 | Continuous Shooting L (Self 2 seconds) |
| 31 | Continuous Shooting L (Remote Immediate) |
| 32 | Continuous Shooting L (Remote 3 seconds) |
| 33 | Bracket Shooting (Remote Immediate) |
| 34 | Bracket Shooting (Remote 3 seconds) |
| 35 | Multiple Exposure (Remote Immediate) |
| 36 | Multiple Exposure (Remote 3 seconds) |
| 37 | Interval Shooting (Remote Immediate) |
| 38 | Interval Shooting (Remote 3 seconds) |
| 39 | Interval Composite (Remote Immediate) |
| 40 | Interval Composite (Remote 3 seconds) |
| 41 | Interval Movie |
| 42 | Interval Movie (Self 12 seconds) |
| 43 | Interval Movie (Self 2 seconds) |
| 44 | Interval Movie (Remote Immediate) |
| 45 | Interval Movie (Remote 3 seconds) |
| 46 | Motion Bracket |
| 47 | Motion Bracket (Self 12 seconds) |
| 48 | Motion Bracket (Self 2 seconds) |
| 49 | Motion Bracket (Remote Immediate) |
| 50 | Motion Bracket (Remote 3 seconds) |
| 51 | Focus Bracketing |
| 52 | Focus Bracketing (Self 12 seconds) |
| 53 | Focus Bracketing (Self 2 seconds) |
| 54 | Focus Bracketing (Remote Immediate) |
| 55 | Focus Bracketing (Remote 3 seconds) |
| 56 | Mirror Lockup |
| 57 | Mirror Lockup (Self 12 seconds) |
| 58 | Mirror Lockup (Self 2 seconds) |
| 59 | Mirror Lockup (Remote Immediate) |
| 60 | Mirror Lockup (Remote 3 seconds) |
| 61 | Star Stream |
| 62 | Star Stream (Self 12 seconds) |
| 63 | Star Stream (Self 2 seconds) |
| 64 | Star Stream (Remote Immediate) |
| 65 | Star Stream (Remote 3 seconds) |

#### User Mode

| Value | Description |
|:--|:--|
| 0 | Not in user mode |
| 1 | User mode |
| 2 | User mode 2 |
| 3 | User mode 3 |
| 4 | User mode 4 |
| 5 | User mode 5 |

#### Shooting Mode Option

| Value | Description |
|:--|:--|
| 0 | No options |
| 1 | Hyper |
| 2 | Shift |

### Properties

| Property | Requirement |
|:--|:--|
| Read | Mandatory |
| Write | Mandatory |
| Notify | Mandatory |