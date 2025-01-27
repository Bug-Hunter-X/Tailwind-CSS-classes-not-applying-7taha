# Tailwind CSS Classes Not Applying

This repository demonstrates a common issue when working with Tailwind CSS: classes not being applied correctly. The example shows a simple div with Tailwind classes for background color and hover effect. The hover effect is not working as expected. 

## Bug

The `bug.js` file contains the buggy code. The hover effect on the div is not working.  The issue arises because Tailwind needs proper configuration and compilation.  Simple typos can also cause this.

## Solution

The `bugSolution.js` file provides the solution. The main solution is to ensure the Tailwind directives (`@tailwind directives`) are present in your CSS file and that your Tailwind configuration is correct (including the `purge` option in `tailwind.config.js` which helps remove unused CSS classes).