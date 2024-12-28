# Tailwind CSS @apply Directive Issue

This repository demonstrates a problem with the `@apply` directive in Tailwind CSS v3.3.3 where `text-opacity` does not seem to be applied correctly when used within a custom class.  The issue only occurs when the class is applied using `@apply`. Directly applying the class works as expected.

## Steps to Reproduce

1. Clone this repository.
2. Install the necessary dependencies if needed.
3. Run the development server (if needed) to observe the rendered output.

You will notice that the text in the `.custom-text-class` does not have the expected opacity, unlike the text in the `.direct-text-opacity` class.

## Solution

The solution is provided in `bugSolution.css`.  It demonstrates a potential workaround or suggests an alternative approach. Please refer to the `solutionContent` for details.