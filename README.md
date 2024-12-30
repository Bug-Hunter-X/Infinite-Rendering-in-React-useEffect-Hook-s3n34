# React useEffect Infinite Loop Bug
This repository demonstrates a common error in React's `useEffect` hook that leads to infinite rendering. The `useEffect` hook is used incorrectly, causing the component to re-render continuously.

## Bug Description
The provided code has an infinite render loop in the `useEffect` hook. This happens because the dependency array `[count]` includes `count`, which changes on every render. This triggers an endless loop of updates.

## Solution
The solution involves modifying the `useEffect` to avoid this infinite loop. Check the `bugSolution.js` file for the correct implementation.