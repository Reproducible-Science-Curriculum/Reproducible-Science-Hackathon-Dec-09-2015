# Reproducible Science Hackathon, Take 2

  * hashtag: [#rrhack](https://twitter.com/hashtag/rrhack)

  * link: [hackthaon repo](https://github.com/Reproducible-Science-Curriculum/Reproducible-Science-Hackathon-Dec-09-2015)

In fall 2014, NESCent held an [initial hackathon] to develop a set of materials for teaching reproducible research to computational scientists. Participants in the hackathon then taught three #rrhack workshops to ~~unsuspecting guinea pigs~~ students, postdocs, faculty and staff at [Duke University], [iDigBio / University of Florida] and the [Duke Marine Lab]. A year after the initial hackathon, we re-convened people from the first event, along with a few locals from the University of Florida. This [second hackathon] aimed to expand / update the lessons based on feedback from the first three workshops.  

Here is a summary of the feedback from our first three workshops:
1. Participants didn't need to be convinced about the need for reproducibility. They could see the problems in their own work, and wanted concrete solutions. The lessons from the initial hackathon spent a fair bit of time motivating reproducibility, and it turns out we need less of that.
2. More participants than expected had some experience with programming / scripting, whether in R or python. This was true across all three workshops. Compare to Software or Data Carpentry, where we expect a significant fraction of participants to have little to no prior experience with computational science. It was still a challenge to teach literate programming without *actually* teaching programming.
3. Participants really wanted to know version control! We did not include a version control lesson in the  first workshop, but our feedback cards after each session included requests for VC, so we added a short demo at the end of the second day. We experimented with a Software Carpentry style git lesson at the Florida workshop and a GitHub-only lesson at the Duke Marine Lab.  
4. Lessons needed clear goals, and more exercises / less presentation.

Based on this feedback, we made the following changes to the workshop materials:

* better [overview of the workshop] for potential organizers and instructors
* created a [workshop template] and [template repo] for lesson maintainers / creators
* improved the instructor notes for all lessons
* made sure each lesson had clear goals
* created new [version control lessons] for git-in-github and git-in-rstudio
* new exercises for project organization
* converting slides to common, text-based formats

**A final note on R-vs-python**: The materials currently use R + RStudio + knitr for all examples, and we intially had  'translate-the-lessons-to-python' on the agenda for this meeting. After some discussion, we decided that our time in Gainesville was better spent revising the existing lessons. This gives us a high-quality set of R-based lessons ready for teaching. But, pythonistas should not despair! We are already planning another event focused on developing a parallel set of materials on reproducibility using python (likely using [Jupyter notebooks]).

[initial hackathon]: (https://github.com/Reproducible-Science-Curriculum/Reproducible-Science-Hackathon-Dec-09-2015)
[Duke University]: (http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/)
[iDigBio / University of Florida]: (http://reproducible-science-curriculum.github.io/2015-06-01-reproducible-science-idigbio/)
[Duke Marine Lab]: (http://reproducible-science-curriculum.github.io/2015-09-24-reproducible-science-duml/)
[second hackathon]: (https://github.com/Reproducible-Science-Curriculum/Reproducible-Science-Hackathon-Dec-09-2015)
[overview of the workshop]: (https://github.com/Reproducible-Science-Curriculum/workshop-planning/blob/master/workshopOverview.md)
[workshop template]: (https://github.com/Reproducible-Science-Curriculum/workshop-planning/blob/master/moduleTemplate.md)
[template repo]: (https://github.com/Reproducible-Science-Curriculum/template-module)
[version control lessons]: (https://github.com/Reproducible-Science-Curriculum/rr-version-control)
[Jupyter notebooks]: (http://jupyter.org/)
