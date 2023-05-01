---
layout: home
---

# 0428

# 마리아 DB

- 마리아 DB는 오픈소스의 관계형 데이터베이스 관리 시스템이다.
    - 관계형 데이터베이스 관리 시스템은 연관된 데이터를 테이블로 정의하고 각 테이블간 관계를 나타내는 것을 관계형 데이터베이스라고 한다.
    - 이러한 관계형 데이터베이스를 관리하는 소프트웨어가 관계형 데이터베이스 관리시스템이다.
- MySQL과 동일한 소스 코드를 기반으로 하며 GPL v2 라이선스를 따른다.
    - GPL v2 ⇒ 자유 소프트웨어 재단(FSF)에서만든 자유 소프트웨어 라이센스로 GNU-프로젝트로 배포된 프로그램의 라이센스를 사용하기 위해 작성되었다.
    - 아래는 GPL v2의 네 가지 조항이다.
    
    ① 컴퓨터 프로그램을 어떤 목적으로든지 사용할 수 있다 
    ② 컴퓨터 프로그램의 복사를 언제나 프로그램의 코드와 함께 판매 또는 무료로 배포할 수 있다 
    ③ 컴퓨터 프로그램의 코드를 용도에 따라 결정할 수 있다 
    ④ 변경된 컴퓨터 프로그램 역시 프로그램의 코드와 함께 자유로이 배포할 수 있다'라는 네 가지 조항을 명시하고 있다.
    
- mySQL은 스웨덴 MySQL AB이 만들었으나 썬마이크로시스템즈가 인수하였고 이후 오라클이 썬을 인수하며 실질적인 소유주는 오라클이다. ⇒ GPL 라이센스를 따르게 되었으나 MySQL을 상용화하는데 사용하게 된다면 라이센스 요구 사항을 밝히지 않은 오라클이었기에 비용을 지불할 수도 있는 상황이 되어 불안감이 증폭되었다.
- 위와 같은 문제로 MySQL AB 출신 개발자들이 만든 것이 MariaDB이다. 초창기 버전은 MySQL 버전을 기반으로 포크하였기 때문에 거의 모든 기능이 호환된다.
- 마리아 SQL에는 저장엔진 **Aria**와 **InnoDB**를 교체할 수 있는 **XtraDB** 저장 엔진을 포함하고 있다.

### ARIA

- Aria는 디스크 기반 및 메모리 기반 저장 엔진 중 하나로 여러 플랫폼에서 실행가능하다는 장점이 있다.
- 대규모 트랜잭션 환경에서 더욱 안정적으로 동작한다.
- 하지만 ACID의 특성을 지원하지 않기 때문에 여러 스레드에서 동시 작업하는 경우 성능 문제가 발생한다.
- 메모리 기반이기 때문에 캐시에 저장하여 빠른 읽기 및 쓰기 작업을 수행할 수 있기 때문

### InnoDB

- 마찬가지로 저장 엔진 중 하나로 ACID 특성을 지원하며 다중 버전 동시성 제어 및 트랜잭션 롤백 기능을 제공한다.

### XtraDB

- InnoDB 저장 엔진의 포크로 시작된 것으로 안정성, 성능, 및 확장성을 향상시키는 목적으로 제작된 것이다.
- 대규모 트랜잭션 및 고성능 OLTP 애플리케이션에 적합하다.