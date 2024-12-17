# Firebase Realtime Database Listener Issue

This repository demonstrates a common issue encountered when working with Firebase's Realtime Database: a listener failing to trigger on partial data changes. The bug is in `firebaseBug.js`. The solution is provided in `firebaseBugSolution.js`.

The problem arises from structuring data in a way that doesn't trigger the listener when only specific child nodes are modified.  The solution involves restructuring the data or using a more specific listener to ensure updates are captured correctly. 

## Setup

1. Clone this repository.
2. Install Firebase:
   ```bash
   npm install firebase
   ```
3. Configure your Firebase project and replace the placeholder values in the code with your Firebase config.