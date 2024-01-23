# SUPP1
내일배움캠프 타운 만들기

# 구현 기능
* 필수 요구 사항 - 캐릭터 만들기, 캐릭터 이동, 방 만들기, 카메라 따라가기, 캐릭터 애니메이션 추가, 이름 입력 시스템, 캐릭터 선택 시스템
* 선택 요구 사항 - 시간 표시, 인게임 이름 바꾸기, 참석 인원 UI(미완성), 인게임 캐릭터 선택, NPC 대화(미완성)

# CS 구성
* AimRotation : 캐릭터 모습 방향 바꾸기
* CameraController : 카메라가 캐릭터 위치로 따라다니기
* CharacterController : 캐릭터 이벤트 생성
* CharManager : 선택한 캐릭터 StartScene에 불러오기, 캐릭터 변경 및 창 온오프
* GameManager : 캐릭터 선택 온오프와 선택한 캐릭터 인덱스 값 저장
* JoinButton : 입력한 이름 설정하기, 씬 불러오기
* Movement : 캐릭터 움직임 적용
* NameInput : 이름 가져와서 할당해주기
* PlayerInputController : 캐릭터 이동, 시선 입력
* TimeManager : 현재시간 분 나타내기
* UIManager : 이름 바꾸기, 이름바꾸기 버튼, 참가자 버튼 온오프
* NPCTalking : NPC에게 가까이 가면 대화시작 창 뜨기, 대화창 온오프

