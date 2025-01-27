# Tailwind CSS @apply Directive Configuration Error

This repository demonstrates a common yet easily overlooked error when using Tailwind CSS's `@apply` directive.  The `@apply` directive is a powerful feature, allowing you to apply pre-defined styles to your classes.  However, it requires proper configuration within your `tailwind.config.js` file.

## The Problem
The provided code utilizes the `@apply` directive to apply styles to a div element. Without proper configuration, the styles may not be applied correctly.

## How to reproduce the bug
1. Clone this repository.
2. Run `npm install` to install dependencies (if any).
3. Open `bug.js` and observe the code.
4.  Notice how styles are not applied correctly. This is because the Tailwind configuration file is missing or is not correctly setup.

## Solution
The solution involves correctly configuring `tailwind.config.js`. The corrected configuration is shown in `bugSolution.js`

## How to fix the bug
1. Correctly configure your `tailwind.config.js` file as demonstrated in `bugSolution.js`
2. Recompile your css.
3. The styles will then be correctly applied.
