# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
# The primary libraries used were pandas for data handling and matplotlib and seaborn for plotting.

    > Who is your intended audience? 
# The intended audience includes:

# Scientists and analysts from Environment and Climate Change Canada (ECCC)

# Stakeholders and policymakers involved in Great Lakes water quality monitoring

# Educators and students interested in eutrophication trends and long-term ecological changes in freshwater systems

    > What information or message are you trying to convey with your visualization? 
# The goal is to:

# Visualize temporal trends (1976–2023) in Total Phosphorus (TP) and Chlorophyll-a (Chl-a) across the four Great Lakes in Ontario.

# Emphasize how eutrophication indicators have changed over time, especially in response to environmental regulations and restoration efforts.

# Reveal any persistent elevated levels of nutrients or chlorophyll in specific lakes (e.g., Lake Erie) which is directly related to Lake Erie's higher euthrophication in comparsion for exmple with Lake Superior

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

# applied several best practices from the course:

# Consistent line and marker styles to make each lake visually distinct.

# Increased marker and line sizes to enhance readability.

# Clear axis labels and titles with units included (e.g., “TP (mg/L)”).

# A clean white grid background using seaborn-whitegrid style.

# Legend positioned to the side for easier comparison.

# Applied tight layout to prevent overlapping elements.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
# The initial analysis was performed in Python using open-source libraries with all steps scripted in a .ipynb file. The CSV dataset is version-controlled and included in the project directory. Because every step is coded and annotated, anyone can reproduce the same visualizations by running the notebook

# added the second set of visualizations made in Excel Pivot Tables for both parameters to demonstrate that similar time-series trends of Total Phosphorus (TP) and Chlorophyll-a (Chl-a) across Ontario’s Great Lakes can be visualized using spreadsheet tools. These charts, consistent with the Python plots, aim to highlight long-term nutrient trends that indicate eutrophication pressure in lakes such as Erie and Ontario compared to Superior.



    > How did you ensure that your data visualization is accessible?  
    

# I used color-blind-friendly palettes from Seaborn.

# Chose high-contrast lines and markers.

# Added clear legends, axis labels, and plot titles for screen-reader compatibility.

# Avoided 3D and overly complex charts to keep visual structure simple and interpretable.

# in excel: To ensure clarity and comparability, I grouped data by year and calculated the average TP and Chl-a concentrations for each lake. I used line charts with distinct colors, added axis labels, units, legends, and titles for accessibility.



    > Who are the individuals and communities who might be impacted by your visualization?  

# Environmental monitoring agencies (e.g., ECCC, MOECC)

# Local communities and municipalities near the Great Lakes

# First Nations and Indigenous Communities dependent on Great Lakes water quality

# Fisheries, recreation, and agricultural sectors

# These visualizations provide evidence for nutrient pollution trends and may influence future management decisions and policies.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

# From the full dataset, I focused on:

# Total Phosphorus (TP) — a key driver of eutrophication. I wanted to add Total Nitrogen as well, but the data was only up to 2015, therefore thought to visualize TP and Chl-a, which are directly related parameters for eutrophication

# Chlorophyll-a (Chl-a) — a biological indicator of algal growth. These two metrics are well-established indicators of lake productivity and eutrophic conditions, making them ideal for this analysis. 

# Excel was chosen to showcase how even basic tools can be used for scientific communication and stakeholder engagement. This complements the Python workflow and strengthens reproducibility across platforms.


    
    > What ‘underwater labour’ contributed to your final data visualization product?

# Data cleaning: Exported Excel to CSV, renamed parameters, handled missing values, and aggregated by year.

# Code setup: Wrote reusable plotting functions in Jupyter Notebook, adjusted styling, and filtered for relevant lakes and years.

# Manual review of column names and unique values to identify correct codes and units.

# Design iteration: Tuned marker sizes, line widths, and layout using course-taught principles.

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
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
