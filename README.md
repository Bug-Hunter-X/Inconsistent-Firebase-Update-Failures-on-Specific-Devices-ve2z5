# Inconsistent Firebase Update Failures

This repository demonstrates an uncommon bug encountered when using Firebase's `update()` method.  On some devices, updates are seemingly successful, but the changes don't persist in the database. This is inconsistent and only happens intermittently.

The `firebaseBug.js` file contains the problematic code snippet.  `firebaseBugSolution.js` offers a potential solution.  The problem only occurs in certain circumstances which are not fully understood at this time. More details are needed to replicate and debug the issue.