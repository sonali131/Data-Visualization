# 📊 Matplotlib Visualization Project – Sonali

This project demonstrates how to create and save a simple plot using **NumPy** and **Matplotlib** in Python.  
It was created in **Google Colab** and shows how to visualize and save data programmatically.

---

## 🚀 Features

- Uses `numpy.linspace()` to generate evenly spaced values
- Cubes the values of `x` to form a nonlinear curve
- Labels axes and adds a title
- Saves the plot as an image file (`sonali_plot.png`)

---

## 🧠 Code Example

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 5, 11)
y = x ** 3

plt.plot(x, y)
plt.title("Sonali")
plt.xlabel("X axis")
plt.ylabel("Y axis")

plt.savefig("sonali_plot.png")  # Save the figure
plt.show()
📁 Output
sonali_plot.png – generated plot showing the cubic relationship between X and Y.

🧩 How to Run
Open the notebook in Google Colab or any Python IDE.

Run all cells to generate the plot.

The output file (sonali_plot.png) will appear in your working directory.

🌐 Deploy on GitHub Pages
If you want to display your plot live:

Convert the notebook to HTML:

bash
Copy code
jupyter nbconvert --to html matplot_demo.ipynb
Upload the .html file to your GitHub repo.

Enable GitHub Pages in repo settings → Pages → Deploy from main.

👩‍💻 Author
Sonali Mishra
📧 Email: mishrasonali1198@gmail.com
```
