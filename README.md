# React Router Dom v6 Catch-All Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router Dom v6. The catch-all route should match any route that isn't explicitly defined. However, in this example, it does not work as expected, and the `NotFound` component is not rendered when navigating to a non-existent route. 

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to a non-existent route (e.g., `/nonexistent`).

You'll notice that the `NotFound` component is not rendered.  The issue is resolved in the `AppSolution.js` file.