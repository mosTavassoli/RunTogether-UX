# Milestone 4: Usability Testing - Run Together

## Overview and Script

### Preparation and setup

The usability testing has been done through each pair of team members, one as Facilitator for introducing the application and giving the tasks, and another one as Note-takers take notes of the participant’s behavior, comments, errors, and completion of each task.
The application ran on the facilitator's PC and through Zoom, the permission for working with the application was given to the participant and the meeting was recording. The notetaker was connected to the meeting and observed everything.

### Participants

- Target population: Amateur Runners
- Age range: 18-70
- Basic skills in using a smartphone
- Expertise with our app: no, never seen it
- Usage of running apps: yes at least once a month
- Doing running activity: yes at least once a month
- At least basic knowledge of English

### Equipment

- Computer and webcam (for remote call)
- Internet connection
- Pen and paper (notetakers)

### Artifacts

- [Informed consent form](./docs/InformedConsentForm.pdf)
- [Post-test questionnaire (SUS)](./docs/SUS.pdf)

Recruiting is conducted orally, with a brief list of questions to verify that the potential participant respects the constraints.

### Execution

- **Roles:**  
  One facilitator and one notetakers (all remotely).  
  The full script is available [here.](./docs/Script.md)

- **Methodologies:** Think-aloud for tasks 1 to 8

* **Measures (for each task):**
  - Successful Task Completion
  - Critical Errors
  - Non-Critical Errors
  - Error-Free Rate

### Tasks

| Task | Task Description                                  | Methodology | Success criteria                                                                                                                 | maximum task time |
| ---- | ------------------------------------------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| T1   | Complete one running activity, send your feedback | Think-aloud | Start a Run activity and finish it, finally fill the provided form as feedback and send it.                                      | 10 min            |
| T2   | View the beginner training plan                   | Think-aloud | Select the beginner level and related plan, review the weekly plan and read tips for warming up                                  | 4 min             |
| T3   | Create a running group and add one participant    | Think-aloud | Find the "PLUS" button and fill the provided form (with mandatory fields) and add one participant to the group.                  | 7 min             |
| T4   | Find the most popular running group to join       | Think-aloud | Using the provided "Sort By" box and select the most popular group, move to Group details, and click on the JOIN button.         | 7 min             |
| T5   | Check your history of running                     | Think-aloud | After the running activity which is done in T1, check the running activity in the CHART and review the history (Weekly/Monthly). | 5 min             |
| T6   | Leave from one of your joined group               | Think-aloud | Look at the joined group list and select one of them, once the group page opens, click on the remove button.                     | 3 min             |
| T7   | Find the MILANO group; check its information      | Think-aloud | Use the provided search box in Gropu Menu and write the "MILANO" word and check the Group Details on its pages.                  | 5 min             |
| T8   | Check your created group                          | Think-aloud | Make sure that his created group is added into his joined group with correct details (especially the number of runners).         | 3 min             |

### Post-Task Questionnaire: Single Ease Question (SEQ)

After finishing each task the difficulty level of the given task was asked.

1. very difficult 2. 3. 4. 5. 6. 7.very easy

| Tasks  | User 1 | User 2 | User 3 | User 4 | User 5 | User 6 | Average Difficulty |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------------------ |
| Task 1 | 3      | 5      | 5      | 6      | 5      | 6      | 5                  |
| Task 2 | 6      | 7      | 7      | 6      | 7      | 7      | 6.66               |
| Task 3 | 6      | 6      | 5      | 6      | 6      | 6      | 5.83               |
| Task 4 | 4      | 5      | 6      | 6      | 4      | 4      | 4.83               |
| Task 5 | 6      | 7      | 7      | 6      | 7      | 7      | 6.66               |
| Task 6 | 6      | 6      | 7      | 6      | 7      | 7      | 6.5                |
| Task 7 | 6      | 5      | 6      | 6      | 5      | 4      | 5.33               |
| Task 8 | 6      | 7      | 7      | 6      | 7      | 7      | 6.66               |

### Post-test oral questions

- In general, how was your experience with our application?
- During the test, **\<something noticed by the notetakers\>**. Can you tell us about it?
- According to your opinion, which are the best and the worst things about this application?
- Do you have any additional comment?

## Run the Tests

The tasks were read by the facilitator to the participant and repeated when the participant asked them.
During the usability tests, we captured screenshots in the moments that were necessary while the meeting was recorded.

<br/>

<div align="center">
  <img src="images/6.jpg" width="350" alt="accessibility text">
</div>
  <p style="text-align:justify">
  <b> Task 1:</b> After running the activity for giving feedback, the user found this page vague at the first glance.
</p>
<br/>
<div align="center">
  <img src="images/7.jpg" width="350" alt="accessibility text">
</div>
  <p style="text-align:justify">
  <b> Task 3:</b> For adding participants, the user could not find any user to add.
</p>
<br/>

<div align="center">
  <img src="images/1.jpg" alt="accessibility text">
</div>
  <p style="text-align:justify">
  <b> Task 4:</b> The user could not find the search and filtering the groups. 
</p>
<br/>

<div align="center">
  <img src="images/4.jpg" width="350" alt="accessibility text">
</div>
  <p style="text-align:justify">
  <b> Task 7:</b> The user could not understand the same city filtering
</p>
<br/>

<div align="center">
  <img src="images/T7.png" alt="accessibility text">
</div>
  <p style="text-align:justify">
  <b> Task 7:</b> The user has confused about the details of the group, why the date, time, and location for running are always the same. 
</p>

<br/>

<div align="center">
  <img src="images/T5.png" alt="accessibility text">
</div>
  <p style="text-align:justify">
  <b> Task 2:</b> The user checks his running activity, he does not know what is the vertical column of the chart is.  
</p>

## Results and List of Changes

After all the heuristic evaluations, we gathered all the data to analyze some of the issues present in the system.

| Task # | # Successful Task Completion | # Critical Errors | # Non-Critical Errors | Error-Free Rate |
| ------ | ---------------------------- | ----------------- | --------------------- | --------------- |
| 1      | 6                            | 0                 | 2                     | 0.66            |
| 2      | 6                            | 0                 | 0                     | 1.0             |
| 3      | 6                            | 0                 | 1                     | 0.83            |
| 4      | 4                            | 2                 | 3                     | 0.0             |
| 5      | 6                            | 0                 | 1                     | 0.83            |
| 6      | 6                            | 0                 | 1                     | 0.83            |
| 7      | 5                            | 1                 | 2                     | 0.4             |
| 8      | 6                            | 0                 | 0                     | 1.0             |

### Successful Task Completion

The number of participants who completed the task successfully. The only tasks (T4, T7) were not completed by all the participants.

### Critical Errors

The critical errors for these (T4, T7) tasks are about finding the Searching and Filtering box in the page and users did not use them for finding and filtering the groups, because the user for the first time using this application could not find them at the first glance.

### Non-Critical Errors

For the Non-Critical Errors for the T1, for giving the feedback after Running activity the user found the form vague and complex for filling the activity.
For T3, the user could not find the + button to create the group.
For T6, after leaving the user could not redirect back to the group page.

### Error-Free Rate

Analyzing the measures computed on the tasks, we discovered that some tasks are more difficult than others to the user.
Tasks with an Error-Free Rate >= 0.83 (T2, T3, T5, T6, T8) can be considered easy for the user to do.
Task with an Error-free Rate = 0.66 (T1) can be considered as a medium task for user to do.
The tasks with Error-Free Rate =< 0.4 are difficult Tasks (T4, T7).

### SUS Results

| SUS question | User 1 | User 2 | User 3 | User 4 | User 5 | User 6 |
| ------------ | ------ | ------ | ------ | ------ | ------ | ------ |
| 1            | 4      | 4      | 4      | 4      | 4      | 4      |
| 2            | 1      | 2      | 1      | 1      | 1      | 1      |
| 3            | 4      | 5      | 5      | 5      | 5      | 5      |
| 4            | 3      | 4      | 1      | 1      | 2      | 1      |
| 5            | 4      | 4      | 5      | 5      | 3      | 4      |
| 6            | 2      | 1      | 1      | 1      | 2      | 2      |
| 7            | 4      | 5      | 4      | 5      | 5      | 5      |
| 8            | 1      | 1      | 1      | 1      | 2      | 1      |
| 9            | 4      | 4      | 5      | 5      | 5      | 5      |
| 10           | 1      | 1      | 1      | 1      | 1      | 1      |
| **TOTAL**    | 80     | 82.5   | 95     | 97.5   | 85     | 92.5   |

The scores are all above 88.75, meaning that out interface can be considered to be above average.

### Post-test considerations

We received positive feedback from users, especially for having the functionality of showing groups to users and enabling them to join the groups. Some feedback we received about the possibility to change or improve some parts of the interface such as starting the activity, searching groups, and extending features of the profile page. Other feedbacks were mainly about changing the color of buttons or adding some icons especially when he needs to enter the inputs. To sum up, most feedbacks were positive about accepting this application and trying to use them in everyday life.

### Test 1 Findings

| Task | Feedback                                                                        |
| ---- | ------------------------------------------------------------------------------- |
| T1   | The complete task with confusion, need guidance to reach the starting activity. |
| T4   | The user does not know the popularity is based on what.                         |
| T6   | After leaving, the group redirect back to the group page                        |

### Test 2 Findings

| Task | Feedback                                                                         |
| ---- | -------------------------------------------------------------------------------- |
| T1   | Completed a partial task; first part entirely, some issues in the feedback form. |
| T4   | Confusing about the icon listed in each group.                                   |
| T7   | The user does not use a search box for searching                                 |

### Test 3 Findings

| Task | Feedback                                                                                                    |
| ---- | ----------------------------------------------------------------------------------------------------------- |
| T1   | Confused about using this part, feedback for after the activity is vague                                    |
| T3   | User does not find the PLUS button for creating group                                                       |
| T4   | Confusing Icons: User does not know what is the popularity is based on, User does not use box for searching |
| T7   | User does not use box for searching                                                                         |

### Test 4 Findings

| Task | Feedback                                                     |
| ---- | ------------------------------------------------------------ |
| T1   | Timer for running should count when switching between pages. |
| T5   | The vertical column of the activity chart is unclear.        |

### Test 5 Findings

| Task | Feedback                                |
| ---- | --------------------------------------- |
| T1   | Some issues for the feedback part.      |
| T4   | The user could not find the sort box.   |
| T7   | The user could not find the search box. |

### Test 6 Findings

| Task | Feedback                                                                   |
| ---- | -------------------------------------------------------------------------- |
| T1   | For the first part, there were some issues with using the map in web mode. |
| T4   | Could not find the sort box.                                               |

### List of Changes

We would like to address some issues found during the tests by impelneting the following modificarions:

- Adding proper spaces between the elements in the "Feedback Form"; appearing after the run activity to make it much clearer.
- Add icon in "Add Participants" field in the Creating Group page and adding "No Options" if there are no participants related to the character users searched, led to confuse users doing this activity.
- Add "measure units" on the Chart, and the numbers in the lower parts on the "My Activity". Change the design of the chart (color, add functionality by clicking each point on charts, add more spaces)
- Change the design of the Group Page entirely, put the "search-box", and "sort by" on the top of the page with the proper Icon.
- Change the text in the "Sort By" combo Box from the "same city" to "Location", and link its result with the search name text filed.
- Move the information of the running activity of the Group from its page to the FEED page.

The new version of the prototype was designed based on all of the above-mentioned changes.
