# React useEffect Cleanup Function Issue

This repository demonstrates a problem with the cleanup function in React's `useEffect` hook.  The expected behavior is for the cleanup function to execute when the component unmounts, but this is not happening in this example.

The `bug.js` file contains the problematic code.  `bugSolution.js` offers a corrected version.

## Problem Description

The component uses `useEffect` to log messages to the console upon mounting and unmounting.  The mount message appears correctly, but the unmount message does not. This suggests an issue with the component lifecycle or how the cleanup function is implemented.