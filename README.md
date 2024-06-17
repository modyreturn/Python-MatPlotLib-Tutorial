import matplotlib.pyplot as plt
import numpy as np

print("Studying MatPlotLib Module")

xpoints = np.array([0, 2, 4, 6, 8,10, 12,14, 16, 18, 20])
ypoints = np.array([1, 3, 5, 3, 7, 9, 5, 7, 9, 11, 9])

plt.plot(xpoints, ypoints, "o-.b", ms = 7, mec = "c", mfc = "k" ) #formating the line chart.
plt.show()

xpoints = np.array([0, 4, 2, 8, 6,10, 12,14])
ypoints = np.array([1, 3, 5, 3, 7, 9, 5, 7])

plt.plot(xpoints, "o-b", ms = 10, mec = "r", mfc = "b" ) #formating X-axis
plt.plot(ypoints, 'o--y', ms = 10, mec = '#4CAF50', mfc = '#4CAF50') #formating Y-axis


plt.savefig("Figures.png")
plt.show()
