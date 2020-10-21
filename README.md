# Toolkit

The Transforming Publishing team have created a toolkit of templates, guides and resources to support the modernisation of both the back end production of statistical products ([Reproducible Analytical Pipelines](#reproducible-analytical-pipelines)) and the user-facing output of statistical products to a digital platform ([Transformed Publications](#transformed-publications)). These tools will also be helpful when moving from a proprietary software such as SPSS or SAS, to an open source software such as R for any statistical analyses. If you have any questions about this toolkit then please contact our team at phs.transformingpublishing@phs.scot and we'd be delighted to help. 

## Reproducible Analytical Pipelines
Reproducible Analytical Pipelines are a way to introduce a robust, efficient and reproducible work flow when carrying out data analysis. They have traditionally been applied to statistical publications, but the principles are relevant to any analysis.

### Guidance and templates
- [**This paper**](https://www.isdscotland.org/About-ISD/Methodologies/_docs/Reproducible_Analytical_Pipelines_paper_v1.4.pdf) explains what Reproducible Analytical Pipelines are, how to assess whether your work is suitable to ‘RAP’ and details several levels of code maturity and RAP which can be selected depending on a number of factors, such as the skill in your team or the available IT infrastructure.
- The [**PHS R Style Guide**](https://github.com/Public-Health-Scotland/R-Resources/blob/master/PHS%20R%20style%20guide.md) should be followed by analysts when writing any R code to improve consistency across the organisation and ensure that our R code is readable, shareable and reusable. 
- Use the recommended [**PHS R project structure**](https://github.com/Public-Health-Scotland/r-project-structure) when writing R code to ensure you have a sensible workflow and structure. **It's now even easier to use this template:** an R project which follows the recommended structure can be created from within RStudio using the new [**phstemplates package**](https://github.com/Public-Health-Scotland/phstemplates).
- Use these [**National Statistic publication templates**](https://github.com/public-health-scotland/National-Stats-Template) to automate your PDF reports using Rmarkdown. 
- See [**RMarkdown Tips**](https://github.com/Public-Health-Scotland/RMD-tips) for a variety of tips and guidance relating to producing RMarkdown reports. It is a live document and more tips can be added in overtime.
- See [**Infographics Template**](https://github.com/public-health-scotland/Infographics-Template) for creating an inforgraphic containing some aligned charts and descriptive text, by using either RMarkdown or R plotting package ggpubr.
- See [**Automating Excel Guidance**](https://public-health-scotland.github.io/automating-excel/) for tips and guidance on how to automate tables and charts within Excel.

### Further resources
- [**This app**](https://scotland.shinyapps.io/nhs-r-resources/) contains a range of resources for R, such as links to online training and cheatsheets, and information about internal R user groups.
- The Transforming Publishing team also have a [**resources area**](https://github.com/public-health-scotland/resources), with useful resources on technical issues such as version control.
- If using git for version control, you should follow our team's [**GitHub guidance**](https://github.com/public-health-scotland/GitHub-guidance) on workflow and security.


## Transformed Publications
PHS have developed a new web-based way of releasing statistical publications to our users and has now released two publications in this format: [Acute Hospital Activity and Beds](https://www.isdscotland.org/Health-Topics/Hospital-Care/Publications/2018-12-18/acute-hospital-publication/?49401491881) and [Psychiatric Inpatient Activity](https://www.isdscotland.org/Health-Topics/Mental-Health/Publications/2018-09-25/psychiatric-inpatient-activity/). This new design has been developed with users at the heart of the process, and incorporates elements of static text, D3 charts, RShiny dashboards and open data. 

### User engagement
It is vital that users are part of the development, or re-development, of a statistical publication so that we can ensure that the final product meets their needs and is usable. This means involving users before, during and after development. 
- [Initial User engagement guidance paper](https://www.isdscotland.org/About-ISD/Methodologies/_docs/Initial-User-Engagement-v1-2.pdf)
- [Usability testing guidance paper](https://www.isdscotland.org/About-ISD/Methodologies/_docs/Usability-Testing-v1-0.pdf)

### Transforming output
- Use this [**blank RShiny template**](https://github.com/public-health-scotland/rshiny-project-structure) when starting to build a new app or dashboard to ensure you have a sensible workflow and structure.
- Follow these examples of our existing RShiny dashboards for good practice in terms of both coding and design: [**Psychiatric Inpatient Activity Data Explorer code**](https://github.com/public-health-scotland/Psychiatric-Inpatient-Activity) and [**Acute Activity Data Explorer code**](https://github.com/public-health-scotland/Hospital-Acute-Activity).
- When developing data visualisations and dashboards follow the style and design guidelines in the [Chart and dashboard guidance paper](https://www.isdscotland.org/About-ISD/Methodologies/_docs/ChartDashboardGuidelines_v1.1.pdf).


## Templates Index

**Resource** | **Link**
----------- | -------------
Infographics | https://github.com/Public-Health-Scotland/Infographics-Template
ioSlides | https://github.com/Public-Health-Scotland/ioslides-structure
Leaflet Map | https://github.com/Public-Health-Scotland/Leaflet_Map_Template
National Stats | https://github.com/Public-Health-Scotland/National-Stats-Template
PHS Templates | https://github.com/Public-Health-Scotland/phstemplates
R Project | https://github.com/Public-Health-Scotland/r-project-structure
R Shiny Project | https://github.com/Public-Health-Scotland/rshiny-project-structure
