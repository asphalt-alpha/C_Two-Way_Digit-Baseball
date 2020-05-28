﻿# C_ Two-Way_Digit-Baseball 
> 흔히 C언어로 제작하는 숫자야구를 벗어나 숫자아구라는 주제를 가지고 다양하게 즐길 수 있도록 만든 토이 프로젝트 입니다.

---

## Files
```
helper.c
```
사람들과 숫자 야구를 즐기면서 사람들은 불필요한 조합으로 구성된 숫자를 가지고 공격하는 상황이 발생합니다.
이를 줄이고자 사용자가 `숫자 _Strike _Ball`을 입력해 가능한 case만을 사용자에게 리턴하는 프로그램입니다.

---
```
1P_vs_2P.c
```
두 명의 사용자가 한 컴퓨터에서 즐길 수 있도록 UI를 구성한 숫자야구 게임입니다.
흔히 예전에 즐긴 플래시 게임처럼 구성하였습니다.

---
```
1P_vs_com.c
```
한 명의 사용자가 컴퓨터와 즐기는 숫자야구게임을 제작하였습니다. 단순히 컴퓨터가 랜덤 생성한 숫자를 사용자가 맞추는 형식이 아니라
사용자와 컴퓨터 모두 자신의 숫자를 생성하고 상대방의 숫자를 맞히는 쌍방향 숫자야구게임을 개발하였습니다.
`helper.c` 파일을 참고하여 제작되었습니다.
