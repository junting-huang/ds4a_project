## ds4a_project (team 54)
This is an archive for all notebook files created for the DS4A Project (Team 54).

Effective 2021, the federal government promulgated a new rule for hospitals requiring them to disclose pricing on a wide range of hospital services. This project explored how this price transparency regulation can help patients understand costs, and examine the relationship between hospital pricing and demographic data in Michigan. 

![alt text](https://github.com/junting-huang/ds4a_project/blob/main/Team%2054.png)

See the [Project Feature](https://www.correlation-one.com/blog/ds4a-capstone-project-spotlight-is-your-hospital-bamboozling-you). Or read the [Final Report](https://www.correlation-one.com/hubfs/Datafolios/Empowerment%202.0%20Capstone%20Project%20Datafolio/Team_54_Final%20Report.pdf.pdf) of this  project.

## File List

* data folder
  * df_hospital_clean.csv (hospital data)
  * df_population.csv (demographic data)
  * df_price_clean.csv (pricing data)
* data_schema_diagram.drawio </br>
This is the diagram for the data schema.

* batch_processing_excel_files.ipynb </br> 
This notebook is created to batch process excel files. It reads and extracts a selection of features by cpt_code.

* dataset_merging_check.ipynb </br>
This notebook prepares all dataframes for the merging. It checks foregin keys for typos, erros, and potentially missing values.

* eda_nyembo.ipynb </br>
This notebook is the first version of eda, developed by kasole nyembo.

* knn_imputation.ipynb </br>
This notebook is the first implementation of knn imputation, which did not end up in the final product.

* regression_model.ipynb </br>
This notebook is the main file for predictive modeling. In addition to model selection/optimization, it also contains correlation matrix and pca biplot for the eda.
