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
   | project manager |

</details>

## How to write a commit message

1) Commit message's title should not exceed 50.
2) Commit message's title in the form **Implementation Type** Implementation content
3) Implementation type of commit message's title is as follows :
   1) **Add** to add something that did not exist before.
   2) **Update** to improve the function of an existing one.
   3) **Refactory** to improve non-functionality of an existing one.
   4) **Rename** to changing the name of a file or directory, changing its location.
   5) **Fix** to fix correct an error.
   6) **Delete** to delete an existing one.
4) Implementation content of commit message's title are written semantically.
5) Description of commit message is written after a newline of 2 new lines below the title.
6) Description of commit message is written semantically about what the commit will do.
7) Here is an example of a commit message:

   > Add README.md  
   > 
   > Add a readme file from the repository.

## How to create an issue and pull request

### Common rules for creating issues and pull requests

1) Issue title must not exceed 50 characters(Github recommends title of 50 characters or less).
2) Issue title in the form **[Type of issue]** Issue content.
3) If issue title contains issue details, do not duplicate them. Example :
   - [ ] add: add README.md
   - [x] add: README.md
5) Issue content should be written semantically so that it can be inferred what kind of content it is. Example :
   - [ ] [BUG] Process of initial is not working
   - [x] [BUG] Initialization error due to dependency conflict in Package.json
6) Please fill in the description section of the issue form in accordance with the 5W1 principle.
7) Please fill out the reproduction method required by the form procedurally.
   1) Cloning repository
   2) Initialization project
   3) Test about successful execution
   4) ...

### Kind of issue

There are five types of issues(bug report, question, suggestion, implementation, test about implementation).
- *Bug report* is written when there is a problem in use. 
- *Question* are for non-bug questions.
- *Suggestion* is a suggestion for this project or repository.
- *Implementation* is an issue for contributors, and is used to track progress when there is content to be implemented.
- *Test about implementation* is an issue for contributors, and is used to track progress when there is test about implementation.

### How to create an issue

This is a guide on how to write an issue for each type of issue.

#### How to create issue about *Bug report*

*Bug report* is created when there is an error that occurred during use.

*Bug report* can be created in the following way:

1) Please fill in the title in the form of [BUG] Bug report content. Example : 
   - [BUG] Initialization error
2) Please add the type of bug to the label.
3) Please describe the bug in detail.
5) Please write about the environment in which the bug occurred.
6) Please bug me on how to reproduce it.
7) Write down what to expect when no bugs occur.
8) Please upload about the screenshot where the bug occurred.
9) If you have more to write about the bug, please write it.
10) If you have any references to the bug, please write.

#### How to create issue about *Question*

*Question* write when you have question other than bug.

*Question* can be written in the following way:

1) Please fill in the title in the form of [QUESTION] question content. Example :
   - [QUESTION] How to sync repository
2) Please add the type of question to the label.
3) Please describe the question in detail.
4) If the question requires information about the environment, write it down.
5) Please write down any alternatives you have tried before asking the question.
6) If you have anything else to write about the question, please do.
7) If you have any references to the question, please write.

#### How to create issue about *Suggestion*

*Suggestion* writes when you have plans to make a proposal to this project or repository.

*Suggestion* can be made in the following ways:

1) Please fill in the title in the form of [SUGGESTION] suggestion content. Example : 
   - [SUGGESTION] Improvements to the initialization experience
2) Please add the type of suggestion to the label.
3) Please describe the suggestion in detail.
4) If the suggestion requires information about the environment, write it down.
5) Please write down any alternatives you have tried before suggest.
6) If you have anything else to write about the suggestion, please do.
7) If you have any references to the suggestion, please write.

#### How to create issue about *Implementation*

*Implementation* is written when tracking progress(work progress and goals) towards implementing this project or repository.

*Implementation* can be written in the following way:

1) Please fill in the title in the form of [Kind of implement] Implement content. Example :
   - [REPOSITORY] Add issue template
2) Please add the type of implementation to the label.
3) Please describe what you are trying to solve with your implementation.
4) Write about implementation goals.
5) Write about the environment for implementation.
6) Write down task for implementation.
7) Please let me know if you have an alternative implementation.
8) If you have anything else to write about the implementation, please write it down.
9) If you have any references to the implementation, please write.

#### 구현 테스트에 대한 이슈(기여자용) 작성

*구현 테스트*는 이 프로젝트 혹은 저장소에 구현된 것에 대한 테스트 사항(테스트 진척도 및 목표)를 추적할 때 사용합니다.

구현은 다음과 같은 방법으로 작성하면 됩니다.

1) 제목에는 [테스트] 테스트 내용 양식으로 작성해주시기 바랍니다.
   - 예를 들어 : [저장소] 이슈 템플릿 추가
2) 구현 테스트 종류를 라벨에 추가해주시기 바랍니다.
3) 테스트 할 대상에 대해 설명 하십시오.
4) 구현 테스트 목표에 대해 적으십시오.
5) 구현 테스트를 위한 환경에 대해 적으십시오.
6) 구현 테스트를 위한 작업을 적으십시오.
7) 구현 테스트에 대해 추가로 작성할 내용이 있다면 적어주세요.
8) 구현에 대해 참고할 것이 있다면 적어주세요.

### 풀 리퀘스트 작성 방법

*풀 리퀘스트*로 저장소에 기여하고자 할 떄 다음과 같은 방법으로 작성해주시기 바랍니다.

1) 제목에는 *풀 리퀘스트로 하는 행동* 풀 리퀘스트 내용 양식으로 작성해주시기 바랍니다.
   - 예를 들어 : Add contributor code of conduct
2) 풀 리퀘스트로 하는 행동은 다음과 같습니다.
   1) **Add** to add something that did not exist before
   2) **Update** to improve the function of an existing one
   3) **Refactory** to improve non-functionality of an existing one
   4) **Rename** to changing the name of a file or directory, changing its location
   5) **Fix** to fix correct an error
   6) **Delete** to delete an existing one.
3) 풀 리퀘스트 작성 방식으로 작성된 예제:  
   Changed :  
     - Add README.md in repository
     - Update content Item in README.md
     - Refactory source for login method
     - Rename README.md to readme.md
     - Fix login error
     - Delete README.md

## 이슈 처리 방침 및 풀 리퀘스트 처리 방침

이슈 및 풀 리퀘스트를 처리하는 방침은 다음과 같습니다.

1) 담당자에게 이슈가 배정됩니다.
2) 담당자는 이 이슈가 유효한 이슈한 지, 이슈 유효성 체크리스트를 통해 확인합니다.
   - 이슈 유효성 체크리스트
      - [ ] 이 이슈가 이 프로젝트 혹은 저장소에 관한 이슈입니까?(아닌 경우 `is invalid` 라벨을 추가합니다)
      - [ ] 이 이슈가 중복 되었습니까?(아닌 경우 `is duplicated` 라벨을 추가합니다)
      - [ ] 이 이슈의 유형이 올바릅니까?(아닌 경우 `is incorrect type` 라벨을 추가합니다)
      - [ ] 이 이슈가 기여 가이드에 작성된 작성 방법에 따라 작성되었습니까?(아닌 경우 `is invalid format` 라벨을 추가합니다)
      - [ ] 이 이슈를 처리하는 데, 추가적인 정보가 필요합니까?(필요한 경우 'request more information` 라벨을 추가합니다)
      - [ ] 이 이슈는 처리하는 데, 논의가 필요합니까?(필요한 경우 `is under discussion` 라벨을 추가합니다)담당자는 이슈 유효성 체크리스트를 확인한 후 이슈를 처리하는 데 필요한 코멘트를 남깁니다.
3) 담당자는 이슈를 처리하는 데, 필요한 정보를 코멘트로 남겨 이슈 소유자에게 전달합니다.

## 이슈 및 풀 리퀘스트 담당자

<details>
<summary>Toggle the issue assigner list</summary>
   
   | <img src="https://user-images.githubusercontent.com/65880526/122337343-2f826800-cf79-11eb-879a-e5b3daa0c082.png" width="144" height="144">  |
   | :-------------: |
   | [jinseobhong](../../../../jinseobhong) |
   | project manager 

</details>
