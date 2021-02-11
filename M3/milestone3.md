# Milestone 3: Wireframe and Heuristic Evaluation - [RunTogether]

<!-- _ISTRUCTIONS_: Fill this template by writing under each title, according to the instructions reported in `[]`. When you have done, remove this line, and put the file in your private group repository on GitHub, under a `M3` folder. -->

## Wireframe
<!-- [Add here the link to the PDF documents, or embed the images, that represent your wireframe. Briefly explain which tool you used to create the wireframe, any relevant decision you took starting from the outcome of M2, and describe in short the navigation among pages (with a picture or in text).] -->

Tools: the final wireframe is drawn in Figma
<br/>
After designing the pen and paper prototype in M2, we decided to complete the missing description and choose a better title for the pages in prototype 2, so we add 2 pages containing the actions for start running and discovering last activities in the joined groups. Moreover, the page for Training plan was changed into another design to motivate users more. In the last Molestone, the design for the profile page contained some tabs in the middle of the page and it became an issue, hence we decided to move the tabs to the bottom of the page in a specific menu.<br/>

<b>Feed page</b><br/>
This page is the starting page of the application. In this page user can discover the last notifications or plans for running from the nearby groups or the groups which he joined.<br/>

<img src="images/gray/Feed.png"  width="300" alt="Feed page">
<br/>
<b>Start workout page</b><br/>
After pressing "start the run" button in the Feed page, the application will monitor the user's running. <br/><br/>
<img src="images/gray/Start.png" width="300" alt="Start workout page">
<br/>

<b>Training plan page</b><br/>
According to the level of the user, the appropriate level of plan will be unlocked and in the next page user can discover the groups which fits his needs and level.<br/><br/>
<img src="images/gray/plan.png" width="300" alt="Training plan page">
<br/>

<b>Plan details</b><br/>
After pressing the train plan, following image will be shown
<br/>

<img src="images/gray/pdetail.png" width="300" alt="Plan details">
<br/>

<b>Group Search page</b><br/>
In this page, user can find the groups according to the filters which he applies ( location, number of participants , maximum KM , maximum time )

<br/>
<img src="images/gray/search.png" width="300" alt="Group Search page">
<br/>
<b>Group detail page</b><br/>
After pressing view details in group search page, the next page will be shown<br/>

<br/>
<img src="images/gray/Gdetails.png" width="300" alt="Group detail page">
<br/>
<b>Add Group page</b><br/>
By selecting the plus button in Group Search page, User can create a group and add the participants by inserting their user names.<br/>


<br/>
<img src="images/gray/Gadd.png" width="300" alt="Add Group page">
<br/>

<b>Joined Groups</b><br/>
In this page, user can visit or remove the groups that he is joined in.


<br/>
<img src="images/gray/Ghistory.png" width="300" alt="Joined Groups">
<br/>

<b>Profile Page</b><br/>
The history of running is shown to the user according to the filters he selects ( last week, last month , year)

<br/>
<img src="images/gray/Profile.png" width="300" alt="Profile Page">
<br/>

<b>Navigation</b><br/>
The below image is showing clearly the navigations between pages.The footer menu from left to right navigates to Feed, Training plan, Group Search, Joined Groups and Profile page. 
 
<img src="images/Navigations.png" width="800" alt="Navigation between pages">


## Heuristic Evaluation
<!--[Describe here the heuristic evaluation you received. In particular, report your preparation of the heuristic evaluation: which material you used (with links and/or pictures). Then, briefly summarize how the heuristic evaluation was conducted by the facilitator, by including 1-2 photos/screenshots from those taken by the facilitator for each evaluation. Include the evaluation result from the evaluators (please mention which group helped you), for example as a link to the on-line spreadsheet.
Finally, write a non-trivial list of potential changes that your team plans to implement and justify each change by explaining which piece of feedback generates it.]-->

### Overview
For Heuristic Evaluation we asked the Sportify Team. First facilitator explained the project's description and main activites, then facilitator asked the evaluator to do the some tasks through the wireframe. The list of tasks are in the below table. While doing these tasks they encountered with some issues and doubts, the evaluator jot down on the paper and at the end the two evaluators entered their feedbacks into the sheet and they sent it to the facilitator. 

The faciliator shared the excel document and ask them after finishing the evaluation it is needed to fill this sheet:<br/>
https://docs.google.com/spreadsheets/d/1OdyJ5gXErBWyZoP9PEIsTN6Kymwd0BWhgXqkmuWeM-c/edit#gid=0

The facilitator shared the link of wireframe to the evaluators: <br/>
https://www.figma.com/file/6H5F2Tti7uppQfdXxuSG5t/profile-page?node-id=109%3A240


### Tasks 

| # | Tasks |
| ------| -----------|
| T1   | Find a group for running |
| T2   | Join a group |
| T3   | Check your running progress in the last week/ last month |
| T4   | Check your joined groups |
| T5   | Check the total KM that you runned |
| T6   | Check the details of a group|
| T7   | Create a group |


### Screenshots  
While the evaluator was doing the certain task, the another teammate capture the screen. The task for create and join the group was given to both of the evaluators and the below the screen was recorded.


|  Task  | Screenshot |
| ------| -----------|
| Join a group|<img src="images/heuristic/JoinGroup.gif" alt="Heuristic Evaluation">  
| Create a group, Join a group|<img src="images/heuristic/CreateJoinGroup.gif"  alt="Heuristic Evaluation"> 

## Feedbacks 

### Evaluator 1

| # | Feedback  | Changes |
| ------| -----------|-----------|
| 1   | You cannot go back after you have joined a run group |  After joining to a group, it will redirect to the joined groups and if you cancel you will back to the groups	|
| 2   | Search bar does not appear in the search menu | Filtering the groups and searching groups by name	|
| 3   |Menu at the bottom of the application lacks description; it is not simple to understand functionality of the icon |We will add a short text for each icons such as: Feed,Training,Groups,Profile to convey its  functionality easier and without hesitation|
| 4   |Plus button in the search menu is counterintuitive; it is better to place it in the homepage||


### Evaluator 2

| # | Feedback  | Changes |
| ------| -----------|-----------|
| 1   |The page for searching teams doesn't have a search bar for finding teams by name | Putting this function for filtering the groups based on the location, number of members, max km for runnign and group rate and also by typing name of the group  |
| 2   |When choosing a team to join the button "Join" appears in the position occupied by the "Cancel" button in the page that comes before| The arrangement of the buttons will be fixed |
| 3   |Buttons "Join" and "Cancel" in the page for joining a team and also the "Add" button when registering a team all share the same color, making it confusing| The proper set of colors will be apply for buttons and texts |
| 4   |When adding a new team having the button named as "Add" instead of "Save" isn't conform to standards.| We think for adding a new group the proper word is "Create" |
| 5   |Having the "+" button for adding a new team in the page for searching teams may not be intuitive at first.| For adding a new group the only page that seems related and easier is searching group |
| 6   |The procedure for adding members isn't easy to understand: requiring the user to insert manually all names in a single text field can lead to errors.|Putting placeholder name for textboxes to help user to write the username and at the same time searching that username |


### Non-trivial list of potential changes 
Based on the feedback, we came to these potential changes.

| # | Changes  | Rating
| ------| -----------| ------|
| 1   | Realtime search by entering the name of user for creating the group |4|
| 2   | Filtering the groups and searching groups by name |2|
| 3   | Adding text and icon for bottom menu |2|
| 4   | The proper set of colors will be apply for buttons and texts |2|
| 5   | The proper arrangement for buttons (join and cancel) |2|

