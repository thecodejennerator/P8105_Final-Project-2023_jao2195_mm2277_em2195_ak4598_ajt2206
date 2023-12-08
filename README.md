# P8105_Final-Project-2023_jao2195_mm2277_em2195_ak4598_ajt2206
Final Project for P8105 Data Science 

# 11/21 Meeting with TA

* Have we been able to download the format in a way that we could actually work with? Yes, Diana found where we can download a .csv fil with all objects and import it into a single dataframe
* Are we planning to include formal statistical analyses? Probably a few. TA says that if it's not a good fit or we can't get the formal analyses working properly, we don't have to include them
* ggplot probably has specialized visualizations (including color schemes) that could make our plots look pretty
* TA's recommendation: identify three main themes that our analyses will cover, and then include our planned analyses within that
* TA recommends adding dashboards to our website. If we can figure it out, a `shiny` dashboard might be more attractive than a `plotly` dashboard
* Reach out to Tvisha if we need any help
* Important that our analysis comprehensively covers the topic we've picked
* The report isn't a separate word file, it's just the analyses written within the R markdown file. The report is essentially the website
* We may run into issues with uploading the entire dataset into github. If it's taking forever/not working because the dataset is too big, can export portions as csv files and then just upload those to github. Can make different csv files based on different filtering criteria
* Divide out responsibilities: 2 on cleaning data and making plots, 2 on writing up the narrative about the results, 2 on making the website


# 12/1 Check-In

* Use a .txt extension to load the datafile so that it works for everyone

## Categories

* Aleya: The Met's growing collection / changes in the Met over time
^ How does the Met acquire art?

* Diana: Arists/Departments (not geolocated stuff)
^ Example: Objects by department 

* Melike: One big page that's just a big interactive map of art by countries
^ Diana's going send the link of a prior project's Github which did something like this

* Andy: Diving into Egypt specifically

* Anyone: zooming in on a particularly momentous year for Met (1963?)
^ Pull any weird things that come out from our individual analyses

* Jennifer & Emily: website
- Diana can also help with writing portion on the website 

## Focus on Complete Categories

* `years` are very complete
* 50% of the objects had a defined `culture`
* `department` and `classification` are really complete

# Chunking out the Data

* Create an R datafile with just all of observations that have non-missing years, culture, department, and classification. How small does does this make the dataset?

## Due Dates

By EOD Wednesday: finish draft of site
Thursday afternoon: meet for a Zoom call
- Everyone free 4:30 to 5:30pm to Zoom
By EOD Thursday: review site and fix any last minute things
Friday: Emily works on screencast, send to everyone for review 
Saturday: submit!

# 12/7 Meeting with TA

Examples for describing data: 

* https://st3431.github.io/abortionlaws.github.io/data.html
* https://shunxie.github.io/life_expectancy.github.io/Imputation.html
* https://sopochkon1.github.io/sheroes_finalproject.github.io/Data.html

Examples of the final report:

* https://shunxie.github.io/life_expectancy.github.io/Project-report.html

Example phrasing for analysis: 

* First, we want to examine the distribution of movies according to Bechdel Test dimension. The code chunk below summarizes the proportion of movies in movies_df according to their Bechdel Test Score, as well as the proportion of movies that pass or fail the Bechdel test.

* "In our dataset, we have a lot of vaccinations for different diseases. Therefore, it is natural to check whether the vaccinations data are correlated to each other. It seems like they are all very correlated to each other, with correlation value higher than 0.6. In consequence, we decide to only choose vaccinations for measles as our chosen vector as it was one of the most common disease and now almost fully controled by vaccination. There is still some cases remain for the people that did not get vaccinated according to CDC website."

* "Life expectancy as our dependent variable has similar trends for both developed and developing countries. Two life expectancy indices have a persistent increase over time. However, the expectancy for developed countries is 10 years higher than the developing countries over 16 years. The similar trends also holds for different income groups but countries classified in low income group has a higher growth rate for life expectancy than other groups."


TO DO 
* Diana to convert most of her plots to ggplot to reduce loading time
* Update the header (right under theme) using `code_folding: hide` to add a show/hide code toggle to each code chunk on the html pages. Need to remove eval = FALSE, etc. to get it to work
* Jennifer to clean up the landing page a bit. Update the background image to be a little bit darker and mysterious. Could swap the footer logo for a clear background or drop it entirely
* Diana to make the Data page headers not bolded
* Diana to add a narrative about the plots and only include the ones that seem interesting
* See if there's a way to make plots take up the full width of the screen
* Aleya to add a link back to the homepage to her timeline page, add a narrative to the report about what her plots are displaying, and see if there's a way to get the header to match the Cosmo theme
* Andy continue investigating how to use the bottom third of the page. Rename the dynasties using Roman Numerals. Add a link back to the home page
* Figure out the curators page and why earlier fixed got overwritten


