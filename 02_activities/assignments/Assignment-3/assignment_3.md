# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I used Python (Jupyter Notebook in VS Code) and R (R Markdown in R studio) to create the two visualizations. Python was used for the time series line plot using matplotlib, while R was used to generate the heatmap using ggplot2. Both tools are open-source, support reproducible workflows, and are widely used in the data science community.

    ** Link to the dataset ; https://data.ontario.ca/dataset/breakdown-of-covid-19-positive-hospital-admissions
    

    > Who is your intended audience? 
    The intended audience includes public health officials, policymakers, epidemiologists, and the general public interested in understanding trends in COVID-19 hospital and ICU admissions. The visualizations are designed to communicate clearly to both technical and non-technical audiences.

    > What information or message are you trying to convey with your visualization? 
    The line plot highlights the temporal trend of hospital admissions due to COVID-19, showing how they have fluctuated over time.
    The heatmap complements this by offering a categorical comparison over time between ICU and hospital admissions for COVID-19 versus other conditions.
    Together, they emphasize the burden COVID-19 placed on the healthcare system and how it evolved throughout the pandemic.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I applied several core data visualization principles:
    Clarity: Axis labels, titles, and legends are explicitly labeled with readable fonts (in bold).
    Consistency: Dates were formatted uniformly (Month-Year) across both visualizations to improve clarity too.
    Color: In the line plot, a clear contrast was used between the smoothed and raw data. In the heatmap, a custom color gradient (orange to purple) was applied with a strong visual contrast to distinguish low and high proportions. Both plots are also neutral and do not evoke an emotional response. 
    Minimalism: Grid lines and background colors were subtle and not distracting.
    Space: Adequate space was created along the x-axis by rotating date labels to improve readability.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Both Python and R support reproducibility through code scripts. I used notebooks and R Markdown to document every step: data cleaning, transformation, and visualization. These files can be rerun to produce the same results, fulfilling aspects of the FAIR (Findable, Accessible, Interoperable, and Reusable) principles. Saving the code and figures in version-controlled folders ensures long-term accessibility and transparency.

    > How did you ensure that your data visualization is accessible?  
    I used color gradients that are distinguishable for most types of color vision deficiency (e.g., orange, blue and purple). I also provided:
    Descriptive titles and axis labels
    Rotated x-axis text for readability
    Scalable fonts for better visibility
    To improve accessibility further, figures can be accompanied by alt text or data summaries for screen reader users.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Public health decision-makers could use these insights to allocate resources.
    Hospital administrators might track changes in ICU capacity.
    General public may understand the severity of certain waves of the pandemic.

    
    > What ‘underwater labour’ contributed to your final data visualization product?
    The final visualizations were preceded by substantial “invisible” work, including:
    Downloading and exploring the raw dataset
    Cleaning and transforming data (e.g., converting proportions to percentages, reshaping the dataset)
    Managing date formats
    Customizing plot aesthetics to improve readability and interpretability
    Debugging issues with file saving and color gradients
    Verifying the integrity of the dataset and cross-checking variables
    This “underwater labour” is essential for producing accurate, ethical, and meaningful visualizations, even though it’s not always visible in the final plots.

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
* Submission Due Date: `23:59 - 09/05/2025`
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
