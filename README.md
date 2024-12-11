# Expo AsyncStorage Intermittent Crash

This repository demonstrates a bug where using AsyncStorage in an Expo app leads to intermittent crashes without clear error messages in the console. The app simply stops responding.

## Bug Description

The problem is that AsyncStorage sometimes fails silently, without providing any helpful information for debugging. This makes identifying the root cause difficult, especially since the crashes are intermittent.

## Solution

The proposed solution includes detailed error handling and logging, enhancing the debugging process.  Additionally, techniques to mitigate data loss are implemented.  See the solution file for specifics.

## How to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run the app on an emulator or physical device.
4. Observe intermittent crashes with no clear log messages.
