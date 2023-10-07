### Description
Implemented a new feature that allows users to sort items in the list alphabetically.

### Related Issue(s)
- #12 - Feature request: Sorting functionality
- #15 - UI: Add sorting button to the toolbar

### Motivation and Context
The sorting functionality was requested in issue #12 due to users having difficulty finding items in long lists. Implementing this will enhance user experience by organizing listed items in a structured manner.

### Type of Change
- [X] New feature (non-breaking change which adds functionality)

### Proposed Changes
- Added a `sort` button to the UI.
- Implemented a `sortItems` function that utilizes the JavaScript `sort()` method to arrange items alphabetically.
- Connected the `sortItems` function to the UI button.

### Testing
- Manual testing was performed by adding items to the list and verifying the sort functionality in the UI.
- Automated testing was performed using Jest, focusing on the `sortItems` function to ensure items are sorted accurately.

### Checklist
- [X] I have added tests that prove my fix is effective or that my feature works
- [X] I have added necessary documentation (if appropriate)
- [X] I have tested the changes locally

### Screenshots (if appropriate)
_[Include screenshots that highlight the changes made. You can include the screenshots by dragging and dropping in the web interface.]_

