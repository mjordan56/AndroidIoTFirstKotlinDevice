# Android Things First Kotlin Device

This is a Kotlin version of the [Android Things First Device ](https://mjordan56.github.io/AndroidIoTFirstDevice/) project. This project uses the same hardware as the First Device project. The software in this project uses Kotlin instead of Java to implement the simple test IoT device.

## Pre-requisites

- Raspberry Pi 3 Model B
- Android Things Release 1.0
- Android Studio 3.1.2
- Electronic Components
  * Breadboard
  * Jumper wires
  * LED
  * Tactile Push Switch
  * Resistors:
    * 1 - 470 ohm
    * 1 - 10K ohm
- Optional Additional Electronic Components
  * GPIO Breakout Board
  * Ribbon cable

  ## Build and Install

  In Android Studio, click on the "Run" button or to run from the command line enter:

  ```bash
  ./gradlew installDebug
  adb shell am start com.example.androidthings.myproject/.MainActivity
  ```
