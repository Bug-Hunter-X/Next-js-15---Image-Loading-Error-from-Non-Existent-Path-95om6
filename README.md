# Next.js 15 Image Loading Error

This repository demonstrates a common error in Next.js 15 applications: handling image loading from non-existent paths.  The `pages/about.js` file attempts to load an image from `/nonexistent.jpg`, which will result in an error.  This example shows how to effectively handle this scenario, preventing app crashes and providing a graceful user experience.  The solution file shows how to handle the error with robust error handling.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to the `/about` page.  You should see an error in your console.

## Solution

The solution involves implementing error handling to gracefully manage cases where the image fails to load.  Check the `bugSolution.js` file for a demonstration of how to implement it using error handling and optional chaining.