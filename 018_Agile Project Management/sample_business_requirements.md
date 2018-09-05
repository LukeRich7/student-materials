# Exeter: Online Student Collaboration Project

## Executive Summary

This document will explain objective, background, necessity, scope requirements, schedule & limitations of the Online Student Collaboration Project (OSCP). Each section will focus on a specific portion of the development of this web application & will be useful to obtain a broad view of the project at hand. 

## Business Objectives

This application will provide a medium to:
- share project ideas
- search existing project ideas
- provide online workspace for collaboration with remote team members
- provide online communication & file sharing functionality to aid in efficent project completion

## Background

The client has expressed desire for students located in various regions to have the capability to collaborate on projects.

## Scope

This is a new application. There is no legacy integration required. The end product will feature:
- a user interface to upload project ideas & files
- a user interface to search existing/ongoing projects & request access
- an online workspace to visualize collaborative efforts
- a social communication functionality that is lightweight & integrates seamlessly with the workspace

## Functional requirements

Big Idea: a web application which will allow students to connect with like-minded students for projects, share ideas & files, and communicate via text or video chat while doing so.

Access/Security: 
- Each user will need to create a unique profile & login in to access the application; this id will be used to track project access
- Each user will be able to request access to ongoing projects by other users & grant permission(s) to access their original projects

Creating/Joining:
- Each user will have the ability create a new project folder & post it to the application database
- The creator of any project will be notified & prompted to approve access by other users to created projects 
- Each user will have the ability to search the database of existing projects & request access to join
- There will be 3 levels of access: view only, contribute & edit that will determined by the project admin (creator)

Collaborating:
- Each user will be able to view a shared workspace & visualize existing code, images, files etc.
- Each user will be able to upload files & attachments to be used or viewed by other team members

Communication:
- Each user will be able to send and/or receive text driven messages to other team members in a DM/chat style
- Each user will have the ability to video chat with other team members


## Personnel requirements

- Project Manager
- Lead Designer/Developer
- (6) Assistant Developers
- QA & Testing Lead

## Delivery schedule

Phase 1:
- Test functionality of access/security portion by successfully creating profile & posting a unique project with auto-generated ID

Phase 2:
- Test functionality of creating/joining portion by verifying reciept of notification upon access request & all appropriate projects in 
  database return on search
  
Phase 3:
- Test functionality of collaborating portion by verifying access to shared space & ability to upload files

Phase 4:
- Test functionality of communication portion by verifying chat & video chat features.

## Other requirements

The client values quality and innovative solution or something that is quick to market. They are looking to us & our team to help define some features that would motivate students to engage in using this platform to connect and build better communication.

## Assumptions

N/A

## Limitations

Ongoing conversations with client to maintain project integrity & desired functionality may affect critical path.

## Risks

Personnel & competive market to create a similar application
