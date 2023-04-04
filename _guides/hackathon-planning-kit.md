---
title: Hackathon Planning Kit
shorthand: Hackathon-Planning
---


CSC hackathons are an internal event where the CSC team and collaborators work together to solve a clinical problem with the aim to speed up innovation, complete work or to produce a prototype. Other hackathons are also held, such as hackathons to speed up project progress. The planning kit here only discusses the former type of a hackathon: where a clinical problem is being solved, usually by means of AI model training.

This guide aims to provide the hackathon organiser with the tools to set up and carry out a multi-day hackathon. 
 
***
## Before the hackathon
### Consider your problem
The clinical problem being solved must be appropriate for the hackathon format. For example, training an AI model is an appropriate problem to solve as a team, whereas ingesting data into XNAT is not.  
### Governance
Ensure your project has the correct governance in place, including ethics approvals if this is a research project, or QIPS registration and approval if this is a service evaluation or a service improvement.

### Key Objectives
Set the key objectives by outlining the work that has already been done and the work that must be done to consider the project completed. Write those out.

### Data
The quality, quantity and accessibility of your data will define the success of your hackathon. This is particularly true for AI projects. Data collection is a long process from data curation, data labelling and data retrieval. This part must be done in advance of the hackathon.

### Gather volunteers
A hackathon is a team effort: find out who is available and who wishes to participate and create a list of stakeholders, including the clinical team you're collaborating with and any external collaborators that wish to contribute. You will need to use this list repeatedly to inform everyone on details - keep it handy.

To ensure the success of your hackathon you must identify all the key staff you need, e.g. QMS expert and MLOps expert. Make sure they are available on the selected dates, as the hackathon cannot go ahead without them.

### Pre-hackathon meetings
You should organise at least 2 pre-hackathon meetings which cover the topics needed to ensure the success of the hackathon (e.g. clinical pathway you're trying to improve). These will give you a chance to present the problem to your collaborators, present the data you have gathered (including data quality and demographics), and discuss the aims for the hackathon. It will give you a chance to conduct any training necessary, including refresher on MLOps, on XNAT, on medical imaging, or similar. If tools are used as part of the hackathon, such as the QMS or Voxel5, discussion and training on setting those up will also be vital.

If your objectives aim to improve or affect a clinical pathway, you must understand the current method of work well. If possible, it is recommend you organise to follow the whole pathway end to end by either shadowing or by performing interviews or similar research to map the pathway in detail.

Finally, once the user requirements are gathered, you must translate those into technical requirements and establish a traceable pathway between your goals during the hackathon and the user requirements. This can be done in the form of a pre-hackathon meeting or it can be performed in group at the start of the hackathon.

***

## During the hackathon
Your hackathon should begin with an introduction at the start of the day and a clearly set out agenda. The agenda should include the summary of the clinical problem including the affected clinical pathway, it should include the summary of your data and the clearly stated purpose and aims of the hackathon. It should state the expected deliverables.

If you're working in teams, create those teams at the start of the day. Otherwise, assign roles and duties as appropriate - consider both the expertise of your team members and what they wish to gain from the hackathon. 

Each hackathon participant should have a clear aim of what they are trying to achieve and know who to turn to when they run into issues.

In your agenda, you should set aside time for:
- check points 
- stand ups 
- lunch / refreshment break
- team photo 
- synchronisation times (if multiple teams working on similar problems)
- end of day demos

Agree on a GitHub branch naming convention - best practice is to create branches out of issues to ensure consistent naming and linking between requirements and features.

There should be a scrum master whose task is to ensure team members are on track to deliver on the aims set out. This includes walking around and seeing what individuals are doing, how they are approaching it, as well as being available for those who seek help. The scrum master should also monitor the repository, review changes to merge into main, and review branch naming.

If the team members writing the documentation are separate from those doing the programming or training, it is essential they work together closely to ensure the documentation reflects the solution which reflects the user and CSC requirements. There must be traceability of every feature in the solution to the CSC or user requirement.

***

## After the hackathon
Immediately after the hackathon it is useful to gather feedback on the process. Best time to do so is immediately after the hackathon is done. It's also worth considering organising a celebration of completing the hackathon.

In the week after the hackathon, review the GitHub repository and clean it up - there will be a lot of unfinished or half-finished work. 

Set out a plan with your team on how to continue the development and how to continue to improve AI performance. The plan should reflect the size of the work. 

Communicate the outcome of the hackathon to the clinical team and ask them to review any relevant work (such as reports or similar). 

***

## Other things to consider

The following are other pieces of advice collected from feedback from previous hackathons:
- Setting up tiers of achievement / milestones - this helps teams understand where they are in the process and brings a sense of achievement as progress is made
- Consider asking for creative input such as AI model naming
- Consider the optimal ways of working: some people thrive in paired work, some thrive in tackling problems solo. The best way to get most out of your team is to facilitate both.
- It is important each day ends with a show and tell where some piece of work or progress is demonstrated - not only described. Hyper-focus should be on _showing_ a tangible step of progress towards the final solution. This will help at the end too when tying loose ends. 
- It is always easier to improve an existing solution that works than create a perfect solution from scratch. 

Below is a handy checklist to keep tabs of your preparation. Each section corresponds to the advice above. 

***

## CSC hackathon planning checklist

***

#### Before the hackathon: preparation
- [ ] Clinical problem to solve is clear and defined
- [ ] Project has all relevant approvals
- [ ] Key objectives have been defined in writing
- [ ] Ensured clinical pathway is well understood
- [ ] Data is ready, it has been:
    - [ ] collected / identified
    - [ ] labelled
    - [ ] imported into XNAT
- [ ] Participants have been identified
    - [ ] Participants include key staff

***

#### Before the hackathon: pre-hackathon meetings
- [ ] Organised all pre-hackathon meetings needed
- [ ] Wrote the agenda for each pre-hackathon meeting
- [ ] Sent out meeting invite to all participants for pre-hackathon meetings

***

#### Before the hackathon: organisation
- [ ] Duration of the hackathon agreed
- [ ] Dates of the hackathon agreed
- [ ] Rooms for the hackathon booked
- [ ] GitHub repository for project created
- [ ] QMS templates added to the GitHub repository

***

- [ ] User requirements gathering meeting organised
- [ ] Written the agenda for the meeting
- [ ] Written a list of specific questions for the clinical team (you can use the CSC template)
- [ ] Made the user requirements identified in meeting into GitHub issues
- [ ] Translated user requirements into technical requirements
- [ ] Made technical requirements into GitHub issues

***

- [ ] Wrote the hackathon agenda for each day and included:
    - [ ] Start and end times
    - [ ] Check points
    - [ ] Stand ups
    - [ ] Break times
    - [ ] Team photo time
    - [ ] Synchronisation time (if multiple teams)

***

- [ ] Prepared an introduction presentation
- [ ] Sent a final reminder of the hackathon to all participants

