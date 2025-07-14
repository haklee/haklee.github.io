---
title: "어플리케이션 - Windows"
---

[:material-arrow-left-bold: 어플리케이션](./index.md){ .md-button }

Windows의 공간을 구현하는 데에는 크게 두 가지 기술이 활용되었다.

- 증강 현실: Vuforia 엔진을 활용한다. 이 엔진은 기기의 카메라를 통해 인식한 주변 환경의 이미지를 미리 3차원 스캔을 해둔 이미지와 비교하여 미리 구현해둔 3차원 오브젝트들을 현실 공간에 맵핑해주는 역할을 한다.
- 스텐실 쉐이더(stencil shader): 유저의 시선과 오브젝트 사이에 조건이 걸려있는 평면을 두어 해당 평면의 조건을 만족하는 오브젝트만 유저에게 보이도록 한다. 조건부 렌더링을 한 것이라고 이해하면 된다.

아래의 영상에서는 유니티를 통해 설계실 공간을 바탕으로 AR 기능을 구현하는 것을 확인할 수 있다.

<iframe width="560" height="315" src="https://www.youtube.com/embed/kr9xXlv0-YU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[:material-arrow-left-bold: 어플리케이션](./index.md){ .md-button }
