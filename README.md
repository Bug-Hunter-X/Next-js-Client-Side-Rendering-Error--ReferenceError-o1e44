# Next.js Client-Side Rendering Error: ReferenceError

This repository demonstrates a common error in Next.js applications where a runtime error occurs on the client-side during rendering. The error is a `ReferenceError` caused by referencing a variable that has not been defined.

## Bug Description
The `pages/about.js` file attempts to access a variable (`nonExistentVariable`) which is not defined, causing a runtime error in the browser when the page is loaded. This happens specifically during client-side rendering.  The error is not caught during the server-side rendering phase.

## How to Reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about`.
5. Observe the error in the browser's console.

## Solution
The solution involves checking for the existence of the variable before using it or defining the variable properly. The corrected `aboutSolution.js` file demonstrates a working solution.