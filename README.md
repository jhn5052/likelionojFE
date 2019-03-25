# LikeLion LAB : HufsLion OnlineJudge 프론트 엔드
[![vue](https://img.shields.io/badge/vue-2.5.13-blue.svg?style=flat-square)](https://github.com/vuejs/vue)
[![vuex](https://img.shields.io/badge/vuex-3.0.1-blue.svg?style=flat-square)](https://vuex.vuejs.org/)
[![echarts](https://img.shields.io/badge/echarts-3.8.3-blue.svg?style=flat-square)](https://github.com/ecomfe/echarts)
[![iview](https://img.shields.io/badge/iview-2.8.0-blue.svg?style=flat-square)](https://github.com/iview/iview)
[![element-ui](https://img.shields.io/badge/element-2.0.9-blue.svg?style=flat-square)](https://github.com/ElemeFE/element)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudgeFE.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudgeFE)

* * *
## 개발자
 * 팀장 : 한민지
 * 팀원 : 박준호, 원상현, 신정수

## 특징

+ Webpack3 을 이용한 다중 페이지
+ 쉽게 사용 가능한 codemirror editor
+ 시각화 모듈(echarts 활용)
+ 사용자 친화적인 명령어 가능

## 시작 방법

nodejs **v8.12.0** 버전이 설치되어있어야 합니다.

```bash
* npm을 통해 설치합니다.
  -  sudo npm install
  
* 웹팩 DLL 레퍼런스를 사용하려 빌드 시간을 절약합니다.
* 이 명령어는 build/webpack.dll.conf.js 내부의 패키지를 업그레이드 하지 않았다면 한번만 수행하면 됩니다.
  - NODE_ENV=development npm run build:dll

#  개발 서버에서 백엔드 서버에 프록시 테이블을 설정합니다.
  - export TARGET=http://Your-backend
  
# 8080포트에서(localhost:8080) 프론트 서버가 생성됩니다.
  - npm run dev
```
실행 이후 호스트 80포트 혹은 443번 포트와 본 서버의 8080포트와 포트 포워딩을 해줘야 합니다.

## Screenshots

*이미지 추가*

## Browser Support
  
  * 인터넷 익스플로러 10 이상 버전을 포함한 다양한 브라우저

## 온라인 저지 백엔드
  * 기본적으로 온라인 저지 백엔드는 Qingdao University의 Online Judge Server 모듈의 Docker Version 사용
  * 한글 패치 적용
  
## 향후 개발 방향
  * 멋쟁이사자처럼 운영진 및 팀원들에게 여러 난이도와 알고리즘을 제공하여 채점 정보를 활용해 이용자들의 수준을 판별하고 분류
  * REST API를 활용한 Micro Service 원칙을 철저하게 따름
  
## LICENSE

[MIT](http://opensource.org/licenses/MIT)
