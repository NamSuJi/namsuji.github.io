---
layout: post
title: "[JSP]게시판-DBConnection"
description: 데이터 베이스에 접근하는 클래스
headline: 
modified: 2020-01-24
category: webdevelopment
tags: [JSP, board]
imagefeature: 
mathjax: 
chart: 
comments: true
share: true
featured: true
---
> #### DB에 접근하기 위한 DBConnection
>> 게시판에 필요한 write.jsp, edit.jsp, writeSave.jsp, editSave.jsp, delete.jsp 등등 거의 모든 페이지에서 DB에 접근하기 위해 Connection이 필요합니다.  
>> 코드는 마찬가지로 [이곳](https://github.com/NamSuJi/Web/tree/master/Board)에 저장해두었습니다.  
>> Connection과 Statement, ResultSet를 한꺼번에 관리해주기 위해 클래스를 생성하고 함수를 만들어주었습니다.  
>
> ![img](/postimage/Board/dbconnec.png)
