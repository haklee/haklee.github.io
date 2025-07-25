---
title: "도구함"
---
*(last modified: 2025. 07. 14.)*

## Intro

언제부턴가 도구는 프로젝트에 따라 언제든지 바꾸거나 새로 공부할 수 있는 것이라는 생각을 한다. 하지만 인생은 유한하고 도구를 사용해볼 수 있는 시간은 한정되어 있으니, 아쉽게도 내 앞에 보이는 모든 도구들을 숙달하는 것은 불가능할 것이다. 하지만 그렇더라도 다뤄보고 싶은 마음이 생긴 도구들은 최대한 사용해보자는 마음가짐으로 계속 새로운 도구들을 배워보고 있다. 이곳에는 그간 사용해본 도구들을 나열한다.

| 숙련도  | 설명 |
| :-----: | :--- |
|    1    | 살짝 시도해본 정도. 해당 도구를 0~1개의 프로젝트에 활용해보았다. |
|    2    | 사용해보았으나 아직 어색한 수준. 프로젝트를 1~2개 정도 진행해보았다. |
|    3    | 도구를 써서 뭘 할 수 있을지, 앞으로 어떤 스킬들을 더 공부해야 하는지 대충 감을 잡은 수준. 프로젝트를 2~3개 정도 진행해보았다. |
|    4    | 프로젝트를 진행함에 있어 우선적으로 선택할 정도로 숙련되었다. 내가 모르는 것이 무엇인지 명확하게 안다. |
|    5    | 내 신체의 일부 수준으로 도구의 언어를 구사한다. |

## 언어

| 도구       | 숙련도 | 설명 |
| :--------- | :----: | :--- |
| python3    | 4      | 간단한 서버, 태스크 큐, 기하 연산을 위한 패키지 개발을 하거나 각종 알고리즘 문제를 푸는 데에 주 언어로 사용했다. |
| javascript | 3      | 서버 개발을 목적으로 주로 다뤄보았으며, 프론트엔드 개발을 위해 조금 다뤄보았다. |
| typescript | 2      | 서버를 타입스크립트를 기반으로 개발하긴 했으나, 타입 시스템 자체에 대한 이해가 충분하지 않다는 생각에 숙련도를 낮게 책정했다. |
| C#         | 3      | RhinoCommon, AutoCAD .NET API를 다루는 프로젝트에서 주로 사용했다. |
| C++        | 2      | 엔진스튜디오에서 게임 유지보수를 하며 처음 다뤄보았고, 이후에는 성능이 중요한 기하 문제를 풀기 위한 알고리즘 구현, 그리고 wasm을 위해 조금 다뤄보았다. |
| Kotlin     | 2      | 앱 개발을 공부하며 조금 다뤄보았다. |
| Dart       | 2      | 앱 개발을 공부하며 조금 다뤄보았다. |
| R          | 1      | 서울대학교 도시건축보존계획연구실에서 랩 내부에서 진행하는 스터디에 초대되어 참여하며 조금 다뤄보았다. |

## 웹 서비스 관련

### 프레임워크

| 도구    | 숙련도 | 설명 |
| :------ | :----: | :--- |
| NestJS  | 4      | Express로 서버 개발을 하다가 추후 NestJS에 정착했다. 소켓 통신, 로깅, 가드, 타입 체킹, 간단한 테스팅, Swagger 연동 및 각종 orm 연동 기능들을 활용해보았으며, 로그인 및 클라우드 스토리지 연동, 태스크 큐 연동 기능들을 구현해보았다. |
| Next.js | 2      | 프론트와 서버가 통합된 토이 프로젝트 제작을 위해 조금 다뤄보았다. |
| Flask   | 2      | python 기반의 프로젝트들에 서버 기능을 붙여야 할때 조금 다뤄보았다. |
| Django  | 2      | Celery와 연동되는 api 서버를 만들기 위해 조금 다뤄보았다. DRF와 Django Ninja를 살펴보고 DRF가 너무 ORM과 얽혀있는 점, 그리고 Django Ninja가 처음 접근했을때 훨씬 사용하기 쉬운 점을 이유로 Django Ninja와 같이 사용해보았다. |

### 라이브러리

| 도구    | 숙련도 | 설명 |
| :------ | :----: | :--- |
| Zustand  | 2      | React 활용시 상태 관리를 할때 복잡한 Redux 대신 사용하기 좋은 라이브러리를 찾다가 사용하기 시작. Jotai와 비교해봤다가 더 큰 프로젝트에 사용하기 용이한 구조인 것으로 보여서, 그리고 npm에 나오는 다운로드수를 보니 더 많은 사람들이 사용하는 것 같아서 선택했다. Zustand에 대한 이해도는 Next.js랑 같이 사용하려 하면 서버가 stateless해야 한다는 것과 Zustand의 상태는 전역적으로 관리된다는 것이 충돌하므로 이를 신경써주어야 한다는 것을 아는 정도이다. |
| R3F | 1 (AI)      | 웹 화면에 프로세싱 같은 화면 구현을 위해 사용해보기 시작. 처음에는 Three.js를 보다가 R3F가 react랑 사용하기에 더 편하게 되어있는 것으로 보여서 Cursor AI로 이것저것 만들어보기 시작했다. |

### Query Builder / ORM

| 도구    | 숙련도 | 설명 |
| :------ | :----: | :--- |
| TypeORM | 2      | TypeORM으로 구현되어 있던 프로젝트를 유지보수하며 다뤄보았으나, ORM 특유의 엔티티를 기반으로 DB를 바라보는 관점이 취향에 맞지 않아 이후 query builder 진영으로 넘어갔다. |
| Kysely  | 4      | 쿼리문 작성에 익숙해서 query builder를 찾아다니다가 typescript에 매우 친화적이라는 점에 이끌려 Kysely에 정착했다. 마이그레이션 및 시딩도 kysely를 통해서 진행한다. |
| Prisma  | 1      | TypeORM를 대체할 수 있는 쿼리 빌더 / ORM을 찾던 중 잠시 사용해보았으나, 당시 mysql의 여러 도형 타입들에 대한 지원이 아직 되지 않아서 잠시 다뤄본 다음 넘어갔다. |

### MQ

| 도구   | 숙련도 | 설명 |
| :----- | :----: | :--- |
| Celery | 3      | python으로 구현한 기능들과 태스크 큐를 연동하기 위해 사용하기 시작했다. |
| ZeroMQ | 2      | 엔진스튜디오에서 내부 툴을 만들때 처음 접해보았으며, 이후 Node.JS로 구축한 서버의 태스크 큐를 구현할때 잠시 사용해보았다. |

### 모니터링

| 도구       | 숙련도 | 설명 |
| :--------- | :----: | :--- |
| Prometheus | 2      | 서비스 모니터링을 위해 조금 다뤄보았다. |
| Grafana    | 2      | 서비스 모니터링을 위해 조금 다뤄보았다. |

### 테스팅

| 도구     | 숙련도 | 설명 |
| :------- | :----: | :--- |
| Swagger  | 2      | 주로 NestJS와 연동하여 각종 api 기능들을 수동으로 테스팅할때 사용해보았다. |
| Postman  | 3      | 각종 api 기능들을 수동으로 테스팅하거나, 일련의 api 콜을 연달아 수행해야 할때 사용해보았다. |
| Insomnia | 1      | Postman을 사용하기 전 각종 api 기능들을 수동으로 테스팅할때 사용해보았다. |

## 버전 관리

| 도구 | 숙련도 | 설명 |
| :--- | :----: | :--- |
| git  | 4      | 각종 시행착오를 거치면서 git 사용방법을 배웠다. 개발팀의 상황에 맞춰 변형한 gitflow 전략을 만들어 정착시킬 수 있을 정도의 이해도를 갖추고 있다. |

## 프로젝트 관리

| 도구       | 숙련도 | 설명 |
| :--------- | :----: | :--- |
| Jira       | 3      | 엔진스튜디오에서 게임 유지보수 과정에서 처음 활용해보았고, 개발팀의 상황에 맞춰 티켓 관리 전략을 만들어 시험적으로 사용해볼 수 있을 정도의 이해도를 갖추고 있다. |
| Confluence | 3      | 엔진스튜디오에서 코드 유지보수를 위한 문서화 과정에서 처음 활용해보았다. |
| Trello     | 2      | 한때 개인 일정 관리 및 작은 토이 프로젝트의 기획 및 구현 작업 목록을 관리하는 데에 활용했었으나, 현재는 사용하지 않고 있다. |
| Notion     | 2      | 한때 개인 자료 정리 및 작은 토이 프로젝트의 랜딩페이지를 만드는 데에 활용했었으나, 현재는 사용하지 않고 있다. |
| Slack      | 3      | 지금까지 거쳐온 여러 팀들에서 공통적으로 사용하였으며, 슬랙봇을 만들어서 필요 내용 로깅 및 간단한 투표 기능 구현 등의 작업을 해낼 수 있을 정도의 이해도를 갖추고 있다. |

## 데이터베이스

| 도구       | 숙련도 | 설명 |
| :--------- | :----: | :--- |
| MySQL      | 4      | 서비스 운영을 위한 기본적인 DB 설계부터 공간 인덱스 설정, 느린 쿼리 최적화, CTE를 활용한 재귀 쿼리 작성, 트리거 및 프로시저 작성, DB 덤프 및 마이그레이션 등의 작업을 수행해보았다. |
| PostgreSQL | 3      | 서비스를 처음부터 만들어야 하는 상황에서는 주로 mysql을 선택하지만, postgresql을 활용한 토이 프로젝트들도 여럿 진행해본적이 있다. |
| SQLite     | 2      | 앱 개발과 같이 로컬에 DB를 두는 상황이 발생할 경우 sqlite를 활용해본 적이 몇 번 있다. |
| Redis      | 2      | 태스크 큐를 다루는 경우 redis를 활용한 적이 있으며, 꼭 관계형 데이터베이스로 데이터를 관리하지 않아도 되는 상황에 redis를 활용해본 적이 몇 번 있다. |

## 배포

| 도구           | 숙련도 | 설명 |
| :------------- | :----: | :--- |
| pm2            | 3      | 빠른 무중단 서버 배포, 로그 확인에 자주 활용한다. |
| docker         | 3      | 각종 배포 상황에서 활용해보았다. 상황에 따라 필요한 기능들 위주로만 사용해보아서 전반적인 이해도가 높지는 않을 수도 있다고 생각한다. |
| docker compose | 3      | 각종 배포 상황에서 활용해보았다. 상황에 따라 필요한 기능들 위주로만 사용해보아서 전반적인 이해도가 높지는 않을 수도 있다고 생각한다. |
| github actions | 2      | 현 사이트는 github actions를 활용하여 자동으로 배포하는 방식으로 관리하고 있다. |
| serverless     | 2      | NestJS를 활용하여 lambdalith한 API서버를 구현하는 데에 활용해보았다. |

## 3D/CAD/GIS

| 도구                      | 숙련도 | 설명 |
| :------------------------ | :----: | :--- |
| Rhino3D                   | 2      | 건축학과 전공 수업을 들으며 활용해보았다. |
| Grasshopper               | 4      | 건축학과 전공 수업 및 다양한 외부 프로젝트에서 활용해보았다. 라이노로는 원하는 형태를 만들지 못하더라도 그래스호퍼로는 작업이 가능한 경우가 많았다. |
| RhinoCommon               | 4      | 경계없는 작업실에서 처음 사용해본 뒤로 다양한 외부 프로젝트에서 활용해보았다. 아직 RhinoCompute가 나오기 전 상용 프로젝트에서는 Rhino에 의존성을 두기 어렵겠다는 판단을 한 이후로 거의 활용하지 않다가, 2024년부터 다시 사용을 시도해보고 있다. |
| AutoCAD                   | 2      | 건축학과 전공 수업을 들으며 활용해보았다. |
| AutoCAD .NET API          | 3      | 2024년에 각종 오토데스크 제품군을 활용한 기능을 둘러보던 중 처음 사용해보았다. |
| AutoLISP                  | 1      | AutoCAD에 프로그래밍을 접목시킬 방법을 찾아보다가 잠시 공부해보았으나, .NET API를 활용하는 쪽으로 관심이 기울면서 더 자세히 알아보지는 않았다. |
| Dynamic Block(AutoCAD)    | 2      | AutoCAD의 기능들을 찾아보던 중 동적 블록을 통해서 쉽게 구현할 수 있는 기능들을 발견하여 조금 다뤄보았다. |
| Revit                     | 2      | 서울대학교 건축사연구실에서 목가구 구조물을 구현하는 작업을 진행하며 처음 사용해보았고, 이후에 Dynamo를 사용해보기 위해 다시 다뤄보았다. |
| Dynamo(Revit)             | 2      | Rhino3d의 grasshopper에 대응되는 기능들이 제공된다는 설명을 듣고 잠시 사용해보았으나, revit에 익숙하지 않아서 기본적인 튜토리얼 정도를 따라가본 뒤로 많이 사용해보지는 않았다. |
| Autodesk Platform Service | 2      | Revit 및 AutoCAD로 수행할 수 있는 기능을 자동화하는 데에 활용이 가능한 것을 몇몇 사례들을 통해서 확인한 뒤 기본적인 튜토리얼을 따라가보았다. |
| Blender                   | 2      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. 사용했다가 잊어버렸다가를 몇 번 반복해서 Blender Guru님의 도넛 튜토리얼을 세 번 정도 들었고, 파이썬으로 스크립트도 몇 번 작성해보았지만, 현재는 마지막으로 사용한지 오래되어 거의 잊어버렸다. |
| Cinema4D                  | 2      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. 사용했다가 잊어버렸다가를 몇 번 반복해서 Greyscalegorilla님의 기본 튜토리얼을 두 번 정도 들었지만, 현재는 마지막으로 사용한지 오래되어 거의 잊어버렸다. |
| 3ds Max                   | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| SketchUp                  | 1      | 건축학과 전공 수업을 들으며 활용해보았다. |
| SolidWorks                | 1      | 기계과 전공 수업을 들으며 활용해보았다. |
| QGIS                      | 2      | 2017년 1학기에 공공데이터포털에서 제공하는 지리 정보를 설계 과제에 활용하기 위해 처음 QGIS를 다뤄본 뒤, 2학기에 학생자율연구 수업에서 QGIS에 python을 연동하여 보행 데이터를 분석하는 데에 활용해보았다. 이후 건축학과 학부생 및 대학원생을 대상으로 QGIS를 사용하는 방법을 설명하는 워크숍을 몇 주에 걸쳐 진행한 경험이 있으나, 현재는 오랜 기간 사용하지 않아 사용법을 거의 잊어버렸다. |
| NVIDIA Omniverse          | 1      | 간단한 기능들을 살펴보고 Extension 개발을 시도해보았다. |

## 2D

| 도구              | 숙련도 | 설명 |
| :---------------- | :----: | :--- |
| Adobe Photoshop   | 3      | 건축학과 전공 수업을 들으며 활용해보았다. |
| Adobe Illustrator | 2      | 건축학과 전공 수업을 들으며 활용해보았다. |
| Adobe InDesign    | 2      | 건축학과 전공 수업을 들으며 활용해보았다. |
| Adobe Lightroom   | 1      | 사진 편집을 위해 간단히 다뤄보았다. |

## Video

| 도구                | 숙련도 | 설명 |
| :------------------ | :----: | :--- |
| Adobe Premiere Pro  | 3      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| Adobe After Effects | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |

## Sound

| 도구          | 숙련도 | 설명 |
| :------------ | :----: | :--- |
| SuperCollider | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. 사용했다가 잊어버렸다가를 몇 번 반복해서 Eli Fieldsteel님의 기본 튜토리얼을 세 번 정도 들었지만, 현재는 마지막으로 사용한지 오래되어 거의 잊어버렸다. |
| Pure Data     | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| Max/MSP       | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| FL Studio     | 1      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. |
| Cubase        | 1      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. |
| Ableton Live  | 1      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. |
| GoldWave      | 1      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. |

## Graphics & Other

| 도구           | 숙련도 | 설명 |
| :------------- | :----: | :--- |
| Processing     | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| vvvv           | 1      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| Resolume Arena | 1      | 개인 프로젝트 진행을 위해 잠깐 사용해보았다. |
| TouchDesigner  | 1      | 수업에서 다루진 않았으나 어떤 기능들이 있는지 테스트를 해보기 위해 잠깐 사용해보았다. |
| OpenGL         | 1      | C++로 구현한 기하학적인 알고리즘의 결과물을 확인하기 위해 사용해보았다. |
| Vulkan         | 1      | 그래픽스 관련 자료를 찾던 중에 발견하여 흥미가 동해 잠시 시도해봤다. 900줄 짜리 hello triangle 코드를 작성해본 뒤 흥미를 잃었다. |
| Unity3D        | 2      | AR을 이용한 안드로이드 앱 개발을 위해 조금 다뤄보았다. AR 기능 개발에는 Vuforia를 사용했으며, stencil shader를 적용한 오브젝트를 생성해보았다. |

## Electronics

| 도구         | 숙련도 | 설명 |
| :----------- | :----: | :--- |
| Arduino      | 3      | 영상매체예술 연합전공 수업을 들으며 활용해보았다. |
| Raspberry Pi | 2      | 두 번째 버전 홈페이지는 rpi로 홈서버를 구축하여 워드프레스 사이트를 올리는 식으로 구현했었다. |
| Synology NAS | 2      | 첫 번째 버전 홈페이지는 나스에 indexhibit으로 만든 사이트를 올리는 식으로 구현했었다. |
