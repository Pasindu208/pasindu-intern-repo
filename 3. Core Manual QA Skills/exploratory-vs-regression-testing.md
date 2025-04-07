# Exploratory Testing vs. Regression Testing

## Reflection

### 1. Why is exploratory testing particularly useful for an app like Focus Bear?

In the context of the Focus Bear app, it is mainly geared towards boosting users' productivity and helping build good habits, with many of its features connected to usage in the daily life of its different users with unique usage patterns. Exploratory testing is very useful to simulate these patterns such as user trying to bypass a blocker, multitasking across apps, or having multiple focus sessions in a row.

Testers can try inputs and behaviors that test the boundaries of what the app is meant to block, as this type of unpredictable behaviour isn’t easy to cover through just scripted test cases. 

Exploratory testing can also quickly catch issues in UI/UX, timing, or device-specific behaviour, which are common in cross-platform apps like Focus Bear.

### 2. What risks come with relying too much on exploratory testing vs. only doing regression testing?

1. Relying too much on exploratory testing:
    - Regression testing will not be covered properly to ensure the existing features and components are functioning as expected
    - Very hard to map out testing progress
    - Hard to keep up documentation on testing

2. Relying too much on regression testing:
    - New components will not be properly tested
    - Any edge cases will not be caught

### 3. How would you document and report issues found during an exploratory testing session?

- Maintain a goal for each testing session, so that I don't stray away from the initial testing plan
- Document the following:
    - What was tested – specific flows, devices, conditions
    - Steps taken – especially if they led to a bug, include detailed reproduction steps
    - Findings – any bugs, weird behaviour, UI glitches, or performance issues
    - Screenshots or videos – to help developers reproduce the issue faster
    - Environment details – OS, app version, network conditions, etc
    - Severity and impact – how likely a user is to encounter the issue and what effect it might have
- Communicate with the development team the findings
