---
title: "How do I set defaults for my organization?"
description: "Use your organization profile to create default settings for classes, users, enrollment cancellations, courses, surveys, and several other items."
isPublished: true
---

# How do I set defaults for my site?

> Please be aware that functionality covered in this and linked articles may not be available to you.

Creating users, classes, and courses have fields allowing organizations to choose their own default values. The default value automatically displays when you are creating a new entity, and each of these items can be revised as needed. You can set defaults through Organization Preferences.

To set your defaults:
1. On the **Admin** menu, in the **Organizations** group, click **My Organizations**. 
1. Select the organization **Name** to access the **Organization Profile**.
1. Click **Edit**. 
1. Open the **Preferences** tab. 

### Article contents
* [Business Settings](#business-settings)
* [User Settings](#user-settings)
* [Enrollment Settings](#enrollment-settings)
* [Class Settings](#class-settings)
* [Course Settings](#course-settings)
* [Default Surveys on new Courses and Classes](#default-surveys-on-new-courses-and-classes)
* [Miscellaneous Settings](#miscellaneous-settings)

## Business Settings
You can set the days and times your organization is open, this displays when any user views your organization profile.

* **First Day of Work Week** - Set the first day of your normal work week
* **Week Days** - Set the open and close times for your organization by selecting a day and select times from the Hour and Minute chart as well as either AM or PM
* **Microsoft Partner Id** - Input your Microsoft Partner ID
* **Microsoft Campaign Code** - Add your Microsoft Campaign Code

[Return to Article contents](#article-contents)

## User Settings
Three defaults can be set for creating new user accounts: the User Password and the UserName Pattern. 

* **User Password** - Type in a password to be used for all new user accounts. The password must be at least 8 characters long. Your default password is applied to users created directly in the Skillable TMS or can be used when importing users
* **UserName Pattern** - Select either **E-mail** or **FirstName.LastName** for the default of new users username

[Return to Article contents](#article-contents)

## Enrollment Settings

Enrollment settings allow you to add a late cancellation time period and text. When a student cancels their own enrollment, you can have a a pop up message appear letting them know their cancellation is considered late and you can add a message about your late cancellation policy.

* **Set window on Late Cancellation warning when student cancels an enrollment** - Input the number of days before class starts that qualifies as a late cancellation
* **Late Cancellation warning text** - Type in the late cancellation information you want to relay to a student when they late cancel their enrollment

[Return to Article contents](#article-contents)

## Class Settings
Several defaults can be set for the classes you create such as the class capacity, the pattern of days classes are held, the start and end times for classes, and the status of the class.

* **Use basic class editor** - Check the box to enable the basic class editor if you would like to only view the essential fields when creating or editing a class. All fields are still available when the **Advanced Settings** link is clicked
* **Class Status** - Select a default class status from the dropdown. Please note, for class functionality to work the status must be set to either **Scheduled** or **Guaranteed to run**
* **Class Minimum Capacity** - Set a minimum capacity to use as a search for classes you may want to cancel if the minimum number of students have not enrolled. To use this search criteria, go to **Find Classes** and filter by **Has not Met Minimum Enrollment**
* **Class Maximum Capacity** - Set a maximum capacity for classes. This restricts the total number of enrollments for your classes to the number you have set
* **Use Event Training Key for self-enrollment** - Checking the box to use event training key enables the Event Training Key on all newly created classes
* **Class Session Pattern** - Check the days of the week you normally want your classes to run. Class session will be scheduled on the checked days and skip the unchecked days. For example, if you do not hold classes on Saturday and Sunday leave those days unchecked, if you scheduled a 10 day class, by default, it will only be scheduled on dates falling on Monday - Friday
* **Class Session Start** and **End Time** - Set the class start and end times for your normal class day
* **Enable Class Notifications** - Checking the box to enable class notifications defaults all newly created classes to having notifications enabled
* **Enable reminder message when a classroom has not been added** - Enabling a reminder when a classroom has not been added will pop up a reminder message anytime you save a class that does not have a classroom
* **Allow Wait List Auto Enroll For Classes** - Enabling auto-enrollment causes students in a wait-listed or requested status to be enrolled when an enrolled student cancels their own enrollment for a class at maximum capacity. [**How do I automate enrollment of wait-listed students?**](https://docs.learnondemandsystems.com/tms/tms-administrators/classes/enrollments-roster/auto-enroll-waitlisted-students.md) 
* **Show Instructor Certification Filter** - When creating or editing a class and adding an instructor, the Instructor chooser dialog can be set to add the Instructor certifications filter by default. Certifications can be set on an instructor's user profile to show which courses they are qualified to teach. Adding the filter when choosing an instructor will only show instructors who are set as certified to teach the course
* **Show Organization filter to choose instructors from outside my organization** - When creating or editing a class and adding an instructor, the Instructor chooser dialog can be set to add the organization by default. Adding the filter when choosing an instructor allows you to select from organizations you have access to
* **Uses Contract Instructors** - Check this box to opt in to use contract instructors, you gain access to view contract instructor contact information and the ability to schedule these instructors for your classes. [**What is the Contract Instructor Pool?**](https://docs.learnondemandsystems.com/tms/tms-administrators/users/instructor-management/what-is-contract-instructor-pool.md)

[Return to Article contents](#article-contents)

## Course Settings
Several defaults can be set for your courses, such as, adding a new icon, and set defaults for course feedback or course ratings. 

* **Available Instructor-Led** - Check this box to have newly created courses default to have available instructor-led enabled
* **Available Self-Paced** - Check this box to have newly created courses default to have available self-paced enabled
* **Show "New" icon (# of days)** - Input the number of days you would like a new icon to display on Find Courses and a course catalog for any newly created courses
* **Enable simple course feedback** - Check this box to have course feedback enabled on all newly created courses
* **Display course ratings** - Enable course ratings based on Simple course feedback to show on the course catalog. Once checked additional choices show for a minimum of ratings to display and to only show if a minimum rating is set
* **Total ratings required before displaying** - Input the number of ratings that must be submitted through Simple course feedback before the rating displays
* **Specify minimum course rating** - Check specify minimum course rating to reveal a percentage field, enter the minimum rating that must be met for course ratings to display on a course catalog
* **Automatically create course when new lab profile is found on lab sync** - Courses can be created automatically from newly published labs if the feature is enabled. For a published Lab Series, marking a Lab Profile complete triggers immediate creation of a course for a lab profile in the Skillable TMS. Additional set up is required by our help desk
* **Program** - Input the Program set for the course for an automatically created course from a lab profile
* **Content Provider** - Input the Content Provider set for the course for an automatically created course from a lab profile
* **Publishing Group** - Input the Publishing group set for the course for an automatically created course from a lab profile
* **Show activity status on activities listings** - Enables showing the status of activities on Course Assignment and Class Enrollment pages
* **Show activity score on activities listings** - Enables showing the score of activities on Course Assignment and Class Enrollment pages

[Return to Article contents](#article-contents)

## Default Surveys on new Courses and Classes

Surveys can be set to be added by default on all new courses and all new classes. If different survey selections are added directly on a course, then a class based on the course inherits the course's surveys. Surveys can be added or changed on a class.

* **Student Survey** - Input a default student survey to be added by default to all newly created courses and classes
* **Survey Availability** - Input the number of hours you want the student survey to show in the class activities after the event begins or before the event ends. Also input the number of days after the event ends the survey will be available for students to take
* **Instructor Survey** - Input a default instructor survey to be added to all newly created courses and classes
* **Organization Survey** - Input a default organization survey to be added to all newly created courses and classes

[Return to Article contents](#article-contents)

## Miscellaneous Settings

* **Course Assignment - Use simple course assignment** - Enable using simple course assignment to use the most update user interface for self-paced learning
* **Discussion Disclaimer - Set a Disclaimer** - Discussions can have a disclaimer message added which displays to users on discussion posts
* **On-Demand Course browser - Show subscription profile name** - You can display the subscription name when you have the On-Demand course browser enabled on the subscription profile
* **Organization Room Calendar - Include external classrooms** - Organizations have several calendars available, the Room Calendar can have external classrooms display
* **Achievements - Enable using Achievements** - Achievements allow you to award users for accomplishing designated parameters either automatically or by assigning them
* **Participate in Global Achievements** -  Any achievements set as global in the platform are enabled for your organization

[Return to Article contents](#article-contents)
