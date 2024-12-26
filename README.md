# React Router v6: useNavigate Hook Usage Error

This repository demonstrates a common error when using the `useNavigate` hook in React Router v6.  The `useNavigate` hook must be used within a functional component.  Using it outside of a component that React renders will lead to unexpected behavior or errors. This example shows the bug and its solution.

## Bug
The bug lies in the `About` component. The `useNavigate` hook is called outside of a functional component, causing it to not work as expected. 

## Solution
The solution involves ensuring the `useNavigate` hook is used within a component.  The corrected code is provided in `bugSolution.js`.