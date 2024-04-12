# sld-good-programming-practices

Suppose developers deliver features as quickly as possible without considering clean code principles at the beginning of the project. In that case, the system turns out messy, and touching even one line of code breaks the whole infrastructure. All developers should consider the below clean code principles to avoid gradual slowness.

## Speed
🟣 Go fast, if it goes well.

🟣 Do not be overconfident about you will clean the code up later to be fast you can right now.

🟣 Improve your coding skills by learning new concepts and making practices to be able to write code faster in long term.

🟣 Do not forget there is no way to write faster for tomorrow due to it is an ability that can be gained in long term.

## Functions
🟣 Do not add above two or three arguments in a function.

🟣 Do not pass hardly ever be 20 lines long in a function block.

🟣 Stay at one or two indent level in a function block for readability.

🟣 Make each function responsible for a single action.

🟣 Do not repeat yourself by gathering code snippets that have same purpose under a function.

💜 You should leverage objects or data structures when you need to pass more than three things into a function.

## Exceptions
🟣 Prefer exceptions instead of returning errors.

🟣 Avoid using nested track path blocks into the exception blocks.

## Comments
🟣 Try to explain your code itself without comment.

🟣 Try everything else then comment as a last resort because every use of a comment represents a failure.

🟣 Clean it before commenting when you write the bad code.

🟣 Do not forget comments do not make up for bad code.

🟣 Delete the useless comments in both your code and your teammates code.

🟣 Avoid leaving journal comments that contain historical changes on the codebase and leave this job to the version control systems.

🟣 Never talk about code that is somewhere else. If the code is changed, your comment will become a lie.

🟣 Do not comment for mandatory purposes such as having a rule that says that every function must have a Javadoc.

🟣 Avoid leaving ambiguous or unclear comments called mumble comments, as they can lead to confusion for other developers reviewing the code.

🟣 Do not leave commented-out code in the source code. It confuses future developers and version control systems.

🟣 Never talk about code that is somewhere else. If the code is changed, your comment will become a lie.

💜 No one usually wants to maintain comments.

💜 A good idea to have a comment that tells you what the regular expression is matching.

## Naming
🟣 Reveal your intent about variable, functions etc by naming descriptive.

🟣 Update the name when it that requires a comment does not reveal its intent.

🟣 Evaluate variable scope according to how many times it appears in naming. Long scope needs to more detailed name to remind you of usage well.

🟣 Variable names that are in a couple of lines of if statement, tiny while loop, or four lines long functions should be pretty short.

🟣 Global names have a huge scope and instance variables have a slightly huge scope in class. Their name should be long and descriptive.

🟣 Function and class names have an opposite naming approach than variable names. When a function or class scope is large, its name should shrink.

🟣 Avoid using noise words when naming like data, info etc. These names do not explain anything for us.

🟣 Do not name some functions with nearly same meaning as GetAccounts(), GetAccounts(), or GetAccountData()

## Security
🟣 Do not include confidential information like security credentials in the code. Take these credentials from trusted providers.

## Testing
🟣 Ensure the code works instead of guessing it works before you release it.

🟣 Be ready to deploy before iteration ends. It may not have enough features to deploy. However, this is a business decision.

🟣 Do not deploy your project by hoping there will be no error and if you did not test the code well, no error in prod within a time range does not show us it is okay.

🟣 Do not slow down as system gets older. You should be able to produce features with same rate at the whenever period of the project.

🟣 Leverage unit tests to be sure about your code.

🟣 Do not except the QA team find bugs in your code. They should find nothing.

🟣 Decouple the application from its tests. Changes made to the application should not impact the tests, ensuring that modifications can be made to either side independently.

🟣 Build APIs for tests you use for decoupling.

🟣 Do not forget the tests are part of the entire system.

🟣 Avoid from manual tests, automate them because the number of manual tests that are used will be decreased with time.

💜 It is common for the structure of the application code and the test code to differ, reflecting their distinct purposes and responsibilities.

💜 QA team is under the most stress between IT teams. They pass some tests due to stakeholder pressure. Therefore, we should not believe they guarantee code quality.

## Estimation
🟣 Give three honest deadline estimations from worst scenario to best scenario to your managers.

🟣 Say no if the answer is actually no without hesitating when your colleagues want you to commit something.

🟣 Refuse feature estimates that make the team slow in long-term because missing feature estimates cost you to slowness.

## File Structures
🟣 Try to stay under ~120 lines of code for each file.

🟣 Prefer 25-45 chars per line and try not to pass 80 chars if there is no necessity.

💜 You can limit the number of characters in a single line to 150 characters via IDE you use.

## Architecture
🟣 Make the maintenance effort constant for keeping systems well according to time.

🟣 Minimize the human resources required to build and maintain software systems.

🟣 Enable the architecture to accommodate changes in direct proportion to its level of scope.

🟣 Assert your authority about showing the importance of architecture when prioritising tasks due to stakeholders just care about requirements.

🟣 Do not forget stakeholders have no right to tell us what the architecture ought to be and say us to skip the architecture for getting a task done fast.

🟣 Defend what you believe without giving up against people that have a method to seek truth by testing people and trying to understand actually people know.

🟣 Be responsible for the importance, not the urgency that comes from stakeholders. *[Check out this page!](https://e-student.org/eisenhower-matrix/)
 
💜 If architecture comes last, cost will grow.

## General
🟣 Do not expect you to say that destroys our entire architecture when a small change comes up from customer.

🟣 Make software easily changeable to meet requirements in both today and tomorrow. This is not hardware and it comes from soft.

🟣 Make getting better your code with time, not worse.

💜 Software means that easily changeable products opposite to the hardware.

## Teamwork
🟣 Cover your teammates especially when they fail.

🟣 Prefer the pair programming with your teammates for active learning instead of making the code reviews.

🟣 Make the pair programming at few times a week as 30min or 1hr, no need to be planned.

🟣 Set branch and pull request rules to keep on track and stay updated for everyone's work.

🟣 Show fearless competence for cleaning bad code somebody else wrote it and do not afraid from if I break it, it will be yours.
