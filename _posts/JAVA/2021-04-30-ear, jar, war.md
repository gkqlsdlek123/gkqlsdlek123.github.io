---
layout: post
title: ear, war, jar 차이 
subtitle: compile
tags: [ear, war, jar, JAVA]
categories: [java]
comments: true
---
```
ear, war, jar파일에 대해서 알아보겠습니다
 
1. EAR(Enterprise Archive)
 하나의 웹 어플리케이션 단위를 넘어 실제 서버에서 배포하기 위한 단위입니다. 이를 위해서 jar와 war를 묶어서 각각의 기능을 지원합니다
 
 
2. WAR(Web Archive)
웹 어플리케이션을 지원하기 위한 압축 방식입니다. 웹 어플리케이션을 지원하기 위해서 war압축방식은 jsp, servlet, gif, html, jar 등을 압축하고 지원합니다.
 
 
3. JAR(Java Archive)
JAR는 여러 개의 자바 클래스 파일과 클래스들이 이용하는 관련 리소스 등 메타데이터를 하나의 파일로 모아서 자바 플랫폼에 응용 소프트웨어나 라이브러리를 배포하기 위한 소프트웨어 패키지 파일 포맷입니다. 컴퓨터 사용자들은 JDK에 포함된 jar 명령러를 이용하여 jar파일을 만들거나 압축을 풀 수 있습니다.
 
4. 사용이유(jar, war 등)
사용 단위는 ear > war > jar > class입니다
jar, war등을 사용하는 이유는 파일을 압축해 용량을 가벼워지게하고 그렇게되므로 관리가 편해지기 때문입니다
```

