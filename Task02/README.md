# Task 2: 가위, 바위, 보 게임 만들기 (Copilot Chat사용)

## Use case: 
- GitHub Copilot를 활용하여 가위, 바위, 보 게임을 만들고, 기본 게임에 추가적인 게임 로직을 추가하는 실습을 통해, Copilot의 활용도를 높입니다.

## 목표:
- Python으로 가위, 바위, 보 게임을 만듭니다.
- 게임을 실행하고 게임 결과를 출력합니다.
- 기본적인 가위, 바위, 보 게임 외에, Lizard, Spock 등의 확장판 게임을 추가합니다.
- Copilot Chat의 `Vision` 기능을 활용하여, 그림파일을 붙여넣기 하고, 이를 기반으로 코드를 제안받아 봅니다.
- Copilot Chat의 `Review and Comment` 기능을 활용하여, 코드에 대한 리뷰를 받아 봅니다.
- `Review and Comment`에 Custom instruction을 제공하여, 원하는 형태로 리뷰를 받아 봅니다.

## Step 1: 가위, 바위, 보 게임 만들기
- mygame.py 라는 파일을 신규로 생성합니다.   
  <img width="374" height="196" alt="image" src="https://github.com/user-attachments/assets/9e75816a-83bc-4641-81f9-cb251ec86bbe" />
- GitHub Copilot을 열어봅니다. 상단의 아이콘을 활용하거나 `'Ctrl + Alt + I'` 버튼을 이용합니다.   
  <img width="1392" height="409" alt="image" src="https://github.com/user-attachments/assets/7bdcc8a1-bfd0-41d9-863a-7fedc11e1402" />
- GitHub Copilot의 Mode를 'Agent' 모드로 변경합니다.   
  <img width="382" height="263" alt="image" src="https://github.com/user-attachments/assets/fe46f596-dc57-4759-a48e-a1e0d5a35648" />
- 현재 생성단 `mygame.py`을 참고하기 위해 '#'을 눌러서 mygame.py를 선택합니다. 코파일럿이 참고할 수 있도록 지정된 자료들은 상단에 표현됩니다.   
  <img width="239" height="100" alt="image" src="https://github.com/user-attachments/assets/c4a52c14-a00d-417f-9406-e9a6d15b5504" />

  
- 그리고 아래와 같은 프롬프트를 복사/붙여넣기 합니다.
   ```
      사용자와 간단하게 할 수 있는 가위바위보 게임을 만드려고 해.
      콘솔 앱으로 간단하게 만들어줬으면 좋겠고, 다음과 같은 조건을 지켜서 게임을 만들어 줘
      
      1) 사용자가 가위, 바위, 보 중 하나를 선택하고, 컴퓨터가 무작위로 선택한다.
      2) 사용자의 선택과 컴퓨터의 선택을 비교하여 승패를 결정한다.
      3) 사용자가 이기면, "이겼다 야호!", 컴퓨터가 이기면 "졌네..젠장", 마지막으로 비기게 된다면 "다시 한번 더!" 를 출력한다.
      4) 만약 비겼다면, 이기거나 질 때까지 게임이 반복되도록 한다.
      5) 사용자가 "그만" 이라고 입력하면 게임을 종료한다.
      6) 게임을 종료하기 전에는 그동안의 가위바위보 이력을 출력해 주고, 종료한다.
  ```
   <img width="721" height="511" alt="image" src="https://github.com/user-attachments/assets/cc6ef65a-7eb8-48fc-9b86-0ece130cd7ef" />

- GitHub Copilot이 생성한 소스코드를 확인하고, Keep 버튼을 눌러서 반영한다.
  <img width="1749" height="1435" alt="image" src="https://github.com/user-attachments/assets/6d2404ce-f7b1-410d-b7fb-18e573aa7527" />

- 다음과 같이 바로 테스트를 해 봅니다. 그리고 마지막에 '`그만`'을 입력해서 그동안 게임 승패 결과도 함께 확인합니다.
   <img width="1808" height="994" alt="image" src="https://github.com/user-attachments/assets/22c13261-a4cb-4f55-8519-d9ea12b8fb20" />





## Step 2 : Lizard, Spock 추가하기
- 만들어진 게임에 추가로 Lizard, Spock의 로직을 Copilot을 활용하여 추가합니다.<br>
   <img src="img/image.png" width="600"><br>
- `choices` 리스트에 Lizard와 Spock을 추가합니다.<br>
    <img src="img/03.png" alt="image" width="400"/><br>

- Copilot Chat에 위 그림파일을 복사하여 Copilot Chat에 붙여넣기 합니다.<br>
    <img src="img/04.png" alt="image" width="400"/><br>
    <img src="img/05.png" alt="image" width="400"/><br>

- Copilot Chat에 붙여넣기 한 그림파일 'Pasted Image'가 있음을 확인합니다.<br>
    <img src="img/06.png" alt="image" width="300"/><br>

- Copilot Chat에 `그림파일데로 Lizard, Spock을 추가해 주세요` 라고 요청합니다.<br>
    <img src="img/07.png" alt="image" width="300"/><br>

- Copilot Chat에서 제안된 코드를 확인합니다.<br>
    <img src="img/08.png" alt="image" width="500"/><br>

- Copilot Chat에서 `Apply to file` 버튼을 클릭하여, 제안된 코드를 적용합니다.<br>
    <img src="img/09.png" alt="image" width="300"/><br>

- 필요시 미진한 코드를 추가하고 실행해 봅니다.<br>
    <img src="img/10.png" alt="image" width="400"/><br>

## Step 3: Review and Comment 사용해 보기
- 마우스 오른 버튼을 클릭하여, `Review and Comment` 기능을 사용하여, 코드에 대한 리뷰를 받아 봅니다.<br>
    <img src="img/11.png" alt="image" width="500"/><br>

    <img src="img/12.png" alt="image" width="600"/><br>

- 아래 절차데로 `Review and Comment`에 대한 `Custom instructions`을 설정해 봅니다.<br>
  - Ctrl + Shift + P를 눌러서 명령 팔레트를 엽니다.<br>
  - `Workspace settings(JSON)`을 선택합니다.<br>
    <img src="img/13.png" alt="image" width="400"/><br>

  - JSON 파일에 아래와 옵션을 추가하고 아래 예제와 같이 입력합니다.<br>
    - `"github.copilot.chat.reviewSelection.instructions"`<br>
    <img src="img/14.png" alt="image" width="400"/><br>
    - ` "함수의 이름은 '_'로 시작하고, 변수 네이밍 규칙과 동일하게 작성합니다. 클래스와 생성자의 이름은 파스칼케이스(PascalCase)를 사용합니다. 들여쓰기는 스페이스 2개로 한다."`<br>

   - 다시 한번 `Review and Comment` 기능을 사용하여, 코드에 대한 리뷰를 받아 봅니다.<br>
    <img src="img/15.png" alt="image" width="600"/><br>

## 지식 확인:
- 코드 완성 기능과, Copilot Chat 기능의 차이점
- Vision 기능으로 가능한 다른 활용법
- Copilot Chat의 `Review and Comment` 기능과 custom instruction을 활용하여, 원하는 형태로 리뷰를 받아 보는 방법
