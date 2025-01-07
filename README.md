# React useEffect Unexpected Behavior

This repository demonstrates a common error in React's `useEffect` hook where the intent is for the effect to run on every render, but it only runs once due to an empty dependency array.

## Problem
The `useEffect` hook in the `bug.js` file is intended to log a message on every render. However, because of the empty dependency array `[]`, it only runs once after the initial mount.