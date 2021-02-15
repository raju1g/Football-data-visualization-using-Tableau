# Football data visualization using Tableau
 I use Tableau and its various features to visualize some of the highlights from the Veikkausliiga season 2020 data and create a highly interactive, informative and engaging dashboard. The Tableau file called `Veikkausliiga 2020_dashboard.twb` contains 1 main dashboard comprising of 6 separate workbooks each of which analyses a particular metric using the free (limited) data available to download in CSV format from https://fbref.com/en/ 
 
**Data import**:The season data is stored in a single file as noted by the filename: `sportsref_download_Veikkausliiga2020.txt`. Each line in the file represents some information and key season stats for a *player*, as identified by `Player` column. An example of this is shown below:

!rawdata[screenshot/import.PNG]

*Note*: This season data (free) downloaded from the aforementioned website has significant limitations. It mainly contains player information in terms of performance (frequency of scoring goals, assits, etc.). It does not contain any location data (x-, y-coordinates on the pitch) so that advanced analysis such as, modeling can not be perfomed. 

**Understanding the data**: Upon performing a quick search on the file, it is apparent that only the frequency of some performance related metrics such as, `Total starts`, `Total goals scored`, `Total assists`, etc. can be visualized. Depending on the need, separate worksheets were created for each observable metric. All the examples are shown below:

