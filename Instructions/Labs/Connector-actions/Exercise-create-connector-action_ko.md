실습: 커넥터 액션 생성하기

이 실습에서 배우는 내용:

Copilot Studio에서 커넥터 액션 생성하기

Microsoft Teams에서 커넥터 액션 테스트하기

커넥터 액션 저장 및 게시하기

작업 1: Copilot Studio에서 커넥터 액션 생성하기

이 작업에서는 MSN Weather 커넥터의 커넥터 액션을 구성합니다.

Copilot Studio로 이동하여 회사 또는 학교 계정으로 로그인합니다. 필요한 경우 환영 메시지는 건너뜁니다.

참고: Copilot Studio를 처음 열면 챗 인터페이스가 표시될 수 있습니다. 이 경우 오른쪽 상단의 …(더보기) 메뉴를 선택한 후 **Copilot 생성 취소(Cancel copilot creation)**를 선택하여 챗 인터페이스를 종료하고 Copilot Studio 홈 페이지로 이동하세요.

왼쪽 탐색 메뉴에서 **라이브러리(Library)**를 선택합니다. 여기에서 기존 액션과 커넥터 목록을 확인하고 새 항목을 생성할 수 있습니다.

화면 상단의 **항목 추가(Add an item)**를 선택합니다. Copilot for Microsoft 365 확장 옵션이 두 개 표시됩니다.
:::image type="content" source="../Media/extend copilot options.png" alt-text="Copilot 확장 옵션을 보여주는 창. 'Copilot 생성'과 '액션 생성' 중 선택 가능":::

**새로운 액션(New action)**을 선택합니다.

**커넥터(Connector)**를 선택하여 커넥터 액션을 설정하는 마법사를 엽니다.

MSN Weather를 커넥터로 선택합니다.

**설명 검토(Review the description)**를 진행합니다.

중요:
이 설명은 Copilot이 사용자 메시지를 플러그인과 매칭할 때 사용됩니다. 설명이 명확하지 않으면 Copilot이 커넥터 액션을 올바르게 실행하지 못할 수 있습니다.

**다음(Next)**을 선택합니다.

현재 날씨 가져오기(Get current weather) 액션을 선택합니다.

**액션 설명 검토(Review the action description)**를 진행합니다.

중요:
Copilot이 올바른 액션을 실행하려면 액션 설명이 명확해야 합니다. 설명이 부정확하면 Copilot이 잘못된 액션을 실행할 수 있습니다.

**다음(Next)**을 선택합니다.

**입력 및 출력 설명 검토(Review the descriptions of all the inputs and outputs)**를 진행합니다.

중요:
Copilot이 정확한 입력값을 받아 실행하고, 올바른 출력을 생성하도록 입력 및 출력 설명이 명확해야 합니다.

**다음(Next)**을 선택합니다.

추가적인 액션을 설정할 수 있는 화면이 나타나지만, 이번 실습에서는 **건너뛰기(Skip)**하고 **다음(Next)**을 선택합니다.

작업 2: Microsoft Teams에서 커넥터 액션 테스트하기

이 작업에서는 Microsoft 365 Copilot에서 구성한 커넥터 액션을 테스트합니다.



기존 연결이 있으면 선택하고, 없으면 **새로운 연결(New connection)**을 선택하여 MSN Weather 커넥터의 새 연결을 생성합니다.

새로운 연결(New connection) 메뉴에서 **생성(Create)**을 선택합니다.

선택한 연결(Selected connection) 섹션에서 방금 만든 연결을 선택합니다.

액션 테스트(Test action) 버튼을 선택합니다.

참고:
이 과정에서 커넥터 액션이 Microsoft Teams에 배포됩니다.

**테스트 열기(Open to test)**를 선택하여 테스트를 진행합니다.

참고:
새 브라우저 탭이 열리며 Microsoft Teams가 실행됩니다.

Teams 실행 팝업이 나타나면 **취소(Cancel)**를 선택합니다.

**웹 앱 사용(Use the web app instead)**을 선택합니다.

참고:
Microsoft Teams에서 Microsoft 365 Copilot이 실행됩니다.

Teams의 Copilot 메시지 입력창에서 플러그인(plugin) 아이콘을 선택합니다.

Test-MSN Weather 플러그인을 찾아 **토글을 활성화(Enable toggle)**합니다.

참고:
다음과 같은 메시지가 표시됩니다.


Microsoft 365 Copilot에 다음 메시지를 입력하여 테스트합니다.

What is the current weather in <your location> in <celsius/fahrenheit> according to MSN Weather?

Copilot이 플러그인을 사용하여 응답을 제공하면 성공적으로 실행된 것입니다.



참고: Copilot이 플러그인을 사용하기 전에 권한을 요청할 수 있습니다. 이 경우 **항상 허용(Always allow)**을 선택하여 Copilot이 플러그인을 사용할 수 있도록 설정하세요.

:::image type="content" source="../Media/test-msn-weather-allow.png" alt-text="Copilot이 플러그인 사용을 요청하는 화면.":::

작업 3: 커넥터 액션 저장 및 게시하기

이 작업에서는 커넥터 액션을 저장하고 게시합니다.

Copilot Studio에서 진행을 계속합니다.

마법사에서 **다음(Next)**을 선택하면 커넥터 액션이 게시됩니다.

참고:
다음 화면에서는 세부 정보 페이지로 이동하거나 저장 후 닫을 수 있습니다. 액션이 Copilot 환경에 표시되기까지 몇 분이 걸릴 수 있습니다.



**저장 및 닫기(Save and Close)**를 선택합니다.

이제 커넥터 액션이 구성 및 게시되었습니다.
