# The-Best-College-Towns-for-Remote-Workers-Project
This repository is about a comprehensive ranking project that provides a list of top US college towns ideal for remote workers. The repository includes Python code in a Jupyter Notebook, data and results folders, and a README file with instructions. 

### Methodology & Sources: 
The data used was collected from different sources; 

The list of college towns was gotten from wikipedia (https://en.wikipedia.org/wiki/List_of_college_towns#United_States),

The internet speed was obtained from Speedtest(speedtest.net)

Some demographic data(population,median income etc.) was obtained from Bestplaces(https://www.bestplaces.net)

Walkscore and Bikescore of each town was obtained from Walkscore (https://www.walkscore.com/)

Number of coworking space in each town was obtained from CityFeet(https://www.cityfeet.com/cont/coworking-space)

The data for each college town was obtained from the sites above,and the relevant attributes were normalised to bring   the attributes to same scale, using the following weights for each attributes:- Unemployment rate: 10%, Cost of living   index: 20%,Number of eateries per capita: 10%,Number of coworking spaces per capita: 10%, Median income per capita: 15%,
Speed score: 20%, Active Mobility Score: 15%.These weights were assigned based on perceived importance of the attributes to remote workers.The final ranking score was obtained using weighted sum of each score of each attributes taking into  consideration their weights. where missing data was encoutered for any town, the median value of the attribute for the  state was used.
The data was collected between 4th-7th of May,2023.

### Result
the ranking based on weighted sum was used as it is simple and more intuitive and it gave a similar result to topsis method.

### Tableau Dashboard
![Dashboard.png](https://github.com/vaadewoyin/The-Best-College-Towns-for-Remote-Workers-Project/blob/main/Dashboard.png)
