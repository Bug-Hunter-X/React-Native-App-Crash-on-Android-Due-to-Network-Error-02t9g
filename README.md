# React Native App Crash on Android Due to Network Error

This repository demonstrates a common error in React Native applications where the app crashes on Android when encountering a network error during data fetching.  The issue stems from improper error handling in the asynchronous data fetching process.

The `DataFetch.js` file shows the buggy implementation, while `DataFetchSolution.js` provides a corrected version.

## Problem:
The original code lacks comprehensive error handling. When a network request fails, the app crashes without providing any user feedback.

## Solution:
The solution implements a `try...catch` block to handle potential errors during the fetch operation.  A user-friendly error message is displayed if an error occurs.