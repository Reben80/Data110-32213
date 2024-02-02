## Week Two Recap: Diving into the World of Data Visualization

---

### 1. Inspiration Behind Some Data Visualization Graph
The graph design of our dataset is inspired by the iconic visual from Joy Division's 1979 album, "Unknown Pleasures." This design has influenced a wide array of designers and data visualization enthusiasts.

![Joy Plot Inspired Design](media/joy-plot%201.jpg)


[Watch the Video on Joy Division - Unknown Pleasures](https://www.youtube.com/embed/oo7lt0lLOvg?start=436&amp;feature=oembed)

---

### 2. A Journey Through Data Visualization History
A good place to learn about History of Data Visualizaion is the articale  "A Brief History of Data Visualization" by Michael Friendly to understand the evolution and milestones in visualizing data.

[A Brief History of Data Visualization](A_Brief_History_of_Data_Visualization-2.pdf)

---

### 2. Important of Data Visualizaion
Anscombe's quartet consists of four datasets that have the same statistical properties but different distributions, highlighting the importance of visualizing data.

![Anscombe's Quartet](media/2560px-Anscombe's_quartet_3.svg.png)

[Learn More About Anscombe's Quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet)

---

### 2.1 Further Exploration in Data Visualization
We watched "Same Stats, Different Graphs - CHI 2017," emphasizing the significance of visual representation in data.

[Watch the CHI 2017 Video](https://www.youtube.com/embed/DbJyPELmhJc?feature=oembed)

---

### 2.2 Additional Resources for Insight
 We examined resources that provide insights into data correlations and their visual representations.

[What data patterns can lie behind a correlation coefficient?](what-correlations-look-like.pdf)


---

### A Powerful Visualization Example
We reviewed a New York Times article as an excellent example of meaningful data visualization and storytelling. 

[Read the NY Times Article on ‘Stop-and-Frisk’](https://www.nytimes.com/interactive/2014/09/19/nyregion/stop-and-frisk-is-all-but-gone-from-new-york.html?_r=0)

---

### Exploratory vs. Explanatory Visualization: A Comparative Study
We compared Exploratory Visualization (used for analyzing and understanding data) with Explanatory Visualization (used for communicating findings or narrating a story).

#### Examples:
- [Map of Reddit](https://anvaka.github.io/map-of-reddit/?x=19992.255291973044&y=21168.629572051443&z=6703.234703310886&v=2) (Exploratory)
- [The Fallen of World War II](http://www.fallen.io/ww2/) (Explanatory)
- [538: Various Sports Analyses](http://fivethirtyeight.com/) (Explanatory)

**Question of the Week:**
"In data-driven fields, do business analysts primarily use exploratory visualization while data scientists lean towards explanatory visualization for definitive insights?"

---

## Python Lab 1 :Google Colab Introduction and Data Visualization



This week we delved into the powerful capabilities of Google Colab for data analysis and visualization. Here's a breakdown of our learning journey:

## 1. Introduction to Google Colab
   - Explored the versatile environment of Google Colab, a platform that enables running Python code in the browser.

## 2. Package Importation in Google Colab
   - Mastered the process of importing essential data analysis packages such as `matplotlib` for visualization and `pandas` for data manipulation.
   ```python
   import matplotlib.pyplot as plt
   import pandas as pd
   ```

## 3. Plotting Basic Graphs
   - Learned to create simple line graphs using `plt.plot` from the `matplotlib` library with two lists of numbers of the same length.
   ```python
   plt.plot(list1, list2)
   plt.show()
   ```

## 4. Graph Aesthetics Enhancement
   - Enhanced the visual appeal of graphs by customizing aesthetic aspects such as color, style, width, and grid.
   ```python
   plt.plot(list1, list2, color='blue', linestyle='--', linewidth=2)
   plt.grid(True)
   plt.show()
   ```

## 5. Data Reading with Pandas
   - Utilized `pandas` to efficiently read external data from CSV files, an essential skill for data analysis.
   ```python
   data = pd.read_csv('your_data.csv')
   ```

## 6. Creating Scatter Plots
   - Generated insightful scatter plots using data from the `happiness_2017.csv` file, a practical application of data visualization.
   ```python
   plt.scatter(data['column1'], data['column2'])
   plt.show()
   ```


### Week 2 Assignment

1. **Understanding Anscombe's Quartet**:
   - Complete the tasks in the Jupyter Notebook. Ensure the notebook is compatible with Google Colab for a seamless experience.
   - [Understanding Anscombe's Quartet Notebook](Understanding_Anscombe's_Quartet.ipynb)

2. **Exploring Temperature Trends in Death Valley**:
   - Open and run all the code cells in the Jupyter Notebook. Verify that it runs smoothly on Google Colab.
   - [Exploring Temperature Trends in Death Valley Notebook](W2_Matplot_plot.ipynb)


