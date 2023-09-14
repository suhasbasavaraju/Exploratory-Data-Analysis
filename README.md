# Exploratory-Data-Analysis
This repository encompasses a comprehensive analysis of risk analytics within the banking and financial services domain. The primary focus of this project lies in the Exploratory Data Analysis (EDA) performed on the provided dataset, with the target variable being 'TARGET.'

The data preprocessing phase involved meticulous handling of missing values and outliers across all variables. Additionally, thorough data type validation and conversion were executed to ensure data integrity.

The EDA phase comprised several facets of analysis:

Univariate Analysis: Utilizing boxplots and distribution plots, a detailed examination of individual variables were conducted. This process facilitated the identification of outliers, offered insights into variable behaviors, and provided an understanding of variable distributions. Both unordered categorical and ordered categorical variables underwent dedicated univariate analysis.

Bivariate Analysis: This phase was categorized into three distinct categories: numeric-numeric, numeric-categoric, and categoric-categoric. This analysis aimed to unearth relationships between variables, assess dependencies, and reveal patterns between numeric and categorical attributes.

Multivariate Analysis: Employed techniques such as pivot tables and data visualization, particularly through heatmaps to delve deeper into variable behavior concerning the target variable, . This process allowed me to explore complex interactions between two variables in the context of the target variable.

Correlation Analysis: Heatmaps were also used to visualize correlations between variables, shedding light on the interdependencies within the dataset.

Furthermore, this repository includes the merging of the 'application_data' and 'previous_application' datasets based on the 'SK_ID_CURR' column using an inner join operation. The merged dataset facilitated the derivation of valuable insights from the combined data.

After merging, I tried to extend univariate and bivariate analyses to specific variables within the merged dataset, to extract meaningful insights and patterns.

Lastly, multivariate analysis was carried out to investigate relationships between variables concerning the target variable and the contract status variable from the 'previous_application' dataset. Heatmaps were once again employed to enhance the visualization of these complex associations.

Please note that detailed insights obtained at each stage of the variable analysis have been thoughtfully documented as comments within the Jupyter Notebook for reference and transparency.
