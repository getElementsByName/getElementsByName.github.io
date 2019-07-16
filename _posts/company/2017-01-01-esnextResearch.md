---
layout: post
title:  "사내 esnext 리서치"
description: ""
categories: ['company']
---
- 사내에 es2015을 사용하는 개발자들이 겪은 비슷한 문제를 수집하여 공유하고 다른 개발자들이 같은 문제를 겪지 않도록 도와주기 위한 목적
  - 네이버 자바스크립트 코딩컨벤션
  - 사내 es.next 개발자 인터뷰
  - (참여/메인개발) ES6+ 변환 테스트 페이지 개발
  - (참여/메인개발) 사내 기술 행사 참여

### ES6+ 변환 테스트 페이지
- ES6+ Transpiled 코드 테스트

![test_min](/assets/image/esnextResearch/test_min.png){:width="100%" style="max-width: none;" }
- 브라우저별 ES6+ Transpiled 테스트 결과

![summary_min](/assets/image/esnextResearch/summary_min.png){:width="100%" style="max-width: none;" }

### 사내 개발 행사(엔지니어링 데이) 참여
- 부서 ES next 관련 활동 소개
- 퀴즈 페이지
  - 운영: 퀴즈 생성 및 퀴즈 결과 관리, 사용자: 퀴즈 풀기

![esnext_quiz](/assets/image/esnextResearch/esnext_quiz.png){:width="100%" style="max-width: none;" }

### 기술
- ES6+ 변환 테스트 페이지
   - js parsing(babylon/estraverse/escodegen)
   - es6+ 코드 변환 처리를 위한 webpack loader
   - mocha HTML Reporter를 위한 webpack plugin
- ES next 퀴즈
  - MEAN stack (mongo, express.js, Angular4, node.js)