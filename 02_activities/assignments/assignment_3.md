# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

- For each visualization, describe and justify: 

### Visualization 1: TTC delays in Toronto, 2025

> What software did you use to create your data visualization?
    Python

> Who is your intended audience? 
    The intended audience is TTC users, particularly people who regularly travel by bus, streetcar, or subway
    
> What information or message are you trying to convey with your visualization? 
    The visualization compares delay incidents across TTC buses, streetcars, and subways. It shows that buses recorded the largest number of incidents and accumulated delay minutes in 2025. Buses accounted for 73% of the delay incidents and 80% of total delay minutes included in the analysis.
    
> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I created a clear visual hierarchy using a large title, a short explanatory subtitle, and three plots that answer related but distinct questions. The horizontal bar chart compares the number of incidents, the donut chart communicates the share of total delay minutes, and the dot plot compares average delay duration without repeating the same chart format.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The complete Python code will be included with the submission. It loads the three original CSV files, converts the date and delay variables into consistent formats, filters the observations, calculates the summary measures, and produces the final visualization.
    
> How did you ensure that your data visualization is accessible?  
    I used a colorblind-friendly palette with blue, orange, and yellow.
    
> Who are the individuals and communities who might be impacted by your visualization? 
    The visualization concerns TTC passengers, including commuters, students, older adults, people with disabilities, shift workers, and communities that depend heavily on public transportation. Bus delays may particularly affect neighbourhoods where buses are the primary connection to subway stations and employment areas. 
    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I included the transportation mode, date, delay minutes, and location information needed for the project. For this visualization, I used the number of positive-delay incidents, total delay minutes, and average delay per incident because these measures describe both the frequency and duration of disruptions.

    I limited the analysis to 2025.
    
    > What "underwater labour" contributed to your final data visualization product?

    The underwater labour included testing several chart types, choosing an accessible palette, finding and formatting icons, adjusting their size and position and improving label placement.

    Data sources: City of Toronto Open Data, TTC Bus Delay Data, TTC Streetcar Delay Data, and TTC Subway Delay Data.

### Visualization 2: Reported Bicycle Thefts in Toronto, 2024–2025

    Interactive visualization
    https://www.datawrapper.de/_/RIaz4/

    <iframe title="Reported Bicycle Thefts in Toronto, 2024–2025" aria-label="Symbol map" id="datawrapper-chart-RIaz4" src="https://datawrapper.dwcdn.net/RIaz4/2/" scrolling="no" frameborder="0" style="border: none;" width="600" height="519" data-external="1"></iframe>

 > What software did you use to create your data visualization?
    Datawraper


> Who is your intended audience? 
    Bicycle owners and cyclists in Toronto. The map may help them understand where bicycle thefts have been reported and encourage them to take additional precautions when parking their bicycles.

    
> What information or message are you trying to convey with your visualization? 
    The map shows the locations of reported bicycle thefts in Toronto during 2024 and 2025.
    
> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I used a symbol map because the main purpose was to show the geographic location of individual incidents.
    
    I limited the visualization to two years to avoid excessive visual clutter.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The interactive visualization includes a download button that allows users to obtain the same dataset used to create the map. I also retained the original colums from Toronto Open Data.

> How did you ensure that your data visualization is accessible?  
    I used Datawrapper’s colour-blindness checker. 
    Datawrapper requires an Alternative description for screen readers, so I added a detailed text description explaining the map’s purpose, the years included, and the main geographic pattern.

> Who are the individuals and communities who might be impacted by your visualization?  
    The visualization may affect anyone who owns, uses, purchases, stores, or provides parking for bicycles in Toronto.

    The downloadable dataset provides more detail than the map alone, including the date and time of the theft, location and premises type, police division, bicycle make, model, type, colour, estimated cost, and recovery status. These variables may help users identify patterns related to where, when, and what types of bicycles are reported stolen.

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Although all columns remain available in the downloadable file, I displayed only year and location. 

> What ‘underwater labour’ contributed to your final data visualization product?
    The underwater labour included locating and downloading the data dataset, reviewing its columns, filtering the observations, checking the geographic coordinates, uploading the filtered file to Datawrapper, and checking the interactive map at different sizes. 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
