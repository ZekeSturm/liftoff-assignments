# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
ScheduleSheets (Name not necessarily final) is an application designed to help people keep and coordinate their schedules. Groups may be created to schedule events, both blocking off available time between persons and setting a final event time once the time is settled on. Users may create accounts to add individual scheduling events to, as well as coordinate between group schedules. Group (and user) events may be set to repeat weekly, monthly, or for a certain date/date range, and events may be set to remind their users via SMS/Email alerts if they opt in. Registered users will also have the benefit of schedule conflict detection - events that are overlapping (or possibly too close together chronologically if their distance is too great, if the location API is implemented) will trip a flag and alert the user of an overlap when scheduling conflicts arise.

In addition, temporary users may participate in individual groups without creating accounts, so that if someone needs to be included in an event but doesn't want to deal with a whole account, they can do that. They may also create temporary, single-use rooms of their own that registered users and temporary users alike may participate in - these rooms will still sync up with the registered users' schedules. The idea itself comes from my own issues scheduling events with others, on top of a general need for a bit more personal organization.
### Features
 1 - Users may create persistent accounts - these accounts save scheduled items from groups they are in, as well as individually scheduled items the user creates and displays them on a home page. Conflict detection will tell persistent users if they have overbooked a time.
 2 - Users may create groups for persistent or temporary event scheduling, based on repeating weekly, monthly, or date range/individual dates. Groups will have admins (The creating member, permissions may be granted to others) who can request time from group members if the members allow it. Allow showing blocks of free time without hard scheduling, possibly
 3 - Temporary "accounts" (no persistence beyond the group, essentially just username) and groups may be created a la when 2 meet. Persistent users may still link in with these - they will appear on their schedule and be conflict detected/send alerts. Groups may be able to send alerts if temp users give cell # or email
 4 - Users may set up email and text alerts for themselves or for groups they admin
 5 - Users may utilize google maps (or similar) to sync locations for events.
### Technologies
Java
Spring Boot/Thymeleaf templatees
MySQL

### What I'll Have to Learn
I will need to learn how to use an SMS proxy API, as well as an email API, if I want this to work as intended, on top of the Google Maps API as a sort of bonus feature (or a similar such location service). On top of that, I'm going to need to either find some stylesheet things to use along the lines of twitter's bootstrap or build my own, and while in theory that's nothing new it's going to require some rather notable exploration outside my comfort zone I feel. I'll also need to implement cookies or somesuch to validate user logins I'd think...

### Project Tracker
Thus far it seems like I'll be using PivotalTracker but I'm also looking at Trello. I will update this once I've.. properly figured that out.
