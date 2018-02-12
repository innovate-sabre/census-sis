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

For these reasons, a novice R user will find it challenging to determine which R package, if any, can help them with their project related to US Census Data.

These issues might be leading to R packages which duplicate functionality.

***Data Navigation***

People often turn to the Census Bureau for answers to questions such as "How many people live in my state?" They are often surprised that the answer depends on which data product they query. That is, many R users begin their interaction with Census Data not fully understanding the array of data that is available to them, and when it is better to use one data product over another. 

# The Plan 

_How are you going to solve the problem? Include the concrete actions you will take and an estimated timeline. What are likely failure modes and how will you recover from them?_

Within three months we would like to complete an initial version of the Guide that

1. lists and describes packages currently available via CRAN that work with US Census Data. 
2. links to reference materials for better understanding and working with Census data.

The biggest risk in this phase is determining where the Guide will live. Should it exist as a CRAN Task View, blog post or something else?

# The Team 

_Who will work on the project. Briefly describe all participants, and the skills they will bring to the project._

Ari Lamstein: Data Science Instructor at the US Census Bureau and author of the Choroplethr suite of packages.

# Project Milestones

_Outline the milestones for development and how much funding will be required for each stage (as payments will be tied to project milestone completion). Each milestone should specify the work to be done and the expected outcomes, providing enough detail for the ISC to understand the scope of the project work._

The initial work on this project does not require funding.

The initial milestone is to create a Guide that simply lists and links to 

 * CRAN Packages that work with US Census Data 
 * Training resources which the Census Bureau supplies.

# How Can The ISC Help

_Please describe how you think the ISC can help. If you are looking for a cash grant include a detailed itemised budget and spending plan. We expect that most of the budget will be allocated for people, but we will consider funding travel, equipment and services, such as cloud computing resources with good justification. If you are seeking to start an ISC working group, then please describe the goals of the group and provide the name of the individual who will be committed to leading and managing the group’s activities. Also describe how you think the ISC can help promote your project._

The R Consortium can help to disseminate this guide. 

# Dissemination

_How will you ensure that your work is available to the widest number of people? Please specify the open source or creative commons license(s) will you use, how you will host your code so that others can contribute, and how you will publicise your work. We encourage you to plan content to be shared quarterly on the R Consortium blog._

The content of the guide can be stored on github under a permissive license. It is currently unclear where the final guide should be published.

The work will be publicized on my website (www.AriLamstein.com).