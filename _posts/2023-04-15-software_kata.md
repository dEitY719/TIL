---
layout: post
title: Software KATA
subtitle: Which doctor should I see to improve my chances of survival?
# gh-repo: daattali/beautiful-jekyll
# gh-repo: https://github.samsungds.net/pages/byoungwoo-yoon/deity719/
# gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/KATA-thumb.png
cover-img: /assets/img/KATA-cover.png
# share-img: /assets/img/path.jpg
tags: [kata, tdd]
comments: true
---

# `심근경색` <sub>(feat. 어떤 의사에게 치료받아야 생존율을 높일 수 있을까?)</sub>
소중한 가족 중 한명이 `심근경색`이라는 질병에 걸렸습니다. 여기 15년차의 수술 경험이 많은 심장외과의사와 5년차의 경험이 많지 않은 심장외과의사가 있습니다. 당신은 어떤 의사에게 수술과 치료를 맡기시겠습니까? 

저라면 15년차 의사에게 수술받으려고 했을거에요. `늙은 말이 길을 안다`는 뜻의 [노마식도(老馬識途)](https://namu.wiki/w/%EB%85%B8%EB%A7%88%EC%8B%9D%EB%8F%84)를 중학교 한문 시간에 주입식으로 받아들인 세대라서 선택했다고 말하면 근거가 될까요? 대부분 연륜을 맹신하며 선배 심장외과의사를 선택할 것이라고 생각합니다.

# 년차가 뭣이 중한디? <sub>(feat. 끊임없이 공부한 의사에게 수술받으면 됩니다.)</sub>
미국의 심근경색 환자를 대상으로 조사한 결과에 따르면, 5년차 심장외과의사로부터 수술 받은 환자의 생존율이 더 높았다고 합니다. 이유는 40세 미만의 심장외과의사들이 급성심근경색 후에 아스리핀이나 베타 차단제를 이용하면 생존율을 높인다는 사실을 인지하고 있는 비율이 높았고<sup>1)</sup>, 이를 치료과정에 적용했기 때문에 생존율이 높았다고 합니다.

다시말하면, 의사의 경력이 길어질수록 최신 치료기준을 따르지 않는 경향이 있고, 73%의 의사가 치료방법에 대한 지식이 세월이 지날수록 낮아진다고 합니다. 즉, 경험이 많은 의사일수록 개선된 새로운 치료방법에 대한 관심과 지식이 적어, 환자의 생존율이 높지 않을 수 있다는 뜻입니다. 어느 분야든 끊임없이 공부하고 새로운 것을 받아들여야 하는 상황이네요.

# 소프트웨어 KATA
당신 주변에 소프트웨어 장인이 있나요? 최신 소프트웨어 기술에 관심이 많고 신규 시스템 수용에 적극적이고  새로운 소프트웨어 개발문화를 전파하려는 개발자와 함께 일하고 있다면 당신은 운이 좋은 사람입니다. 그런 사람이 없다면 당신이 소프트웨어 장인이 되려고 노력하면 됩니다. 생명을 다루는 의사처럼 Critical 하지는 않지만, 윈도우 블루스크린을 생성하는 소프트웨어를 개발해서는 않으려고 노력해야겠죠?

소프트웨어 개발에서 적극적으로 사용되는 KATA는, 단순한 예제나 문제를 해결하고 반복적으로 연습함으로써 개발자의 역량과 팀의 생산성을 향상시키는 방법론입니다. KATA는 일본어에서 "품세"를 의미하는 단어입니다. 그러나 소프트웨어 업계에서 KATA는 개발자들이 반복적인 문제를 풀면서 자신의 역량을 강화하는 것을 의미합니다. 소프트웨어 개발에서 문제 해결 능력을 강화하기 위해 반복적인 연습이 필요하다는 인식에서 비롯됩니다. 멋진 품세를 유지하기 위해서 끊임없이 수련하는 것처럼 말이죠.

# KATA의 효과
KATA는 개발자들이 문제 해결 능력을 강화할 수 있는 여러 가지 이점을 제공합니다. 
1. 반복적인 연습은 개발자들이 다양한 상황에서 문제를 해결하기 위해 필요한 기술을 자동화하고, 창의적인 문제 해결 능력을 키울 수 있도록 도와줍니다. 
2. KATA는 새로운 도구나 기술에 익숙해지는 데 도움이 됩니다. 예를 들어, 새로운 프로그래밍 언어나 프레임워크를 배우는 개발자는 KATA를 사용하여 새로운 기술을 익힐 수 있습니다. 
3. KATA는 팀의 생산성을 향상시키는 데도 도움이 됩니다. 팀원들이 반복적인 문제 해결 능력을 향상시키고, 빠르게 문제를 해결할 수 있게 되면 프로젝트의 성공에 도움이 됩니다.

# KATA 예시
* [코드카타](http://www.codekatas.org/)
* [CodeKata](http://codekata.com/): Because experience is the only teacher

소프트웨어 KATA와 관련된 사이트는 많이 있습니다. 대부분 간단한 문제가 주어지고 이를 구현하여 제출하면 채점을 해주는 방식입니다. 아울러 다른 개발자는 어떻게 개발했는지를 보여주기 때문에 남들이 많이 사용하는 효율적인 코드 기법도 배울수 있습니다.

## 샘플 문제
> 파이썬 pandas 관련 문제입니다. `points` column의 값을 참고하여 미슐랭 'stars' column의 값을 계산하세요.
> * 95점 이상은 3 스타
> * 85점 이상은 2 스타
> * 85점 미만은 1 스타

소프트웨어 KATA 를 통해 자신의 코드를 보면서 부끄러움도 느끼고, 다양한 해법을 확인하면서 실력도 향상할 수 있는 좋은 기회가 될 것입니다. 아래 4개는 모두 `pass`된 Solution 입니다. 여러분은 어떻게 코딩 했을까요? 가장 많은 패턴의 Solution은 무엇일까요? 어떤 Solution이 유레카 별점을 받았을까요? 궁금하시면 바로 KATA 사이트에 가입해서 도전해보세요.

## Solution A
``` python
def get_stars(row):
    if(row.points >= 95):
        return 3
    elif(row.points >= 85):
        return 2
    else:
        return 1
star_ratings = df.apply(get_stars, axis='columns')
reviews['stars'] = star_ratings
```
## Solution B
``` python
def get_stars(row):
    return 3 if row.points >= 95 else 2 if row.points >= 85 else 1
star_ratings = df.apply(get_stars, axis='columns')
reviews['stars'] = star_ratings
```
## Solution C
``` python
star_ratings = pd.cut(reviews['points'], bins=[0, 84, 94, 100], labels=[1, 2, 3])
reviews['stars'] = star_ratings
```
## Solution D
``` python
import numpy as np
conditions = [
    (reviews['points'] >= 95),
    (reviews['points'] >= 85)
]
choices = [3, 2]
star_ratings = np.select(conditions, choices, default=1)
```

# 기-승-전-TDD
TDD(Test Driven Development) 개발 문화를 확산시키고픈 강박관념이 기승전TDD(起承轉結)를 타이핑하고 있네요. 최초 계획한 16부작 드라마가 제작 국장의 강압에 20부작이 되는 순간 드라마 질은 떨어지는 법인데 말이죠.

* TDD 개발이 생경하더라도 소프트웨어 KATA 처럼 꾸준히 수행하다보면
* 기술 부채<sup>3)</sup>를 줄이는 효과와 함께 개발자들에게 복리의 마법 혜택을 선물할 것입니다.

# TL;DR
1. 노마식도(老馬識途) 맹신 말고 학습하는 사람 믿자.
2. 환자가 생명을 맡길수 있는 의사를 원하듯이 고객도 후진 소프트웨어는 원하지 않는다. 

<details>
<summary>페이 닥터 만큼 돈을 받으면 완벽한 소프트웨어를 개발할 수 있을까요?</summary>

<div markdown="1">

* 버그없는 Software는 없습니다.
* 완벽한 Software 없습니다.<sup>2)</sup>
* 끊임없이 도전하고 도전에서 배운 것을 가지고 개선하는 것이 가장 좋은 Software 입니다.

![Why](../assets/img/KATA_why_not_work_why_work.png)
</div>

</details>
<br>

3. 소프트웨어 KATA 사이트 가입하고 매일 수련하자.
4. 데이터에 기반한 의사결정을 지향하자. 

* 의약정책연구<sup>1)</sup> 결과(≒ Data)를 몰랐으면 계속 연륜을 맹신하며 생명을 맡기는 우를 범했을지도

# 참고
* <sup>1)</sup> 하버드 의대 2005년 의약정책연구, 나이티쉬 콘드리 박사
* <sup>2)</sup> `구글엔지니어는 이렇게 일한다` 본문에서
* <sup>3)</sup> 기술 부채(technical debt, code debt)는 더 나은 접근방식을 사용하는 대신(시간도 더 많이 필요) 쉬운(제한된) 솔루션을 채택함으로써 발생되는 추가적인 재작업의 비용