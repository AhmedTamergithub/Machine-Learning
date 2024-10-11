
What is np?

In machine learning, np refers to NumPy, a Python library used for efficient numerical computations. It plays a key role in handling large datasets by providing multi-dimensional arrays (np.array) and offering fast mathematical operations. NumPy is commonly used for linear algebra, matrix manipulations, random number generation, and statistical calculations—crucial for training models and performing optimizations.

What is plt?


In Python, plt refers to Matplotlib's pyplot module, which is commonly imported as plt. It is a powerful tool for creating a wide variety of plots and visualizations. pyplot provides functions to generate graphs, such as line charts, histograms, scatter plots, bar charts, and more, making it essential for data visualization in machine learning and data science.

Plt built in methods:Here are some commonly used built-in functions of plt (Matplotlib's pyplot module):
1. plt.plot()

    Creates a line plot.
    Example:

    ```python

    plt.plot([1, 2, 3], [4, 5, 6])

2. plt.scatter()

    Creates a scatter plot.
    Example:

     ```python

    plt.scatter([1, 2, 3], [4, 5, 6])

3. plt.bar()

    Creates a bar chart.
    Example:

    ```python

    plt.bar([1, 2, 3], [4, 5, 6])

4. plt.hist()

    Creates a histogram.
    Example:

     ```python

    plt.hist([1, 2, 2, 3, 3, 3, 4])

5. plt.pie()

    Creates a pie chart.
    Example:

    ```python

    plt.pie([10, 20, 30], labels=['A', 'B', 'C'])

6. plt.xlabel() and plt.ylabel()

    Set the labels for the x and y axes.
    Example:

     ```python

    plt.xlabel('X-axis')
    plt.ylabel('Y-axis')

7. plt.title()

    Adds a title to the plot.
    Example:

     ```python

    plt.title('Sample Plot')

8. plt.legend()

    Displays a legend for the plot.
    Example:

     ```python

    plt.legend(['Line 1'])

9. plt.grid()

    Adds a grid to the plot.
    Example:

     ```python

    plt.grid(True)

10. plt.show()

    Displays the plot.
    Example:

     ```python

    plt.show()

These functions help customize and create different types of plots to visualize data effectively in Python.


n Python, the .shape attribute is primarily used with NumPy arrays to get the dimensions (shape) of the array. It returns a tuple indicating the size of the array along each dimension.
Example:

  ```python

import numpy as np

# Creating a 2D NumPy array (matrix)
arr = np.array([[1, 2, 3], [4, 5, 6]])

# Getting the shape of the array
print(arr.shape)

Output:
(2, 3)















 ```


Explanation:

    The array has 2 rows and 3 columns, so the shape is (2, 3).

General Use of .shape:

    .shape is useful when working with multi-dimensional arrays, matrices, or tensors, allowing you to inspect the structure of the data.
    For example, in machine learning, .shape is often used to check the dimensions of input data, weights, or output data.

Usage in Machine Learning:

In machine learning, .shape is frequently used for:

    Input data: Checking the number of samples and features.
    Weight matrices: Ensuring the dimensions of matrices are compatible for operations like matrix multiplication.
    Tensor operations: When working with deep learning frameworks like TensorFlow or PyTorch, .shape is used to handle high-dimensional data.






