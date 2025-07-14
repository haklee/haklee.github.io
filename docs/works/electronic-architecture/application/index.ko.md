---
title: "어플리케이션"
---

[:material-arrow-left-bold: 전자-건축](../index.md){ .md-button }

`ELEC-SPACE-PROJECT`는 물리적으로 존재하는 것은 불가능하지만 전자적인 방식으로는 존재할 수 있는 공간에 대해 탐구하고 이를 직접 구현해보기 위해 시작한 프로젝트이다. 공간의 구현에는 다음과 같은 기술들이 활용되었다.

- Unity: 앱 개발에 사용한 게임 엔진.
- Vuforia: AR 기능 개발에 사용한 라이브러리.
- git: 버전 관리 도구

이 프로젝트는 처음에 projectMZ라는 이름으로 시작했고, 전시 직전까지도 이름을 정하는 것을 보류했다가 마지막 순간에 ELEC-SPACE-PROJECT라는 이름으로 변경되었다. 앱 개발에 있어서 이름이 필요한 순간은 처음 프로젝트를 생성하는 순간 뿐이고 나중에 정식으로 사용할 프로젝트 이름을 정한 뒤 얼마든지 관련 정보를 수정할 수 있다는 생각에 이렇게 진행했는데, 개발을 진행하는 데에 있어 큰 문제는 없었다.

바닥부터 쌓아올라나가는 게임 개발은 처음이어서 시행착오를 많이 겪었다. 처음에는 배포까지 염두에 두었으나 중간에 AR 기능을 추가하며 앱이 장소특정적으로 작동하는 것이 되어버려서 배포는 하지 않기로 결정했다.

이번에 개발한 앱은 싱글 플레이, 즉, 유저가 다른 유저와 상호작용하는 것을 고려하지 않고 개발했다. 멀티 플레이 기능을 추가하고자 한다면 고려할 것이 훨씬 많아지는데, [`Maze`의 멀티플레이어 기능 기획](../maze-multiplayer/index.md) 문서에 좀 더 자세히 설명되어 있다.

ELEC-SPACE-PROJECT에서는 크게 두 가지의 공간을 구현해보고자 하였다.

- [Maze](./maze.md): 길을 따라 가다가 뒤를 돌아보면 왔던 길이 사라져있는 공간.
- [Windows](./windows.md): 창문을 통해 보이는 공간이 서로 다른데 같은 위치를 차지하고 있는, 중첩된 공간

전시는 Windows만 구현된된 상태로 진행했다. 아래는 전시 영상이다.

<iframe width="560" height="315" src="https://www.youtube.com/embed/bE7T5-TVkQQ?si=cen74f4bpezG8RR3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[:material-arrow-left-bold: 전자-건축](../index.md){ .md-button }
