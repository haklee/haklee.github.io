---
title: "조건문"
---

[:material-arrow-left-bold: 글 목록](../index.md){ .md-button }

조건에 따라 변수에 값을 할당하거나 연산을 하고 싶다면 조건문을 사용하거나 삼항연산자를 사용하면 된다.

## 조건문

대부분의 유명한 언어에서 조건문, 혹은, if문을 지원한다. if문은 보통 다음과 같은 구조로 되어있다.

    ``` txt
    if (조건 A):
        (조건 A가 참일 경우 실행할 코드)
    else if (조건 B):
        (조건 A는 거짓이지만 조건 B는 참일 경우 실행할 코드)
    else if (조건 C):
        (조건 A, B는 거짓이지만 조건 C는 참일 경우 실행할 코드)
    ...
    else:
        (앞선 모든 조건들이 거짓일 경우 실행할 코드)
    ```
이를 각 언어에서는 다음과 같이 구현해서 쓸 수 있다.

=== "python"

    ``` python
    # 다음의 규칙에 맞게 점수에 따라 성적을 매겨보도록 하자.
    # - 90점 이상은 A
    # - 90점 미만, 80점 이상은 B
    # - 80점 미만, 70점 이상은 C
    # - 70점 미만, 60점 이상은 D
    # - 그 외 F

    score = 87
    grade = ''  # 빈 값으로 초기화한다.

    if score >= 90:
        grade = 'A'
    elif score >= 80:  # 파이썬에서는 'else if'가 아니라 'elif'다.
        grade = 'B'
    elif score >= 70:
        grade = 'C'
    elif score >= 60:
        grade = 'D'
    else:
        grade = 'F'

    # 위 코드를 돌고 나서 grade는 'B'가 되어있다.


    # 1학기, 2학기에 받은 점수가 모두 85점이 넘으면 good student라고 하자.
    # 아래의 코드는 두 점수를 받아서 good student인지 판별해준다.
    score_1, score_2 = 87, 93
    is_good_student = False

    if score_1 > 85 and score_2 > 85:
        is_good_student = True
    else:
        is_good_student = True
    
    # 하지만 이미 처음에 is_good_student를 False로 초기화했기 때문에 else문을 생략해도 된다.
    if score_1 > 85 and score_2 > 85:
        is_good_student = True
    
    # 혹은 처음에 is_good_student를 True로 초기화하고 두 점수 중 하나라도 85점 이하인지
    # 판별하는 방식으로 접근해도 괜찮다.
    is_good_student = True

    if score_1 <= 85 or score_2 <= 85:
        is_good_student = False
    ```

=== "javascript"

    ``` js
    // WIP
    ```

=== "C#"

    ``` cs
    // WIP
    ```

=== "C++"

    ``` cpp
    // WIP
    ```

## 삼항연산자

간단한 if문은 좀 더 짧게 표현하는 것도 가능하다. 많은 유명한 프로그래밍 언어들이 다음과 같은 삼항연산자를 지원한다.

    ```txt
    (조건) ? (참일 경우 값) : (거짓일 경우 값)
    ```

실제 구현은 코드를 보도록 하자.

=== "python"

    ``` python
    # 파이썬은 특이하게도 삼항연산자를 조금 다르게 구현한다.
    # - (참일 경우 값) if (조건) else (거짓일 경우 값)

    # 1학기, 2학기에 받은 점수가 모두 85점이 넘으면 good student라고 하는 문제를
    # 아래와 같이 구현하는 것이 가능하다.
    score_1, score_2 = 87, 93
    is_good_student = True if (score_1 > 85 and score_2 > 85) else False
    ```

=== "javascript"

    ``` js
    // WIP
    ```

=== "C#"

    ``` cs
    // WIP
    ```

=== "C++"

    ``` cpp
    // WIP
    ```

[:material-arrow-left-bold: 글 목록](../index.md){ .md-button }
