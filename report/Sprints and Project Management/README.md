# Team Working Method

For the management of this cooperative project, we chose the group working method of StageWise-Model. This Model has its own characteristics, which can be well adapted to our application program that may have minor changes in functional requirements in the early and middle term. The technical feature of the iterative Model is that it does not require the development of a complete software system at one time. Think of software development as a process of gradually acquiring improvement points, acquiring requirements, and refining the software product.


<p align="center">
 <img src="https://github.com/bristolcs828/Project-Account/blob/main/report/Sprints%20and%20Project%20Management/sp-and-ma-1.jpg" width="600" height="410">
</p>


In addition, we assign each person's work. If the project have their own do not understand or need to negotiate, we will place your problem in our discussion group, so that everyone can in view of the problems put forward some rationalization proposal for reference, and we will set up a feasible schedule plan, for everyone on the project schedule to communicate (via Zoom or Wechat), and arrange the next work content to ensure that the project can be carried out in an orderly way, to ensure that the project is completed in advance and there is relatively enough time to listen to the TA or professor's opinions for targeted modifications. 

In the iterative development approach, the overall development effort is organized into a series of short, fixed-length (e.g., 4 weeks) projects, known as a series of iterations. Each iteration includes requirements analysis, design, implementation, and testing. With this approach, development work can be started before requirements have been fully identified and a portion of the system's functionality or business logic can be developed in one iteration. Then through customer feedback to refine the requirements, and start a new iteration. 

The difference between iteration and version can be understood as follows: iteration generally refers to the production process of a version, including from requirements analysis to test completion; A release is generally the result of some stage of software development, a deliverable product.

## What are the advantages of the StageWise-Model？

(1) Reduce the risk of spending on an increment. If the developer repeats an iteration, all that is lost is the cost of that ill-developed iteration. 

(2) It reduces the risk that the product cannot enter the market according to the scheduled schedule. By identifying risks early in development, you can address them sooner rather than rushing them later in development. 

(3) It speeds up the overall development effort, because developers know what the problem is focused on and they can work more efficiently. 

(4) Since users' requirements cannot be fully defined at the outset, they are usually refined in subsequent stages. Therefore, the iterative process pattern makes it easier to adapt to changing requirements, and therefore more reusable.


<p align="center">
 <img src="https://github.com/bristolcs828/Project-Account/blob/main/report/Sprints%20and%20Project%20Management/260.jpg" width="600">
</p>


# Team roles

The role of the cooperative project team is 5 people in total, and the work of each person is assigned as follows:

#### Peng Gao - UX researcher
Discuss with product planners to complete the conception of early prototype, complete the design of map, understand the needs of overseas students, and propose the specific process of project interaction process.

#### ZeJia Liu - Backend developer
Responsible for the logic implementation of the overall project application, complete the prototype of the project, and make it have the basic positioning and basic function implementation.

#### Hengbin An - Backend and background research
Discuss the interesting elements proposed by the product planning on the basis of the completed project, and select some appropriate elements to add to the project to increase the interest of the project.

#### WeiBang Tang - Frontend developer
To complete the front end of the work, to achieve web-based effect display.

#### Gang Li - (UI/UX) / team management
Be responsible for the direction of the project, understand the benefits that the project application may bring to the society, propose the general purpose that the project ultimately needs to realize, and give reasonable and developmental suggestions.

# Sprints
About the team project, we are the number of 17 team, we made a schedule, and in a few important points set up six meeting (on April 3rd to May 5th, is our whole team sprint time period of the project, requires the participation of each team member as soon as possible, especially the content of the discussions with members of the position is responsible for large, should need to be involved). The key issues that should be discussed by team members in each meeting are listed, which play a vital role in our team project. 


<p align="center">
 <img src="https://github.com/bristolcs828/Project-Account/blob/main/report/Sprints%20and%20Project%20Management/lcomp.gif" width="500">
</p>


Some of our team members are in China and some are in the UK. Finally, for convenience, the meeting places in the whole schedule are all held in ZOOM. Here's what we focused on and discussed during our last six sprints. The schedule is as follows:


<p align="center">
 <img src="https://github.com/bristolcs828/Project-Account/blob/main/report/Sprints%20and%20Project%20Management/gantt%20chart.jpg" width="720">
</p>


In the whole development process of the project, we are divided into three stages, namely the Preparatory Phase, the Spring Cycle and the Final Stage. Each Stage is divided into many small T stages, and the Preparatory Phase contains two T1 and T2 events. The Sprint Cycle stage includes T3, T4, T5, T6, and T7, a total of five T stages. During the Sprint Cycle stage, our team project progresses very fast. We can quickly locate and optimize everyone's problems after the ZOOM meeting. And start the next task. In the Final Stage, there is only one T8 event. At this time, our project has been completed. Generally, minor modifications are carried out during the T8 event. The following is a summary of all T events:

T1 event: completion of project proposal

T2 events: Prototype decision, data collection

T3 event: After Zoom's first meeting, the back end starts writing functional code and the UI/UX design begins

T4 event: After ZOOM's second meeting, the front-end code was written and the interactive function was determined

T5 event: After Zoom's third meeting, he continued to write the back-end code and finished it by 4.30. During this time, choose a time to discuss the next optimization of the project with Allison(TA).

T6 event: After the fourth ZOOM meeting, complete the front-end code and UI/UX design demonstration, and add some game elements according to the results discussed with the teaching assistants in T5 event.

T7 event: After the fifth ZOOM meeting, the overall project was basically completed and all functions were tested. And provided to part of the users for use, to collect their opinions.

T8 event: After ZOOM's sixth meeting, I summarized the whole project, classified and supplemented the README document, uploaded all previous text documents, optimized the entire README document, and prepared to submit the team project task

# Git and CI/CD

### Continuous Integration/Deployment

Our team set up a GitHub account. When creating the repository, we realized that there would be three people to upload at any time, so it was necessary to set it on the main branch. Our group's git repository has three branches: master, develop, and test. Each branch plays an important role. 

At the beginning of the project, which is the preliminary development stage of backend, front end and database design, we put the overall framework of each part on the Master and then entered the Agile work mode. This mode of work required us to iterate on and off the project based on the user's test experience and our own tests, adopting and discarving things we didn't need, so most of our development was done on the Develop and Feature branches after we went to Agile mode of work. Since Agile requires that each module work at the same time and the project iterations quickly, we basically develop on Develop, updating every detail on the Feature branch and doing the best we can. 

Each member of our team runs a feature branch independently and will push it to git repository regularly. After team members update their feature branch, they will merge into the Develop branch. Before each merge, they will pull request and report to the project experience in the TEAMS meeting. Each team member will send a request to inform the rest of the team and invite others to participate when they find the problem has changed. So every member of our team was involved in every iteration and change of the project module. Finally, after each module is mostly complete, the Develop content is merged into the master branch as a temporary result.

In addition, we had to give permissions to each programmer separately, which was the most convenient for programmers to use in terms of convenience. There are mainly three repository, including the front-end repository, the back-end warehouse and the project-account repository (which contains the flow chart, mind map and README file).

Git continuous integration and continuous deployment on the whole mainly involves the basic Git commands, including Git clone, Git add, Git commit, Git push, etc., through the basic Git commands to complete the deployment of project code.


