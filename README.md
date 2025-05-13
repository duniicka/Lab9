import numpy as np
x_values = np.linspace(4.0, 5.0, 1000)
solutions = []
for x_val in x_values:
    if np.isclose(x_val + 3 * (x_val - 6.09)**(1/3), 0, atol=1e-6):
        solutions.append(x_val)
print(solutions)
