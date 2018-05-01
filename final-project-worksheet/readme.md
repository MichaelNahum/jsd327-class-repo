# Project Overview

Endorsement Geo-Tracker.

APIs involved: Gmail, Google Map 

SPA setup: Left 70-75% an embedded GoogleMap, the right 25-30% an empty text column with two input boxes at the top of the screen: location, and window.

UX: User types location name into the first input box, and how many hours back they want to search (the latter feature will be added later). The map will populate with pins corresponding to endorsement locations (a post-MVP feature will include a hover event producing a popup containing the full text of the endorsement). The right column will populate with divs containing all endorsements to match the search criteria within the last 24 hours. 

Backend logic: upon the submit event, an ajax call to the gmail api will get all endorsement emails containing the search term. Each endorsement will be parsed for location data, source text (non-English), caption text (our translated summary), and timestamp. Location data will be used to generate pins in the map-component, while divs containing the main text and timestamp will populate the text column to the right. 

Resources: 
[Google Maps Documentation](https://developers.google.com/maps/documentation/javascript/tutorial)
[Gmail Documentation](https://developers.google.com/apps-script/reference/gmail/gmail-thread)



## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|May 1st| Project Description | Incomplete
|May 8th| Wireframes / Priority Matrix / Functional Components | Incomplete
|May 15th| External API(s) Decision / Core Application Structure (HTML, CSS, etc.) | Incomplete
|May 22nd| Minimal Viable Product | Incomplete
|May 29th| Styling / Bug Fixes | Incomplete


## Project Description

Use this section to describe your final project and perhaps any links to relevant sites that help convey the concept and\or functionality.

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe.

## Priority Matrix

Include a full list of features that have been prioritized based on the `Time and Importance` Matix.  

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 

- Find and use external api 
- Render data on page 
- Allow user to choose favorites 
- Save their choices in firebase

#### PostMVP 

- Add user auth

## Functional Components

Based on the initial logic defined in the previous  phases section try and breakdown the logic further into functional components, and by that we mean functions.  Does your logic indicate that code could be encapsulated for the purpose of reusablility.  Once a function has been defined it can then be incorporated into a class as a method. 

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. 

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | H | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 3hrs| 2.5hrs | 2.5hrs |
| Total | H | 6hrs| 5hrs | 5hrs |

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

| Function | Description | 
| --- | :---: |  
| Capitalize | This will capitalize the first letter in a string of text | 

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## jQuery Discoveries
 Use this section to list some, but not all, of the jQuery methods and\or functionality discovered while working on this project.

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object
