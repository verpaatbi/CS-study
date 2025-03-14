# eXtreme Programming (XP)

> 작성자 : [정희재](https://github.com/Hee-Jae)

참조 : [위키피디아](https://ko.wikipedia.org/wiki/%EC%9D%B5%EC%8A%A4%ED%8A%B8%EB%A6%BC_%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D)
<details>
<summary>Table of Contents</summary>

- [eXtreme Programming이란?](#extreme-programming-이란)
- [다른 애자일 방법론과 구분되는 특징](#다른-애자일-방법론과-구분되는-특징)
- [XP 실천 방법](#xp-실천-방법)

</details>

---

## eXtreme Programming 이란?
**익스트림 프로그래밍(eXtreme Programming, XP)** 은 `켄트 백` 등이 제안한 소프트웨어 개발 방법이다. 비즈니스 상의 요구가 시시각각 변동이 심한 경우에 적합한 개발 방법이다. 1999년 `켄트 백`의 저서인 'Extreme Programming Explained - Embrace Change'에서 발표되었다. **애자일 개발 프로세스**라 불리는 개발 방법 중의 대표적인 하나로 꼽히며, 약칭인 'XP'로 잘 알려져 있다.

## 다른 애자일 방법론과 구분되는 특징
1. 프로그래머들이 코딩을 할 때 **테스트 코드**도 함께 작성한다.
2. **테스트를 기반**으로 프로젝트를 완성해 나간다.
3. **반복적으로 고객에게 프로토타입을 전달**함으로써 고객의 요구사항 변화에 민첩하게 대응한다.
4. 매번 프로토타입을 고객에게 전달함에 있어서 프로토타입 자체로써 **버그가 상대적으로 적은 완벽에 가까운 데모**를 경험하게 해준다.


## XP 실천 방법

#### Whole Team
프로젝트에 참여하는 모든 팀원들을 가리킨다. 디자이너, 프로젝트 관리자, 개발자, 테스터, 유저 등 역할들이 많은데 이중 **유저가 제일 중요하다.** 유저가 프로젝트의 키를 가지고 있는 `Stakeholder`이기 때문이다.

#### Planning Game
어떤 개발 과정을 끝마칠 것인가, 다음에는 어떤 일을 할 것인가에 중점을 두어 `iteration`을 계획한다. 일반적으로 2주를 주기로 한 `iteration`을 진행한다.  한 `iteration` 동안 프로토타입을 만들어서 의뢰인에게 보여주고 회의를 한다. 따라서 **기한 내에 프로토타입이 반드시 개발되어야 한다.** 이를 통해 기업은 본인들의 실력을 입증할 수 있고, 의뢰인 입장에서는 프로토타입이 마음에 안들 때 빠르게 손절해서 비용을 아낄 수가 있다.

#### Customer Tests
의뢰인이 원하던 결과물을 만들어내는게 중요하다. 따라서 주기적으로 **결과물이 정말 의뢰인이 원하는 게 맞는지 테스트를 해본다.**

#### Small Releases
**개발자는 주기적으로 의뢰인에게 프로토타입을 보여준다.** 의뢰인은 이를 통해 추가적인 요구사항을 제시할 수 있으며, 개발자는 이를 통해 현재까지 개발 상황이 올바르게 가고 있음을 알 수 있다.

#### Simple Design
개발을 하다 보면 코드가 복잡해진다. 따라서 **코드를 가능한 심플하게 설계를 한다.** (KISS 원칙 : Keep It Small, Simple)

#### Test-Driven Development
XP에서 가장 중요한 요소이다. **테스트를 거치면서 코딩한다.**

#### Pair Programming
**두명 혹은 그 이상의 프로그래머가 함께 코딩을 한다.** 코딩 하는 역할, Quality Assurance 역할 등으로 나누어서 개발과 테스트에 모두 집중한다.
