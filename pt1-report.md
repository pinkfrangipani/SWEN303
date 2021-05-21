# Project - Pt1 Prototyping Report  

## Table of Contents
1. [Background](#background)  

2. [Personas](#personas)  

3. [Scenarios](#scenarios)  

4. [Designs Ideation](#ideation)  

5. [Designs Review](#review)  

6. [Prototype](#prototype)  

8. [Demonstration Video](#video)  

9. [Group Reflection](#reflection)  
  
## Background<a name="background"></a>

### Description
A student questioning system (SQS) allows students to create and answer each other’s multi-choice exam-style questions on course content. It is mainly targeted at university students for this context. This allows students to demonstrate their understanding by answering, rating and providing feedback as explanations, as the creator and answerer. It solves an accessibility problem in where students can help to teach their peers and themselves via a platform that encourages collaboration. This allows the reciprocation of feedback among students to consolidate understanding of course content, therefore a likelihood of achieving better grades. It can also be beneficial in the context of distance learning and large class sizes as it enhances the social aspects of collaboration, creating a community.  

The main users are university students, but it can also assist lecturers. Most of the time goes towards the communication of key ideas and techniques rather than the application of it. Through the SQS, lecturers can moderate the students' questions, which may lead to valuable insights in students applying learned ideas. This may improve teaching judging from the gaps in knowledge demonstrated. 

The current user interface of the Peerwise system is dated and a new system will aim to remedy this to modern standards. A new SQS will be proposed based on the existing system of Peerwise and the designs of our team. The SQS will be in the form of a prototyped website that demonstrates user flow control and semi-functionality. This will feature an improved interface design that includes the needs that will be explored by different users. 

We aim to ideate and combine aspects of the different designs our team have created. This proposition will be delivered with an emphasis on different types of users and their goals. This will be explored by selecting and combining existing personas, and scenarios through our team. Explanations on our team's decision making in how we approach the final prototype will be provided.

### Business Objectives

Our business objectives are as followed:

1. Provide smoothness and simplicity for students' interaction and their needs in a university context
2. Aid students in improving their quality of learning and assessments results
3. Support lecturers in their role of overseeing, moderating and teaching
4. Enhance cost efficiency and effectiveness

To meet these objectives, the new system needs to assist students’ learning and understanding of course content through getting answers to questions and having confidence that the information is correct. To achieve this, the system needs an unconvoluted interface with optimised methods of question creation and evaluation and functions for navigating the website. This means that the system should be smooth and seamless to utilise. If students' interactions are positive, they will continue to use it and possibly improve their quality of learning, therefore achieving better assessment results. In addition, the system can incorporate the conveniences of user-created social study spaces and remove the requirement of unlocking features to increase accessibility. 

The needs of the students and the lecturers are essential for the success of the system's usage. From the perspective of the students, it will need the features of creating, answering, rating, sorting and commenting on questions. From the lecturer's, they will need moderator tools such as inviting students, deleting questions and comments. 

It is also important that the system must assist lecturers that will organise and maintain it. The key role of lecturers in this system is to oversee and moderate students. This can be in terms of a behavioural and an academic manner. For example, behaviourally, the lecturer will need to delete inappropriate questions and comments from students. Academically, it can be commenting on questions that focus on content that is not likely to be assessed.

The overall cost to use the SQS would be low, due to the nature of the students handling their own content. There is just the cost of time from the lecturer. This includes the initial setup from inviting students and ongoing frequent moderation. An example of cost-effectiveness is reducing the amount of hours the university must pay tutors. The students should be able to collaborate with any amount of interaction from the lecturer supported by the system itself. This interaction can be minimal to frequent in terms of moderation, inviting new students and feedback in comments.      

## Personas<a name="personas"></a>
- [Rebecca Taylor](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/personas/rebecca.md) - Te Ata 
- [Dennis Casas](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/personas/dennis.md) - Te Ata
- [Elizabeth](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/personas/elizabeth.md) - Jane  
- [Steven Ash](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/personas/Steven.md) - Justin  

### How personas were selected and merged  
We selected our personas based on a comprehensive discussion, throwing ideas and thoughts back and forth. We mainly selected our personas based on similarity and diversity. To help us make these decisions we created a table of attributes that spanned across all our personas. This table covers their strengths, weaknesses, abilities, and system usage.  

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/personas/persona-attribute-table.PNG" alt="Persona Attribute Table" width="1311" height="787">

Throughout the group, we found out that many personas were similar and diverse in many ways. Our different personas were similar in terms of their goals and habits. This was beneficial as we could tweak and combine different aspects in our personas. The similarities also meant that we had a consensus with attributes that we valued and agreed upon.  

It was also necessary to focus on differences among our selection. A necessary part was to cover a wide range of needs for our system. This meant validating how generalised our personas were. If our personas were too similar, our system would be built around only those personas. Therefore, excluding potential users with diverse traits. Through our discussion, we found that our personas were different in terms of abilities, resilience, and weaknesses. This meant that we had a range of attributes that our system needed to assist with.  

We selected two student personas; Rebecca and Dennis, that were created by Te Ata. We felt that Rebecca and Dennis captured two individuals with a different lifestyle and approach to their studies. Both of their goals are to succeed in their courses to achieve their dream careers. The SQS is a system that they use to understand course content. Dennis is characterised as a busy student that finds it difficult to manage his time. Rebecca is Dennis is categorised as an individual with low organisation whereas Rebecca is categorised as highly organised. We correlated how organised an individual is to their usage of the system which may represent two archetypes of individuals.  

We also selected Jane's Elizabeth and Justin's Steven personas. With Elizabeth, she has a goal of pursuing an academic career with an emphasis on helping her peers. She is characterised as an individual that does not have much experience with a student questioning platform but enjoys teaching and tutoring. The SQS is the perfect platform to practice her teaching skills in creating questions and explanations. Steven is a lecturer that primarily uses the SQS to provide his students with a platform where they can help each other in demonstrating knowledge of taught content in his course. He wishes to make sure that the students are using the system properly in a safe and collaborative environment. His goal is to maximise the quality of his teaching resources and academic research while minimising effort.

Through this selection process, we believe that we found a diverse range of personas but are also general enough to capture a large number of similar users while minimising our biases. We have selected personas with different goals, attitudes and motivations that users may relate to so the SQS can help them and their needs.



## Scenarios/Use cases
We have selected multiple use cases to represent our system and the needs of our personas:

**Create question - Personas: Rebecca, Dennis, Elizabeth**    
From Te Ata

| User                      | System                       |
|:--------------------------|:-----------------------------|
| Choose classroom          |                              |
|                           | Display classroom main menu  |
| Choose create question    |                              |
|                           | Display create question page |
| Write question            |                              |
|                           | Submit text                  |
| Write alternative answers |                              |
|                           | Submit text                  |
| Indicate correct answer   |                              |
|                           | Select answer                |
| Submit question           |                              |
|                           | Publish question             |

**Answering question - Personas: Rebecca, Dennis, Elizabeth**  
From Te Ata

| User                                 | System                      |
|:-------------------------------------|:----------------------------|
| Choose classroom                     |                             |
|                                      | Display classroom main menu |
| Choose view other people’s questions |                             |
|                                      | Display questions page      |
| Choose question                      |                             |
|                                      | Display answers page        |
| Select answer                        |                             |


**Rate question - Personas: Rebecca, Dennis, Elizabeth**  
From Te Ata  

| User                                 | System                      |
|:-------------------------------------|:----------------------------|
| Choose classroom                     |                             |
|                                      | Display classroom main menu |
| Choose view other people’s questions |                             |
|                                      | Display questions page      |
| Choose view answers                  |                             |
|                                      | Display answers page        |
| Rate question                        |                             |
|                                      | Highlight selected ratings  |
| Enter rating                         |                             |
|                                      | Submit rating               |


**Take quiz - Personas: Rebecca, Dennis, Elizabeth**  
From Te Ata  

| User             | System                      |
|:-----------------|:----------------------------|
| Choose classroom |                             |
|                  | Display classroom main menu |
| Choose quiz      |                             |
|                  | Display quiz menu           |
| Choose quiz type |                             |
|                  | Start quiz                  |
| Answer question  |                             |
|                  | Record answer               |
|                  | Display next question       |
| Finish quiz      |                             |
|                  | Display quiz results page   |


**Find question - Personas: Rebecca, Dennis, Elizabeth**  
From Te Ata 

| User                  | System                      |
|:----------------------|:----------------------------|
| Choose classroom      |                             |
|                       | Display classroom main menu |
| Choose view questions |                             |
|                       | Display question page       |
| Select search bar     |                             |
|                       | Display search options      |
| Enter search terms    |                             |
|                       | Display search results      |
| Choose question       |                             |
|                       | Display question page       |


**Add comment to a question - Personas: Rebecca, Dennis, Elizabeth**  
From Te Ata  

| User                                 | System                 |
|:-------------------------------------|:-----------------------|
| Choose classroom                     |                        |
|                                      | Display classroom      |
| Choose view other people’s questions |                        |
|                                      | Display questions page |
| Choose view answers                  |                        |
|                                      | Display answers page   |
| Write comment                        |                        |
|                                      | Publish comment        |


**Join classroom - Personas: Rebecca, Dennis, Elizabeth**  
From Chris 

| Moderator           | System                          | Student                                                  |
|:--------------------|:--------------------------------|:---------------------------------------------------------|
| Enter student email |                                 |                                                          |
|                     | Generates code                  |                                                          |
|                     | Send email with code to student |                                                          |
|                     |                                 | Student enters code from email in classroom page to join |



**Ask a general question on the forums - Personas: Rebecca, Dennis, Elizabeth**  
From Chris

| User                  | System                                   |
|:----------------------|:-----------------------------------------|
| Choose course         |                                          |
|                       | Display course page, posts and actions   |
| Make new post         |                                          |
|                       | Allow for text input                     |
| Enter content of post |                                          |
| Confirm post          |                                          |
|                       | Add post to list of posts on course page |

**Answer a general question on the forums - Personas: Rebecca, Dennis, Elizabeth**  
From Chris

| User                   | System                                 |
|:-----------------------|:---------------------------------------|
| Choose course          |                                        |
|                        | Display course page, posts and actions |
| Select post to answer  |                                        |
|                        | Allow for text input                   |
| Enter content of reply |                                        |
| Confirm reply          |                                        |
|                        | Add reply to list of replies on post   |

**Modify/Remove Question/Comment - Personas: Steven**  
From Justin

| User                                     | System                                      |
|:-----------------------------------------|:--------------------------------------------|
| Choose classroom                         |                                             |
|                                          | Display classroom main menu                 |
| Choose view questions                    |                                             |
|                                          | Display question page                       |
| Select a question                        |                                             |
|                                          | Display selected question                   |
| Select question/comment to remove/modify |                                             |
|                                          | Display removal/modification prompt         |
| Select confirmation                      |                                             |
|                                          | Remove/modify question/comment from display |

### How scenarios were selected and merged
In our scenarios selection process we based our scenarios on the following criteria:

1. Similarity  

Upon analysing the scenarios we had created, we found that we all had similar scenarios such as answering and creating questions. This meant that we could just pick one and refine it since our similar scenarios were essential to the personas and the system. 

2. Relevance to selected personas needs  

A key part of the scenarios is the involvement of our selected personas. Since we are building the system around them, it is necessary to manage how they will perform in these scenarios. This means selecting and adapting scenarios that will help our selected personas to achieve their goals and needs.  

3. System functionality  

In deciding which scenarios to choose and modify, the system has to be taken into consideration. To meet the needs of our personas, the system must help them in achieving their goals so the scenario can be possible. This means incorporating the relationship between the different features and how the features will be used by our personas in the system.  

<br>

This selection process was relatively smooth. Since almost everyone had used essential use cases instead of the long narrative scenarios, it was simple to examine the use cases. In Te Ata's designs, we noticed that she had use cases for mostly all the essential features that we wanted for our system. We felt that it was time efficient to select those and modify them.   

We also chose three use cases from Chris' designs, specifically asking/answering general questions and joining a classroom. It was decided that we would incorporate a forum-like page to ask general questions like lecture schedule and course-related admin topics. This was supported by Te Ata's design which included a similar feature.  

Lastly, we chose Justin's moderator scenario in deleting and modifying questions/comments. We converted his long narrative style into a shortened use case. We felt that since we included a lecturer persona, we should also include their scenario so we could demonstrate how the system will help the lecturer persona. 


## Designs Ideation<a name="ideation"></a>  
Here is a sample each team member's designs on the question answering page and feature.  

**[Chris](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/individual-designs/Chris)**

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/individual-designs/Chris/UX_Concepts_1_Quiz.png" width="751" height="589">

<br>

***

**[Jane](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/individual-designs/Jane/peerwisewireframes.pdf)**

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/individual-designs/Jane/question-answering.PNG" width="480" height="856">

<br>

***

**[Justin](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/individual-designs/Justin)**

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/individual-designs/Justin/web-student-answer-question.PNG" width="914" height="514">

<br>

***

**[Te Ata](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/individual-designs/Te%20Ata)**

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/individual-designs/Te%20Ata/PSYC327_Quiz_question_page_answered.png" width="640" height="875">


## Designs Review<a name="review"></a>    
To review our designs, we use used a heuristic evaluation to measure the issues in all of our individual designs. We all individually assessed each other's designs using a spreadsheet template containing a list of Nielsen's Heuristics. We focused on the issues as we were striving for key elements that we could improve on our own designs and think of solutions that could remedy the issues. We believe that a key step in creating a combined prototype was to learn from our mistakes first. If we learn from what went wrong in our individual designs, we take one step closer to a better design and a better final prototype.

[Heuristics evaluations](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/tree/master/heuristics_analysis)

In our spreadsheet we measured issues by one of ten heuristics by Nielsen based on the following:   

- Severity: How big of an issue is it? 
- Frequency: Is the issue common or not?
- Persistence: Is the issue a one-time problem or a repeated one?
- Impact: Will the issue be easy or difficult for users to overcome?  

Here is an overview of what we found in our individual heuristic evaluations in assessing each others designs:

**Chris**

| Pros                                                                              | Cons                                            |
|:----------------------------------------------------------------------------------|:------------------------------------------------|
| Designs of pages are very clear and simple                                        | Designs does not have any colour                |
| Pages and layouts are consistent following the style of the content being centred | Courses directory should be less search focused |
| Design contains a feature of asking general questions in a forum styled page      | Limited help and documentation                  |
| Font choice and size is very clear                                                |                                                 |
| Consistent use of button representations and clickable objects                    |                                                 |

**Jane**

| Pros                                                                                                      | Cons               |
|:----------------------------------------------------------------------------------------------------------|:-------------------|
| Great consistency and use of classic iOS theme                                                            | Limited colour use |
| Good placement of navigation tabs at the bottom for ergonomic thumb placement                        | Misrepresentation of pages according to highlighted navigation buttons at the bottom                   |
| Indicators for selection/touch are clear                                                                  | Issues in login screen navigation                      |
| Space use is great with navagation buttons at the bottom, content in the middle and title at the top | Lack of confirmation for selecting an answer                  |
| Contrast between white and grey background makes the design clear and pleasant to look at                 | Limited help and documentation                   |

**Justin**

| Pros                                                                              | Cons                                            |
|:----------------------------------------------------------------------------------|:------------------------------------------------|
| Designs of pages looks modern                                        | Colour choice is a bit odd                |
| Good use of gradients and shadows | Not visual impairment friendly |
| Thought has gone into colour separation     | Gamification aspects such as quests, scores, points and leaderboards that encourage repetitive use are outdated (reminiscent of early 2000s)                   |
| Font choice is good                                             |Poor log out button placement 
|                   |  Some text are small                                               |
|                                                                                   | Underlines look like clickable links| 
|                                                                                   | Limited help and documentation| 
| | Poor hierarchy flow |
| | Lots of elements to process on Question answering completed page |
| | Shapes and information on the question (view, create and result) pages should be in a different arrangement |
|  | Indication of which class the user is currently browsing/creating questions in should be bigger/clearer |

**Te Ata**

| Pros                                                                              | Cons                                            |
|:----------------------------------------------------------------------------------|:------------------------------------------------|
| Contains lots of comprehensive features to utilise such as quiz generations and a dedicated general questions section/forums.                                       | Course selection page is a bit busy                |
| Good use of colours and icon to indicate selection and correctness                | Drop downs on quiz question details are unnecessary  |
| Great use of size and space, makes it very clear and obvious                      | Limited help and documentation                  |
| Simple colour scheme of blue, white and grey works well                           |                                                 |
| Lots of user freedom and control with adjusting quiz settings                     |                                                 |


## Prototype<a name="prototype"></a>     
### Description
Our team developed our final click-through prototype with Adobe XD. Our system contains the following layouts and features according to their functionality and intractability. We overestimated our capability in terms of making our desired use case scenarios functional. To remedy this, we picked the most essential to produce an interactive sequence. 

| Pages/features                | Interactability                                       |
|:------------------------------|:------------------------------------------------------|
| Homepage                      | Access login page via login button                    |
| Login                         | Access student dashboard/classrooms via login button  |
| Student dashboard/classrooms  | Access PSYC327 classroom via PSYC327 classroom button |
| Browse questions              | Interactive sequence initiated from "What brain slice is this question.".                                                          |
| Answer question              | Selecting answer and submit buttons are clickable. After submitting, difficulty and quality rating stars are clickable with submit button. Retry and exit buttons are also functional.                                                      |
| Create questions              | This leads to an interactive sequence where all of the buttons on the page are clickable.                                                       |
| Forums                        | Not functional                                                      |
| Starting quiz                 | This leads to an interactive sequence where some of the buttons on the page are clickable.                                                      |
| Profile                       | Not functional                                                         |
| Lecturer dashboard/classrooms | Interactive sequence initiated from entering PSYC327 classroom button                                                     |
| Lecturer question deletion    | This sequence continues after selecting the "What brain slice is this" question and clicking the delete button.                                                      |
| Lecturer admin page           | Not functional                                                      |


### Approach 
From our designs review, we decided to choose a prototype as a foundation for our revised system. We chose Justin's design to build off because it was a good starting point to combine our designs and ideas. Justin's prototype looked modern and it contained components and layouts that were well fleshed out. Time efficiency was considered in this decision. The assets in the existing prototype were already well made and ready for use, it would be inefficient to restart from zero again. With this choice, we agreed that we would be focusing on a website based system. 

Although there were many flaws in Justin's prototype, they were all easily fixable. An example was the flow hierarchy structure in transitioning between different pages and features. The hierarchy structure in the original prototype was not clear in terms of what classroom/course the header buttons referred to. Drop-down boxes were used to select which classroom the user wanted to answer or create questions in which was confusing. A solution to this problem was to have a state where the user would have to enter a classroom. This allowed the removal of drop-down boxes and made the system more user-friendly by removing this complex association with picking a classroom for every feature in the classroom. 

In analysing the hierarchy structure, we decided to rethink the flow of our system. We created the following diagram to describe the architecture of the new system. Through this, we took in the features we wanted, which was represented in the use cases above.    

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/project-hierarchy.png" width="942" height="672">


### Prototype Design
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/prototype-storyboard-view.PNG">

#### Aesthetics
From our heuristics evaluations, clarity plays a major factor in judging how well a design performs. In our approach we used big fonts and a modified colour palette.

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/resource%20Board.png">
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/final-prototype/designs-images/colour%20palette.png">

Most of the fonts were kept from Justin's original prototype. We felt that these fonts were good enough and there were not any reasons to switch. We did modify the colour palette and scheme to emphasize productivity. From [Shift e-learning](https://www.shiftelearning.com/blog/how-do-colors-influence-learning), shades of blue represent productivity which is a key theme for the system which is dedicated to question-based learning. We made the change to include more shades of blue. I think we were all sceptical about this colour scheme but it eventually grew on us because we looked and worked on the designs for a long period. We will be interested in the results of how users feel during the next part of user testing.   

#### Prototype discussion and walkthrough

In this section, key pages with interactions will be discussed. Full coverage of the system will be demonstrated in the video.

Most pages in our design follow a similar layout containing the same header bar. The header bar contains:
- The PeerRevise logo for returning to the classrooms/dashboard page.
- A nonfunctional notification indicator.
- The profile icon which leads to a profile page containing a bio, created questions and answered questions.
- A nonfunctional (but animated) drop down box containing nonfunctional options for settings, help and logging out. 
- Selection buttons for browsing questions, creating a question, starting a quiz, and starting a quiz.

We felt that the header bar was an essential component for navigation. In our heuristic evaluations we thought that this header bar was better than a directory path navigation flow. This was because the directory path can be often long and it is difficult to fit this into the page clearly and consistently. The header bar achieves this by having most of the main features at the top of every page, the user does not have to know the path of the pages that they have taken.

##### Classrooms/Dashboard Page
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/dashboard%20-%20student.png">

Components of page:
- Boxes showing joined classrooms
- Join classroom box 
- Pending requests indication

This page appears after the user has navigated from the login page. Upon entering, a selection of classrooms are shown in a light blue boxes. The PSYC327 classroom box is clickable, which is demonstrated by a hover animation where it outlines the box as grey. After clicking the box, the user is transitioned into the PSYC327 classroom where all the features such as question browsing, answering and creating are accessed from.   

## Demonstration Video<a name="video"></a>  
Video goes here.  


## Group Reflection<a name="reflection"></a>  
### Design merge reflection  
- How did we get together? 
- How did we decide and what was the process?  
- Were our decision technique effective?  
- What were some difficulties?
- Did we do anything wrong, if so what would we change next time?    
- What did we learn from this?

We decided to book a room at campus to meet up once a week to exchange files, decide on the tasks we needed to complete, and allocate these tasks. We used a spreadsheet and a chat group to keep track of our ideas and discussions. As a team, we had to decide what the essential features of PeerWise (PeerRevise) were, so as to avoid convoluting the design with too many features and making the scope of the prototype larger than we could complete within the timeframe. The choosing of and agreement on whose design and personas to use took us longer than was ideal, possibly because we were afraid to appear controlling and bossy, leading us to be too careful in starting anything without listening to all feedback and getting the confirmation from every team member. This meant we were left with a short amount of time before the due date, and had to quickly make decisions on what the prototype would look like and what features it would have. If we had the chance, we would improve on this rushed decision process by doing a formal analysis and heuristic evalution of each other's designs beforehand. 

When combining our ideas, each member had to make compromises on their personal vision for what PeerWise should be able to do.  

### Analysing best and worst aspects of the prototype
- What was good about the prototype?  
- What was bad about the prototype?
- What can we do to make it better?
- Did we do anything wrong, if so what would we change next time? 
- What did we learn from this?

Points to cover:
- We chose to use Justin's design as a base to build off of since it has the closest look and feel to what we wanted. This saved us a lot of time
- We should have possibly done the heuristics analysis of designs before choosing the design that we were going to use as our base


- The prototype has a simple design which is easy to understand and navigate
- The peerwise logo takes you to the dashboard which is an effective use of space but does require the user to remember that that is how you get back to the dashboard
