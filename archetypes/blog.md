---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
slug: "" # 해당 포스트 URL의 꼬리부분에 붙을 부분(비워놓으면 파일명) => seo 최적화에 유리
description: "" # 검색엔진이 찾는 부분
keywords: [] # 검색엔진이 찾는 부분
draft: true # true: 비공개상태 // false: 공개상태
tags: [] # 내 블로그 내부 분류
math: false # 수학 수식을 코드로 작성하면 자동으로 이쁘게 랜더링해주는 것을 사용할 것인가?
toc: false # 1024px이상의 브라우저 크기에 한해서 오른쪽 사이드에 뜨는 '목차(toc)' 기능을 사용할 것인가?
---
