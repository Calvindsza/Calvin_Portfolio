[Check out the Dashboard I made with Tableau](https://public.tableau.com/app/profile/calvindsza/viz/COVID-19U_S_CasesDashboard/Dashboard1)

<div class='tableauPlaceholder' id='viz1631489827271' style='position: relative'><noscript><a href='https://public.tableau.com/app/profile/calvindsza/viz/COVID-19U_S_CasesDashboard/Dashboard1' target="_blank" rel="noopener noreferrer"><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CO&#47;COVID-19U_S_CasesDashboard&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='COVID-19U_S_CasesDashboard&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CO&#47;COVID-19U_S_CasesDashboard&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                

# [CDC COVID-19 U.S. Case Surveillance](https://github.com/Calvindsza/CDC-COVID-Cases-US)
* Gathered 10M records from the CDC public data set
* Created a time series starting from January 2020
* Frequency plots by gender, ethnicity and age group

![ts](/images/time_series_graph.png)

![age](/images/age_group_graph.png)




# [Johns Hopkins COVID-19 Global Time Series](https://github.com/Calvindsza/JH-COVID-Global-TS)
* Gather time series data from JHU GitHub to create a time series
* Took 3 different time series data sets (deaths, confirmed and recovered) and merged into one dataframe
* Converted Wide to Long format to be able to use in time series

![all](/images/jhu_all_countries_deaths_ts.png)




# [Worldometer Global COVID-19 Cases](https://github.com/Calvindsza/Worldometer-Global-COVID-Cases)
* Scraped [Worldometer](https://www.worldometers.info/coronavirus/) using BeautifulSoup to get global COVID-19 data
* Cleaned/transformed data, normalized data to improve integrity when comparing different countries
* Displayed Cases, Tests, Deaths per 1M for several countries


![global_cases](/images/worldometer_cases_per_m.png)
