# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

*This exercise assesses student's understanding of applying appropriate configuration in transpose (chosing right fields for key columns and data columns) based on required format of data output*

#### Context

*Its important to learn 'name-value concept' and configuraion settings of transpose tool to understand how this tool re-organizes data by switching columns into rows.Restructuring data is very commonly needed in ETL process to prepare the data for the next step in data manipulation or to add meaning to data e.g it will be easier to summarize the data points when all the required data points are available in column*

#### Steps to be executed by the student (max 6)

*- Step 1 - Drag the transpose tool to canvas , and connect with existing select tool 
 - Step 2 - Click on the transpose tool to look at the configuration settings.
 - Step 3 - Select 'entity' field in Key Columns and '2014 Happiness Score', '2015 Happiness Score' and '2016 Happiness Score'
 - Step 4 - Add browse tool after transpose tool and run the workflow*


#### Exercise question:
*How many column and rows are there in the output ?*

#### End goal:

*![9D03230C9EAB44F19D904CEB22486A95](https://github.com/giniyagupta/sme-bi-course-application/assets/48961515/5bd0910d-4cd7-4a5e-b198-f425caf3e3d4)*


## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

*This excercise assesses learner's undertanding of how unwanted columns/fields are dropped in transpose tool , while rest of the columns are re-arranged to be included in output data*

#### Context

*Its important to learn how to drop unwanted columns while using transpose tool , otherwise output data may not be as per requirement . Also , keeping unwanted column in output may not allow appropriate usage of  data for next step in the process . It may also lower the data quality. Understanding this concept , allows user to attain Maximum value from data *

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

Step 1 - Drag the transpose tool to canvas , and connect with existing cleansing tool 
 - Step 2 - Click on the transpose tool to look at the configuration settings.
 - Step 3 - Select 'Year' field in Key Columns and 'Avg_Life_Satisfaction_Denmark', 'Avg_Life_Satisfaction_Finland', 'Avg_Life_Satisfaction_France'and    'Avg_Life_Satisfaction_Grt_Britain'
 - Step 4 - Add browse tool after transpose tool and run the workflow
 - Step 5 - Notice columns not selected in configuration settings are dropped from ouput*


#### Exercise question:
*How many column and rows are there in the output ?*

#### End goal:

*![625204EB6F574F929C8CB567AFEC2B90](https://github.com/giniyagupta/sme-bi-course-application/assets/48961515/b77c5532-a177-4dbc-8883-ad90cd500988)*


