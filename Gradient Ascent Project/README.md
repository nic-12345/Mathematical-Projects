# Gradient Ascent Visualization

This project explores **gradient ascent optimization** on a chosen two-variable function. It combines symbolic computation, numerical analysis, and visualization to help understand how gradient ascent finds local maxima.

## Features

1. **Function Visualization**
   - 3D surface plots and 2D contour plots of functions.
   - Helps understand the function's topology and potential maxima.

2. **Symbolic Computation**
   - Computes first-order partial derivatives with SymPy.
   - Solves for critical points where the gradient is zero.
   - Calculates directional derivatives in any chosen direction.

3. **Gradient Ascent Implementation**
   - Iteratively updates starting points using the gradient.
   - Computes an optimal step size along the gradient.
   - Stops when the gradient is close to zero.
   - Visualizes iterations on contour plots.

4. **Interactive Exploration**
   - Users can choose starting points.
   - Modify the function to explore other surfaces and maxima.

## Installation

```bash
git clone https://github.com/yourusername/gradient_ascent_project.git
cd gradient_ascent_project
pip install -r requirements.txt
