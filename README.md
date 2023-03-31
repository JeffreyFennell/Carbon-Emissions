# Carbon Emissions Data Project

## Overview:
Climate change has been a growing topic of concerns for what seems forever now. Despite all of the news headlines and horrible milestones that the entire Earth has encountered, we still seem to be operating in a such a way that would all but guaranteed absolute fiery doom. Well... not our but your children's children's children's children's yada yada yada. I'm sure they wouldn't like the burn, though. I've heard it's not all that pleasant a sensation. 

Enter this beginner level project. I'll be using my rudimentary analytical skills to try to paint a picture of where we started and where we're going in terms of carbon emissions. It should be noted, however, that emissions are but one part of the climate/environmental crisis. It's a multifaceted problem, after all. Have you heard of the trash island floating in the ocean?!

## Requirements:
- Please make sure to run the included requirements.txt before attempting to execute the project.
- To begin, open the carbon_emissions_final.ipynb.
- The .ipynb  will be accessing the co2_emissions_kt_by_country.csv dataset located in the assets folder so ensure that you are working in the correct directory.
- There is an additional backup_country_codes.csv listed under assets just in case my raw country codes data doesn't properly read in via the url. If the url fails, then follow the marked down instructions in the jupyter notebook.

## How to read project:
Personally, I write in a conversational tone. I view this project as more of a teachable piece for me and less so a professional showcase for future employers. I've marked down pieces of code to help explain why it was needed and what it was accomplishing. Hopefully, this will serve as an aid for me in the future when I'm working on future, more serious projects.

## Questions being answered:
- Per the data, which countries currently produce the most carbon?
- What is the US's general history of carbon emission?
- Compare US to other countries within the top 5 carbon emitters.
- How are US emissions trending amidst current talks of climate change and global warming? 
- Percentage of world emissions for each of the top 5?

## Code Louisville Project Requirements:
- Read in CSV files
    - via local file
    - via URL
- Manipulated and Cleaned data
    - Briefly demonstrated pivoting and transposing dataframes
    - Rounded data to nearest hundredths
    - Renamed columns for better readability
    - Used second CSV file to help filter primary CSV (Hardcore coding right there!)
    - Sorted data by specific date
        - Then via carbon output in descending order (Ascending = False)
    - Utilized concatenination to combine two separately created dataframes.
- Analysis
    - Trendlines were generated
    - Percentage of the world output was calculated per top 5 country.
    - Percent change calculated on data points.
    - Used basic math functions
        - Helped with generating pie charts
        - Helped with calculating percent change (mentioned above)
- Visualize Data
    - Multiple graphs were generated.
    - Experimented with multiple axes in a single figure. Haven't quite gotten the hang of that one. I feel there is room for improvement and downsizing the amount of code present. (See Japan, India, and China figure)
    - Actually created a relevant pie chart.
        - Was able to determine percentage of output on a worldwide scale.


## Sources:
- Dataset:          https://www.kaggle.com/datasets/ulrikthygepedersen/co2-emissions-by-country
- Country Codes:    https://raw.githubusercontent.com/lukes/ISO-3166-Countries-with-Regional-Codes/master/all/all.csv

## Special Recognition
- Where would we be without ChatGPT? It's such a helpful tool.
- Thank you to the numerous websites and tutorials and StackOverflow queries.
- Finally, I owe thanks to the mentors of my Code Louisville session. It has been quite the journey.