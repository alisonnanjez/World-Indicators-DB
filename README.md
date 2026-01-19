# Global Socio-Economic Data Analysis

![World map](https://github.com/user-attachments/assets/7dbacd1d-a5f2-4d65-bcde-c97cbf076ff1)

### What the Project Does

This project performs a comprehensive analysis of global development indicators—including GDP, life expectancy, education enrollment, and labor statistics—using a relational database approach. It takes raw socio-economic data from Kaggle and transforms it into a structured SQLite database (`world_data_v4.db`) consisting of five dimension tables (`demographics`, `economy`, `education`, `labour`, and `lifespan`) and a central `country_facts` table. Using SQL within a Jupyter Notebook environment, the project extracts high-level insights such as regional GDP growth rankings, gender disparities in education, and health extremes across 204 countries.

### Why the Project is Useful

Understanding the interconnectedness of economic health and social well-being is crucial for identifying global development trends. This project is useful because:

* **Structured Analysis:** It demonstrates how to turn flat CSV data into a relational schema for more efficient and complex querying.
* **Actionable Insights:** It identifies which regions are outperforming global averages in growth and where significant health or employment crises exist.
* **Technical Showcase:** It serves as a template for using advanced SQL techniques like **Common Table Expressions (CTEs)**, **Window Functions** (e.g., `RANK()`), and **Conditional Logic** (`CASE` statements) directly within Python-based workflows.

### How Users Can Get Started

To explore this analysis on your own machine, follow these steps:

1. **Clone the Repository:** Download the project files and the Jupyter Notebook.
2. **Install Dependencies:** Ensure you have Python installed, along with the necessary libraries:
```bash
pip install pandas ipython-sql

```


3. **Download the Data:** Obtain the "Global Data: GDP, Life Expectancy & More" dataset from [Kaggle](https://www.kaggle.com/datasets/arslaan5/global-data-gdp-life-expectancy-and-more).
4. **Run the Notebook:** Open the Jupyter Notebook. The first few cells will handle the data cleaning, subdivision of CSVs, and the creation of the `world_data_v4.db` file.
5. **Execute SQL Queries:** Use the `%load_ext sql` and `%%sql` magic commands provided in the notebook to interact with the database and view the insights.

### Contributions

Contributions to improve the analysis or add new data dimensions are welcome!
