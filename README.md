# React Native Async Operations in useEffect Hook: undefined data error
This repository demonstrates a common error in React Native when dealing with asynchronous operations inside the `useEffect` hook. The problem arises when the component attempts to render JSX that relies on data fetched asynchronously before that data has been fully retrieved.

## Bug Description
The provided `bug.js` file contains a component that fetches data using `fetch`.  The component renders before the data is available, resulting in an error or undefined values being used.