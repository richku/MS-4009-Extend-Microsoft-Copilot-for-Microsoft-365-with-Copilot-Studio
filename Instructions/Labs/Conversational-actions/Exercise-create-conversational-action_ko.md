Exercise: Create a conversational action

이 실습에서는 "Project ABC"라는 가상의 조직 프로젝트에 대한 정보를 제공하는 대화형 액션을 생성합니다.

실습 목표

Copilot Studio에서 대화형 액션 생성하기

Microsoft Copilot에 대화형 액션 게시하기

Microsoft Copilot에서 대화형 액션 테스트하기

작업 1: (선택 사항) 기본 환경 테스트하기

Microsoft Teams를 열고 직장 또는 학교 계정으로 로그인합니다.

왼쪽 사이드바에서 **채팅(Chat)**을 선택합니다.

Copilot을 선택합니다.

메시지 입력란에 다음을 입력합니다.

Who should I contact for questions about Project ABC?

현재 Microsoft 365 Copilot이 Project ABC에 대한 정보를 제공하지 않는 것을 확인합니다.

작업 2: 새로운 대화형 액션 생성하기

Copilot Studio에 접속하고 직장 또는 학교 계정으로 로그인합니다.

**환영 메시지(Welcoming messages)**가 표시되면 **건너뛰기(Skip)**를 선택합니다.

왼쪽 메뉴에서 **라이브러리(Library)**를 선택합니다.

상단에서 **항목 추가(Add an item)**를 선택합니다.

**새로운 액션(New action)**을 선택합니다.

**대화형(Conversational)**을 선택하여 대화형 액션을 생성합니다.

이름(Name) 필드에 Project ABC를 입력하고 기본 솔루션과 스키마를 유지합니다.

**생성(Create)**을 선택하여 진행합니다.

작업 3: 주제 구성하기

대화형 액션의 주제(Topics) 탭으로 이동합니다.

기본값인 "Untitled" 제목을 Project ABC info로 변경합니다.

트리거(Trigger) 노드의 텍스트 상자에서 Project ABC에 대한 정보를 제공하며, 목표, 담당자 및 롤아웃 일정에 대한 질문에 답변합니다.를 입력합니다.

작업 4: 메시지 보내기

트리거(Trigger) 노드 아래에서 + 아이콘을 선택하여 새로운 노드를 추가합니다.

**메시지 보내기(Send a message)**를 선택합니다.

메시지 노드의 텍스트 상자에 다음 메시지를 입력합니다.

Project ABC는 회사의 문화와 참여도를 향상시키기 위한 이니셔티브입니다. 
프로젝트 목표는 직원 사기 향상, 직원 설문조사 결과 개선 및 문화 평가 개선입니다. 
Project ABC에 대한 추가 정보는 Devon Torres에게 문의하세요.

**저장(Save)**을 선택하여 변경 사항을 저장합니다.

작업 5: 액션 게시하기

페이지 상단에서 **게시(Publish)**를 선택합니다.

플러그인 게시(Publish Plugin) 페이지에서 **게시(Publish)**를 선택합니다.

최신 콘텐츠 게시(Publish latest content?) 페이지에서 Project ABC Info 플러그인이 활성화되었는지 확인한 후 **게시(Publish)**를 선택합니다.

게시 완료 후 상단에 알림이 표시됩니다.

작업 6: 액션 활성화 및 테스트하기

Microsoft Teams를 엽니다.

왼쪽 사이드바에서 **채팅(Chat)**을 선택합니다.

Copilot을 선택합니다.

메시지 입력 영역에서 Copilot 응답 관리(Manage Copilot response) 버튼을 선택합니다.

표시된 메뉴에서 Copilot Studio를 검색한 후 **추가(Add)**를 선택합니다.

Project ABC info 액션이 목록에 나타나는지 확인한 후 **활성화(Enable)**합니다.

창을 닫고 메시지 입력란에 다음을 입력합니다.

Who should I contact for questions about Project ABC?

Microsoft 365 Copilot이 Project ABC에 대한 정보를 제공하면 성공적으로 실행된 것입니다.

(선택 사항) 도전 과제: 직접 만들어보기

이 실습에서 배운 내용을 활용하여 새로운 대화형 액션을 만들어보세요. Copilot Studio에서 설정하고 게시하며 테스트하는 과정을 연습해 보세요.

참고:

Copilot은 응답을 자체 스타일로 재작성할 수 있습니다.

대화형 액션의 설명이 중요합니다. 설명이 명확할수록 Copilot이 정확한 응답을 제공할 확률이 높아집니다.

Copilot이 플러그인을 호출할지 여부는 다를 수 있으며, 예상 결과가 항상 나오는 것은 아닙니다.
