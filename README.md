# CS416-Dashboard-Project
public repository to house CS416 Dashboard data for grading purposes


In this repository you will find:
  1. a word doc titled "Dashboard Project Instructions" that asnwers the review criteria questions for the project
  2. An Excel file "Table 5" dataset that summarizes crime by state for 2019. This was downloaded from the FBI.gov website found here: https://ucr.fbi.gov/crime-in-the-u.s/2019/crime-in-the-u.s.-2019/topic-pages/tables/table-5
     - This data had to be cleaned in order to show totals, in some cases this data was formed using some estimates/extrapolations on population crime rates. These extrapolations were performed by the fbi to get a 100% population estimate for each state.
     - data for each crime category was then used to calculate a crime rate per 100k, in addition a total crime rate was created based on the summation of violent and property crime rates (two mutually independent categories)
     
  3. An Excel file "Table 6" dataset that summarizes crime in the US by year (2000-2019). This was also downloaded from the fbi.gov website found here: https://ucr.fbi.gov/crime-in-the-u.s/2019/crime-in-the-u.s.-2019/topic-pages/tables/table-1
     - This data was also cleaned in a similar fashion to 2 above; however, because of the constraints on the dashboard being one page and a timeline chart taking up a lot of room, I ultimately didn't use it in the project (although a sheet does exist for it)
  4. **A FINAL CLEANED DATASET "FBI Violent and property crimes by state and year (Union) was used for the project. this is simply a union of the state dataset (2) and year dataset (3).** This was done because the crime categories were already very similar and it made it     easier to report in tableau. some columns were added (state and year) in this dataset to properly capture some of the differing fields between the two.
     - the yearly data was not used in the project although could be utilized later if need be. it did need to be filtered out in the sheets to make the summations correct


# Additional considerations
1. the data used was only cleaned to get rates per 100k citizens because raw volume would be biased towards larger populous states
2. The heat map contains a cool to hot coloring, but is a different enough color scale to not be confused by violent crime (red) and property crime (blue)
3. other international crimesets were investigated (UN crime set) but were found to be to varying between the relative definitions and types of crimes to that of the FBI's definition, and so only the FBI state 2019 set was used
4. Cross filtering is the ability to select multiple states in any of the charts and have it filter to those specific states in the other charts
5. the violent crime and property crime visuals initially are somewhat tight (the state name isn't fully visible). however once filtered the names can become visible. This was done to give a 1000ft view of the data with the knowledge that hovering would display the name of any bar that was desired
