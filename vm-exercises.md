# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

*One measurable learning objective that this exercise assesses*
Apply the visualization elements of color and boldness to the visuals and headlines to enhance the effectiveness of visuals. 


#### Context

*3 - 4 sentence description of why it’s important to learn how to do this task (linking back to the learning objective). Explain how this would be used in a real-life situation. Why is it useful, what problem does it solve?*
Visualization techniques are used to help guide a reader’s eyes on where to look. Elements like color selection, font size, and font boldness within the visual and headline text are used to intentionally draw attention, which allows the reader to focus on the key takeaways presented. Being able to apply these elements will ensure your analysis and visualizations communicate the information you want clearly without distraction from other relevant - but less important - details within a chart’s immediate area.


#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

You are doing an analysis on Westminster and Camden neighborhoods in London. 

Using the `ex-1-initial.twbx` file, follow these steps to highlight them for your analysis.
- Step 1: Remove the existing pill (Neighborhoods) on the color marks to change the bar colors back to monochrome.
- Step 2: Create a calculated field called "Is Westminster or Camden?" using IF/THEN and OR statements to assign TRUE to neighborhoods Westminster and Camden and FALSE to all other neighborhoods.
- Step 3: Apply the "Is Westminster or Camden?" pill to the marks shelf. 
- Step 4: Using a categorical, cool colors palette, assign the TRUE values to a bolder, brighter color. Assign the FALSE value a duller, more faded color.
- Step 5: Change the colors of the cities in the title to correspond with the color chosen for your TRUE values.
- Step 6: Bold the colored text in the title.

#### Exercise question:
*This is a question presented to learners to check if the steps above were properly completed. It can be a multiple choice question or a question with a 1-3 word answer. It is often not possible to check if all the steps are completed, in this case; the priority is to check that the learner meets the learning objective.*

Resort the neighborhoods so that it is ranked in descending order by total # of reviews. 
- Q: Which neighborhood is #1?  A: Westminster
- Q: Is this neighborhood one of the highlighted neighborhoods (as indicated in the title)?  A: Yes

#### End goal:

*Add an image of the final visualization here.*

![ex-1-sol-image](https://user-images.githubusercontent.com/94759820/143809876-a34ace1f-20f1-4559-959d-de9e1b15e7ff.JPG)


## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

*One measurable learning objective that this exercise assesses*

#### Context

*3 - 4 sentence description of why it’s important to learn how to do this task (linking back to the learning objective). Explain how this would be used in a real-life situation. Why is it useful, what problem does it solve?*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Step 1
- Step 2
- Step 3
- ...

#### Exercise question:
*This is a question presented to learners to check if the steps above were properly completed. It can be a multiple choice question or a question with a 1-3 word answer. It is often not possible to check if all the steps are completed, in this case; the priority is to check that the learner meets the learning objective.*

#### End goal:

*Add an image of the final visualization here.*

