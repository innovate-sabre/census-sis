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

People often turn to the Census Bureau for answers to questions such as "How many people live in a certain region?" They are often surprised that the answer depends on which data product they query. That is, many R users begin their interaction with Census Data not fully understanding the array of data that is available to them, or when it is better to use one data product over another.

# The Plan 

_How are you going to solve the problem? Include the concrete actions you will take and an estimated timeline. What are likely failure modes and how will you recover from them?_

We would like to create an R Consortrium Working Group to foster greater cooperation between the Census Bureau and R community.

The first project we would like to take on is the creation of a guide to working with Census data in R ("The Guide"). The Guide would address the problems listed above by:

1. Listing, describing and linking to packages currently available via CRAN that work with US Census Data. 
2. Listing, describing and linking to reference materials for better understanding and working with Census data.

The most likely failure mode for the **Package Selection** is not including all the relevant packages, or not communicating their differences in a way that helps users decide which package is most appropriate for their use. For example, it is not clear whether the Guide should simply copy the CRAN description of packages, or also include additional information (and if so, what information?). We plan to address this risk by publishing drafts of our work online, and incorporating feedback from the R community.

The most likely failure mode for **Data Navigation** is not providing resources which are useful or relevant to the actual needs of the R community. We plan to address this by publishing drafts of our work online, and incorporating feedback from the R community.

# The Team 

_Who will work on the project. Briefly describe all participants, and the skills they will bring to the project._

**Ari Lamstein**. Ari is an R Trainer and Consultant who is currently working as a Data Science Instructor at the US Census Bureau. He has written several R packages that deal with US Census Data. Ari is planning to focuson on the **Package Selection** portion of the Guide.

**Logan T Powell**. Logan is the Developer Experience and Engagement Lead at the US Census Bureau. Logan is planning to work on the **Data Navigation** portion of the Guide.

# Project Milestones

_Outline the milestones for development and how much funding will be required for each stage (as payments will be tied to project milestone completion). Each milestone should specify the work to be done and the expected outcomes, providing enough detail for the ISC to understand the scope of the project work._

***Milestone 1: Select Publication Technology (1 Month)***

Our first task will be selecting technology to use to publish the Guide. We would like the technology to be free and easy to update. Current candidates are WordPress and Github Pages.

***Milestone 2: Assemble list of resources to include (1 Month)***

Which packages should be included in the Guide?

Which resources should the Guide link to?

***Milestone 3: Complete Publication of Guide (1 Month)***

After assempling the list of content to include, we need to write up the results as a standalone work.

***Milestone 4: Complete Dissemination (1 Month)***

After publication, we will announce the completed Guide on our blogs and social media. In this phase we plan to reach out to other organizations (such as CRAN and the Census Bureau) to see if are interested in linking to the Guide from their website.

# How Can The ISC Help

_Please describe how you think the ISC can help. If you are looking for a cash grant include a detailed itemised budget and spending plan. We expect that most of the budget will be allocated for people, but we will consider funding travel, equipment and services, such as cloud computing resources with good justification. If you are seeking to start an ISC working group, then please describe the goals of the group and provide the name of the individual who will be committed to leading and managing the group’s activities. Also describe how you think the ISC can help promote your project._

We are seeking to create an ISC Working Group to promote using R to analyze US Census Data. The individual who will be committed to leading and managing the group's activities is Ari Lamstein.

We are requesting a $2,000 grant to fund completion of the Guide. We believe it is likely that after the Guide is created, the group will wish to apply for other grants. For example, Census is interested in getting feedback from the R community on its API. We plan to apply for a separate grant to coordinate those activities. 

In addition to creating a Working Group and financially supporting the creaiton of the Guide, we believe that the R Consortium can help this project to succeed by facilitating cooperation among stakeholders and disseminating and promoting the Guide on the R Consortium website.

# Dissemination

_How will you ensure that your work is available to the widest number of people? Please specify the open source or creative commons license(s) will you use, how you will host your code so that others can contribute, and how you will publicise your work. We encourage you to plan content to be shared quarterly on the R Consortium blog._

We plan to releaser the Github under the [Creative Commons Attribution 4.0 License] (https://creativecommons.org/licenses/by/4.0/). 

We plan to publish the guide as website or webpage. 

We plan to publicize the completion of the guide on our blogs and social media. 

We think that CRAN might wish to link to the Guide on the [Official Statistics & Survey Methodlogy Task View](https://cran.r-project.org/web/views/OfficialStatistics.html).

We think that the Census Bureau might also wish to link to the Guide on their Training website.