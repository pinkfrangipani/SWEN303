# Project Report

## Table of Contents

[Part 1: Prototyping](#pt1)

1. [Background](#background)  

2. [Personas](#personas)  

3. [Scenarios](#scenarios)  

4. [Designs Ideation](#ideation)  

5. [Designs Review](#review)  

6. [Prototype](#prototype)  

8. [Demonstration Video](#video)  

9. [Group Reflection](#reflection)  
  
  
[Part 2: User Testing](#pt2)

10. [Usability Testing Plan](#testingplan)
  
11. [Usability Test Results](#results)  
  
12. [Updated prototype based on user testing](#updates)
  
13. [Usability Test Discussion](#discussion)
  
  
# Pt1 - Prototyping <a name="pt1"></a>
  
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
We selected our personas based on a comprehensive discussion, throwing ideas and thoughts back and forth. We mainly selected our personas based on similarities and differences. To help us make these decisions, we created a table of attributes that spanned across all of our personas. This table covers their strengths, weaknesses, abilities, and system usage.  

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/personas/persona-attribute-table.PNG" alt="Persona Attribute Table" width="1311" height="787">

Throughout the group, we found out that many personas were similar and diverse in many ways. Our different personas were similar in terms of their goals and habits. This was beneficial as we could tweak and combine different aspects in our personas. The similarities also meant that we had a consensus with attributes that we valued and agreed upon.  

It was also necessary to focus on differences among our selection. A necessary part was to cover a wide range of needs for our system. This meant validating how generalised our personas were. If our personas were too similar, our system would be built around only those personas. Therefore, excluding potential users with diverse traits. Through our discussion, we found that our personas were different in terms of abilities, resilience, and weaknesses. This meant that we had a range of attributes that our system could assist with.  

We selected two student personas; Rebecca and Dennis, that were created by Te Ata. We felt that Rebecca and Dennis captured two individuals with a different lifestyle and approach to their studies. Both of their goals are to succeed in their courses so that they can achieve their dream careers. The SQS is a system that they use as a way to achieve these goals by succeeding in their understanding of course content. Dennis is characterised as a busy student that finds it difficult to manage his time. Rebecca is characterised as a diligent student that manages her time well. Through this contrast, we correlated how organised a persona is to their usage of the system which may represent two archetypes of individuals.  

We also selected Jane's Elizabeth and Justin's Steven personas. With Elizabeth, she has a goal of pursuing an academic career with an emphasis on helping her peers. She is characterised as an individual that does not have much experience with a student questioning platform but enjoys teaching and tutoring. She uses the SQS to practice her teaching skills in creating questions and explanations. We found this  Elizabeth to be valuable where her values may represent a user archetype categorised by frequent usage and a desire to help individuals learn.

Steven is a lecturer that primarily uses the SQS to provide his students with a platform where they can help each other in demonstrating knowledge of taught content in his course. He wishes to make sure that the students are using the system properly in a safe and collaborative environment. His goal is to maximise the quality of his teaching resources and academic research while minimising effort. Steven is an entirely different archetype compared to students which brings in a user with different goals. To diversify our range of users, we thought it would be great to include Steven. 

Through this selection process, we believe that we found a diverse range of personas but are also general enough to capture a large number of similar users while minimising our biases. We have selected personas with different goals, attitudes and motivations that users may relate to so the SQS can help them and their needs. 


## Scenarios/Use cases<a name="scenarios"></a>
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

Lastly, we chose Justin's moderator scenario in deleting and modifying questions/comments. We converted his long narrative style into a shortened use case. We felt that since we included a lecturer persona, we should also include their scenario so we could demonstrate how the system will help the lecturer's goals and needs. 


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

Here is an overview of what we found in our individual heuristic evaluations in assessing each other's designs:

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
| Space use is great with navigation buttons at the bottom, content in the middle and title at the top | Lack of confirmation for selecting an answer                  |
| Contrast between white and grey background makes the design clear and pleasant to look at                 | Limited help and documentation                   |

**Justin**

| Pros                                                                              | Cons                                            |
|:----------------------------------------------------------------------------------|:------------------------------------------------|
| Designs of pages looks modern                                        | Colour choice is a bit odd                |
| Good use of gradients and shadows | Not visual impairment friendly |
| Thought has gone into colour separation     | Gamification aspects such as quests, scores, points and leaderboards that encourage repetitive use are outdated (reminiscent of the early 2000s)                   |
| Font choice is good                                             |Poor log out button placement 
|                   |  Some text is small                                               |
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
| Good use of colours and icon to indicate selection and correctness                | Dropdowns on quiz question details are unnecessary  |
| Great use of size and space, makes it very clear and obvious                      | Limited help and documentation                  |
| Simple colour scheme of blue, white and grey works well                           |                                                 |
| Lots of user freedom and control with adjusting quiz settings                     |                                                 |



## Prototype<a name="prototype"></a>     
### Description
Our team developed our final click-through prototype with Adobe XD. Our system contains the following layouts and features according to their functionality and intractability. We overestimated our capability in terms of making all of our desired use case scenarios functional. To remedy this, we picked the most essential and only made interactive sequences for them. 

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
From our heuristics evaluations, clarity plays a major factor in judging how well a design performs. In our approach, we used big fonts and a modified colour palette. Most of the fonts were kept from Justin's original prototype. We felt that these fonts were good enough and there were not any reasons to switch. We did modify the colour palette and scheme to emphasize productivity. From [Shift e-learning](https://www.shiftelearning.com/blog/how-do-colors-influence-learning), shades of blue represent productivity which is a key theme for the system which is dedicated to question-based learning. We made the change to include more shades of blue. I think we were all sceptical about this colour scheme but it eventually grew on us because we looked and worked on the designs for a long period. We will be interested in the results of how users feel during the next part of user testing.   

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/resource%20Board.png">
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/colour%20palette.png">


#### Prototype discussion and walk-through

In this section, key pages with interactions will be discussed. Full coverage of the system will be demonstrated in the video.

Most pages in our design follow a similar layout containing the same header bar. The header bar contains:
- The PeerRevise logo for returning to the classrooms/dashboard page.
- A nonfunctional notification indicator.
- The profile icon, which leads to a profile page containing a bio, created questions and answered questions.
- A nonfunctional (but animated) drop-down box containing nonfunctional options for settings, help and logging out. 
- Selection buttons for browsing questions, creating a question, starting a quiz, and starting a quiz.

We felt that the header bar was an essential component for navigation. In our heuristic evaluations, we thought that this header bar was better than a directory path navigation flow. This was because the directory path can be often long and it is difficult to fit this into the page clearly and consistently. The header bar achieves this by having most of the main features at the top of every page, the user does not have to know the path of the pages that they have taken.

##### Classrooms/dashboard page
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/dashboard%20-%20student.png">

Components of page:

- Boxes showing joined classrooms
- Nonfunctional join classroom box 
- Nonfunctional pending requests indication

This page appears after the user has navigated from the login page. Upon entering, a selection of classrooms is shown in light blue boxes. The PSYC327 classroom box is clickable, which is demonstrated by a hover animation where it outlines the box as grey. After clicking the box, the user is transitioned into the PSYC327 classroom where all the features such as question browsing, answering and creating are accessed from.   

##### Questions browsing page
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/questions%20-%20student%20login.png">

Components of page:

- Nonfunctional filter bar
- Rectangles represented as questions

This page allows users to search and browse for questions. Each question is displayed with their details such as question name, topics associated, number of times the question has been answered, quality and difficulty ratings given the highlighting of stars and the number of comments, and the author and date created at the top right.

The first question is clickable where an interactive sequence is initiated for answering a question.   

##### Question answering page
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/answer%20quiz%20question.png">

Components of page:

- Question title and optional question diagram
- Answer selection boxes
- Submit and return buttons
- Question details box
- Nonfunctional add to quiz box

The question answering page contains the question and its multi-choice selections. These multi-choice selections are functional and change to a different shade of blue, font colour and icon. From our heuristic evaluations, we found that matching a selected colour and an icon is important for supporting users with visual impairment. 

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/quiz%20question%20results.png">

Updated components of page:

- Rate quality and difficulty box
- Explanation box
- Nonfunctional comments and add comment box

After clicking the submit button, the page will be updated to reflect the result of the user's correctness to the question. This is shown by the colour change to green, with the text "Correct!," and alongside a tick icon.

The rating and comment boxes are visible to the user after they have answered the question. The rating box is functional with each star being clickable with the submit rating button.

##### Question creation page and interaction sequence
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/question%20creator.png">

Components of page:

- Question text input box
- Add image box
- Answer selection buttons
- Save draft, preview and publish buttons
- Add explanation text input box
- Choose topics box

This create question page allows a user to create their own question. This whole page is intractable with each component that can be selected or clicked. Unfortunately, user input such as typing is currently unsupported by Adobe XD, this means that we had to simulate typing with predetermined input with clicking. 

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/question%20creator%20-%20simulated%20input.PNG">

After the user has clicked all of the components on the page, this is what it looks like. 

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/question%20creator%20-%20preview.png">

After clicking the preview button, the page updates to a question answering page with a return and publish button. This ensures that the question creator can directly see how it is displayed and that their uploaded image is correct.

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/question%20creator%20-%20created%20question%20appears.png">

The question creator interaction sequence ends after the user has clicked the publish question button. This new page displays an updated question browsing page with the newly created question.

##### Start quiz page and interaction sequence
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/start%20new%20quiz.png">

Components of page:

- Nonfunctional Generate and start quiz boxes
	* Choose quality box
	* Choose difficulty box
	* Choose topics box
	* Choose quiz size/number of question box
	* Generate and start quiz button
- Browse quizzes section 
	* Nonfunctional filter bar
	* Rectangles represented as quizzes with a start quiz button

The start quiz page allows users to assess themselves with a collection of questions instead of just completing one and finding another. These collection of quizzes are usually the same type according to their topics selected

The generate and start quiz is not demonstrated in this prototype. It is a feature that automatically generates a quiz by putting similar questions together based on the user's preferences and options applied through the boxes. 

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/taking%20a%20quiz.png">

Updated components of page:

- Quiz title
- Quiz author
- Quiz number selection and indicator
- Next question and exit quiz button

Upon clicking the start quiz button on the first quiz in the browse quiz section, the user is brought to a quiz answering page. This page is similar to a single question answering page but it displays a banner of numbers representing each question of the quiz. This provides the user navigation to move between questions and an indicator for the question that they are on. Previous questions have their numbers faded with a line underneath and the current question number is highlighted.

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/taking%20a%20quiz%202.png">

Updated components of page:

- View results button

After the user has reached the last question in the quiz and selected their answer a view results button appears. This takes the user to a new page to view their results and how well they did in the quiz.

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/quiz%20results.png">

Updated components of page:

- Results title page with the title of quiz and author
- Each numbered question box denoting the correctness of the user's answers 
	* Feedback on user's answers vs actual answers 
	* A button to access the question

On this quiz results page, the user can see what question they got wrong as every numbered question is represented as a green or red box. Green indicating that their answer is correct and red is incorrect. They also can click the icon in the top right of a question to see more information about the question.

Upon clicking the return to browse quizzes button, the interaction sequence ends.

##### Lecturer pages and delete question interaction sequence
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/dashboard%20-%20lecturer.png">

Components of page:

- Boxes showing joined classrooms
- Nonfunctional join classroom box 
- Nonfunctional classroom analytics and feed

This interaction sequence is focused on the lecturer's task of moderation. The sequence interaction starts with the lecturer's own dashboard/classrooms page. This page is similar to the students' classroom page except there are classroom analytics and stats to keep track of what kind of activity is occurring with the PeerRevise system. 

There is also a separation of colour themes between students and lecturers views of the system. This was because it was easier to distinguish differences between interactions of students and lecturers during development. This can serve as a reminder to users as they could be a lecturer or a student in different classrooms.

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/questions%20%E2%80%93%20lecturer%20login.png">

Upon clicking the PSYC327 classroom, the lecturer is taken to the questions page to moderate questions. The lecturer selects the first question to look at.

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/lecturer%20view%20-%20modifying-removing.png">

Components of page:
- Everything from students page
- Admin operations box
	* Nonfunctional modify question title button
	* Nonfunctional modify correct answer button
	* Nonfunctional modify explanation button
	* Delete question button

In this interaction sequence, the lecturer decides to delete this question as the topic is no longer being assessed. 

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/lecturer%20view%20-%20modifying-removing%20%E2%80%93%201.png">

Upon clicking the delete question button, the page becomes transparent with a pop-up message appearing in the centre with a blue cancel button and a red delete question button. 

<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/lecturer%20question%20deletion%20-%20question%20disappears.png">

After confirming deletion by clicking the red delete button again, the lecturer is taken to the question browsing page. The deleted question is removed from the question browsing page and the interaction sequence ends.


## Demonstration Video<a name="video"></a>  
[Walkthough video of the system](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/final-prototype/VideoWalkthrough_Final.mp4)
<br>
<a href="https://www.youtube.com/watch?v=HlXoAkfIUQ4">Youtube link</a>

## Group Reflection<a name="reflection"></a>  

We decided to book a room at campus to meet up once a week to exchange files, decide on the tasks we needed to complete, and allocate these tasks. We used a spreadsheet and a chat group to keep track of our ideas and discussions. As a team, we had to decide what the essential features of PeerWise (PeerRevise) were, so as to avoid convoluting the design with too many features and making the scope of the prototype larger than we could complete within the timeframe. The choosing of and agreement on whose design and personas to use took us longer than was ideal, possibly because we were afraid to appear controlling and bossy, leading us to be too careful in starting anything without listening to all feedback and getting the confirmation from every team member. This meant we were left with a short amount of time before the due date, and had to quickly make decisions on what the prototype would look like and what features it would have. If we had the chance, we would improve on this rushed decision process by doing a formal analysis and heuristic evalution of each other's designs beforehand. 

When combining our ideas, each member had to make compromises on their personal vision for what PeerWise should be able to do. For example:
- Te Ata wanted to consolidate in one area as many links to other areas as possible, but it could not be implemented completely without violating the heuristic of aesthetics and minimalism 
- Justin was attached to the idea of the user scoring system/leaderboard, but it was vetoed to keep the scope of the prototype manageable and to conform to modern website design

Although our own personal opinions for what PeerWise should look like and how it should operate were not always compatible, and all of our ideas couldn't be incorporated into the final prototype, the merging of our designs allowed us to discover the unique features in each other's designs that we wouldn't have come up with individually. Evaluating each member's designs highlighted the importance of clear, understandable user interface hierarchies that are presented to the user simply and effectively. Creating a clear hierarchy is important not just to the user, but is also a useful first step in designing an interface, as it guides the creation of interface elements.

Our prototype has a more modern design than the original PeerWise website with:
- full colours instead of mostly white
- gradient background
- tile-based elements rather than a document with headings
- interactive, responsive components
- rounded buttons
- a forum based on contemporary social media websites
 
Due to time constraints, the full functionality of the proposed design was not realised in the prototype's interactions, and the composition is still unpolished. 
For example:
- the 'Settings' and 'Help' that is linked from the dropdown menu next to the profile picture does not have an interaction
- the Sort/Filter bar in the Browse Questions pages does not have an interaction
- the Staff account view does not have all its pages created, and not all of the admin controls have an interaction
- the different types of buttons aren't consistently coloured the same way, such as the text input fields and the exit buttons are both light blue
- some elements aren't consistently aligned from page to page, leading them to jump around when the user navigates through the prototype
- we didn't update the URLs in the browser to reflect the pages we created or the navigational hierarchy of the website
- the PeerRevise logo acts as a button that takes the user to their dashboard, but this is not indicated to the user, making it so they would have to guess that the logo is a button and where it links to

One of the best parts of our prototype is that we have four interactable sequences for user testing in the next part. We have three for the student archetype with question answering, question creation, and quiz answering. We have one for our lecturer archetype which is question moderation. With these four interactive sequences, we believe that we have enough use cases across two archetypes that generally covers the main aspects of our system. This means that we should have plenty of data to collect to give us a comprehensive review of how good our designs and prototype are.

# Pt2 - User Testing <a name="pt2"></a>

## Usability Testing Plan <a name="testingplan"></a>  

[Usability testing plan document](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/blob/master/testing/usability-testing-plan.md)

  
## Usability Test Results <a name="results"></a>

In our user testing, we tested three users from our suggested pairing group.  
  
During this process there were a few issues that may have caused inaccuracies with our results. The recorded times are inaccurate of the users' time of each completed substask. This is because some substasks occurred too quickly which caused some delay in the timekeeper's reaction time. This happened frequently in the last task which was question creation. In the question creation task, each time was recorded from the first substask to the end of the last substask. An average time for each substask was calculated by dividing the time taken for the total task divided by the nine subtask. Time was also counted when instructions were given between tasks and substasks. This does not represent the true time taken as users would pause and take time to interpret the question before actually moving the mouse and interacting with the prototype.  
  
A factor that many have caused further inaccuracies in our results was the way we set up the laptop which contained the prototype. We decided to use a mouse instead of the laptop trackpad for consistency. We failed to notice that the mouse was too sensitive for one of our users. We did not have a choice but to keep going as we wanted to preserve and record the users' initial experience.  

### Time Taken

| Task              | Subtasks                   | User 1 - Time Taken (Minutes/Seconds/Milliseconds) | User 2 - Time Taken | User 3 - Time Taken | Mean Time Taken |
|:------------------|:---------------------------|:---------------------------------------------------|:--------------------|:--------------------|:----------------|
| Login             | Go to login screen         | 00:04.44                                           | 00:03.40            | 00:03.21            | 00:03.68        |
|                   | Login                      | 00:05.25                                           | 00:04.74            | 00:06.28            | 00:05.42        |
|                   | Select PSYC327 classroom   | 00:02.76                                           | 00:06.32            | 00:05.94            | 00:05.01        |
|                   |                            |                                                    |                     |                     |                 |
| Answer a question | Select question            | 00:07.69                                           | 00:14.69            | 00:08.56            | 00:10.31        |
|                   | Select an answer           | 00:10.37                                           | 00:11.61            | 00:11.51            | 00:11.16        |
|                   | Submit                     | 00:15.05                                           | 00:18.19            | 00:18.55            | 00:17.26        |
|                   | Rate question              | 00:05.56                                           | 00:14.37            | 00:07.04            | 00:08.99        |
|                   |                            |                                                    |                     |                     |                 |
| Start a quiz      | Select quiz tab            | 00:05.50                                           | 00:14.98            | 00:14.3             | 00:11.59        |
|                   | Start neuroanatomy quiz    | 00:10.19                                           | 00:12.45            | 00:09.21            | 00:10.61        |
|                   | Answer the questions       | 00:11.85                                           | 00:10.96            | 00:07.76            | 00:10.19        |
|                   |                            |                                                    |                     |                     |                 |
| Create a question | Select create question tab |                                                    |                     |                     |                 |
|                   | Enter question title text  |                                                    |                     |                     |                 |
|                   | Enter an image             |                                                    |                     |                     |                 |
|                   | Enter multi-choice answers |                                                    |                     |                     |                 |
|                   | Select suggested answer    |                                                    |                     |                     |                 |
|                   | Enter explanation text     |                                                    |                     |                     |                 |
|                   | Enter relevant topics      |                                                    |                     |                     |                 |
|                   | Preview question created   |                                                    |                     |                     |                 |
|                   | Publish question           |                                                    |                     |                     |                 |
|                   | All the above              | 00:45.35                                           | 00:54.27            | 02:09.35            | 01:25.01        |
|                   | Create Q subtask avg       | 5.04 secs                                          | 6.03 secs           | 13.93 secs          | 8.33 secs       |
|                   |                            |                                                    |                     |                     |                 |
| Total Time        |                            | 1.97 minutes                                       | 2.77 minutes        | 3.63 minutes        | 2.82 minutes    |


### Recorded Actions

| Task:      | User 1 Actions                 | User 2 Actions                            | User 3 Actions                    |
|:-----------|:-------------------------------|:------------------------------------------|:----------------------------------|
| Login      | Clicked on login               | login                                     | login                             |
|            | email                          | email, password                           | email                             |
|            | password                       | login                                     | pass                              |
|            | login                          |                                           | login                             |
|            |                                | psyc class                                |                                   |
| Answer     | psyc class                     | clicks 2nd then first                     | psyc class                        |
|            | clicked question               | selects a.                                | 2nd q (non-functional)            |
|            | selected a.                    | hovers over browse q's                    | 1st q                             |
|            | submit                         | submit                                    | a.                                |
|            | rate quality 4                 | rate quality 4                            | submit                            |
|            | rate diff 5                    | rate diff 3                               | rate quality 5                    |
|            |                                |                                           | rate diff 5                       |
|            |                                |                                           | scrolled to comments              |
|            |                                |                                           | browse questions                  |
|            |                                |                                           |                                   |
| Start quiz | hovered log out                | scrolls down                              | star a quiz                       |
|            | clicked psyc dropdown          | start a quiz                              | start quiz                        |
|            | start a quiz                   | start quiz                                | selected c.                       |
|            | start quiz                     | selected d.                               | next                              |
|            | selected c.                    | next                                      | selected b.                       |
|            | next                           | selected c.                               | see results                       |
|            | select b.                      | see results                               |                                   |
|            | see results                    |                                           |                                   |
|            |                                |                                           |                                   |
| Create Q   | create question                | create question                           | create question                   |
|            | all areas selected and a, c, d | image                                     | clicked question twice (confused) |
|            | preview                        | selected a.                               | selected a.                       |
|            | publish                        | selected b.                               | publish                           |
|            |                                | create question                           | intervene                         |
|            |                                | selected d.                               | image                             |
|            |                                | re clicked a bunch to set them as correct | publish                           |
|            |                                | caption                                   | intervene                         |
|            |                                | topics                                    | explanation text                  |
|            |                                | preview                                   | selected a,b,c                    |
|            |                                | publish                                   | preview                           |
|            |                                |                                           | publish                           |

### Transcript and Interviews

#### User 1

##### During Testing

This looks really flash (the home page)  
This mouse is fast  
What class, sorry? (PSYC327)  
I am not sure if I clicked it  
Depends if its meant to do something more than that (rate and submit button)  
It’s changing colour  
Sorry? (navigate to question creator)  

#### During Interview

Do you have any questions about the prototype?  
No  
  
Tell us how did you feel when you were testing the prototype?  
Really good, felt like it’s a perfect system  
  
On a scale from 1 - 5, rate your experience in testing the prototype, where 1 is very negative, 3 is neutral, and 5 is very positive.  
4, 4 and a half  
  
What are some parts of the prototype that you thought it was difficult to do or was not clear?  
This is probably not part of the prototype, the mouse settings  
  
What are some parts of the prototype that you thought it was easy or clear?  
Yes, just the general layout, and the straightforward headings  
  
If the prototype was fully functional, would you use this system for revising course material? Why or why not?  
Yes, if someone wrote the questions for me, like the lecturer, not if it was me just because it is time consuming  
Definitely use it if the other class members 
You guys did a really good job  
  
#### User 2

##### During Testing

(no speech)

#### During Interview

Do you have any questions about the prototype?  
No, seems pretty straightfoward  

Tell us how did you feel when you were testing the prototype?  
Um, I felt curious, in some places I felt a little confused, but I thought that it was more to do with that it was just a prototype, that the interactions weren’t fully implemented, but I got the general gist of it, 
I felt good, mostly good  
  
On a scale from 1 - 5, rate your experience in testing the prototype, where 1 is very negative, 3 is neutral, and 5 is very positive.  
I’d say 4  
  
What are some parts of the prototype that you thought it was difficult to do or was not clear?  
Um, I thought that, It wasn’t entirely clear when creating a questions, you shouldn’t be able to  
When editing the text, it shouldn’t be possible to select the answer, because its easy to select the wrong one  
I felt like the questions could have been smaller so that they fit on one page, instead of needing to scroll down, cause I didn’t see them initially  
All the options on one screen  

What are some parts of the prototype that you thought it was easy or clear?  
I thought the way that you can answer and browse questions was clear  
I thought the creation, browsing, the quiz, it was clear most of the time  
I liked everything else aside from those (two that were unclear)  
  
If the prototype was fully functional, would you use this system for revising course material? Why or why not?  
I would, with the caveat that it would have to be widely used, if it was adopted by teachers or tutors as well as students, it would be a good platform because there would already be questions  
If there wasn’t much content it wouldn’t be very useful  
  
#### User 3

##### During Testing

Okay, cool (logging in)  
Oh, I see (answering a question)  
Rate a question? (checking what Jane said)  
Oh okay (rating the question)  
Sorry, could you repeat that? (Please input the shown fields)  
Oh I’ve messed up  
I’m not sure what you mean by shown fields  
Ah yep (click the show image button)  
I’m struggling with this, sorry  
I’m not sure what I’m meant to achieve, sorry  
Ah okay so you’ve put a picture in  

#### During Interview

Do you have any questions about the prototype?  
None that come to mind  
  
Tell us how did you feel when you were testing the prototype?  
Quite calm and relaxed, bit unsure what to do at the last part, it was unclear  
  
On a scale from 1 - 5, rate your experience in testing the prototype, where 1 is very negative, 3 is neutral, and 5 is very positive.  
4 It’s definitely more pleasant to navigate than the old PeerWise, it wasn’t perfect obviously,  
Maybe making the create a question part more immediately obvious might make it  
  
What are some parts of the prototype that you thought it was difficult to do or was not clear?  
Create a question was unclear what I was doing, but I did gloss over it, I’m not the best at taking in a lot of information at once  
If I was feeling more focused   
  
What are some parts of the prototype that you thought it was easy or clear?  
The starting quiz part, it was quite cool, a big start button where you’d expect it to be,  
The cards at the top it and slides was a lot of information at once,  
Generate and browsing, my brain was expecting just browsing quizzes, maybe make generation a separate thing  
  
If the prototype was fully functional, would you use this system for revising course material? Why or why not?  
Personally, if I did revise, I would use it, but personally I don’t revise or do assignments, but someone who is into that I’d imagine it would be quite a useful tool   

### Issues

Through analysing our usability test results, we saw the following key points that we could update our prototype with:

**1. Quiz feature - Too much information on a single page**  
  
https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/issues/6  
  
Severity Rating: 2 - Minor usability problem: fixing this should be given low priority  
  
An issue we found was that users were having difficulty in interpreting the quiz page and knowing the distinction between quiz generation and browsing pre-made quizzes. This was because the quiz generation page was a bit too busy with the question generation at the top and question browsing at the bottom. During testing, we were only testing for quiz browsing and selection. This was actually indirectly testing the user in following instructions rather than utilising the system itself. This meant that we had to separate these two quiz related functions separately so we test the system and not the user.  

**2. Question creator - Too much information and steps**
  
https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/issues/7  
  
Severity Rating: 3 - Major usability problem: important to fix, so should be given high priority  
  
Through the interviews and testing conducted, we found that users were confused about the features and steps in order to create a question. The question interaction sequence asks the user to enter a title, add an image, enter answers, select an answer, enter an explanation, add topics, and submit to create a question. From this, we could see that the users could not differentiate the different components in the layout of the page correlating to a single step in creating a question. This ultimately confused some of our users which resulted in a long pause where an intervention for help was required.  

**3. Answer question - Rating stars not being properly utilised**  
  
https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/issues/8  
  
Severity Rating: 3 - Major usability problem: important to fix, so should be given high priority  
  
A key issue we saw was that users were selecting the ratings wrongly during question answering. This was when they have submitted the answer and were told to rate the difficulty and quality ratings by clicking the stars. There were no visible confusion or response from the users in this task which meant that they did not cognitively know that they were doing the task wrongly. The correct way to do this task was to select all the stars up to the user's desired rating, eg. rating the question 4 stars would require the first 4 stars to be clicked and the last one to be empty, users would click the 4th star by itself and submit it. This issue was originally an Adobe XD limitation where the prototyping tool could not control selected states between the different stars.

**4. Question answering - Have to scroll down the page to find submit button**
  
Severity Rating: 1 - Cosmetic problem only: need not be fixed unless extra time is available on the project  
  
We think that this issue is a cosmetic problem. To solve this, we will have to re-scale the question answering page which voids one of our goals which is clarity and use of space. This would potentially clutter the page make it too hard to visually process just like the other two issues listed here. 


## Updated prototype based on user testing <a name="updates"></a>

### 1. Quiz feature - Too much information on a single page  
  
- A solution we made to separate these two features was to hide the quiz generation functions but leave the title visible with a functional dropdown icon. This would help the user to direct themselves to the quiz browsing section instead of focusing on generating a question.  

Before:  
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/start%20new%20quiz.png">
  
After:  
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/updates-from-testing/quiz-dropdown.gif">  
  
This update benefits the project as it separates the quiz generation and browsing features, reducing the number of visual stimuli and processing a user must go through.

### 2. Question creator - Too much information and steps  
  
- A solution we made was to add functional dropdown icons to the add question title, add image, and add answers sections. Upon entering the page the titles are visible but further functionalities are hidden until the user selects the dropdown icon. This helped to reduce the amount components on the page to visually process. This also may help the user to comprehend the different steps and functionalities in order to create a question.  

Before:   
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/designs-images/question%20creator.png">
  
After:  
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/updates-from-testing/question-creator-dropdown.gif">

This update benefits the project as it separates each question creation feature into steps that the user can mentally break down. This reduces the visual complexity and the number of mental hoops that the user must go through to create a question. 
  
### 3. Answer question - Rating stars not being properly utilised  
  
- We found a solution to make all the stars selected up to the user's selected star, eg. selecting the 4th star would select all previous ones. We brute-forced the Adobe XD limitation by creating many states and linking them together which took a long period of time.   

Before:  
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/updates-from-testing/rating-testing.gif">
  
After:  
<img src= "https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2021/project1/t13/peerwise-project/-/raw/master/final-prototype/updates-from-testing/rating-redo.gif">
  
This update benefits the project as it makes rating the difficulty and the quality of answered questions easier and clearer. This makes the user realise that they are giving the correct ratings when clicking the desired stars.  

## Usability Test Discussion  <a name="discussion"></a>

- my first idea for 'most significant result' would be that the create a question page was too dense in its information, and would benefit from a reduction
- not sure what the most interesting thing was
maybe the comments that the appeal of an sqs, or their interest in using one, is contingent on how much material already exists before they join and start using it?
in other words, users prefer to study with existing material, and not make their own
in the discussion should we think of reasons why they do that?
like maybe they'd feel more assured that they are studying relevant material, or that the answers are correct, if they know the lecturer or tutor made the question
or maybe that most users would be on the side of the scale that means they don't have a lot of time/energy to fully commit and create lots of questions
or maybe simply that a service isn't very useful if it doesn't have any content in it
- maybe that the quiz page contained too much information - which meant that we weren't really testing the system but rather testing the users' in following instructions? - in telling the user to select a premade quiz rather than generate a quiz
another interesting thing was that we only needed to have one intervention maybe?
- One of the users didn't think to scroll down on the questions page I think
- maybe with that we could say that instead of focusing on reducing the need to click through lots of pages, users might prefer not needing to scroll down a page to see everything?
- Yeah at least the important stuff eg not the comments
- i.e. they would like it more if they could see everything in one look, even if it meant they had to click to a different page
- That or we have an indicator somewhere showing that there's more if you scroll down
- i think when I browse the internet, i can tell how long a page is by the size of the scroll bar, but in the prototype, you can't really see the scroll bar can you
- Yeah with this I liked what the team we were the testers for did, they asked us what to do using different words than what was used on the webpage which meant I couldn't just scan the page for the words they mentioned. I actually had to think about how to do the task

One of the most interesting results that we found from our testing was that we only needed to intervene once throughout the process. This was surprising as we did not expect the process to go smoothly. There were a few hiccups where users would get stuck but they were able to complete the tasks by experimenting via clicking and scrolling. These hiccups were seen throughout the tasks where users would be confused in:

- rating and submitting an answer during the question answering page
- navigating through the quiz
- clicking through the components to create a question
  
Most of our users completed these tasks even though they showed signs of trouble which demonstrated that the system can be used, but it just needed to be improved. This is a good sign for our prototype but this may only apply for a set of individuals, or relating back to our personas, personas that have a high tolerance and tinkering traits. This means that if users are not willing to explore and tinker with the prototype, they may have a harder time using it, therefore, have a bad user experience. Our first two users had traits of high tinkering and tolerance which meant that they were able to overcome their uncertainties to achieve the goal of the tasks. This however was not the case for user 3. User 3 demonstrated traits of low intolerance and tinkering which meant that they completed tasks slower and needed an intervention towards the end of the question creation task. This was not the fault of the user but it was a fault of our system which showed a significant flaw in the prototype. The easiest solution to this would be to create a dedicated instructions tab to show the user how to demonstrate the steps in order to achieve the goal in the form of a question mark button. This was not implemented in the updates section because of poor time management.  
  
This was an interesting result because it not only showed a flaw in our prototype, but it reflected how realistic the usage of personas can be. Drawing the parallels between personas and real users was quite eye-opening in analysing the test results. This was because we could relate the individual differences of our users to the personas we had created. This meant that the issue could have been solved from the very beginning with the above-suggested solution if we focused on this small aspect which was in our personas. This could have produced different results as such as time taken, interventions needed, and interview answers. This may also infer that if we selected different personas, our prototype would have changed, therefore the results would have also changed.  
  
The most significant result we found was that there was an occurring theme of 'information overload' and the pages being too busy. This result was found in our interview which was useful in assessing how users' felt. This issue was found in the layout of quiz and question creation pages. This demonstrated that individual differences in information processing and stimuli may have affected how long users' took to complete the task. Although one intervention was needed we thought that this was a key issue in affecting the users' experiences in interacting with our prototype so we updated our prototype with a solution we found. 
  
The solution we found was to partially hide information of features with a dropdown button that hides and displays the additional information to the feature. This was implemented in the quiz page to hide the nonfunctional quiz generation feature and on the create a question page with the added title,  add image, and add answers. The good thing about this update was that it broke down interactions into steps so it may be less intimidating to process the page upon entry. A downside of this is that it adds another barrier to interact with the feature by clicking the dropdown button to reveal the feature. Another downside may be that we are delaying the information to be processed. This means that the user is no longer hit by the information overload upon entry at the page but it is further processed along the way. This may be a positive or negative experience for different users. This is a nontrivial problem as the trade-off is to make the page detailed to enhance user freedom or to hide information to enhance user comprehension.    

