---
layout: post
title: "[Markdown]이미지 저장"
description: 이미지 저장하는 방법
headline: 
modified: 2020-01-14
category: markdown
tags: [Github, Markdown, image]
imagefeature: 
mathjax: 
chart: 
comments: true
share: true
featured: 
---

#### 이미지를 저장하는 방법으로 두 가지가 있다  

1. Github의 Issue를 이용하는 방법  
2. 해당 레포지토리에 이미지를 넣고 경로를 지정해주는 방법  

> ### 1.Github의 Issue를 이용하는 방법
> 
> 1.1 레포지토리의 Issue에 들어가 New Issue를 클릭한다.
>> ![issue1](https://user-images.githubusercontent.com/52815908/72305590-98e0b600-36b7-11ea-8dfe-37b887a8f885.PNG)
> 
> 1.2 아래와 같이 원하는 이미지를 마우스로 끌어 Write에 놓는다. 
>> ![issue2](https://user-images.githubusercontent.com/52815908/72305626-ba41a200-36b7-11ea-8411-f7619189170b.PNG)
> 
> 1.3 굳이 바꿔주지 않아도 되지만 마크다운 문법으로 바꿔서 쓸 수 있다. 
>> ![issue3](https://user-images.githubusercontent.com/52815908/72305628-ba41a200-36b7-11ea-84ca-b1bcb3ccbab8.PNG)
>
> 
> ### 2.해당 레포지토리에 이미지를 넣고 경로를 지정해주는 방법  
> 
> 2.1 레포지토리 안에 _image 디렉토리 생성
>> ![dirimage1](https://user-images.githubusercontent.com/52815908/72305895-96329080-36b8-11ea-8e20-d83d45bd9311.PNG)
>
> 2.2 _image 안에 이미지 삽입
>> ![dirimage2](https://user-images.githubusercontent.com/52815908/72305896-96329080-36b8-11ea-8ac3-f196074b1348.PNG)
>
> 2.3 `![]()`를 사용해 이미지 경로 입력 
>> ![dirimage3](https://user-images.githubusercontent.com/52815908/72305898-96cb2700-36b8-11ea-8767-b3aeb6616df4.PNG)
>
> * `_posts` 디렉토리에서 `postimage`의 이미지를 사용하고 싶을 시에 경로는 `(/postimage/dirimage.JPG)`가 되어야한다.
