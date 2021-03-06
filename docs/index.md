---
layout: default
title: Sprint 2 Working Directory
comments: true
# other options
---

# Ketch Sprint 2 Working Directory for KMUSS Project

## Current Releases

Prototype 0.0.1
Design Specification (planned to release 0.0.1 Wednesday March 21, 2018)
Web Apps (planned for next sprint next week).


## Exec Summary March 20, 2018

- Sprint 2 is scope is being modified to account for other parallel activities that are happening that carry a higher priority.  These higher priority items are fundamental to get the next sprint operating more streamlined.
- The reason for the delays is due to available resources are over-allocated.  To help address this Ketch has brought on another web app developer, Jeff Dederick.  Jeff can be found on slack and will help get back on schedule.
- Ideally, we should be in a sprint where we can accept issues, then to make those changes and re-release the prototypes.  To be clear on how this process works.  Issues are collected and only through an official product release will the changes be incorporated.  Due to the parallel activities, we have NOT issued another release of the prototypes.  We will be doing that when we release the changes to the process flow and updates to the prototypes.  We currently are in RELEASE 0.0.1.  We will be issuing RELEASE 0.0.2 hopefully Thursday.  
- A sprint is defined by a set period.  What doesn't get done in a sprint, gets put back to backlog and reissued to the next sprint, or to another sprint down the road.   This is decided in the sprint 1 stand-down meeting that we will be having on Monday.
- Sprint 2 goal has thus been adjusted to focus on making sure we got all the business requirements nailed down.  on Wednesday, March 21 we will be releasing the 0.0.1 version of the specification document.  The goal of Sprint 2 reviews the specification document to get as many of the required details listed in the specification document.  So there is less emphasis on the prototype screens until next week and we are shifting attention to this spec document.  
- While we wait for the release of the specification document, please continue to work through the details of the design for items like what statuses you need at each step, the rules of the statuses.  Also, the other questions had lots of decisions that we need the business to decide (ie business partner types etc).
- Non-Sprint 2 Priority Items:
  - Network infrastructure installation of SAP CPM, Fiori Decoupled, and HANA XSA (where the app's runtime is).  Currently, this is not live, and we need these systems to do an official app release.  
  - There has been a major change to the process flow for sprint 2 to accommodate the Variant Config and CPQ processes.  This is currently being worked on and this will take a few days to re-issue a new process flow.  This is the higher priority than updating prototypes with changes etc.
  - Designing the development to production pipeline (continuous integration), and supporting project management and issues systems.  This will improve our process, and is required to be done as the modern web apps cannot use the legacy SAP change management system.
  - These items impact sprint 2 in the sense of resources (as the same resources are working on both).

## Key Deliverables Over Next Day

- Dave Beach to compile all comments, 

## Archive Past Items

### Exec Summary March 19, 2018

- Sprint 2 is slightly behind schedule due to the late start.  Sprint 3 will begin in parallel this week, in order to stay on schedule.
- Sprint 1 is for the build-out of the development environment to create the apps.  We are in parallel running sprint 1 and 2.  This may cause some delays in the high-fidelity web app rolling out.  However, this does not impact the majority of sprint 2 deliverables.
- Folks are beginning to use Slack, Great news!!  As we streamline the process, you will see the power that slack has to automated a lot of mundane tasks etc.
- There have been side meetings with the CRM Opportunity, and CPQ groups.  Changes will need to be made.  This is mostly due to the overlap of functionality that exists in CPQ and CPM.  


### Tasks Pending March 19, 2018

**Top Priority**:
  -  CRM/CPM/CPQ change in process proposed.  We need to discuss further to nail down this design.  See
  [New Process Flow](https://raw.githubusercontent.com/KetchPartners/kmsprint2/master/docs/assets/images/bpmn-process-flow-sales-cpm.jpeg) 

**Review Answers to Business Questions**:
  -  Question on project collaboration tool.  See response [here](https://slack-files.com/T86E9TZ8Q-F9S031H2R-589f427c93).   
  -  Logic of workflow routings.  See response [here](https://slack-files.com/T86E9TZ8Q-F9S05RFHB-f7049d4393).   
  -  Process and Ability to Assign Status.  See response [here](https://slack-files.com/T86E9TZ8Q-F9RR5TAUC-a2f1d5dee2). 
  -  Business Partner Types to Assign Roles and People to Steps, Objects etc.  See response [here](https://slack-files.com/T86E9TZ8Q-F9RP85LGK-a8ee96bf25).  
  -  Updates to Sales Team.  See response [here](https://slack-files.com/T86E9TZ8Q-F9S0A2JE9-27160f1e97).   

**Action Items**   

-  All -- please review and update the issues by downloading them at [Taiga](https://ketchpartners.github.io/kmsprint2/) . 
-  Chris or Christine -- set up meeting to discuss the new process flow for interaction with CRM, CPM and CPQ.  This meeting will need to be longer as it has lots of things to it.  Please schedule 2 hours.  

-  Dave / Mateo -- will publish by March 20 draft of design document, for input and review.  

3-  Mateo / Jeff / Dave -- prepare local development environments for UI5 front end.

**Logistics** 

Power of Using Open Formats:  
  - The power of modern applications is because everyone got on board regarding open standards for interfaces, file formats and outputs, and many other things.
  - All software technology companies are now on board these new standards.  This includes Microsoft.  And the Office suite has the option to save in open standard notation.
  - *Why this matters*?  The tech industry has moved beyond vendor locked in practices.  Vendor lock in means you are at the mercy of the software company for innovation.  Whereas moving to open source and open format standards, means that everyone speaks the same language, and they are operating above the software suites.  This allows for companies to be once again, experts in their business processes, rather than having a software vendor claiming a best practice.  
  - *What has this sparked*?  The technology industry has begun to move away from massive central systems like SAP ECC, and replace them with many systems, distributed in many locations, with many operating systems, with many. vendors.  Also defined as distributed computing model.
  - Remember having your stuff hiding behind proprietary code, means can't be seen by the modern world.

What You Can Do:
  -  Word documents on slack - is great, but it is just a file and that is it.  Save that document as an open word format, and now Slack and other tools, can index the contents, read the contents, update the contents etc.  Automation possiblities are endless.  
  -  The new open standard for business processes and rules, is to use BPMN and DMN.
<dl>
  <dt>BPMN</dt>. 
  <dd>Business Process Model and Notation.  Used to map out the business process flow of business process as it pertains to technology systems.  The notation is set up to automate the code generation, and the eventual roll functionality to business to own, rather than having to always go through the IT department.</dd>

  <dt>DMN</dt>. 
  <dd>Decision Model and Notation.  Used along side business process, decision models and notation, are the business rules associated with each process step.  For example, if the purchase order is over 100,000 then it must be routed to VP level for approval.  or as simple as validating the phone number as the format +# ###-###-####</dd>
</dl>. 
[Download open source software to do BPMN and DMN at this link](https://bpmn.io)

### Archive
1. Please complete this questionaire [at this link]({{ '/questions.html'| relative_url }})
2. Please review the Agile Boards for Overall Project and Sprint 2.  
  - Epic list of requirments can be found [here](https://tree.taiga.io/project/davebeach-km-rollout/epics).  
  - Requirements backlog can be found [here](https://tree.taiga.io/project/davebeach-km-rollout/backlog).
    - Use case stories - click on the button labelled "Add a New User Story".  This will take you into a dialogue to create a user story.  Please provide details and how it relates to the sprint and items being implemented.  User stories become testing components.
    - Each requirement is specified as a user story.
    - Each user story, is moved from backlog to an actual sprint.  
    - Each sprint has it's own task board.  This is where user stories and issues get pushed down to more detailed tasks to be completed.  On right sidebar under sprint 2, click on "sprint taskboard" or use this [link](https://tree.taiga.io/project/davebeach-km-rollout/taskboard/sprint-2-5806).
3. Review Important Slack Channels:
Slack project is [KM Ketch Project](https://ketchkmproject.slack.com)

Channel        | Purpose                                                 
---------------|----------------------------------------------------------|
sprint2biz     |Central business channel for the sprint.  Starting Point. 
sprint2tech    |For IT technical teams to get geeky.  Anyone welcome.     
kanban         |Listens for updates to Agile boards for project.          
red-alert      |Escalated subjects to PMO for resolution                  
sprint-schedule|Where you discuss upcoming sprints and requirements.      

4. Officially we track issues for Sprint 2 [here](https://tree.taiga.io/project/davebeach-km-rollout/issues).  To make it into the github issues repository you can do one of the following.
  - On this page, please add a comment where you put /issue at the start.  It is best that you are logged onto your KM mail account, as this will align the comment to the right person etc.
  - In Axure process flow or prototype construction and review.  Axure automatically notifies Slack channel sprint2biz.
  - Or you can create an issue in Taiga, and this will workflow to us for inclusion in github id. [Link here.](https://tree.taiga.io/project/davebeach-km-rollout/issues)
  - The business owns the issues, if you do not agree with an issue, or believe it was closed prematurely, please go in and change it to what it should be at.  The technical team defer to the business, on decisions about issues etc.

5.  If not already done, please sign up to Taiga for a free account.  Then request to be added to the KM-rollout project located [Link here.](https://tree.taiga.io/project/davebeach-km-rollout/).

6.  We use github as our main hub for code management.  The github project for this sprint is (ketchpartners/kmsprint2)[https://github.com/KetchPartners/kmsprint2].  The docs directory renders at ketchpartners.github.io/kmsprint2.

7.  We will be tracking requirements and other items at github repository (ketchpartners/km_requirements)[https://github.com/KetchPartners/km_requirements]

8.  Slack @
  - @here sends to currently logged into Slack users.
  - @channel sends notification to all channel users.
  - @everyoen sends notification to all project members.

9.  Slack Slash Commands /
  - /remind Notify my tomorrow to do xyz by noon.
  - /todo to assign tasks, manage your tasks etc.
  - /call to call the participants in a thread.
  - To get other / commands go into Slack and enter / and your options will be displayed.  

10.  Email is no longer an acceptable form for this project's design deciscions etc.  If it is email and not on Slack, the requirement doesn't count and will not be done.  Only items on Slack and our other supporting apps will be considered.  The goal of this project, is to reduce meetings to only when necessary and to elimiante the need for emails.

11.  Please reach out if you have any questions by putting in the comments on each web page, your question and name. In slack enter /help-me.

12.  As Tiaga was down during our meeting, when the server came back up, I ran through Tiaga and you can watch on this youtube video:

{% include tiaga-video.html %}

13.  Next steps - we will be getting into the process flow details and reqired detailed decisions.  You can find details of the process flow and prototype work in progress, at this [link]({{ '/sprint2.html' | relative_url }}).


