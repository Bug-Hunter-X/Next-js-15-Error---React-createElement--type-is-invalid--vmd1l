# Next.js 15 Error: 'React.createElement: type is invalid'

This repository demonstrates a bug in Next.js 15 where using a simple functional component in the `pages` directory throws a 'React.createElement: type is invalid' error.  This issue occurs due to a specific interaction of Next.js's new App Router with functional components that aren't properly exporting a default component.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the error in your console.

## Solution

The solution involves ensuring that your functional component exports a default component in a correct structure, as demonstrated in `bugSolution.js`.