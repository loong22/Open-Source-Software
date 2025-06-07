# SCI
Some scientific agent software.

## Turn off system updates in Windows

### 1. Open the registry editor:

Press Win + R, enter regedit, press Enter, and agree to the UAC prompt.

### 2. Navigate to the specified path:

Locate: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings

### 3. Create DWORD (32-bit)

Value name: FlightSettingsMaxPauseDays
Value data (hexadecimal): 5000

### 4. Close the registry editor

Open Windows Settings->Update and Security->Windows Update->Advanced Options->Pause Updates until (just scroll to the bottom date)->Return to see that updates will resume after [your selected date]
