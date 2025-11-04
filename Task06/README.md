# Task 6: 코드 리팩토링, 보안 문제 확인

### Use case: 
- GitHub Copilot를 활용하여 코드 리팩토링을 진행합니다.

### 목표:
- GitHub Copilot Chat을 활용해 코드를 리팩토링 하는 예제를 실습합니다.
- GitHub Copilot Chat을 활용해 문제점을 찾고, 해결 방법을 제안 받습니다.

## Steps 1:
- [getDiscoun.py](src/getDiscount.py) 파일의 블럭을 선택하고, GitHub Copilot Chat에 리팩토링을 요청합니다.
  - 프롬프트 예시 : `이 코드를 성능 관점에서 리팩토링 해줘`

- [PetController.java](src/PetController.java) 파일의 `99-113 라인` 블럭을 선택하고, GitHub Copilot Chat에 리팩토링을 요청합니다.
  - 프롬프트 예시 : `구조적인 관점에서 기능별 분리하는 리팩토링 해줘`
  
- [vulnerableserver.js](src/vulnerableserver.js) 파일의 코드 블럭을 선택하고, 해당 블럭에 대한 보안 문제점을 Copilot Chat에게 질문합니다.
  - 프롬프트 예시 : `이 코드에서 보안 문제점이 있는지 확인해줘`, `이 코드의 개선할 부분 있으면 제안해줘`

## Step 2:
- 코드 내 Inline Copilot Chat 사용해 봅니다.
- 원하는 코드를 블록한 후 `Ctrl + I` 혹은 마우스 우클릭 후 `Open Inline Chat` 을 누릅니다.   
  <img width="693" height="436" alt="image" src="https://github.com/user-attachments/assets/f8f082b3-aaf3-4062-a9cb-b62f884aed3f" />
- 이후 원하는 내용을 입력해서 작업합니다.   
  <img width="573" height="303" alt="image" src="https://github.com/user-attachments/assets/74a50564-ec9b-4af3-aeab-82f41fb1b284" />

## 이번 핸즈온에서 기억해야 할 것은?
- GitHub Copilot을 다양한 작업을 위해 사용할 수 있는 아이디어를 얻어갑니다.
- 일반 챗이 아닌, 블록 후 간단하게 사용할 수 있는 Inline Chat 기능을 사용해 봅니다.

## 추가자료
  - [다양한 GitHub Copilot 사용에 대한 가이드](https://docs.github.com/ko/enterprise-cloud@latest/copilot/using-github-copilot/guides-on-using-github-copilot)
  - [GitHub Copilot을 이용해 리팩토링 하는법](https://github.blog/ai-and-ml/github-copilot/how-to-refactor-code-with-github-copilot/)
  - [GitHub Copilot과 함께 디버그](https://github.blog/ai-and-ml/github-copilot/how-to-debug-code-with-github-copilot/)
  - [10 Unexpected Ways to Use Github Copilot](https://github.blog/2024-01-22-10-unexpected-ways-to-use-github-copilot/)

## 다음은?
- 처음으로 돌아가려면? [여기로 이동하세요](https://github.com/ChangJu-Ahn/CopoilotWorkshop-VSCode-Changju-Custom)
- 이전 실습은? [여기로 이동하세요](https://github.com/ChangJu-Ahn/CopoilotWorkshop-VSCode-Changju-Custom/blob/main/Task05/README.md) - Task 5: 프롬프트와 컨텍스트 사용
- 다음 실습은? [여기로 이동하세요](https://github.com/ChangJu-Ahn/CopoilotWorkshop-VSCode-Changju-Custom/blob/main/Task07/README.md) - Task 7: MCP (Model Context Protocol) 활용 실습
  

