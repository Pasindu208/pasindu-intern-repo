# Testing on Different Devices & Environments

## Reflection

### 1. What unique bugs could occur on Android vs. iOS, or Windows vs. macOS?

* Android vs iOS: 
    * Wide range of screen sizes and resolutions in Android will cause issues
    * Manufacturer specific customizations to the OS and the device can cause issues in Android
    * In iOS the tight restrictions put in place by Apple can be problematic for features, especially ones present in Focus Bear as it is required to run in the background and monitor the users work
    * Some OS features available in one of these OS may not be available in the other causing issues when providing the feature across platforms
* Windows vs macOS:
    * Different Windows hardware and drivers can cause issues related to display and performance bottlenecks
    * macOS specific integration issues

### 2. If a bug is reported only on an older OS version, how would you approach testing it?

* Research possible difference in the older OS that might cause the issues such as system API changes, limitations in the OS, etc
* Use VMs to recreate the older OS version for testing
* Need to make sure that VMs don't have any affect on the features being tested in comparison to an actual device
* Document all the findings

### 3. What strategies can you use if you don’t have direct access to a specific device for testing?

* Use a cloud based device testing service such as AWS Device Farm, Browser Stack
* Use emulators and VMs to test on the required platforms
* Get help from beta testers who have the necessary devices
