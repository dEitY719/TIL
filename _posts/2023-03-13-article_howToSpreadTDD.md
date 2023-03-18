---
layout: post
title: How to Effectively Spread TDD Culture to Your Team Colleagues
subtitle: what is TDD?
# gh-repo: daattali/beautiful-jekyll
# gh-repo: https://github.samsungds.net/pages/byoungwoo-yoon/deity719/
# gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/tdd-thumb.png
cover-img: /assets/img/culture-circle-cover.png
# share-img: /assets/img/path.jpg
tags: [tdd]
comments: true
---

# 소개 <sub>(feat. TDD 문화를 전파하는 방법)</sub>
소프트웨어 개발이 계속 발전함에 따라 많은 조직에서는 Test-Driven Development (TDD)를 개발 프로세스의 필수 요소로 채택하고 있습니다. TDD는 품질 높은 소프트웨어를 만드는 효과적인 방법이며 오류를 줄일 수 있습니다. 하지만 팀 동료들이 TDD를 채택하는 것은 도전적입니다. 이 글에서는 팀 동료에게 TDD 문화를 효과적으로 전파하는 방법에 대해 논의하겠습니다.

> **_Introduction_**  
> As software development continues to grow, many organizations have started to adopt Test-Driven Development (TDD) as an integral part of their development processes. TDD has been proven to be an effective approach to building quality software and reducing errors. However, getting your team colleagues to adopt TDD can be challenging. In this article, we will discuss how you can effectively spread TDD culture to your team colleagues.

{: .box-note}
**Note:** TDD가 능숙한 개발자는 빠르게 [Epilogue](#epilogue)만 읽어보시고, Tip 좀 공유해주세요. 사례하겠습니다.🙏

# TDD란 무엇인가요?
Test-Driven Development (TDD)는 코드를 작성하기 전에 자동화된 테스트를 작성하는 개발 프로세스입니다. 이 과정은 실패할 테스트 케이스를 작성하고 해당 테스트 케이스를 통과할 코드를 작성하는 것으로 시작합니다. 코드를 작성한 후에는 해당 테스트 케이스를 실행하여 통과하는지 확인합니다. 이 과정은 코드가 요구 사항을 충족하는 것을 보장하고 코드베이스에 버그가 도입될 가능성을 줄입니다.

> **_What is TDD?_**  
> Test-Driven Development (TDD) is a software development process that emphasizes writing automated tests before writing code. The process involves writing a test case that will fail, then writing code to pass that test case. After the code has been written, the test case is run to ensure that it passes. This process helps to ensure that code is written to meet the requirements and reduces the likelihood of introducing bugs into the codebase.

## TDD의 중요성은 무엇인가요?
TDD에는 다음과 같은 장점이 있습니다.

* **_개선된 코드 품질_** : TDD는 개발자가 더 깨끗하고 유지 보수가 쉬운 코드를 작성하도록 장려하므로 버그가 적고 디버깅이 쉬워집니다.
* **_더 빠른 개발 주기_** : TDD는 개발 프로세스에서 문제를 초기에 식별하므로 디버깅 및 버그 수정에 소요되는 시간이 줄어듭니다.
* **_더 나은 협업_** : TDD는 개발자, 테스터 및 이해관계자 간의 협업을 장려하므로 프로젝트 요구 사항에 대한 커뮤니케이션과 이해가 개선됩니다.

> Why TDD is important?  
> TDD has a number of benefits, including:
> * Improved code quality: TDD encourages developers to write cleaner and more maintainable code, which leads to fewer bugs and easier debugging.
> * Faster development cycles: TDD helps to identify issues early in the development process, which reduces the time spent on debugging and fixing bugs.
> * Better collaboration: TDD encourages collaboration between developers, testers, and stakeholders, which leads to better communication and understanding of project requirements.

## 팀 동료에게 TDD 문화를 효과적으로 전파하는 방법
How to spread TDD culture to your team colleagues

* **_솔선 수범하세요_** : 팀 동료가 TDD를 채택하도록 장려하는 가장 좋은 방법은 본보기를 보여주는 것입니다. 우선 자신의 코드에 대한 테스트를 작성하고 TDD가 제공하는 이점을 자신의 작업을 통해 보여주세요. TDD가 깨끗한 코드 작성, 문제를 초기에 식별하는 데 도움이 되며 팀 동료와의 협업을 개선하는 방법을 보여주세요.

> * Lead by example: The best way to encourage your team colleagues to adopt TDD is to lead by example. Start by writing tests for your own code and demonstrating the benefits of TDD through your work. Show how TDD helps you to write cleaner code, identify issues early, and improve collaboration with your team colleagues.

* **_교육을 제공해주세요_** : TDD를 사용하지 않았던 개발자들에게는 TDD가 이해하기 어려울 수 있습니다. 팀 동료들에게 교육 세션을 제공하여 TDD를 명확하게 이해하고 채택하는 데 도움이 될 수 있습니다. 팀 동료들이 테스트와 코드 작성을 연습할 수 있도록 실습을 포함하는 것이 좋습니다.

> * Provide training: TDD can be difficult to understand for developers who have not used it before. Providing training sessions to your team colleagues can help to demystify TDD and provide a solid foundation for adoption. Be sure to include hands-on exercises to allow your team colleagues to practice writing tests and code.

*  **_작게 시작해보세요_** : TDD를 전체 개발 팀에 도입하려고 하면 압도적일 수 있습니다. 대신, 작은 그룹의 개발자들에게 TDD를 소개하고 그들과 함께 프로세스를 채택하는 것으로 시작하세요. 그들이 TDD에 익숙해지면 다른 팀 동료들에게 이 문화를 전파하는 데 도움이 될 수 있습니다.

> * Start small: Trying to introduce TDD to an entire development team at once can be overwhelming. Instead, start by introducing TDD to a small group of developers and work with them to adopt the process. Once they have become comfortable with TDD, they can help to spread the culture to other team colleagues.

* **_협업을 장려해주세요_** : TDD는 개발자, 테스터, 이해관계자 모두가 참여하는 협업적인 프로세스입니다. 팀 동료들에게 함께 테스트와 코드 작성, 서로의 작업 검토를 하도록 권장하세요. 이는 프로젝트 요구사항의 이해와 의사소통을 개선하는 데 도움이 됩니다.

> * Encourage collaboration: TDD is a collaborative process that involves developers, testers, and stakeholders. Encourage your team colleagues to work together to write tests and code, and to review each other's work. This will help to improve communication and understanding of project requirements.

* **_성공을 축하하세요_** : 성공을 축하하는 것은 TDD의 이점을 강화하고 채택을 촉진하는 데 도움이 될 수 있습니다. TDD를 사용하여 테스트를 성공적으로 작성하거나 기능을 구현하는 팀 동료가 있을 때, 그들의 성공을 축하하고 그들의 노력을 인정해주세요.

> * Celebrate successes: Celebrating successes can help to reinforce the benefits of TDD and encourage adoption. When a team colleague successfully writes a test or implements a feature using TDD, celebrate their success and recognize their efforts.

* **_정량화하기_** : TDD 채택의 성공을 측정하는 것은 개선할 부분을 파악하고 프로세스의 이점을 증명하는 데 도움이 될 수 있습니다. 코드 커버리지, 버그 비율 및 개발 주기 시간과 같은 지표는 TDD의 효과를 추적하는데 사용될 수 있습니다.

> * Measure success: Measuring the success of TDD adoption can help to identify areas for improvement and demonstrate the benefits of the process. Metrics such as code coverage, bug rates, and development cycle times can be used to track the effectiveness of TDD.

# Conclusion

* TDD는 고품질 소프트웨어를 구축하고 오류를 줄이기 위한 중요한 프로세스입니다. 그러나 팀 동료들에게 TDD를 채택시키는 것은 도전적일 수 있습니다. 본인이 모범을 보여주고, 교육을 제공하며, 작은 단계부터 시작하고, 협업을 장려하며, 성공을 축하하고, 성공을 측정함으로써 팀 동료들에게 효과적으로 TDD 문화를 전파할 수 있습니다.
* (셀프 감수를 해보니) TDD에 대한 교과서적인 (원론적인) 내용을 전달하는 것 같아서 민망하기도 하고, 짧은 지식에 스스로를 책망하게 되네요. `기술적 탁월함`을 더 배양해서 다른 개발자들에게 `유레카`를 보여줄 수 있는 내용으로 다시 찾아 오겠습니다.

> In conclusion, TDD is an important process for building quality software and reducing errors. However, getting your team colleagues to adopt TDD can be challenging. By leading by example, providing training, starting small, encouraging collaboration, celebrating successes, and measuring success, you can effectively spread TDD culture to your team colleagues.

# Epilogue
이 글을 쓰기까지 내부적으로 논의되었던 날 것의 이야기를 말씀드리겠습니다.
아래 패널들은 우리 주변에서 쉽게 만나볼 수 있는 동료개발자입니다.

* A(SWE Hawkish), B(SWE Dovish), Y(DEV Hawkish), Z(DEV Dovish)

> B : TDD 문화를 전파한다는 것이 현실적으로 가능할까요? 구글도 TDD 사용하기까지 5년 이상의 시간이 걸렸고, 다른 개발팀을 설득하는데 솔직히 회의적입니다.

> A : 올해는 회사 CEO, 혁신센터의 지원 사격을 받으면서 추진하는 활동이기 때문에 유의미한 큰 목소리를 낼 수 있습니다. 회사에서 성공하려면 일단 회사가 시키는 일은 참여해보고 판단해도 늦지않습니다. 무조건적으로 거부하는 사람들은 회사에서 도태됩니다. 회사 선배들(부사장, 사장)의 조언을 들어도 회사가 시키는 일은 일단 열린 마음으로 수용하고 실천해봐야 한다고 생각합니다.

>> B & Z : (wow~ 회사 선배들의 직책 보소~)

> Z : TDD에 관심도 있고 관련된 교육을 받고 싶은데, 현업에 치이고 교육할 시간도 없습니다. 교육 기회의 혜택도 많은 것 같지 않고요.

> A : Z님의 업무 로드 밸런싱이 정상적인지 리더가 안챙겨주나요? 부재시 협업 동료들은 없나요? 설마 교육 기회가 오픈되어 있지 않고, 깜깜이 방식은 아니죠?

> Y : 이미 자체적으로 유닛 테스트(Unit Test)를 수행하고 있고 TEM 지표도 평타는 칩니다. 업의 특성상 통합 테스트(Integration Test), E2E(End to End) 테스트가 더 중요합니다.

> A : 통합 테스트, E2E 테스트는 비용이 훨씬 비싼데... 과제 마일스톤(Milestone)을 앞 당기기(shift left) 위해서는 유효한 유닛 테스트가 필수적인데... TDD의 궁극적인 목적은 충분한 테스트 케이스 확보를 바탕으로 리팩토링을 원활히 하기 위한 것이라고 배웠습니다. 가독성 높고 유지보수가 편한 S/W 개발을 위해서 리팩토링은 끊임없이 해야하는 개발 활동입니다. 후대를 위해서라도...

> Y : 상용을 하는 입장에서 탁상곤론이고 실효성 없다고 생각합니다. 상용을 직접 해보시면 TDD 개발 문화 적용이 어렵다는 것을 알거에요.

> A : 상용도 오랜 시간 해봤고, 충분히 경험해본 개발자들이 S/W Engineering 관점에서 TDD 문화를 전파하려고 애쓰는 것입니다. 선진사들의 S/W 품질이 높은 이유가 있고, 당사 S/W 품질이 후진 이유가 다 있습니다. `지금처럼 살거나, 지금부터 살거나` 본인의 의지와 노력, 시도가 중요합니다.

>> Z : (귓솟말로 B에게) 팀 전배가고 싶은데 어떻게 해야하나요?

>> B : 팀장님 면담하고 허락받으세요. 오시는 분 환영합니다. 용기있는 자만이 자기 개발하면서 회사 생활할 수 있어요~

이상은 녹취록을 발췌하여 고민했던 내용들을 많이 순화해서 써본 글입니다. 조직에서 새로운 무언가를 전파하려는 사람과 수용하려는 사람 모두 스트레스를 받습니다. "빨리 실패하고 자주 반복하라"는 책(구글 엔지니어는 이렇게 일한다.) 글귀가 생각납니다. 계속 두들기다보면 선진사의 좋은 S/W 개발 문화가 당사에도 스며드는 날이 오겠죠?

## 선진(회)사?
> Z : 브랜드 순위나 위상을 봤을때 우리도 선진사 아닌가요?

> B : 제조사로는 선진사 인정하나, S/W 회사로서는 글쎄요~ 갈 길이 좀 멀죠...

> B : 이런 비유를 들어볼게요. 당사를 퇴사한 개발자가 있습니다. 1년이 지나서 당사를 재입사 할 수 있을까요? 인사 규정상 2년이 경과해야 재입사가 가능합니다. 단, 선진사(구글, 메타, 엔비디아, MS, ...) 로 취직했다가 다시 당사로 오겠다는 사람은 재입사가 가능합니다. 선진사란 그런 곳이죠. ^^