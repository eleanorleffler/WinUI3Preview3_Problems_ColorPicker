# WinUI3Preview3_Problems_ColorPicker

This repository contains two solutions with sample code demonstrating the ColorPicker in both UWP and WinUI3 Preview 3 Desktop.

The UWP sample code works as expected. However, the WinUI3 Preview 3 Desktop sample code crashes when loading the ColorPicker.

-------

**Describe the bug**

ColorPicker from the XAML Controls is unable to load and crashes program in the WinUI3 Preview 3 Desktop sample solution.

**Steps to reproduce the bug**

1. Clone the [WinUI3 Preview 3 ColorPicker repository](https://github.com/eleanorleffler/WinUI3Preview3_Problems_ColorPicker).
2. Go to the ColorPickerWinUIPreview3 folder.
3. Open the ColorPickerWinUIPreview3 solution in Visual Studio 2019 Preview.
4. Build and run with Debug x64.

**Expected behavior**

We expect the application to display a ColorPicker on the MainPage.

We expect to see the same behavior we saw in UWP. 

Build and run the ColorPickerUWP solution inside the TextBoxUWP folder to see expected behavior.

**Screenshots**

Screenshot#1 - Current Behavior (Error Message)

Screenshot#2 - Expected Behavior (ColorPicker)

**Version Info**

NuGet package version: 

[Microsoft.VCRTForwarders.140 1.0.6]
[Microsoft.WinUI 3.0.0-preview3.201113.0]

Targeting:
Target: Universal Windows
Target version: Windows 10, version 1809 (10.0; Build 17763)
Min version: Windows 10, version 1803 (10.0; Build 17134)

Windows app type:
| UWP              | Win32            |
| :--------------- | :--------------- |
| 		Yes 	   |  				  |

| Windows 10 version                  | Saw the problem? |
| :--------------------------------- | :-------------------- |
| Insider Build (xxxxx)              | 						 |
| May 2020 Update (19041)            | 						 |
| November 2019 Update (18363)       | 						 |
| May 2019 Update (18362)            | 						 |
| October 2018 Update (17763)        | 			Yes			 |
| April 2018 Update (17134)          | 						 |
| Fall Creators Update (16299)       | 						 |
| Creators Update (15063)            | 						 |

| Device form factor | Saw the problem? |
| :----------------- | :--------------- |
| Desktop            | 		Yes			|
| Xbox               | 					|
| Surface Hub        | 					|
| IoT                | 					|

**Additional context**
