# Understanding Release Cycles & Version Control

## Reflection

### 1. How would you adjust your testing strategy for a major feature release vs. a small bug fix?

* Major feature release:
    * Do thorough regression testing
    * Perform exploratory testing to find out how users can use the new features along with the existing ones, and find out any issues that can arise
    * Focus testing on newly implemented features
    * Continuously communicate with devs, product managers to stay updated on features, expected behaviours as they are new 
* Small bug fix:
    * Concentrate on the area that was fixed
    * Verify if any other components are affected by the fixes (smoke and sanity checks)
    * Be quick in validation so that fixes can be deployed quickly

### 2. If a developer says, “This bug only happens on an older branch,” how would you handle it?

* Verify if bug is version specific, confirm if the bug is specific to the branch by testing it against a different branch
* Document differences such as dependency versions and features available from the current release
* Plan regression testing so that these issues can be captured in future releases
* Communicate findings clearly with developers

### 3. Why is it important for testers to know which version of the app they are testing?

* It is easier to trace bugs and issues to any code changes, dependency versions and any other configurations 
* Regression testing can be conducted with tests aligned with releases
* Any critical findings can help version rollbacks
