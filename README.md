# India-s-Most-Pleasant-Unpleasant-Cities-using-PCA-in-Python

Statistical Analysis of NASA's Climate Data for Unveiling India's Most Pleasant & Unpleasant Cities using PCA in Python.

Objective: Which cities in India have the overall most pleasant climate?
What about extreme climate events?

Introduction
The project aims to utilize NASA's climate data, collected from 1984 to 2021, for 34 cities in India. The dataset contains 26 climate variables and has dimensions of 34 rows and 353,731 columns. By applying Principal Component Analysis (PCA) in Python, the project aims to rank the cities based on their pleasant climate scores.

Significance
This project holds significant importance for various stakeholders, including researchers, urban planners, and individuals seeking information about the most pleasant cities in India. By analyzing climate data and identifying cities with favourable climatic conditions, this project can provide valuable insights for decision-making regarding city selection, tourism, or relocation.

Procedure
I collect the climate data sets having 26 parameters for the top 34 Indian metropolitan cities from 1 Jan 1994 to 31 Mar 2021 from NASA, POWER | Data Access Viewer. Therefore each data set has 13,605 rows and 26 columns. Then I clean the data sets as there were some descriptions in each data set. Then I convert the 3D data set to a 2D data set as follows: I flatten all rows in one row for each data set so that the column number becomes 353730. Then I merge the flattened data sets by rows. Then I got the final required data set has 34 rows and 353731 columns. Then I perform PCA on that data and sort the first principal component ascendingly. Then I got the required rank.

Findings
The project's findings reveal the top pleasant climate cities in India, based on the rankings derived from the first principal component. The cities are presented in ascending order, with their corresponding PCA scores.

Furthermore, I have noticed clear patterns showing that extreme climate events are gradually increasing in most cities, suggesting a potential impact of climate change.

Interpretation
As we flatten the rows so that City has an extreme climate, got a positive PCA Score. As it has had high value for a long time. On the other hand, which city has a pleasant climate that city got a negative PCA score. As it has had a high value for a short time Therefore the negative PCA scored cities are overall more pleasant climates City. So Kochi, Visakhapatnam, Tenkasi, Chennai, Coimbatore, Madurai, Thekkady, Belgaum, Mysore, Mumbai, and Bengaluru has a pleasant climate. And Srinagar, Shimla, Nainital, Ludhiana, Chandigarh, Meerut, Delhi, Agra, and Kanpur has extreme climate.

Source:
https://power.larc.nasa.gov/data-access-viewer/ NASA/POWER CERES/MERRA2 Native Resolution Daily Data Dates (month/day/year): 01/01/1984 through 03/31/2021 Elevation from MERRA-2: Average for 0.5 x 0.625 degree lat/lon region = 162.41 meters The value for missing source data that cannot be computed or is outside of the sources availability range: -999
