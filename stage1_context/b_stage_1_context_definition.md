[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                                                                                      | Information repository                                             |
| ----------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| RemNote           | A note-taking app with spaced repetition and bi-directional linking for efficient learning.		   | [RemNote Information](competitors/Competitor_Analysis_RemNote.md)  |
| Obsidian          | A Markdown-based tool for networked note-taking, with a focus on customization and knowledge graphs. | [Obsidian Information](competitors/Competitor_Analysis_Obsidian.md)|




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
<!--[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]-->


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Something wrong | 3            | 1        | 0        | Something could be done to the button to... |
| Another thing   | 4            | 3        | 4        | Other thing to recommend                    |
| ...             |              |          |          |                                             |



---
### - Cognitive Walkthrough

#### Method
<!-- [Briefly described  the method you used for the Cognitive Walkthrough analysis. ] -->
>   We conducted a Streamlined Cognitive Walkthrough analysis  
>   1. Identify tasks
>   2. Perform task analysis

#### Task Selection and Task Analysis

<!-- [Which tasks did you select and why. What are the subtasks entailed for each ] -->


| Task                               | Subtasks                                      |
| ---------------------------------- | --------------------------------------------- |
| **1. Taking notes from a lecture** | Search for a way to create a note document    |
|                                    | Take notes                                    |
|                                    | Save done work                                |


| Task                                   | Subtasks                                |
| ------------------------------------   | --------------------------------------- |
| **2. Generate a quiz from a document** | Upload a document                       |
|                                        | Generate a quiz                         |
|                                        | Answer quiz (Choosing options)          |
|                                        | Get feedback                            |


#### Results

Task: 1. Taking notes from a lecture  
>   A user wants to take notes from a lecture

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1 | Create a new Document to write notes | [Yes] | It is not very obvious          | [Yes] |  | [Yes] | The option to create could be easier to find |     |
| 2 | Write down notes                     | [Yes] |                                 | [Yes] |  | [Yes] |                                              |     |
| 3 | Save done work                       | [Yes] | Progress is saved automatically | [Yes] |  | [Yes] |                                              |     |

Task: 2. Generate a quiz from a document  
>   A user wants to generate a quiz from a slideshow to test his skills

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1 | Upload a .pdf containing the a study topic | [Yes] |         | [No] | There are multiple ways to do it and it gets confusing  | [Yes] | Reducing number of paths to the same outcome |     |
| 2 | Generate a quiz | [No] | Gets confusing with the requirement of `flashcards`  | [Yes] |  | [Yes] |                                              |     |
| 3 | Answer a question from a quiz | [Yes] |   | [Yes] |  | [Yes] |                                              |     |
| 4 | Get answer feedback | [Yes] |  | [Yes] |  | [Yes] | Flow is a little confusing and requires extra input / was expecting final report                                             |     |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
