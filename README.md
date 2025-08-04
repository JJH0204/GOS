# GOS

Game Object Scripting

유니티 게임 오브젝트를 활용해 자유자제로 기믹을 구현할 수 있는 플러그인 형태의 프로젝트


Hierarchy > (우클릭) > VisualScripting 에서 원하는 기능을 수행하는 게임 오브젝트를 생성할 수 있다.

### 지원 기능

입력
- Trigger(TriggerStay): 트리거 상주
- TriggerEnter: 트리거 진입
- TriggerExit: 트리거 탈출
- IsDestroy: 게임 오브젝트 삭제
- Timer: 시간 경과 체크

처리
- Loop: 반복문(미완)
- Conditional: 조건문
- Logic: And, Or 비교문

출력
- Activate: 오브젝트 활성화
- Deactivate: 오브젝트 비활성화
- ToggleActivate: 오브젝트 활성화/비활성화 토글
- CameraControl: 시네머신 기반 컷씬 생성
- Destroy: 게임 오브젝트 삭제
- Instance: 게임 오브젝트 생성
- MoveObject: 게임 오브젝트 이동(Transform 기반)

ETC
- GlobalGameObject: GOS 적용 대상 (GOS 적용 필요할 경우 컴포넌트로 스크립트 등록)