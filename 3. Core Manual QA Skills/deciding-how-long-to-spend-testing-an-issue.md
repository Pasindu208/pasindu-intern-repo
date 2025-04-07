#  Deciding how long to spend on testing an issue

## Reflection

### 1. How would you approach testing a small UI bug vs. a critical login issue?

1. Approach for a small UI bug:
    - Set a lesser amount of time to test
    - I will first check if it is affecting user experience by hindering users from completing any tasks
    - Check on multiple devices with different screen sizes/platforms if it is a persistent issue
    - Document and report all info gathered
2. Approach for critical login issue:
    - Set plenty of time to test thoroughly
    - I will test across different scenarios for the issue such as different devices/platforms, password reset issues, multiple failed logins, and even wrong credentials 
    - Report to dev team with high importance tag

I answered my approaches to these scenarios based on:
- Allocating time based on the risk factor of the issue area
- How technically complex the issue is
- How likely the issue is to cause user-facing problems

### 2. If you had limited time, how would you decide what to test first?

In a time constrained situation, I will
- Categorise issues according to if it is a core functionality or something less critical, and focus on the critical components first
- Communicate with the team what was tested properly and what was skipped over with reasons for the decision

### 3. What risks come with over-testing or under-testing an issue?

1. Over-testing:
    - Wasting time with unnecessary testing
    - Releases can be delayed 
    - Irrelevant issues might be caught, causing problems
    - Can be a sign of not properly understanding the testing requirements for the components

2. Under-testing:
    - Bugs and issues will not be caught properly
    - If these versions are released, users will have poor experience
    - This also can be a sign of not properly understanding the testing requirements for the components
    - or not properly scheduling time for testing 
