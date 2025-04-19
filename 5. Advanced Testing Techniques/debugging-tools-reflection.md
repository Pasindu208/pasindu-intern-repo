# Understanding Logs & Debugging Tools for QA

## Reflection

### 1. If Focus Bear crashes on a user’s device but not on yours, how would you use logs to investigate? 

* Request for device details (device model, OS version, app version) and logs from the user
* Analyze logs for the timestamps the issues were encountered
* Recreate the environment and carry out testing to find out any additional information

### 2. What are some useful log messages that should be included when reporting a bug?

* Include logging levels so that the logs can be filtered
* Include timestamps 
* Include user ids and session ids
* Capture user inputs, flags and any environment variables in use
* Record error messages and codes
* Log performance data such as request/response with payload sizes to detect slow endpoints

### 3. If an API call returns an unexpected response, what steps would you take to analyze the issue?

* Use a tool such as Chrome DevTools Network Panel to view request and response details
* Verify endpoint URLs
* Compare headers, payloads with the specifications in the API documentation
* Check server logs if available
