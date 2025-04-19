# Testing Error Handling & Edge Cases

## Reflection 

### 1. What edge cases could break Focus Bear’s onboarding flow?

* Interrupted setup: 
    * App closing midway through the setup of the app
    * App switching
    * Incoming phone call when setting up  
* Invalid inputs:
    * Special characters entered by users
    * Inputs exceeding the max length possible  
* Denial of permission:
    * Denying permissions for notifications, overlays, etc  

### 2. If the app fails midway through a critical action, how should it behave?

1. Retry the failed step automatically 
2. Notify user of error
3. Save any progress up to the point

### 3. How would you test for network instability and ensure Focus Bear handles it gracefully?

* Use throttling profiles when testing
* Manually change between WiFi and mobile data
* Turn off internet to check if everything syncs up as required, interrupted uploads/downloads resume 
