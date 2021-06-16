# 기여에 대하여

우선 기여를 해주시려는 모든 분들에게 감사드립니다. 이 기여 가이드에서는 이슈 및 풀 리퀘스트의 작성 방법에 대해 다룹니다. 먼저, 기여를 하기 전에 다음 유의사항을 지켜주시기 바랍니다.

- 이 프로젝트 혹은 저장소에 속하지 않는 이슈에 대해서는 작성하지 마세요.
- 이 프로젝트를 구성하는 다른 저장소의 이슈에 관해서는 해당하는 저장소에 이슈를 등록해주시기 바랍니다.
- 이 기여 가이드에 맞지 않게 작성된 이슈에 대해서는 답변을 보장하지 않습니다.

## 이슈

### 이슈 종류

이슈의 종류는 총 다섯 가지(버그 리포트 , 질문, 제안, 구현, 구현 테스트)로 되어있습니다. `버그 리포트`는 사용 상 문제가 생겼을 경우 작성합니다. `질문`은 버그 외 질문 사항에 대해 작성합니다. `제안`은 이 프로젝트 혹은 저장소에 대해 제안입니다. `구현`은 기여자를 위한 이슈로, 구현하고자 하는 내용이 있을 때 진행사항을 추적하는 용도로 사용합니다. `구현 테스트`는 구현한 것에 대한 테스트를 작성하기 위한 이슈입니다. 구현 및 구현 테스트에 대한 이슈 템플릿은 공동 기여자로 등록됬을 경우 사용할 수 있습니다.

### 이슈 작성 방법

각 이슈의 종류에 따른 이슈 작성 방법에 대한 안내입니다.

#### 버그 리포트 작성

`버그 리포트`는 사용 중 발생한 오류가 있을 때 작성합니다. 

버그 리포트는 다음과 같은 방법으로 작성하면 됩니다.

1) 제목에는 [BUG] Bug report content 양식으로 작성해주시기 바랍니다.
   - 예를 들어 : [BUG] 초기화 오류
2) 버그가 해당되는 종류를 라벨에 추가해주시기 바랍니다.
3) 버그에 대해 자세히 설명해주세요.
5) 버그가 발생한 환경에 대해 적어주세요.
6) 버그를 재현하는 방법에 대해 적어주세요.
7) 버그가 일어나지 않았을 경우 예상됬던 것에 대해 적어주세요.
8) 버그가 일어난 스크린샷에 대해 적어주세요.
9) 버그에 대해 추가로 작성할 내용이 있다면 적어주세요.
10) 버그에 대해 참고할 것이 있다면 적어주세요.

#### 질문에 대한 이슈 작성

`질문`은 버그 외 질문 사항이 있을 때 작성합니다.

질문은 다음과 같은 방법으로 작성하면 됩니다.

1) 제목에는 [질문] 질문할 내용 양식으로 작성해주시기 바랍니다.
   - 예를 들어 : [질문] 저장소 사용방법에 대한 질문
2) 질문에 해당되는 종류를 라벨에 추가해주시기 바랍니다.
3) 무엇을 질문하는 지에 대해 설명해주시기 바랍니다.
4) 질문에 환경에 대한 정보가 필요하다면 적어주세요.
5) 질문을 하기 전 해본 대안사항이 있다면 적어주세요.
6) 질문에 대해 추가로 작성할 내용이 있다면 적어주세요.
7) 질문에 대해 참고할 것이 있다면 적어주세요.

#### 제안에 대한 이슈 작성 

`제안`은 이 프로젝트 혹은 저장소에 제안할 것이 있을 때 작성합니다.

제안은 다음과 같은 방법으로 작성하면 됩니다.
1) 제목에는 [제안] 제안할 내용 양식으로 작성해주시기 바랍니다.
   - 예를 들어 : [제안] 이슈 템플릿에 대한 개선 사항
2) 제안에 해당하는 종류를 라벨에 추가해주시기 바랍니다.
3) 제안으로 해결하고 자 하는 것을 적어주시기 바랍니다.
4) 제안에 환경에 대한 정보가 필요하다면 적어주세요.
5) 이 제안하기 전에 시도했던 해결 방법이 있다면 적어주세요.
6) 제안에 대해 추가로 작성할 내용이 있다면 적어주세요.
7) 제안에 대해 참고할 것이 있다면 적어주세요.
8) 제안에 대해 

#### 구현에 대한 이슈(기여자용) 작성

#### 구현 테스트에 대한 이슈 작성

## 풀 리퀘스트 요청

### 풀 리퀘스트 전에 확인 사항

### 풀 리퀘스트 리뷰 담당자의 확인 사항

Rule of writing pull request :

Please write the change history as follows:
[Behavior of pull request] [Contents of pull request]
Change history should not exceed 50 characters(Github recommends writing titles with no more than 50 characters)
Write your title label like this:
Add to add something that did not exist before, Update to improve the function of an existing one, Refactory to improve non-functionality of an existing one, Rename to changing the name of a file or directory, changing its location, Fix to fix correct an error, and Delete to delete an existing one.
If the title already contains a corresponding action, do not duplicate it.
 add: add README.md
 Add README.md
example :
Add README.md in repository
Update content Item in README.md
Refactory source for login method
Rename README.md to readme.md
Fix login error
Delete README.md


