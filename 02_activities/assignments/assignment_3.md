# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
For this assignment I use visuals from my previous assignment. 
Bad visualisation (Source: [National Rail Summary by Isuru Lokuge](https://www.mavenanalytics.io/project/17517)):
<img src="Bad visualisation.png">

Good visualisation (Source: [Harry Potter - What the Spell? by Jonathan van der Waard](https://www.mavenanalytics.io/project/1204)):
<img src="Good visualisation.png">

      ```
        Color: 
        "Bad" visualisation didn't pass colorblindness tests - it is not accessible to people with different color vision deficiencies. 
        "Good" visualisation doesn't rely on colors to convey the message. The message can be delivered even within grayscale color scheme. So this it is accessible to people with color vision deficiencies. 
        Text and descriptions: 
        Overall "bad" visualisation is hard to read. The text labels are crossed with multiple ribbons, it makes impossible to understand and read this visual. This visual has no description of visual elements or patterns, and also has no clear legend. 
        The "good" visualisation is easier to read, it has clear labels, legend and description of the visual. It also has descriptions for some data points which makes it easier to understand. 

        Reproducibility
        Both visualisations are part of the dashboards. But "bad" visualisation don't include source of the data so this makes it hard to reproduce. "Good" visual includes the link to the data source. 
        Since both of visuals are from Power BI dashboards, we don't know what steps authors made to create the visuals, and it makes them impossible to reproduce. 

        Equitable
        It is hard to decide if the visuals are equitable, since we don't know how the data was collected, processed and analysed for both of these visuals. 

        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Overall it is hard just to improve the "bad" visualisation. It requires to use a different graph type, maybe map or even the simple table would convey the message more clearly. 
        To improve "good" visualisation I would change the font style, using more accessible typeface. I also would add alt-text to data points, and to accompany labels to make the visual accessible for blind people that uses devices or software that helps them to read. 
        To make the visuals more reproducible, it's probably better to use Python script with comments. 



        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:
| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
