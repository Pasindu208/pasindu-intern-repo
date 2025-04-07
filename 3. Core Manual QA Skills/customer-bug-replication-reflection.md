# Replicating Bugs Reported by Customer

## Reflection

### 1. If a customer reports a crash but you can’t reproduce it, what are your next steps?

When a customer reports a crash but it can't be reproduced, 
- Verify all details such as app version, device type, OS, user actions, and time of occurrence
- Retry using similar conditions. If still unsuccessful, document all findings and keep tracking in case the issue resurfaces

### 2. When should you ask developers to add more logging, and what kind of logs would help?

- When unable to recreate a bug
- When more details are needed for tracing a bug
- If it is required to know the user interactions/actions/events (such as pressing a button, entering text, etc)
- When different stack services/systems are used to get more info

### 3. What are some common patterns in bugs that only occur for some users but not others?

- Bugs related to the user's environment (platform, OS version)
- Permissions and access levels granted by users to the app
- device hardware issues (older hardware)
