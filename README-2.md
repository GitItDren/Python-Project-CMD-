# Houses:  The Lost American Dream
## General Information
The American Dream, since it was first used in the early 1930’s has represented a belief that every individual, regardless of their background, could pursue a life they envisioned for themselves.  Central to this dream is the idea that with hard work and dedication a life of prosperity and happiness could be attained through home ownership.  It has long been understood that by owning a home, one might gain financial independence and even wealth, not to mention a place to call one’s own.
However, the American Dream and the hope many have of home ownership has faced significant challenges during the past 20 years.  This is why we have entitled our project, **Houses:  The Lost American Dream** and have hypothesized that the correlation between Federal Reserve policy and home prices has effectively made owning a home for many elusive if not outright unattainable.
Our project, **Houses:  The Lost American Dream** looks at how one contributing factor, the Federal fund rate impacted averaged home prices in four cities, during the 20 year period between 1996 and 2016, to understand why many consider the American Dream……lost.
We will use *Python* and *Pandas* to create the code that will enable us to prove or disprove our hypothesis about the relationships between our variables and *MatplotLib* to make visual representations of the results.

To generate the results for our Project on your devices you will need to ensure you are using the source data we’ve provided and the same applications we’ve used to complete our project, **Houses:  The Lost American Dream**

## Project Steps
1. **Topic Exploration & Creating a Hypothesis –** Discussed various topics of group interest.  Ultimately decided upon the correlation between Home Prices and Interest Rates because of recent news reports of Federal Reserve activity.  We were interested in discovering what overall impact these policy changes have had, historically.
2. **Data Gathering -** Researched and collected from several sources the Federal Effective Fund Rate and the Housing Price Indices for the 20 years between 1996-2003
3. **Data Cleaning -** The time and effort spent preparing, modifying and merging the data to ensure we would have quality data for our analyses and visualization steps.
4. **Visualizing –** From the datasets, we created variables and axes to create multiple line plots that visualized how interest rates and federal/state housing prices fluctuate.
5. **Analyzing –** Reviewed the graphs and made assumptions about the actual data compared to our initial Hypothesis
6.	**Presentation –** Created a PowerPoint template to present the components of our project.  We each contributed summary information on the slides we are to present to the class.

## Project Instructions 

Even though our project focuses on the 20 years between 1996 and 2016, the framework for our analysis will work for any period of data when the following instructions are followed:

1.  Download and export in .csv State HPI data, for any State and for any timeperiod, from any source, we used the Federal Reserve Bank of St. Louis' website
2.  Download and export in .csv Federal interest rates from any source, we used kaggle.com
3.  Save the .csv files to a Resources folder in any location on your PC/Mac
4.  It may be necessary to update the file names referenced in dataframes if using data from other states.  If modifications are necessary complete these before attempting to run the code. 
5.  Open and run the code using Jupyter Notebook
6.  Review your findings and make adjustments accordingly

## Links
[MD HPI](https://fred.stlouisfed.org/series/MDSTHPI) - All-transaction house price index for Maryland, retrieved from FRED, July 18, 2023

[TX HPI](https://fred.stlouisfed.org/series/TXSTHPI#0) - All-transaction house price index for Texas, retrieved from FRED, July 18, 2023

[CT HPI](https://fred.stlouisfed.org/series/CTSTHPI) - All-transaction house price index for Conneticut, retrieved from FRED, July 18, 2023

[WA HPI](https://fred.stlouisfed.org/series/WASTHPI) - All-transaction house price index for Washington, retrieved from FRED, July 18, 2023

[US HPI](https://fred.stlouisfed.org/series/USSTHPI) - All-transaction house price index for United States, retrieved from FRED, July 18, 2023

[FED INT RATE](https://www.kaggle.com/datasets/federalreserve/interest-rates) - Monthly Federal Reserve Interest Rate, retrieved from kaggle.com and Federal Reserve Bank of St. Louis

[62-YrFFR](https://www.macrotrends.net/2015/fed-funds-rate-historical-chart) - Federal Funds Rate for past 62 years, retrieved from macrotrends, July 25, 2023

[MrkdwnSht](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - Reference and Cheatsheet containing Markdown requirements

[FedBkRt](https://www.bankrate.com/banking/federal-reserve/history-of-federal-funds-rate/#2011) - Federal Interest Rate history with commentary back to 1980s, retrieved from BankRate, July 25, 2023

### Interview with Dren


### Interview with Ciin
1. CHALLENGES FACED: I had trouble using two different scales of measurement for the y-axis. Because I had to plot both housing price and federal interest rates, I didn't even know having two y-axes was possible. It wasn't until Jason told me that it is and I just need to search up "python 2nd y-axis" that I found the answer. I know now that when I'm in doubt, just search it up. 
2. One thing that I'm proud of has to do with cutting the datasets so they could align with each other. I found out I couldn't graph two different csvs' because they did not have the same number of rows. The way I did this was by creating a new df but adding ".head(55)". 55 is the number of rows I wanted.
3. At the end of this project, I learned that a majority of coding is looking things up online. I can't expect myself to remember every line of code and its function, so I had to learn how to accept that without feeling defeated. 

### Interview with Marvina
1. I am proud of myself for having come this far in the program.  I am proud of the fact that I was successful at coding my portion of the project which included:  reading in the .csv files, researching how to convert the date from MM/DD/YYYY to YYYY/MM/DD which was used for all HPI and Fed Int Rate files and researching how to merge the six files using a concat(), I created the dataframes and checked the results of each cell of code with info () or head/tail ().  I am also very proud of the fact that I created a ReadMe file for the first time, and it looks pretty good.
2. A major challenge I knew I would face was how to merge HPI files containing quarterly dates with the Federal Interest Rates containing monthly dates.  Another challenge I experienced was syncronizing everyones contributions to ensure there wasn't file duplication and code duplication.
3. What did you learn in the process?  I learned that I am more than capable.  I learned that I've come along way in this program from Day 1.  I learned that working on large projects effectively can lighten the load and provide opportunities for other ways of thinking and doing.  I learned constant communication is essential when dividing to conquer major projects.  I learned GitHub is a great tool, I just need to use it more efficiently.
