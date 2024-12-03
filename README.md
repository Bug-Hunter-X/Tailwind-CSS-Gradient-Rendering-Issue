# Tailwind CSS Gradient Rendering Issue

This repository demonstrates a bug in Tailwind CSS where gradients may not render correctly in some browsers or configurations. The gradient may display as a solid color or the direction might be incorrect.  This example shows the problem and a solution.

## Bug

The `bug.js` file contains the problematic code.  It uses `bg-gradient-to-r` to create a radial gradient from blue to purple. In some scenarios, this gradient will not render properly. 

## Solution

The `bugSolution.js` file presents a solution involving fallback mechanisms to ensure the gradient renders correctly even in browsers with limited support.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.