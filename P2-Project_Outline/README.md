# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
ScheduleSheets (Name not necessarily final) is a webapp designed to help people keep, update, and coordinate their schedules, both individually and as a group. Designed to be quickly and easily used without an account, or with more in-depth tools when taking the time to register, it offers a variety of degrees of service for user convenience. Registered users may create individual schedules, marking down events (which can be set to repeat) to be reminded of and checked against. In addition, groups, both registered and otherwise, may create scheduling blocks for predetermined group events, or to find a block of time between the group in which to schedule.

SMS and Email notifications for alerts will be available, though nonregistered users must provide this information with each event rather than as part of their account. In addition, any events that might conflict will be marked for the user, indicating either a conflict, or a possible conflict based on timing (for instance, it is unlikely that someone could attend a conference in las vegas and then be in Washington DC within ten minutes) - this would be contingent upon the app's final potential feature, location services, which would allow groups and individuals alike to mark down the where of each event, and using travel time APIs, attempt to mark down events that are too distant to be as close together on a user's timeline. The ideas for this service come from personal issues scheduling events, both with others and on a personal level, and a desire for organization which I felt could be transformed into a useful, marketable user experience for a larger base.
### Features
1 - Event Scheduling - Group or Individual
2 - Guest Scheduling - Unregistered users may create and participate in group scheduling
3 - User Login - Users may create individual events and keep persistent schedules
4 - Conflict Detection - Registered users may detect conflicts betewen their scheduled events
5 - SMS/Email Alerts - Alert users (registered and otherwise) that their events are coming up
6 - Map API Integration - Allow users to coordinate event locations as well as times in-app

### Technologies
Java
Spring Boot/Thymeleaf templatees
MySQL

### What I'll Have to Learn
I will need to learn how to use an SMS proxy API, as well as an email API, if I want this to work as intended, on top of the Google Maps API as a sort of bonus feature (or a similar such location service). On top of that, I'm going to need to either find some stylesheet things to use along the lines of twitter's bootstrap or build my own, and while in theory that's nothing new it's going to require some rather notable exploration outside my comfort zone I feel. I'll also need to implement cookies or somesuch to validate user logins I'd think...

### Project Tracker
Trello - https://trello.com/b/0nboh8qa/schedulesheets
