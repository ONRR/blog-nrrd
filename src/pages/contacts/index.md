---
title: "Six lessons from my time as a government product manager"
authors:
- Jennifer Malcolm
excerpt: "As she gets ready for a new federal position, our first product manager reflects on all she has learned from her time on this team."
tags:
- product management
- training
- public service
- government
date: "2021-06-24"
---

# Re-architecting contact information to meet user needs

## Identifying the problem

One of the biggest user tasks for onrr.gov is finding contact information to answer questions. Industry users need to know who at the Office of Natural Resources Revenue (ONRR) can answer various types of questions. Today, the site includes 9 files with contact information, each organized differently.

Some are organized by company name or by the first letter of the company name and some by user task. The different organizations make it difficult to find the correct person to answer a given question. Users need an easier way to search and find the correct contact. ONRR’s teams also need an easier way to update contacts. They currently send a new copy of the contact file (either a PDF or spreadsheet) each time a contact changes.

Insert Image 1

User interviews showed that users found it difficult to sift through the current contact documents. Thus, I was tasked to come up with a design concept for contacts. I determined a search function would maximize the user’s ease of access and interactivity with the contact directory. Then I started to think about different ways to organize the contacts and create categories from patterns found. I decided to create a spreadsheet and some form of information architecture.

## Initial contact organization

First, I created a “stacked-box” information architecture within a document. Within each box I listed the categories that appeared in the original contact directory to see what fields there were. Then I viewed each category's information structure, but I was not familiar with some terminology which made me ask questions. After I clarified those spots in our meeting, I moved onto creating new categories that the contacts could be organized by.

I then entered the categories and some contacts into a spreadsheet to see how the information could be divided within the directory. Next, I started organizing the entire contact directory onto the spreadsheet. As I was doing this, I realized it would take me longer to complete and was thus inefficient. As a result, I decided to use the first contact listed as an example, then double checked to see if I was missing any areas.

After I felt confident, I proceeded to create information architecture (IA) for the search function and the filter. The IA for the search bar was to figure out how to display the search results, while the filter IA was to determine what filter options should be present. Then to see if they made sense, I created two user journeys detailing the actions to take in using the two functions, which are in the table below.

## User journeys

**Steps to find a contact**

Search Bar:

1. User types in contact name, company assignment, company name, etc.

2. Search Results will be presented in a list

3. User clicks on a listing to expose a drop-down menu containing more information about that individual contact

4. The user has the option to email or call that contact immediately via hyperlink

Filter:

1. User applies up to 4 different filters at the same time. Each time they apply a filter a chip will appear below the search bar/header area, where they can remove it at any time.

2. Search Results will be presented in a list

3. User clicks on a listing to expose a drop-down menu containing more information about that individual contact

4. The user has the option to email or call that contact immediately via hyperlink


I combined the user journeys to create a single user flow of the possibilities the user could take when using the contact directory.

Insert Contacts User Flow Image

## Information architecture

Below are the categoreies I decided on based on the user journeys.

Insert Bulleted drop down list

## Design iterations

After I decided how to organize the information through the IA, I used the old contact directory as a foundation for designing the user interface. I expanded the search bar to span the entire contact directory to prompt the user to interact with the table through the search function. I then created a filter option with chips next to the filter for when the user adds filters to their search. Next, I added the search results under the search bar and the filter, so the user can interact with each one to find out more information about the results.

Insert design iterations image

After meeting with the team, I knew that I needed to differentiate between the categories and test out the design with a sample company. I decided I could start mocking up my sketches and presented them to everyone during our next meeting. The team suggested that I remove the legend because the filter options would save room and make the directory less cluttered.

When I presented my updated wireframe in the next meeting, my mentor, Shannon, and others were confused about whether the user had to use the search function first or not. From this feedback, I decided to make the prototype more dynamic and less linear to make the functionality clearer to the user. Additional feedback I received was regarding the drop-down filters,: to  group everything by category and create a filter for each with its own drop-down menu.

From the feedback, I went back and updated the IA bulleted list for the filters. Then I ran into the problem of how to categorize the main categories, which I brought up at the next intern meeting.

### Revised filter categoreies

insert bulleted list

## Final prototype design and next Steps

After the meeting, where Shannon helped me to revise the categories, I updated the wireframe based on the new IA. As a result of my work on redesigning the contact directory, I received positive feedback from ONRR’s leadership on its efficiency for the users. The next step is to pull in the existing contact information and get it into the prototype, so we can get stakeholder and user feedback. So far, the stakeholders who have reviewed it think it is much easier to find the correct contact. We plan on testing the design with users soon.

Insert Image

Working on the ONRR contact directory made me learn more about IA and usability through the IA bulleted list and creating the user journeys. These methods made me think critically about what information is and isn’t essential for the user. This was especially true when it came to the structure and deciding the filter options by identifying common themes.

From here, I plan to investigate more information architecture techniques that I could use for future projects. Additionally, I plan to read more about usability to get a better sense of how well different features serve the user’s needs in certain contexts.