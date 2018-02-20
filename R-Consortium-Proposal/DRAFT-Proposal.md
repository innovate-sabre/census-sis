DRAFT
===

Proposal to Create an R Consortium Working Group Focused on US Census Data
===

# The Problem

_What problem do you want to solve? Why is it a problem? Who does it affect? What will solving the problem enable? This section should include a brief summary of existing work, such as R packages that may be relevant. If you are proposing a change to R itself, you must include a letter of support from a member of R core._

R users who wish to work with US Census Data face two significant problems: Package Selection and Data Navigation.

***Package Selection***

An R user looking for packages to help with a project on US Census Data would likely start by going to CRAN's [list of contributed packages](https://cran.r-project.org/web/packages/available_packages_by_name.html) and doing a search for "Census". This process is non-optimal for a number of reasons:

1. It yields 41 hits, which is a large number to sort through.
4. Many package titles appear to be duplicative (e.g. censusr's title "Collect Data from the Census API" is very similar to censusapi's  title of "Retrieve Data from the Census APIs").
3. Some packages that deal with US Census Data do not have the word "Census" in their name or title (e.g. the choroplethr package).

For these reasons, a novice R user might find it challenging to determine which R package, if any, can help them with their Census-related project.

Note that these issues might also lead to package duplication on CRAN. That is, a developer might create a package to solve a problem which an existing package already solves.

***Data Navigation***

People often turn to the Census Bureau for answers to questions such as "How many people live in a certain region?" They are often surprised that the answer depends on which data product they query. That is, many R users begin their interaction with Census Data not fully understanding the array of data that is available to them, let alone when it is better to use one product over another

# The Plan 

_How are you going to solve the problem? Include the concrete actions you will take and an estimated timeline. What are likely failure modes and how will you recover from them?_

We would like to publish a guide to working with Census Data in R that 

1. Lists and describes packages currently available via CRAN that work with US Census Data. 
2. Links to reference materials for better understanding and working with Census data.

We imagine that the initial version of the Guide will be hosted online using a technology such as [Github Pages](https://pages.github.com/).

We would like the Guide to be linked to on the R Consortium website as well as on CRAN (perhaps on the Official Statistics Task View).

We believe that this project can be completed within three months.

# The Team 

_Who will work on the project. Briefly describe all participants, and the skills they will bring to the project._

Ari Lamstein: Data Science Instructor at the US Census Bureau and author of the Choroplethr suite of packages.

Logan T Powell: Developer Experience and Engagement Lead at the US Census Bureau

# Project Milestones

_Outline the milestones for development and how much funding will be required for each stage (as payments will be tied to project milestone completion). Each milestone should specify the work to be done and the expected outcomes, providing enough detail for the ISC to understand the scope of the project work._

***Milestone 1: Publication of Version 1 of the Guide***

Milestone 1 will include the publication of the initial version of the Guide. This version will:
  
  1. Summarize R's current package ecosystem for working with US Census Data.
  2. List resources where people can learn more about working with US Census Data.
  
We are requesting $2,000 for Milestone 1.

# How Can The ISC Help

_Please describe how you think the ISC can help. If you are looking for a cash grant include a detailed itemised budget and spending plan. We expect that most of the budget will be allocated for people, but we will consider funding travel, equipment and services, such as cloud computing resources with good justification. If you are seeking to start an ISC working group, then please describe the goals of the group and provide the name of the individual who will be committed to leading and managing the group’s activities. Also describe how you think the ISC can help promote your project._

We are seeking to create an ISC Working Group to promote using R to analyze US Census Data. The individual who will be committed to leading and managing the group's activities is Ari Lamstein.

We are requesting a $2,000 grant to fund completion of Milestone 1 of this project. We believe it is likely that after Milestone 1 is completed, other projects in this area will be identified.

In addition to creating a Working Group and financially supporting Milestone 1, we believe that the R Consortium can help this project to succeed by facilitating cooperation among stakeholders and disseminating and promoting the Guide on the R Consortium website.

# Dissemination

_How will you ensure that your work is available to the widest number of people? Please specify the open source or creative commons license(s) will you use, how you will host your code so that others can contribute, and how you will publicise your work. We encourage you to plan content to be shared quarterly on the R Consortium blog._

The content of the guide can be stored on Github under a permissive license and published using a tool such as Github Pages. The work will be publicized on our respective blogs, social media profiles and mailing lists.