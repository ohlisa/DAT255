# Course PM for Software Engineering Project (DAT255/DIT543) 7.5 HEC, Spring 2016

## News
- May 03: Uploaded slides for HCI lectrue. Changed date for last lecture, from May 16 to May 20
- Apr 26: Thanks to team Outsourcify there is now a list of the troubles reported by the bus drivers. Send Håkan an e-mail if you want access to the file
- Apr 19: On April 22nd the supervision will take place in the morning, 9-12, due to the [TBC] event. Check the lecture slides for the order among the teams
- Apr 18: Added slides for today's lecture
- Apr 15: A team member from each team should by now have received login credentials for the [EIC-API](http://platform.goteborgelectricity.se/). There are java examples of how to [request data from the API](https://github.com/hburden/DAT255/blob/master/Extras/HttpsUrlConnectionDemo.java?raw=true) and how to use the [login credentials](https://github.com/hburden/DAT255/blob/master/Extras/Base64Example.java?raw=true) 
- Apr 14: The Electricty [Platform](http://platform.goteborgelectricity.se/) supplies real-time data from the buses and information regarding the bus stops etc. Apply for an account to the discussion forum [here](http://platform.goteborgelectricity.se/user/register?destination=forum/11)
- Apr 14: Updated the schedule
- Apr 12: Added two links under *Course Literature* that helps in defining the product backlog and tasks
- Apr 11: Unfortunately the electrical buses are all busy on Wednesday. If you go by public transport Bus 32 leaves Eketrägatan at 13.20 and arrives at Arendal Skans 13.37
- Mar 16: Updated course literature and schedule
- Mar 15: Added student representatives
- Mar 10: The grading policy and the schedule were clarified
- Mar 02: Homepage is up and running. The homepage will be continuously edited, reflecting the evolution of the course.

[C1]: https://github.com/hburden/DAT255/blob/master/Slides/HttpsUrlConnectionDemo.java?raw=true
[C2]: https://github.com/hburden/DAT255/blob/master/Slides/Base64Example.java?raw=true

## Course Description
Software remains malleable, often illogical, and incomplete forever. *Sequential approaches* to software development, such as the *waterfall model*, assumes that it is possible to take every single variable that could affect a project into account beforehand. Considerable effort is spent to identify risks, plan mitigation, and what consequences these may have. From a traditional product perspective, this can be compared to creating an assembly line to produce software.

Given the nature of software, is it really feasible to identify all variables beforehand? *Iterative and incremental approaches* accepts that changes are inevitable and integrates change management into the development process. *Agile approaches* promotes iterative and incremental development by using a very tight *design-code-test* cycle. If we again use a traditional product perspective, this can be compared to new product development.

## Course Project
Most of the course time is spent on a course project. This year the project is run in collaboration with Volvo Bus and Keolis with the aim to improve the daily maintenance of the electric and hybrid buses of route 55. More details about the challenge will be presented at the workshop given on the 13th of April.

## Learning outcomes
In this course you will learn how to design and develop software, and to manage projects:
- Knowledge and understanding, the student should be able to:
	- identify the complexities of software design and development
	- describe the fundamentals of software engineering, such as stakeholders and requirements
	- describe the difference between the Customer, the Solution, and the Endeavour as well as the different methods used for each

- Skills and abilities, the student should be able to:
	- elicitate requirements from and design a solution to a real-world problem
	- plan and execute a small software development project in a team
	- apply skills from programming courses and other relevant courses in a project-like environment
	- learn new tools and APIs on his/her own

- Judgement and approach, the student should be able to:
	- reflect on the choice of software engineering methods used in the project

The [grading policy](README.md#examination) will be updated before the first lecture. The aim is to meet the requests from last year's [course evaluation][courseeval].

[courseeval]: https://github.com/hburden/DAT255/blob/master/Extras/DAT255_Software_engineering_project_2015_LP1.pdf

## Teachers

| ID | Name | Gitname | Contact | Role |
| ------ |  ------	| ------	| ------	| ------ | 
| HB | Håkan Burden | hburden | [burden@cse.gu.se](mailto:burden@cse.gu.se) | Course responsible |
| JP | Jan-Philipp Steghöfer | steghoja | [jan-philipp.steghofer@cse.gu.se](mailto:jan-philipp.steghofer@cse.gu.se) | Examiner |
| RJ | Rodi Jolak| rodijolak | | Lecturer |
| DS | Daniel Sjölie | | | Lecturer |


## Student Representatives
| Program | E-mail | Name | 
| ------ |  ------	| ------	| 
TKDAT | hamax@student.chalmers.se | Max Hansson |
TKIEK | jacobho@student.chalmers.se | Jacob Holmén |
TKIEK | markoi@student.chalmers.se | Marko Ivanovic |
TKIEK | antkarr@student.chalmers.se | Anton Kärrman |
TKDAT | marsig@student.chalmers.se | Martin Sigvardsson |
 


## Course Literature 
Book:
- Sommerville, I. (2010) *Software Engineering* (ISBN13: 9780137053469)
- Kniberg, H. (2015) [Scrum and XP from the Trenches - 2nd Edition](http://www.infoq.com/minibooks/scrum-xp-from-the-trenches-2). Free with registration

Vision:
- Writing a product vision: [1][pv1], [2][pv2].

Agile:
- [Breaking a feature into tasks](https://gojko.net/2012/01/23/splitting-user-stories-the-hamburger-method/)
- [Maintaining the full view of a complex system](http://jpattonassociates.com/the-new-backlog/)

Git:
- [Pro Git][GITBOOK], [Git Videos][gitvid]
- [A successful Git branching model][gitbranch]
- [GitHub Student Developer Pack](https://education.github.com/pack)
- Interactive Git learning: [Learn Git Branching][LearnGitBranching]

Android:
- [Design patterns explained with Android examples][AndroidPatterns]
- [Android tutorials](http://www.vogella.com/tutorials/android.html)
- [Android development tools and docs](http://developer.android.com/index.html)


## Schedule
Below you can see the time etc. of the lectures, exercises, workshops and deliverables. There is also a detailed schedule in [TimeEdit]. Note that the TimeEdit schedule contains all possible sessions, while the schedule below contains those that we actually use! 

| Week    | Date & Time        | Room  | Topic        | Who | Deliverable(s) |
|  ------	| ------	| ------	| ------ |  ------ | ------ |
| 01 / 12 | Mar 21 *13.15-15.00* | VasaC | [Course introduction][L1] | HB |  |
|  | Mar 23 *13.15-17.00* | Vasa6 | [Lego scrum][ScrumSurvey] | HB |  |
| 02 / 15 | Apr 11 *13.15-15.00* | VasaC | [Lego Reflections][L3n] & [Scrum][L3o] | HB | [D1.A](README.md#pass--fail) |
|  | Apr 13 *14.00-16.00* | [VBEC][VBEC] | [Project introduction][L4] | HB |  |
|  | Apr 15 *13.15-15.00* | Lindholmen Open Arena | Process & tool supervision | HB, JP & RJ | [D1.B](README.md#pass--fail) |
| 03 / 16 | Apr 18 *13.15-15.00* | VasaC | [Software project management][L5] | HB |  |
|  | Apr 20 *13.15-15.00* | Vasa4 | Tool supervision | RJ |  |
|  | Apr 22 *09.00-12.00* | VasaC | Process & tool supervision | HB, DS & RJ |  |
| 04 / 17 | Apr 25 *13.15-15.00* | VasaC | Automotive Software Development | VCC |  |
|  | Apr 27 *13.15-15.00* | VasaC | Entrepeneurship |  Chalmers Ventures | |
|  | Apr 29 *13.15-15.00* | VasaC | [Human-Computer Interaction][L6l] & [App Design][L6s] | DS |  |
| 05 / 18 | May 02 *13.15-15.00* | Lindholmen Open Arena | Process supervision | HB & JP | [D2](README.md#pass--fail) |
| 06 / 19 | May 09 *13.15-15.00* | VasaC | Future of Software | Interaktionsbyrån |  |
|  | May 11 *13.15-15.00* | Vasa3&4 | Process supervision | HB & JP |  |
|  | May 13 *13.15-15.00* | VasaC | Product and organisation | Spotify |  |
| 07 / 20 | May 20 *13.15-15.00* | VasaC | [Reflection reports][LX] | HB |  | 
| 08 / 21 | May 25 *13.00-16.00* | Lindholmen Open Arena | Final presentation | HB | [D3](README.md#pass--fail) |
| 09 / 22 | Jun 03 *17.00* | -- | Hand off | HB | [D4](README.md#pass--fail) |

[VBEC]: https://www.facebook.com/pages/Volvo-Bus-Experience-Center/477546525732720 
[timeedit]: https://se.timeedit.net/web/chalmers/db1/public/ri157XQQ709Z50Qv17003gZ6y6Y7006Q5Y61Y5.html
[GITBOOK]: http://git-scm.com/book
[gitvid]: http://git-scm.com/videos
[pv1]: http://www.scrumalliance.org/community/articles/2009/january/the-product-vision
[pv2]: http://www.joelonsoftware.com/articles/JimHighsmithonProductVisi.html
[gitbranch]: http://nvie.com/posts/a-successful-git-branching-model/
[LearnGitBranching]: http://pcottle.github.io/learnGitBranching/
[AndroidPatterns]: http://www.slideshare.net/PedroVicenteGmezSnch/software-design-patterns-on-android/
[DELS]: https://github.com/hburden/DAT255/wiki/Deliverables 
[ScrumSurvey]: https://docs.google.com/forms/d/1Z4J-g2Eaj97jCx8NIvEOIQBpr0jCWavUk9x72bjNLv0/viewform?usp=send_form


[socialcontract]: http://www.agileacademy.com.au/agile/sites/default/files/Social%20Contract%202011.pdf

[xkcd]: http://xkcd.com/1425/
[COCO]: http://youtu.be/5HbYScltf1c

[L1]: https://github.com/hburden/DAT255/blob/master/Slides/L1-Overview.pdf?raw=true
[L2]: https://github.com/hburden/DAT255/blob/master/Slides/L2-Project.pdf?raw=true
[L3n]: https://github.com/hburden/DAT255/blob/master/Slides/L3-NewScrum.pdf?raw=true
[L3o]: https://github.com/hburden/DAT255/blob/master/Slides/L3-OldScrum.pdf?raw=true
[L4]: https://github.com/hburden/DAT255/blob/master/Slides/L4-Project.pdf?raw=true
[L5]: https://github.com/hburden/DAT255/blob/master/Slides/L5-SWEPM.pdf?raw=true
[L6l]: http://www.ait.chalmers.se/~sjolie/Pressence/?slides=sep_hci
[L6s]: https://github.com/hburden/DAT255/blob/master/Slides/L6-HCI.pdf?raw=true
[LX]: https://github.com/hburden/DAT255/blob/master/Slides/LX_Final.pdf?raw=true

[L8]: https://github.com/morganericsson/DAT255/blob/master/slides/l8.pdf?raw=true
[PS]: https://github.com/morganericsson/DAT255/blob/master/presentations.md



[gittut]: https://www.atlassian.com/git/tutorials
[androidtut1]: https://github.com/morganericsson/DAT255/blob/master/tutorials/android1.md


## Examination
The individual grades are based on the team contribution. Contribution is in turn defined according to *Stakeholder value*, *Protoype* and *Reflection report*. Each category represents a certain number of points so that the total number of points sums to 50. The points are not evenly distributed across the categories since the assessment occurs at different points in time and represent different efforts.

### Pass / Fail
To pass the course **each team** has to deliver:

- D1: Setup: The first deliverable consists of two parts,
  - D1.A: A one-page document drawing on the lessons from the Lego scrum exercise on how to initially work with scrum. Describe three insights from the exercise and how these will affect how you implement Scrum in your project. To be e-mailed to the course responsible at least 24h before the lecture on Scrum.
  - D1.B: A [vision](README.md#course-literature) or a concept for the prototype. An initial product backlog. A [social contract][socialcontract] for the team. Make sure D1.B is in your git account in time for the first process supervision meeting!
- D2: Half-time evaluation: A one-page document reflecting on the work so far, both in terms of process and product.
- D3: Final presentation: The third deliverable is a *working prototype* (APK) for the final presentation.
- D4: Signing off: The last deliverable consists of deliverables D1, D2 and D3 including the source code and the output from [gitinspector][GitInspector] as well as the artefacts asked for under [Prototype](### Prototype) and [Reflection Report](### Reflection Report).

within the designated deadlines.

To pass the course **a student** has to deliver:
- evidence for active participation in the team effort. The level of student participation is determined on a combined assessment of the output from [gitinspector][GitInspector] and the mean values from the team evaluation. 
- an evaluation of the members of the team, including themselves. Imagine that you have a budget of $10 per group member, including yourself (so, $50 for a group of 5). How would you distribute this "pay" among your group members, based on their value and contribution? Email your evaluation (name and amount for each group member *including* yourself) to burden@cse.gu.se no later than 03 June 17:00 2016. (The evaluation will not affect the group grade, it will only be used to determine individual variation within a group. However, if you do not submit this evaluation, you will not pass the course).

within the designated deadline

### Stakeholder value, 9p
The stakeholder value is assessed during the final presentation. The total score is the sum of
- Completeness (features outlined in vision are present, one application and stable operation)
- GUI (self-explanatory for intended users, clarity and no excess information) 
- Relevance to vision (efficiency and clear relation to vision document)

Each part is worth 0-3 points where 0 represents failed delivery, 1 equals major remarks, 2 signifies minor remarks and 3 no remarks. 

### Prototype, 22p
All artefacts related to the prototype should be in the Git repository. These will be assessed after the final deadline of the course. 
- Code quality, 3p. Code quality is based on the verdict of [FindBugs][FindBugs] where the sum of issues gives the number of points for code quality
  - 0-10 = 3p
  - 11-20 = 1p
  - >21 = 0p where the impact of each kind of *Correctness issues* counts as 4,  *Bad style* as 2,  *Dodgy* as 2  and *Performance* as 1. Each team is responsible for uploading the FindBugs report to their repository.
- Unit tests, 3p
- Integration / system tests, 3p
- Acceptance tests, 3p
- Design rationale (choice of API-level, external dependencies, database structure etc.), 3p
- Overview, 3p
  - Behavioural
  - Structural (What major parts / components are there in the application)
  - Protocol (client/server) 
- User stories, 3p 
- Burn-down chart, 0-1p (present or not)

Each part worth 3 points has an allocation strategy where 0 represents failed delivery, 1 equals major remarks, 2 signifies minor remarks and 3 no remarks.

### Reflection report, 19p
The reflection report is also uploaded to the git repository as a PDF-file. It will be assessed after the final deadline of the course.
- Application of scrum
  - Roles, team work and social contract 
  - Used practices (pair programming, stand-up meetings, etc.)
  - Time distribution (person / role / tasks etc.)
  - Effort and velocity
  - User stories and tasks
- Reflection on the sprint retrospectives, 1p
- Reflection on the sprint reviews
  - Feedback from stakeholders
  - Interaction with stakeholders
- Best practices for new tools and technologies
- Reflection on the relationship between *prototype*, *process* and *stakeholder value*
- Relation to literature or guest lectures
- Comments to D1 and D2

Each part worth 3 points has an allocation strategy where 0 represents failed delivery, 1 equals major remarks, 2 signifies minor remarks and 3 no remarks.

Reflection is here defined as *“assessment of what is in relation to what might or should be and includes feedback designed to reduce the gap”* (R. Smith. Formative Evaluation and the Scholarship of Teaching and Learning. *New Directions for Teaching and Learning*, vol. 88, 2001, pp. 51-62). This means that you should describe the situation as it is, what you would like it to be as well as a realistic way to get there.


### Grades
The team grade is given by the total number of points for the team effort:
- 00 - 20: U (Fail)
- 21 – 30: 3 / G (Pass)
- 31 – 40: 4
- 41 – 50: 5 / VG

The team grade then serves as a baseline for the individual grades so that students with higher contributions **and** team effort receive a higher grade than the team grade and students with lower individual scores receive a lower grade. Higher and lower are approximately 25% more / less than team average.

[FindBugs]: http://findbugs.sourceforge.net/
[GitInspector]: https://github.com/ejwa/gitinspector

We strive for a transparent and fair assessment strategy. [That is why we as teachers are the ones that do the grading based on our experience][fairgrades].

[pmr]: http://github.com/morganericsson/DAT255/wiki/Post-Mortem-Report
[fairgrades]: http://www.cse.chalmers.se/~burden/pdfs/BurdenHeldalAdawi.pdf


