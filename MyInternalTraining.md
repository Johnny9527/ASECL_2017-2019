## ProjectLink Training

Similar to Oracle Agile PLM System, PTC Windchill PLM System is also structured by many different modules. In this repository, I will share 
parts of the internal training material that I made and used to train the internal users of ASECL.

Today I want to talk about ProjectLink, which is used to manage project-related functions within PTC Windchill PLM System 
(similar to PPM module of Oracle Agile PLM System).

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/WindchillPLMStructure.png)

As the picture shows above, the red rectangle box on the left-hand side represents the Work Breakdown Structure (WBS) of a project, such as 
phases, activities, and deliverables, and ProjectLink can also interact with other modules like PDMLink, which mainly controls documents, 
PartsLink, which mainly controls parts, and MPMLink, which mainly controls routing.

Like Oracle Agile PLM System, PTC Windchill PLM System is also able to communicate with other information systems such as Manufacturing 
Execution System (MES) and Enterprise Resource Planning (ERP) System in data transactions within the company.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/ProjectStructureGraph.png)

In each "Project Plan" usually includes several "Summary Activity" and "Milestone". Under "Summary Activity" contains multiples "Activity",
and each "Activity" comes along with a corresponding "Deliverable". In a real use case,  the Project Manager (PM) will decide the structure 
of "Project Plan" and assign detail for each "Task" (Activity) to different engineers. The corresponding engineer who in charge of the "Activity" 
will have to give feedback or hang out a report through the specific "Deliverable". Meanwhile, PM can also monitor the progress of the project 
by setting up a few milestones, to make sure the process is going under control.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/ResourceRelatedGraph.png)

For every "Activity" of the project, PM can not only assign the human resource but also establish usage plans for other resources such as 
required equipment or material.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/ProjectInitiation.png)

After initiating the project, senior managers or supervisors can easily understand the status of each project by checking the "status light" 
(Green: on schedule, Yellow: slight delay, Red: extremely delay or error occurred).

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/GanttChart.png)

###### ↑ Gantt Chart of ProjectLink

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/TimeTable.png)

###### ↑ Time Table of ProjectLink

PM can track the process by using the embedded "Gantt Chart" function or even through the "Time Table".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MSProject.png)

ProjectLink module of Windchill PLM System also provides integration with traditional "Microsoft Project", supporting those PMs who are used to 
the old-school project maintaining way. They can easily upload or download the whole "Project Plan" in only one click.

