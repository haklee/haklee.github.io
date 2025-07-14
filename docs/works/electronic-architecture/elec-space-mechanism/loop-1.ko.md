---
title: "Manifold Garden 사례"
---

[:material-arrow-left-bold: 전자 공간의 메커니즘](./index.md){ .md-button }

<iframe width="560" height="315" src="https://www.youtube.com/embed/IrURcGTEtvQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

앞선 [눈 앞에 보이는 공간으로 이동하는 포탈](./portal-2.md) 글을 통해 포탈 구현 방법을 이해했다면 비슷한 Manifold Garden에 나오는 무한히 떨어질 수 있는 공간을 구현할 수 있을 것으로 보인다.

- 천장과 바닥 양쪽에 모두 아주 넓은 면적의 포탈이 존재한다.
- 바닥 포탈을 통해 보이는 공간에 바닥 포탈을 통해 보이는 공간이 재귀적으로 중첩되어 보일 수 있는데, 이에 대한 처리를 잘 하는 것이 관건일 것이다. 게임에서는 멀리 떨어진 공간이 뿌옇게 보이도록 처리한 것을 볼 수 있다.

[:material-arrow-left-bold: 전자 공간의 메커니즘](./index.md){ .md-button }
