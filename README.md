## Hello, you right there! 👋
I'm a student developer in high school, lhwdev. (he/him)  
I want to be programmer, maybe, and I code things to get my life better. (+ also for fun!)

취미로 개발하는 고등학생 2학년 개발자 이현우라고 합니다!

![Kotlin](https://img.shields.io/badge/Kotiln-5472f7?style=for-the-badge&logo=kotlin&logoColor=fff)
![JavaScript](https://img.shields.io/badge/JavaScript-f7d62d?style=for-the-badge&logo=javascript&logoColor=440)
![Python](https://img.shields.io/badge/Python-3ba4dd?style=for-the-badge&logo=python&logoColor=015)

<br>

## 나의 특징
- 코드를 예쁘고 잘 읽히게 짜는 걸 좋아합니다. 만약 이렇지 않은 코드가 있다면 옛날에
  만들었거나 심심풀이용일 가능성이 높슾니다.  
  그리고 네이밍을 최대한 직관적으로 하고자 합니다. 긴 이름이라도 잘 읽혀야죠.  

- API 설계를 좋아합니다.
  다만 TDD 같은 API가 쓰이는 곳을 더욱 고려해서 개발하는 방법을 써보고 싶습니다.

- 소스코드 뜯어보는 것을 좋아하곤 합니다. 은근 재미있어요

- 밑에서 보면 알 수 있듯 다양한 경험을 해봤지만 **주로 했던 것은 안드로이드 개발**입니다.
  전반적인 앱 개발을 주로 하며, UI 디자인도 좋아합니다.

- **Kotlin**이 가장 자신있는 언어이자 가장 좋아하고 자주 쓰는 언어입니다.
  심지어 코틀린 [컴파일러](https://github.com/lhwdev/Model) [플러그인](https://github.com/lhwdev/kt-ui/blob/master/compiler-plugin)을
  만들기도 했습니다.

- 꽤 잘 할 줄 아는 언어에는 Kotlin, **JavaScript/TypeScript**, **Python**, Java가 있습니다.
  조금 아는 언어나 옛날에 썼지만 기억이 잘 안 나는 언어에는 C/C++, HTML/CSS/SASS이 있습니다.
  기회가 되면 Rust도 써보고 싶네요.  
  어느 정도 규모의 프로젝트나, 안드로이드 앱은 다 코틀린으로 짭니다. 수학, 과학 등이나 간단하게 테스트해볼 것들은
  주로 파이썬을 씁니다.

- 써본 프레임워크/도구에는 **Android**, Jetpack Compose(Android, Desktop), React, **Gradle**, Deno, node.js,
  webpack, babel, eslint, posthtml/postcss 등이 있고,
  써보고 싶은 거에는 Svelte, SWC가 있습니다.
  * Gradle: 시행착오를 아주 많이 해봤습니다. 어느정도 규모의 새 프로젝트를 만든다면 Version Catalog를 통해
    dependency 버전을 관리하고, buildSrc에 일부 유틸리티 코드를 넣어서 쓰곤 합니다.

- 좋아하는 UI 프레임워크는 **Jetpack Compose**입니다.
  옛날부터 지켜봐왔고(`+memo {}` 같은 해괴한 api가 있을 때부터) 소스코드도 여러번 뜯어봤습니다.
  내부구조를 깊숙하게 이해하고 있습니다. 라고 생각합니다.
  [버그 제보](https://youtrack.jetbrains.com/issue/KT-44499)로 아주 약간의 기여를 하기도 했습니다.

- 사용하는 IDE에는 Intellij IDEA(안드로이드/코틀린 개발), Visual Studio Code(JS/Python 개발)을 주로 씁니다.
  깃은 Intellij의 UI나 cli를 선호하는 편이며, Intellij를 꽤 오래 써서 각종 기능이나 단축키를 어느정도 알고 있는 상태입니다.

- 새로운 무언가를 만들기 좋아합니다.
  > _Reinventing the wheel is sometimes **exciting**._

<br>

## 지금까지 한 것들
- **코로나19 자가진단 매크로 앱**
  
  교육청에서 만든 [자가진단 시스템](https://hcs.eduro.go.kr)에 대한 매크로.
  * 매일 자가진단을 하기가 귀찮아서 만들었습니다. 지금 꽤 많은 학생분들이 이 앱을 쓰고 있으며, 버그가 있다면 열심히
    업데이트하고 있습니다.
  * (v3.0.0 기준) UI를 정성들여 만들었고, 다양한 편의기능(여러명 동시 진단, 렌덤 시간, 주말 제외 기능 등)이 있습니다.
  * [내부 API 구조를 분석한 PoC를 올렸습니다.](https://github.com/lhwdev/covid-selftest-macro/blob/master/PoC.md)
  * 자가진단 하기 귀찮아서 만든 거라 초기에 코드가 지저분했고, 현재 아키텍쳐를 어느 정도 깔끔하게 갈아엎었습니다.
  * 만들 때 다른 분들의 도움을 좀 받았고, 도움을 주고 있습니다. 그리고 [관련된 깃허브 Organization](https://github.com/covid-hcs)도
    운영하고 있습니다.

- 고등학교에서 한 개인 프로젝트
  * [공동교육과정 등 프로그래밍 수업](https://github.com/lhwdev/programming-lesson)
    - `프로그래밍`: Jupyter Notebook 사용, 파이썬 기초
    - `응용프로그래밍개발`: 파이썬 tkinter로 GUI 만들기, 기본적인 알고리즘
  * [0/0 부정형의 심플한 극한 계산기](https://github.com/lhwdev/project-math)
  * [사원수에 기반한 간단한 3d projection](https://github.com/lhwdev/project-3d-projection)
  * [생태계 시뮬레이션](https://github.com/lhwdev/EcoSystem)
    - `old` 브랜치: 고1때 만든 허상뿐인 생태계 모델, 허점이 많음
    - `master` 브랜치: 유니티 게임엔진으로 만든 3d 물리적 시뮬레이터. 유전자 및 번식도 구현했고 상당히 기능이 많으나
      기본적인 틀이나 UI는 [다른 리포](https://github.com/SebLague/Ecosystem-2/tree/5763e0f6a4495d5b15a1c24083c9672dd5b3acd3)를 참고함
  * [라즈베리 기반 자동차 원격제어 앱](https://github.com/lhwdev/project-vrcar) (와이파이)

- [개발일지](https://lhwdev.github.io/note)
  * 하나하나 html 만져가며 만들고 싶었지만... 시간이 없어서 마크다운 + mkdocs로 만들었습니다.

- 🚧 디스코드 봇들

- ~~ASM(Android Studio Mobile)~~
  * 어릴 때 만들다 말아서 코드가 지저분합니다.
<br>

## Keep in touch
- 이메일: lhwdev6@outlook.com
- 트위터: [lhwdev6](https://twitter.com/lhwdev6)
- 디스코드: [lhwdev#7325](https://discord.com/users/551597391741059083)
