# React useEffect Hook Missing Cleanup Function

This example demonstrates a common error in React's `useEffect` hook: forgetting to include a cleanup function.  The absence of a cleanup function can lead to memory leaks or unexpected behavior when the component unmounts.  The bug is present in `bug.js`, and the solution is demonstrated in `bugSolution.js`.