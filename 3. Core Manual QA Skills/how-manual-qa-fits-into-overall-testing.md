# How Manual QA Fits into the Overall Testing Approach vs. Automated QA

## Reflection

### 1. If Focus Bear had 100% test automation, why would manual QA still be needed?

Because Focus Bear is designed to be used mainly by users who have ADHD, it is very important that human testers go through the app and test its functionality so that they can catch things like awkward user flows, confusing UI labels, or unclear feedback that automation might pass, because it is very important to maintain a warm and friendly feel to the app.

During automated testing scripts creation, scenarios that include events that were not considered can be caught by manual testing, which is highly likely because real humans interact with and respond to apps in very different ways, which cannot always be replicated by automated testing.

### 2. What are some limitations of automated testing that manual testing can cover?

1. User experience
    - Automated testing might be able to cover checking if certain UI elements such as a button exists in the right place,does the required action when clicked, etc but only a human tester can judge if it is in an intuitive position or how it impacts the user experience as it is.
2. Discovering edge cases
    - Because manual testing does not require a fixed structured approach to testing, it is more likely to catch edge cases and other hidden bugs
3. Human element
    - When testing manually, the tester might accidentally or in some instances on purpose input things that are against the current flow, which can expose any inconsistencies an automated script will not discover
    - Such instances are highly likely to occur with the real users, so it is important to be covered

### 3. How can manual testers help improve automated test coverage over time?

- Manual testers can identify areas that are high risk and critical to be tested and provide insights to the automation engineers
- Insights provided by manual QAs can also help improve automated scripts
- Repetitive tasks can be off-loaded to automated scripts to improve regression testing as releases move on
