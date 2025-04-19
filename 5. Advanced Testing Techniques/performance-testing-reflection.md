# Testing Performance & Responsiveness

## Reflection

### 1. How would you test Focus Bear’s performance on an older device or a slow internet connection?

* Record the performance of the app on high-end hardware as a baseline and then compare it to the performance on lower-end hardware, to make sure that the performance differences are relative and do not suffer massive drops in performance

* Simulate slow internet connections using throttling profiles the performance of the app, testing in conditions such as 3G, slow 4G, patchy signal drops, etc

* Metrics such as time to load UI and responsiveness, frame rates and animation smoothness need to be recorded and compared to check if they are within usable amounts 

### 2. If a user reports that the app feels slow, what steps would you take to investigate?

* Capture logs from the users environment
* Compare differences from the users logs to a bench mark log

### 3. What performance optimizations could help Focus Bear run smoothly on low-end devices?

* Lazy loading
* Use HEIF formats and compression on media
* Use service workers and local storage to reduce network dependencies
* Hardware acceleration
