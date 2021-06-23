# About Contribution

Thank you to everyone who would like to contribute. This attribution guide covers **How to write a commit message** and **How to create an issue and pull request** and **Processing policy for issues and pull Requests**. First, please check the following **Notes** before making a contribution.

- Do not write about issues that do not belong to this project or repository.
- Before writing an issue, search for similar issues already exist in this project or repository.
- If it is an issue from another repository that makes up this project, please register the issue in that repository.
- We do not guarantee answers to issues written inconsistently with this contribution guide.

## Contributor

<details>
<summary>Toggle the contributor list</summary>
   
   | <img src="https://user-images.githubusercontent.com/65880526/122337343-2f826800-cf79-11eb-879a-e5b3daa0c082.png" width="144" height="144">  |
   | :-------------: |
   | [jinseobhong](https://github.com/jinseobhong) |
   | Project manager |

</details>

## How to write a commit message

1) Commit message's title should not exceed 50.
2) Commit message's title in the form **Type of action** content about action.
3) Type of action is as follows :
   1) **Add** to add something that did not exist before.
   2) **Update** to improve the function of an existing one.
   3) **Re-factory** to improve non-functionality of an existing one.
   4) **Rename** to changing the name of a file or directory, changing its location.
   5) **Fix** to fix correct an error.
   6) **Delete** to delete an existing one.
4) Content about taskare written semantically.
5) Description of commit message is written after a newline of 2 new lines below the title.
6) Description of commit message is written semantically about what the commit will do.
7) Here is an example of a commit message:
   > Add README.md  
   > 
   > Add a readme file from the repository.
   
## How to create an issue and pull request

### Common rules for creating issues and pull requests

1) Issue title must not exceed 50 characters(Github recommends title of 50 characters or less). 
2) Issue title in the form **[Type of issue]** content about issue.
3) Actions in messages must not be nested. Example :
   - [ ] [BUG] Bug initialization
   - [x] [BUG] Initialization about repository
4) Content about issue should be written semantically so that it can be inferred what kind of content it is. Example :
   - [ ] [BUG] Process of initial is not working
   - [x] [BUG] Initialization error due to dependency conflict in Package.json
5) Please fill in the description section of the issue form in accordance with the 5W1 principle.
6) Please fill out the reproduction method required by the form procedurally.
   1) Cloning repository
   2) Initialization project
   3) Test about successful execution
   4) ...

### Kind of issue

There are five types of issue.
- *Bug report* is written when there is a problem in use. 
- *Question about something* are for non-bug questions.
- *Suggest for this project* is a suggestion for this project or repository.
- *Task* is an issue for contributors, and is used to track progress when there is content to be implemented.
- *Test for task* is an issue for contributors, and is used to track progress when there is test about task.

### How to create an issue

This is a guide on how to write an issue for each type of issue.

#### How to create issue about *Bug report*

*Bug report* is created when there is an error that occurred during use.

*Bug report* can be created in the following way:

1) Please fill in the title in the form of [BUG] content about bug. Example : 
   - [BUG] Initialization error
2) Please add the type of bug to the label.
   - label list:
     - `Environment`
     - `Feature`
     - `etc`
4) Please describe the bug in detail.
5) Please write about the environment in which the bug occurred.
6) Please bug me on how to reproduce it.
7) Write down what to expect when no bugs occur.
8) Please upload about the screenshot where the bug occurred.
9) If you have more to write about the bug, please write it.
10) If you have any references to the bug, please write.

#### How to create issue about *Question about something*

*Question about something* write when you have question other than bug.

*Question about something* can be written in the following way :

1) Please fill in the title in the form of [QUESTION] content about question. Example :
   - [QUESTION] How to sync repository
2) Please add the type of question to the label.
   - label list :
     - Documentation
     - Environment
     - Feature
     - etc
4) Please describe the question in detail.
5) If the question requires information about the environment, write it down.
6) Please write down any alternatives you have tried before asking the question.
7) If you have anything else to write about the question, please do.
8) If you have any references to the question, please write.

#### How to create issue about *Suggest for this project*

*Suggest for this project* writes when you have plans to make a proposal to this project or repository.

*Suggest for this project* can be made in the following ways:

1) Please fill in the title in the form of [SUGGESTION] content about suggestion. Example : 
   - [SUGGESTION] Improvements to the initialization experience
2) Please add the type of suggestion to the label.
   - label list:
     - `Documentation`
     - `Environment`
     - `Feature`
     - `Re-factory`
     - `etc`
4) Please describe the suggestion in detail.
5) If the suggestion requires information about the environment, write it down.
6) Please write down any alternatives you have tried before suggest.
7) If you have anything else to write about the suggestion, please do.
8) If you have any references to the suggestion, please write.

#### How to create issue about *Task*

*Task* is written when tracking progress(progress of task and goals) towards implementing this project or repository.

*Task* can be written in the following way:

1) Please fill in the title in the form of [Kind of implement] content about implement. Example :
   - [REPOSITORY] Add issue template
2) Please add the type of task to the label.
   - label list:
     - Documentation
     - Environment
     - Feature
     - Fix
     - Re-factory
     - Repository
     - etc
4) Please describe what you are trying to solve with your task.
5) Write about task goals.
6) Write about the environment for task.
7) Write down task for task.
8) Please let me know if you have an alternative task.
9) If you have anything else to write about the task, please write it down.
10) If you have any references to the task, please write.

#### How to create issue about *Test for task*

*Test for task* is used to track tests(progress of task and goals) for what is implemented in this project or repository.

*Test for task* can be written in the following way:

1) Please fill in the title in the form of [TEST] content about test. Example :
   - [TEST] Successful execution about initiazation
2) Please add the type of test to the label.
   - label list : 
     - `Environment`
     - `Feature`
     - `Fix`
     - `Re-factory`
     - `etc` 
4) Describes what to test.
5) Write about test goals.
6) Write about the environment for test.
7) Write down your task to test.
8) Write down describe about testing.
9) If you have any references to the test, please write.

### How to create *Pull request*

If you would like to contribute to the repository as a *Pull request*, please write it in the following way.

1) Please fill in the title in the form of [Action of pull request] content about pull request. Example :
   - Add contributor code of conduct
2) The actions taken with a pull request are as follows :
   1) **Add** to add something that did not exist before
   2) **Update** to improve the function of an existing one
   3) **Refactory** to improve non-functionality of an existing one
   4) **Rename** to 7) Write your own code review checklistchanging the name of a file or directory, changing its location
   5) **Fix** to fix correct an error
   6) **Delete** to delete an existing one.
3) Please add the type of action of pull request to the label.
4) Write the related issues as follows :
   - close #1
   - close #2
5) Write a description of the requested change as follows(Please make changes based on the action type written in item 2) :
- Changed :
  - Add README.md in repository
  - Update content Item in README.md
  - Re-factory source for login method
  - Rename README.md to readme.md
  - Fix login error
  - Delete README.md
7) Fill out a checklist Checklist self-code review
8) Fill out a checklist before requesting a pull

## Processing policy for issues and pull request

The policy for handling issues and pull requests is as follows.

1) The issue is assignIs this issue the correct type?son in charge.
2) The person in charge checks whether this issue is a valid issue through the issue validity checklist.
   - Issue validation checklist
      - [ ] Is this issue belong to this repository or project?(If not, add the label `is invalid`)
      - [ ] Is this issue a duplicate?(If not, add the label `is duplicated`)
      - [ ] Is this issue the correct type?(If not, add the label `is incorrect type`)
      - [ ] Is this issue create according to how it is create in the contribution guide?(If not, add the label `is invalid format`)
      - [ ] Do you need additional information to address this issue?(Add `request more information` label if needed)
      - [ ] Need a discussion to resolve this issue?(Add the `is under discussion` label if needed)
3) The person in charge passes the necessary information to the issue owner by leaving a comment to handle the issue.

## Issue and Pull Request Personnel

<details>
<summary>Toggle the issue assigner list</summary>
   
   | <img src="https://user-images.githubusercontent.com/65880526/122337343-2f826800-cf79-11eb-879a-e5b3daa0c082.png" width="144" height="144">  |
   | :-------------: |
   | [jinseobhong](https://github.com/jinseobhong) |
   | Project manager |

</details>
