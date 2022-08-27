---
date: 2022-05-08 08:08:05
layout: post
title: "What is Carrying Capacity"
subtitle: 우리의 서비스는 몇 명의 고객에게 만족감을 줄 수 있는가?
description:
image: /assets/img/posts/carrying-capacity/toss.png
optimized_image:
category: Business
tags:
  - Startup
author: dayone
paginate: false
---

<br/>물영아리 오름을 다녀와 상쾌한 기분으로 컴퓨터를 켠 주말 오후에 Product Owner를 위한 [영상](https://www.youtube.com/watch?v=tcrr2QiXt9M) 중 재미있는 개념을 배웠다. 바로 carrying capacity라는 개념이다. 이 carrying capacity는 생태학에서 나오는 개념으로 어떠한 환경이 여러 생물종들을 얼마나 수용할 수 있는지 설명하는 개념이다. 영상에서는 호수가 수용할 수 있는 물의 양을 예시로 들어서 개념을 설명한다. 이 생태학적인 개념을 비지니스에 끌고 들어오면 우리의 product는 환경이 되고 유저들이 생물종이 된다. 그렇다면 우리는 carrying capacity를 통해 우리의 product가 몇 명의 유저들에게 만족감을 줄 수용력이 있는지 측정해볼 수 있다.

<br/>Carrying Capacity는 `유입되는 유저 수(inflow)`를 `이탈되는 유저의 비율(churn rate)`로 나눈 수치이다. 유의할 점은 분자는 숫자 이지만 분모는 비율이다. 매 iteration (window size로 생각해도 좋다) 마다 유입되는 유저의 수와 이탈되는 유저의 비율이 고정되어있다면 iteration이 무한정 돌 때 수렴하게 되는 유저의 수가 carrying capacity이다. 예를 들어 매일 100명의 유저가 유입되고 총 유저 중 1퍼센트가 이탈한다면 이 서비스의 carrying capacity는 1만명이라고 할 수 있다. 총 유저가 1만명이면 유입되는 유저의 수가 이탈하는 유저의 수와 일치하기 때문에 총 유저의 수는 변하지 않는다. 만약 현재의 유저수가 1만 명 이하라면 유저수는 1만명까지 증가하게 될 것이고 1만명이상이라면 1만명까지 감소하게 될 것이다. 결국 고객 수의 증감은 carrying capacity를 통해 측정이 가능하며, 스타트업의 생명은 이 carrying capacity를 향상시키는 데 있다고 해도 과언이 아니다.

<br/>데이터를 볼 때 유의할 점은 광고나 마케팅처럼 단기적으로 유입되는 유저 수를 늘려주는 요인들을 발라내고 inflow를 측정하는 것이다. 고비용의 광고를 집행하거나 푸쉬 알림을 증가시켜서 유입되는 유저의 수를 늘리게 되면 그 효과는 일시적으로 총 유저수를 늘려서 지표가 향상된 것처럼 보이지만 carrying capacity를 향상시켜주지 않기 때문에 시간이 흐르면 광고의 효과는 빠지고 유저 수는 감소하고 만다. J 커브를 그리려는 스타트업은 제품 자체의 효력으로 inflow를 증가시키고 churn rate를 감소시키는 방향으로 총력을 기울여야 한다.

<br/>