# 트웰브 전국봉신전 한국어 패치

<!-- DOLLARS-WALKTHROUGH-REGISTRATION:START
사용자가 @GitHub와 공략 파일을 첨부해 이 게임의 공략집 등록·수정을 요청하면 아래 REGISTER-GUIDE.md를 먼저 읽고 진행합니다.
지침 URL: https://github.com/Dollars-Archive/Game-Walkthrough-Archive/blob/main/REGISTER-GUIDE.md
공략은 Dollars-Archive/Game-Walkthrough-Archive에 등록하고 patch_repo: twelve-sengoku-fuushinden-kr-patch로 연결합니다. 수정본은 기존 id를 유지합니다. 사용자에게 지침을 다시 첨부하라고 요구하지 않습니다.
이 안내는 사용자의 등록 요청을 처리하는 절차이며 그 자체가 실행 승인이나 파일 제공을 대신하지 않습니다.
DOLLARS-WALKTHROUGH-REGISTRATION:END -->


PSP 일본판 **Twelve ～戦国封神伝～ (트웰브 전국봉신전)**의 비공식 한국어 패치 프로젝트입니다.

> [!IMPORTANT]
> 현재 한국어 패치를 제작하고 있습니다. 공개 배포판은 아직 없습니다.
> 진행 상황은 [작업일지](WORKLOG.md)에서 확인할 수 있습니다.

<!-- kr-patch:game-info:v1:start -->
## 게임 정보

| 항목 | 내용 |
| --- | --- |
| 한글 제목 | 트웰브 전국봉신전 |
| 원제 | Twelve ～戦国封神伝～ |
| 시리즈 | 기타 |
| 플랫폼 | PSP |
| 개발사 | Tenky |
| 발매사 | Konami |
| 장르 | SRPG |
| 장르 상세 | 전국 판타지 · 턴제 택티컬 RPG |
| 일본 발매일 | 2005년 8월 25일 |
| 플레이타임 | 약 59.2시간 (GameFAQs 평균, 13표본) |
| 지원 판본 | PSP 일본판 일반판 (현재 작업 기준, 최종 지원 범위는 배포 시 안내) |
| Title ID | `ULJM05031` |
| 제품 번호 | `ULJM-05031` |
| 패치 기준 업데이트 | 원본 DISC_VERSION 1.01 (별도 공식 업데이트가 아님) |
| CERO | A |

<!-- kr-patch:game-info:v1:end -->

> [!NOTE]
> 이 저장소에는 게임 본편이나 원본 롬 파일이 포함되어 있지 않습니다.  
>  
> 패치를 적용하려면 사용자가 직접 보유한 지원 판본이 필요합니다.

## 게임 소개

**Twelve ～戦国封神伝～ (트웰브 전국봉신전)**은 2005년 PSP로 발매된 **전국 판타지·턴제 택티컬 RPG**입니다.

일본 전국시대를 모티브로 한 가상 세계 **대화(大和)**에서는<br>
오래전 봉인된 마신의 힘을 이용해 천하통일을 이루려는 **마사나가**의 야망이 움직이기 시작합니다.  

플레이어는 남성 주인공 **히비키** 또는 여성 주인공 **미노리**를 선택해,<br>
마사나가에게 쫓기던 아오이 가문의 공주 **티엔**을 돕게 됩니다.

주인공 일행은 마신에 대항하기 위해 **십이지 정령의 가호를 받은 12개의 신기와 그 사용자들**을 찾아 각지를 여행하며,  
전국시대풍 무장과 정령, 거인족, 자동인형, 비공정이 뒤섞인 세계에서 여러 세력과 얽히며 마신 봉인의 진실에 접근합니다.

### 작품 특징

- 기본 진행은 **ADV 파트 → 군사 선택·전투 준비 → SRPG 전투 → ADV 파트**를 반복하는 구성입니다.
- 남성 **히비키**와 여성 **미노리** 중 주인공을 선택할 수 있으며, 서로 다른 시점과 대화를 통해 이야기를 즐길 수 있습니다.
- 십이지 정령의 가호를 받은 주력 멤버를 중심으로 **100명 이상의 캐릭터가 등장하며 본편은 풀보이스**로 진행됩니다.
- 전투 직전 동료 한 명을 **군사(軍師)**로 선택할 수 있으며, 캐릭터마다 경험치·회피·아이템 획득 등 서로 다른 전투 보너스를 제공합니다.
- 동료 간의 호감도와 인간관계가 **응원(応援)** 시스템과 연결되어 전투 효과에도 영향을 줍니다.
- 무기에 **선옥(仙玉)**을 조합해 능력과 속성, 상태이상, 콤보 성능 등을 조정하고 무기 자체도 사용하면서 성장시킬 수 있습니다.
- 공격 연출 중 타이밍에 맞춰 버튼을 입력해 연속타를 이어가는 **콤보 시스템**이 적용되어 있습니다.
- 전술 난도를 극단적으로 높이기보다는 **캐릭터와 군상극, 세계관을 따라가며 비교적 가볍게 즐기는 SRPG**에 가까운 작품입니다.

보다 자세한 작품 소개와 발굴 자료는 **[Dollars Archive 게임 소개 페이지](https://dollars-archive.github.io/Game-Localization-Discovery-Archive/game.html?file=platforms%2Fpsp%2Fgames%2Ftwelve-sengoku-fuushinden.md)**에서 확인할 수 있습니다.

> **PSP판 Twelve ～戦国封神伝～을 한국어로 플레이할 수 있도록 제작 중인 비공식 한국어 패치입니다.**

<!-- kr-patch:scope:v1:start -->
<!-- 수집용 상태는 아래 HTML 주석에서 관리합니다. 공개 상태 문구나 버전 숫자를 각 항목에 추가하지 않습니다. -->
## 타이틀 한글화

<!-- kr-patch:state: 확인 필요 -->

타이틀 화면의 한국어화 적용 여부는 확인 후 안내합니다.

## 메뉴·UI

<!-- kr-patch:state: 확인 필요 -->

시스템 메뉴·메시지, 캐릭터 이름, 아이템·스킬과 설명을 한국어화 대상으로 검수합니다.

## 대사

<!-- kr-patch:state: 일부 -->

초반 한글 출력과 다음 대사·장면 진행을 확인했습니다. 전체 번역과 검수는 진행 중입니다.

## 이미지 번역

<!-- kr-patch:state: 완료 -->

이미지 번역 작업을 마쳤습니다. 게임 적용과 통합 검수 결과는 작업일지에 안내합니다.

## 동영상 자막

<!-- kr-patch:state: 미작업 -->

오프닝·엔딩 영상의 자막을 준비하고 있습니다. 실제 게임에서의 출력 확인은 후속 작업으로 진행합니다.

<!-- kr-patch:scope:v1:end -->

## 다운로드

현재 공개 배포판은 준비 중입니다. 릴리즈와 패치 파일은 아직 등록하지 않았습니다.

## 설치 방법

패치 제작과 테스트를 마친 뒤 지원 판본과 설치 방법을 안내합니다.

## 오류 및 번역 제보

[Issues](https://github.com/Dollars-Archive/twelve-sengoku-fuushinden-kr-patch/issues)에 제보해 주세요. 발생 장면과 문제 내용을 함께 적어주시면 확인에 도움이 됩니다.

## 작업 안내

- [Codex·GPT 선임 한글화 작업 순서](https://github.com/Dollars-Archive/Dollars-Archive-kr-localization-archive/blob/main/CODEX-LOCALIZATION-BOOTSTRAP.md)
- [Claude 선임 한글화 작업 순서](https://github.com/Dollars-Archive/Dollars-Archive-kr-localization-archive/blob/main/CLAUDE-LOCALIZATION-BOOTSTRAP.md)
- [공개 작업일지 운영 표준](https://github.com/Dollars-Archive/Dollars-Archive-kr-localization-archive/blob/main/workflow/PUBLIC-WORKLOG-STANDARD.md)

## 배포 안내

본 패치는 팬 제작 비공식 한국어 패치이며 게임 원본 파일을 포함하지 않습니다.
원작 및 관련 콘텐츠의 저작권과 상표권은 각 권리자에게 있습니다.
