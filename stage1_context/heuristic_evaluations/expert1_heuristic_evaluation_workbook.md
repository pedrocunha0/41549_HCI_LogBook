<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Pedro Cunha
**Date**: 26-02-2025
**Product**: RemNote

Severity Scale adopted: We adopted a 5-point severity scale to classify usability issues found during the heuristic evaluation. 
- **1 (Cosmetic issue)** – No impact on usability; fixing is optional.
- **2 (Minor problem)** – Slight usability issue; should be fixed if possible.
- **3 (Major problem)** – Causes difficulty; should be fixed as a high priority.
- **4 (Severe problem)** – Significantly hinders usability; must be addressed urgently.
- **5 (Usability catastrophe)** – Prevents task completion; requires immediate action.

Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Slow synchronization between devices, causing significant delays. | 4 | Enhance synchronization efficiency to ensure real-time or near-real-time updates. |
| Lack of clear indicators during the synchronization process, leaving users uncertain about the current state. | 3 | Introduce visual cues or notifications that display sync status, such as loading icons or confirmation messages.
 |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Introduction of unnecessary or confusing features, making the app more complex.  | 3 | Conduct user research to understand real needs before adding new features. Ensure new functionality aligns with user expectations and common practices. |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Difficulties canceling or undoing actions due to the lack of clear undo or cancel options. | 3 | Implement easily accessible "Undo" and "Redo" functions, allowing users to reverse actions efficiently. |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Inconsistencies in the interface, such as formatting issues and unexpected behavior in certain functions. | 3 | Conduct usability testing to identify inconsistencies and ensure all features adhere to uniform design and behavior standards. |
# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Updates introducing severe bugs, leading to data loss or rendering the app unusable. | 5 | Implement rigorous quality assurance processes before releasing updates, including extensive testing and beta phases to detect and resolve bugs. |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Features or commands are not easily discoverable, requiring users to memorize procedures. | 2 | Enhance the interface so that commands and features are clearly visible and accessible, possibly through context menus or tooltips. |
# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Lack of shortcuts or gestures, making tasks slower for experienced users. | 3 | Develop and document keyboard shortcuts and gestures to improve efficiency for power users, ensuring they don't interfere with novice users. |
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| New features adding complexity to the interface, reducing usability. | 3 | Evaluate the necessity of new features and ensure the interface remains clean, focusing on core user tasks.|
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Uninformative error messages, making it difficult for users to understand and resolve issues. | 3 | Develop clear and concise error messages that explain problems in simple terms and provide concrete steps for resolution. |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Lack of comprehensive help documentation, making it challenging for users to find answers. | 2 | Enhance help documentation with tutorials, FAQs, and examples to guide users in resolving common issues. |

[back to stage 1 page](../b_stage_1_context_definition.md)