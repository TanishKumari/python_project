import numpy as np
import matplotlib.pyplot as plt

# Generate sample data: a pulse wave pattern
x = np.linspace(0, 10, 1000)
y = np.sin(2 * np.pi * x) * np.exp(-0.3 * x)  # A decaying sine wave to simulate pulse effect

# Plotting
plt.figure(figsize=(10, 5))
plt.plot(x, y, color="royalblue", linewidth=2, label="Pulse Signal")
plt.title("PulsePoint Signal Visualization")
plt.xlabel("Time")
plt.ylabel("Amplitude")
plt.axhline(0, color='black', linewidth=0.5)  # Zero reference line
plt.grid(True, linestyle="--", alpha=0.6)
plt.legend()
plt.show()
