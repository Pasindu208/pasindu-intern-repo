# How to Test Accessibility

## Reflection

### 1. How would you test if Focus Bear is usable with a screen reader?

Based on the platform I will be testing on, I will use NVDA and JAWS on Windows, VoiceOver on macOS/iOS, and TalkBack on Android.

Steps I will take for testing:
* Verify if all the text visible is read correctly
* If any images or videos are included on the screen, verify if the alt text or labels are being read
* Check if I can navigate the UI using keyboard commands such as tab, shift+ tab, enter, space

Above steps should be followed in the order of end-to-end user flows in the app using the screen reader, documenting missing labels and any unexpected behaviour.

### 2. What accessibility barriers could affect someone with ADHD or Autism using the app?

* Follow guidelines such as the WCAG Guideline 3.2 Predictable to reduce the cognitive load for users with ADHD
* Avoid unexpected changes in the content on the screen
* Provide clear and simple navigation that is intuitive, offering concise instruction where needed
* Provide text formatting settings, colour scheme preferences and distraction free modes to users so that they can toggle them as required

### 3. If a developer says "this doesn't impact most users", how would you advocate for fixing an accessibility issue?

* Highlight the need for fixing accessibility issues as an ethical aspect
* Explain how any users with a disability requiring the accessibility feature will be affected by the lack of a fix
* Discuss during meetings and reviews the importance of accessibility features with Developers, Designers and Product Managers
* Advocate for incremental fixes, no need to rush fixing over other issues that can affect larger numbers of users, but not scrap accessibility fixes
