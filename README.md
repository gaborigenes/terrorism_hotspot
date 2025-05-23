# terrorism_hotspot

Personal project for improve data analysis tools like Python, SQL, Power BI and Excel. This data project has been used as an assignment during the LGM Data Science Virtual Internship and can be found in https://platform.stratascratch.com/data-projects/terrorism-hotspots.

To practice my data analysis tools i'll post a solution using 
- Microsoft Excel with power pivot and power Query
- Microsoft SQL Server
- Python using jupyter Notebooks

# Assignment
Imagine you are a security or defense analyst. Analyze the data and draw conclusions on the distribution and nature of terrorist incidents recorded around the world. In your analysis, include maps that visualize the location of different incidents. Your analysis may also provide answers to the following questions:

- How has the number of terrorist activities changed over the years? Are there certain regions where this trend is different from the global averages?
- Is the number of incidents and the number of casualties correlated? Can you spot any irregularities or outliers?
- What are the most common methods of attacks? Does it differ in various regions or in time?
- Plot the locations of attacks on a map to visualize their regional spread;
You are also free to explore the data further and extract additional insights other than the questions above.

# Data Description
The provided compressed file globalterrorismdb_0718dist.tar.bz2 is an extract from the Global Terrorism Database (GTD) - an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.

Since the number of variables and instances is very large, for this project, feel free to select a subset of columns or a specific timeframe.

Explanation of selected columns:

- success - Success of a terrorist strike
- suicide - 1 = "Yes" The incident was a suicide attack. 0 = "No" There is no indication that the incident was a suicide
- attacktype1 - The general method of attack
- attacktype1_txt - The general method of attack and broad class of tactics used.
- targtype1_txt - The general type of target/victim
- targsubtype1_txt - The more specific target category
- target1 - The specific person, building, installation that was targeted and/or victimized
- natlty1_txt - The nationality of the target that was attacked
- gname - The name of the group that carried out the attack
- gsubname - Additional details about group that carried out the attack like fractions
- nperps - The total number of terrorists participating in the incident
- weaptype1_txt - General type of weapon used in the incident
- weapsubtype1_txt - More specific value for most of the Weapon Types
- nkill - The number of total confirmed fatalities for the incident
- nkillus - The number of U.S. citizens who died as a result of the incident

The provided .tar.bz2 file is a compressed CSV file. Its contents can be loaded to a Pandas DataFrame using the read_csv() method from the Pandas library as follows:




