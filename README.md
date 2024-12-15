# React: Incorrect State Update in useState Hook

This example demonstrates an uncommon error in React where the state is updated incorrectly using the useState hook.  Directly modifying the state variable will not trigger a re-render, leading to unexpected behavior. The solution showcases the correct way to update state using the setter function provided by useState.