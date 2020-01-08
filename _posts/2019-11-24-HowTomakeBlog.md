---
layout: post
title: "블로그 만들기"
description: 
headline: 
modified: 2019-11-24
category: webdevelopment
tags: [jekyll]
imagefeature: 
mathjax: 
chart: 
comments: true
share: true
featured: true
---

Github 블로그 만들기
==================

### 블로그를 시작하기에 앞서,
그동안 블로그를 만들어보려고 많은 분들의 Github 블로그 제작 글을 찾아봤습니다.
Jekyll을 이용하는 방법도 Ruby를 설치해서 하는 방법, 다른 분들이 만들어둔 블로그를 Fork해서 바꾸는 방법으로 나뉘었습니다.
하지만 간단하게 바꾸어 저만의 블로그에 포스팅을 할 수 있게 설명이 있지는 않았습니다.
그러다가 이 분의 [블로그](https://github.com/newhiwoong/newhiwoong.github.io)를 참조해 블로그를 만들 수 있었습니다.
거의 똑같겠지만 제가 어떻게 만들 수 있었는지 보여드리려 합니다.  

> ## Github 계정 및 Repository 생성
 >> 1. 깃허브 메인 페이지로 들어가 준다 -> sign up 클릭 -> 가입
 ![howtomake1](https://user-images.githubusercontent.com/52815908/71948623-f1293b00-3213-11ea-9bca-fec744ac7bea.PNG)

 >> 2. 가입 후 새로운 레포지토리 생성 -> 레포지토리 이름(자신의ID.github.io) -> README.md 는 생성 X 
 ![howtomake2](https://user-images.githubusercontent.com/52815908/71948688-2c2b6e80-3214-11ea-8cf7-7573854a3913.PNG)
 >> 3. 만들어진 레포지토리로 들어가 아래와 같이 색칠된 주소 복사 
 ![howtomake3](https://user-images.githubusercontent.com/52815908/71948689-2c2b6e80-3214-11ea-90bf-db9120feac62.PNG)
 
> ## Git 부분
 >> * 설치되어 있지 않은 경우 -> [여기로](https://git-scm.com/downloads) 이동 후 자신에게 맞는 운영체제로 설치  
 >> 1. 내 컴퓨터 -> 로컬 디스크 C -> github 파일 생성 -> blog 파일 생성  
 >> 2. blog 파일에서 마우스 우클릭 -> Git Bash Here 클릭  
 >> 3. 아래와 같이 입력  

> ## 순서
 >> 1. 블로그 [참조](https://github.com/hmfaysal/Notepad) 에서 ZIP 파일로 다운 받는다  
 >> 2. 압축을 푼 후 post 폴더의 포스트를 삭제한다 , 나는 참고용으로 남겨뒀다  
 >> 3. images 에 cover을 제외한 모든 사진을 삭제한다, 그 후 자신의 프로필 사진, 로고 사진을 폴더에 추가한다 + 로고 사진은 아래 사진 위치에도 저장해준다  
 >> 4. Git 부분에서 만들어진 모든 파일을 폴더에 옮겨준다.  
