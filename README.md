# Expo Camera API Freeze/Crash on Android

This repository demonstrates a bug in the Expo Camera API on certain Android devices. The camera preview may freeze or crash, rendering the app unresponsive. This issue is particularly prominent when switching between the front and rear cameras or making frequent adjustments to camera settings.

## Reproduction

1. Clone this repository.
2. Run the app using Expo Go on an affected Android device.
3. Observe the camera preview.  Switching cameras or adjusting settings frequently may lead to a freeze or crash.

## Solution

The solution involves adding error handling and potentially implementing more robust state management.  See `bugSolution.js` for a potential fix.

## Additional Notes

This bug seems to be related to specific Android device hardware/software combinations and may not reproduce consistently across all devices.