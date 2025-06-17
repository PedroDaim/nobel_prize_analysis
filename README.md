# Nobel Prize Data Analysis: Informing Strategic Philanthropy for The Global Laureate Initiative (GLI)

## Project Overview

This project analyzes historical Nobel Prize winner data to uncover key trends and patterns. The insights derived from this analysis are designed to inform the strategic grant-making, advocacy, and partnership initiatives of The Global Laureate Initiative (GLI), a non-profit philanthropic foundation focused on fostering excellence, diversity, and impact in global academic and peace efforts.

This project demonstrates proficiency in data cleaning, preprocessing, exploratory data analysis (EDA), and data storytelling, with a strong focus on translating data insights into actionable business recommendations.

## Business Problem

The Global Laureate Initiative (GLI) seeks to understand historical trends and patterns in Nobel Prize awards. By identifying areas of significant disparity, concentrations of excellence, and the impact of economic factors on recognition, GLI aims to optimize its resource allocation, develop targeted programs, and advocate for policies that promote greater diversity, encourage innovation, and support future laureates.

## Key Business Questions Addressed

This analysis focuses on providing data-driven answers to the following critical business questions for GLI:

1.  **Gender Diversity & Trends in Laureates:** To inform our strategic initiatives on diversity and inclusion in academia, what are the historical trends and patterns of gender representation among Nobel laureates, including the impact of pioneering female recipients, and which categories or decades show significant progress or disparity?
    * *Objective:* To identify specific Nobel Prize categories and historical periods demonstrating significant underrepresentation or disparities in female laureates, in order to pinpoint critical areas where GLI should focus its grant-making, advocacy, and outreach efforts to enhance gender diversity and equitable recognition.

2.  **Top Organizations, Multi-Laureates & Economic Correlation:** To identify and potentially partner with leading global academic environments, which organizations (with available data from 1960 onwards) have consistently fostered Nobel-winning achievements, and what is the correlation between their success, the prevalence of multi-laureate individuals associated with them, and the economic strength (GDP) of their respective host countries?
    * *Objective:* To identify leading organizations (with available data) that have consistently fostered Nobel-winning achievements, and to analyze the correlation between these organizations' success, the prevalence of multi-laureate individuals associated with them, and the economic strength (GDP) of their respective host countries. This analysis will inform strategies for investing in environments that demonstrate a high return on academic excellence.

3.  **National Trends & Performance (e.g., US focus):** To inform national investment strategies in academic excellence, which historical periods demonstrate the most significant concentration of Nobel laureates originating from specific high-performing nations (e.g., the US), relative to total global awards, and what insights can be drawn from these peaks?
    * *Objective:* [**TO BE DEFINED LATER** - We'll define this objective and its KPIs when we work on this section.]

## Key Findings / Insights

*(This section will be filled in once the analysis is complete. Examples below are placeholders.)*
* Insight 1: For example, "Physics and Chemistry consistently show the lowest female laureate representation throughout history, highlighting a critical area for GLI's targeted grant programs."
* Insight 2: For example, "A strong positive correlation was observed between a country's GDP per capita and the number of Nobel Prizes awarded to its organizations, particularly in recent decades, suggesting the importance of economic investment in research infrastructure."
* Insight 3: For example, "The mid-20th century marked a peak for US-born Nobel laureates, indicating a period of significant scientific and academic flourishing in the country."

## How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/nobel_prize_analysis.git](https://github.com/yourusername/nobel_prize_analysis.git)
    cd nobel_prize_analysis
    ```
2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Download Data:**
    * Place your Nobel Prize dataset (e.g., `nobel_prize_data.csv`) into the `data/raw/` directory.
    * Place your GDP dataset (e.g., `gdp_data.csv`) into the `data/raw/` directory.
5.  **Run Jupyter Notebooks:**
    Launch Jupyter Lab or Jupyter Notebook from the root directory:
    ```bash
    jupyter lab
    ```
    Navigate to the `notebooks/` directory and run the notebooks in the following order:
    * `01_data_ingestion_and_cleaning.ipynb`
    * `02_gender_diversity_analysis.ipynb`
    * `03_orgs_multi_laureates_gdp_analysis.ipynb`
    * `04_national_trends_analysis.ipynb`

## Technologies Used

* Python 3.x
* pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Jupyter Lab

## Data Sources

* Nobel Prize Laureate Data: [Specify your DataCamp source or original Kaggle/other source if different]
* World Bank GDP Data (1960-2020): [Specify your Kaggle source URL for GDP data]

## Limitations

* **Missing 'Organization Name' Data:** Approximately 26% of 'organization name' entries are missing, which may limit the comprehensiveness of analysis specifically for organizational affiliations. The analysis on organizations focuses only on available data.
* **GDP Data Timeframe:** Analysis involving GDP correlation is restricted to the 1960-2020 period due to the availability of the GDP dataset. Other analyses utilize the full Nobel Prize dataset where applicable.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

[Your Name] - [Your Email] - [Your LinkedIn Profile URL (optional)]
