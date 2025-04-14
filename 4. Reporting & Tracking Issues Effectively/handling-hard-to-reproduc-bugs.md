# Handling Hard-to-Reproduce Bugs

## Reflection

### 1. How would you report a bug that only happens occasionally?

- Include very detailed instructions to reproduce the issue, including any unusual conditions that were present when the bug occurred
- Provide logs, screenshots, screen recordings of the bug occurring
- Add notes regarding the context of the system when the bug occurred such as any background processes running, system load, etc

### 2. If a developer marks a bug as "Not reproducible", what’s your next step?

- Verify documentation for anything that might not be properly taken down, missing
- Verify with the developer if the documentation was referred properly and that all logs were taken into account
- Try to schedule a session to reproduce the issue with the developer
- Request developers to implement more logging to make sure that in the future more logs are available to troubleshoot and replicate issues

### 3. What tools or techniques can help capture extra details for unpredictable bugs?

- Tools: Sentry, Firebase crashlytics, Raygun

- Techniques:
    - Perform repetitive automated testing under different conditions and scenarios and document and analyse for any differences in results even if minor
    - Compare version control along with the bugs reported to understand origins of bugs/issues
    - Use a network packet capture analysis tool to monitor for network based interactions such as Focus Bear app communicating with OpenAI apis for distraction blocking, where we can find out if issues are based on network related failures
    - Test in perfect conditions to compare other situations against the expected results effectively
