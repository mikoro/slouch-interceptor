# Slouch Interceptor

Slouch Interceptor is a simple program that reminds you to take small regular breaks from working at your computer, i.e it intercepts your slouchiness ;)

* Author: [Mikko Ronkainen](http://mikkoronkainen.com)
* Website: [github.com/mikoro/slouch-interceptor](https://github.com/mikoro/slouch-interceptor)

![Screenshot](http://mikoro.github.io/images/slouch-interceptor/readme-screenshot.jpg "Screenshot")

## Requirements

At least Windows XP, .NET Framework 2.0 and motivation to obey the program...

## Download

Download the latest version: [Slouch Interceptor 1.3.3](https://github.com/mikoro/slouch-interceptor/releases/download/v1.3.3/Slouch.Interceptor.1.3.3.msi).

Older versions can be found from the [releases page](https://github.com/mikoro/slouch-interceptor/releases).

## Instructions

- The program will start automatically when starting Windows
- Click the program icon in the taskbar to show the context menu
- You can test the program with the _Start Break_ menu entry
- If you want to close the overlay window before the timeout either press Alt+F4 or press the Windows key, click the taskbar icon and select _Stop Break_
- The break interval timer can be enabled/disabled with the _Enable/Disable Timer_ menu entry
- Configuration options:
    - **BreakDuration** is the duration of the break in minutes (can be fractional)
    - **BreakInterval** is the time between the breaks in minutes (can be fractional)
    - **IdleDetectionThreshold** is the idle time in minutes after which the break interval timer is reset (you didn't use the computer and the program takes it as a break) (can be fractional)
    - **BreakNotificationTime** is the time when a notification will be shown (minutes before the actual break) (can be fractional)
    - **AutoLock** sets whether the computer is locked after the break ends (useful if you leave the computer during the break)
    - **DisableClose** makes the overlay window ignore normal closing attempts (can be closed with the taskbar context menu)
    - **DisableSwitch** keeps the overlay window topmost all the time (combining with DisableClose makes closing the overlay window very difficult)
    - **EnableBreakNotification** shows a balloon tip notification before the actual break begins

## Version history

### 1.3.3 (4/10/2014)

- Updated license, readme and setup files

### 1.3.2 (5/16/2012)

- Adjusted break notification timings

### 1.3.1 (5/10/2012)

- Added restart timer support
- Fixed some bugs the break notification and overlay window

### 1.3.0 (5/9/2012)

- Added support for AutoLock
- Added support for DisableClose
- Added support for DisableSwitch
- Added support for BreakNotification
- Changed the configuration window interface
- Added support for minute fractions in the configuration options
- Added fade in effect

### 1.2.1 (3/21/2012)

- Fixed a bug that starts a break immediately after resuming the computer and logging in
- Added a license to the project

### 1.2.0 (2/29/2012)

- Some changes to the taskbar menu and little bug fixes

### 1.1.0 (2/28/2012)

- Added configuration options and support for user idle detection

### 1.0.0 (2/26/2012)

- Initial version
