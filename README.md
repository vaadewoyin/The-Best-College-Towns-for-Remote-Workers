# The Best College Towns for Remote Workers. 

### Methodology & Sources: 
The data used was collected from different sources; 

The list of college towns was gotten from wikipedia (https://en.wikipedia.org/wiki/List_of_college_towns#United_States),

The internet speed was obtained from Speedtest (https://www.speedtest.net/performance/united-states)

Some demographic data(population,median income etc.) was obtained from Bestplaces(https://www.bestplaces.net)

Walkscore and Bikescore of each town was obtained from Walkscore (https://www.walkscore.com/)

Number of coworking space in each town was obtained from CityFeet(https://www.cityfeet.com/cont/coworking-space)


The data for each college town was obtained from the sites above,and the relevant attributes were normalised to bring   the attributes to same scale, using the following weights for each attributes:- Unemployment rate: 10%, Cost of living   index: 20%,Number of eateries per capita: 10%,Number of coworking spaces per capita: 10%, Median income per capita: 15%,
Speed score: 20%, Active Mobility Score: 15%.These weights were assigned based on perceived importance of the attributes to remote workers.The final ranking score was obtained using weighted sum of each score of each attributes taking into  consideration their weights. where missing data was encoutered for any town, the median value of the attribute for the  state was used.
The data was collected between 4th-7th of May,2023.

### Result
the ranking based on weighted sum was used as it is simple and more intuitive and it gave a similar result to topsis method. The top 10 rows are shown below:

| Rank | College Towns                      | Unemployment Rate (%) | Cost of Living Index (%) | Number of Eateries per Capita | Number of Coworking Spaces per Capita | Median Income per Capita | Internet Speed Score | Active Mobility Score | Ranking Score |
|------|-----------------------------------|-----------------------|--------------------------|-------------------------------|---------------------------------------|--------------------------|----------------------|-----------------------|---------------|
| 487  | Montreat, North Carolina           | 4.3                   | 121.7                    | 0.865889                      | 0.005831                              | 178.571429               | 123.505              | 31.375                | 1             |
| 606  | Lower Merion Township, Pennsylvania | 7.9                   | 77.8                     | 0.254252                      | 0.003401                              | 72.988095                | 104.953              | 57.800                | 2             |
| 486  | Misenheimer, North Carolina        | 4.1                   | 76.7                     | 0.423077                      | 0.002849                              | 49.857550                | 123.505              | 31.375                | 3             |
| 133  | St. Leo, Florida                   | 5.0                   | 116.7                    | 0.272514                      | 0.001566                              | 72.435395                | 119.080              | 40.000                | 4             |
| 648  | Due West, South Carolina           | 5.4                   | 75.2                     | 0.384972                      | 0.001855                              | 44.179035                | 112.682              | 32.150                | 5             |
| 460  | Tivoli, New York                   | 5.8                   | 116.8                    | 0.226533                      | 0.002503                              | 56.320401                | 113.536              | 54.800                | 6             |
| 162  | Waleska, Georgia                   | 2.7                   | 111.8                    | 0.210867                      | 0.002587                              | 50.398448                | 95.686               | 28.750                | 7             |
| 141  | Blue Ridge, Georgia                | 2.8                   | 101.5                    | 0.139674                      | 0.005141                              | 24.441302                | 95.686               | 28.750                | 8             |
| 395  | Peru, Nebraska                     | 2.2                   | 72.6                     | 0.108043                      | 0.002401                              | 48.122449                | 130.872              | 44.400                | 9             |
| 737  | Craftsbury, Vermont                | 4.3                   | 92.7                     | 0.183365                      | 0.001890                              | 45.218336                | 109.282              | 66.700                | 10            |


### Tableau Dashboard
![Dashboard.png](https://github.com/vaadewoyin/The-Best-College-Towns-for-Remote-Workers-Project/blob/main/Dashboard.png)
