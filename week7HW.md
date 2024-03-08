### Week 7 Assignment: Data Manipulation and Visualization with Pandas and Matplotlib

#### Objective:
The goal of this assignment is to enhance your skills in data manipulation and visualization using Python, specifically through the pandas and matplotlib libraries. You will work with the penguins dataset to apply filtering, sorting, grouping, and visualization techniques learned this week.

#### Dataset:
The dataset you will be using is the `penguins` dataset, which contains various measurements for three species of penguins from different islands in Antarctica.

#### Tasks:

1. **Data Exploration**:
   - Load the penguins dataset using seaborn's `load_dataset` function. If seaborn is not installed
   - Display the first 10 rows of the dataset to understand its structure.
   - Use the `.describe()` method to get a statistical summary of the numerical columns in the dataset.

2. **Data Filtering**:
   - Filter the dataset to include only those penguins with a body mass greater than 4000 grams. Store this subset in a new DataFrame and display the first 5 rows.

3. **Conditional Filtering**:
   - Create a subset of the data where the penguin's bill length is between 40 mm and 50 mm, and the bill depth is less than 18 mm. Display the shape of the resulting DataFrame.

4. **Data Grouping and Aggregation**:
   - Group the dataset by `species` and `island`, and calculate the average `flipper_length_mm` for each group. Sort the results in descending order of flipper length.

5. **Advanced Visualization** (Replacing Task 5):
   - Create a histogram to visualize the distribution of penguin body masses. Use different colors to differentiate between the species. Ensure your histogram is clearly labeled with a title, x-axis and y-axis labels, and a legend.

6. **Utilizing Loops for Visualization**:
   - Using the `zip` function learned this week, write a loop to create a separate histogram for each island showing the distribution of flipper lengths. Ensure each histogram has a title indicating the island being visualized, and clearly label your axes.

#### Submission Requirements:
- Submit a Jupyter notebook ( or google colab) containing the completed tasks, including comments explaining your code where necessary.



