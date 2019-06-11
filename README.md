# SpringMVC RESTFul API
# 목차
- [1. REST 소개](#REST-소개)
- [2. REST 제약조건](#REST-제약조건)
  - [2.1 클라이언트-서버](#클라이언트-서버)
  - [2.2 무상태성](#무상태성(stateless))
  - [2.3 캐시가능](#캐시가능)
  - [2.4 계층화시스템](#계층화시스템)
  - [2.5 코드 온 디맨드](#코드-온-디맨드)
  - [2.6 인터페이스 일관성](#인터페이스-일관성(Uniform-Interface))
- [3. REST API 설계방법](#REST-API-설계방법)
  - [3.1 URI 설계](#URI-설계)
  - [3.2 복수형을 사용하라](#복수형을-사용하라)
  - [3.3 행위설계](#URI-설계)

# 개요
- REST API를 기존의 MVC 패턴으로 만들어보고, SpringBoot Data REST를 이용하여 개발해보는 레퍼지토리입니다.

# REST 소개
REST는 웹과 같은 하이퍼미디어 시스템에서 사용하는 **통신네트워크 아키텍쳐**이며, 
**HTTP**와 **URI**의 단순하고, 간결한 장점을 계승한 네트워크 아키텍쳐입니다.
- REST의 목적
  - 구성요소 상호작용의 규모확장성
  - 인터페이스의 범용성
  - 구성요소의 독립적인 배포
  - 중간적 구성요소를 이용한 응답 지연감속, 보안강화, 레거시 시스템 인캡슐레이션

# RESTful 제약조건
## 클라이언트-서버
- 이 제약조건의 기본원칙은 관심사의 명확한 분리입니다. 관심사의 명확한 분리가 선행되면 서버의 구성요소가 단순화되고, 확장성이 향상되어 여러 플랫폼을 지원할 수 있습니다.
## 무상태성(stateless)
- 서버에 클라이언트 상태정보를 저장하지 않는 것을 말합니다. 단순히 들어오는 요청만 처리하여 구현을 더 단순화합니다. 단, 클라이언트의 모든요청은 서버가 요청을 알아듣는 데 필요한 정보를 담고 있어야합니다.
- 클라이언트의 컨텍스트(세션, 쿠키 등)을 서버에 저장하지 않습니다. 이로써 서비스의 자유도가 높아지게됩니다.
## 캐시가능
## 계층화시스템
## 코드 온 디맨드
## 인터페이스 일관성(Uniform Interface)

# REST API 설계방법
## URI 설계
## 복수형을 사용하라
## 행위설계