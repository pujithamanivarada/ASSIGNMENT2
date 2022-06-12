1.Make a three-dimensional array with this code below. Here it will arrange the numbers from 0 to 44 as three two-dimensional arrays of shape 3×5. The output will look like this.

x = np.arange(45).reshape(3,3,5)
#output:
array([[[ 0,  1,  2,  3,  4],
        [ 5,  6,  7,  8,  9],
        [10, 11, 12, 13, 14]],
[[15, 16, 17, 18, 19],
        [20, 21, 22, 23, 24],
        [25, 26, 27, 28, 29]],
[[30, 31, 32, 33, 34],
        [35, 36, 37, 38, 39],
        [40, 41, 42, 43, 44]]])

2.Series is a type of list which can take integer values, string values, double value and more. Series can only contain single list with index, whereas dataframes can be made of more than one series or we can say that a dataframes is a collection of series that can be used to analyse the data.

3.Pandas offer a diverse range of built-in functions that can be used to clean and manipulate datasets prior to analysis. It can allow you to drop incomplete rows and columns, fill missing values and improve the readability of the dataset through category renaming.

4.example to convert an array to a dataframe:
import pandas as pd # Create the dataframe df = pd.DataFrame(numpy_array)
df = pd.DataFrame(numpy_array, columns=['digits', 'words']) ...
df = pd.DataFrame(numpy_array, index=['day1', 'day2', 'day3', 'day4'], columns=['digits', 'words']

5.Pandas uses the plot() method to create diagrams. We can use Pyplot, a submodule of the Matplotlib library to visualize the diagram on the screen. Read more about Matplotlib in our Matplotlib Tutorial.
