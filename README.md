# Next.js Hydration Mismatch Bug
This repository demonstrates a common hydration mismatch bug in Next.js applications and provides a solution.

## Bug Description
A hydration mismatch occurs when the client-side rendering (CSR) of a component differs from the server-side rendering (SSR). This typically leads to errors in the browser's console and unexpected visual behavior. In this specific case, the custom component `MyComponent` is not rendered correctly, resulting in a hydration mismatch error. 

## Bug Reproduction Steps
1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the development server.
4. Open your browser and observe the error in the console.

## Solution
The solution involves ensuring the client-side rendering of the component matches the server-side rendering by adding a key prop to the component.