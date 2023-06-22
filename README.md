# -AWS-JavaStudy-202212

### [📖기술블로그(JAVA)](https://donotthinkjustdo.tistory.com/category/JAVA/%EC%82%B0%EB%8C%80%ED%8A%B9%28%EC%9E%90%EB%B0%94%29)
### [📖기술블로그(DB)](https://donotthinkjustdo.tistory.com/category/DB/%EC%82%B0%EB%8C%80%ED%8A%B9%28DB%29)

### JAVA 진행기간 2022.12.28 ~ 2023.03.02
### DB 진행기간 2023.01.19 ~ 2023.02.02
___

#### 📅 2022.12.28

##### 1) 프로그램
  - 짜여진 순서대로 실행되는 것
  - 언어: 의사소통의 도구
  - 기계어: 0 또는 1 컴퓨터가 이해할 수 있는 언어
  - 고급언어: 사람이 이해하기 쉬운 언어
  - 저급언어: 컴퓨터가 이해하기 쉬운 언어
  - 컴파일러: 사람의 언어로 명령한 소스코드를 컴퓨터가 알아 듣도록 변역해주는 역할

##### 2) JAVA
  - 제임스 고슬링이 만듬.
  - 한번 작성하면 어디서든 실행됨.
  - JVM(자바가상기계)를 만들어 JVM만 깔려있으면 어떤 하드웨어여도 상관없이 컴파일 가능 -> 컴파일러 통일
  - JVM: 바이트코드 사용
  - 클래스로딩: 클래스 단위로 소스코드 생성 필요한 클래스만 로딩해서 사용가능
  - 안정적인 언어(가비지 컬렉터): 동적 메모리 관리에 따른 쓰레기 값 자동 수거

##### 3) JDK 설치 및 환경변수 설정
  - JDK: JAVA 소스파일을 컴파일하고 실행하기 위해 필요 -> JDK 11버전 사용
  - 환경변수: 프로세스가 컴퓨터에서 동작하는 방식에 영향을 미치는 동적인 값들의 모임

##### 4) Spring tool 다운 및 설정
  - Spring 개발업체인 SpringSource가 직접 만들어 제공하는 이클립스의 확장판

___

#### 📅 2023.01.02

##### 1) 변수
  - 변하는 수
  - 자료형 + 변수명
  - 데이터를 담을 수 있는 통
  - 자료형: 사이즈, 변수명: 통의 이름
  - 제약사항이 존재함
  - 카멜표기법 사용 (스네이크 표기법, 헝가리안 표기법 등도 존재함)

##### 2) 자료형
  - 정수형, 문자형, 실수형, 논리형

##### 3) 상수
  - 항상 변하지 않는 값
  - 상수는 선언하면 무조건 초기화 필수
  - final 사용
  - 대문자로 표기하고 스네이크 표기법 사용

##### 4) 리터럴
  - 이미 정해져있는 값을 의미함

##### 5) 형 변환
  - 업캐스팅: 값이 작은 범위에서 큰 범위로의 형 변환(묵시적 형 변환)
  - 다운캐스팅: 값이 큰 범위에서 작은 범위로의 형 변환(명시적 형 변환)

___

#### 📅 2023.01.03

##### 1) 연산자
  - 연산에 사용되어지는 기호

##### 2) 문자열
  - 여러 문자를 하나로 묶은 것
  - 기본 자료형 X

##### 3) 스케너
  - 표준 입력: 콘솔에 키보드 입력을 받는 클래

___

#### 📅 2023.01.04

##### 1) 조건문(if문)
  - if: 가정적 조건을 나타냄
  - else: 이미 언급된 것에 덧붙여 또 다른, 혼자 사용불가

##### 2) 조건문(switch case문)
  - 해당 조건에 맞는 case를 찾는 문법
  - break: 제어문을 탈출, 제어문 흐름 중 break 이후 명령을 실행하지 않고 빠져나옴

##### 3) 반복문(for문)
  - 동일한 계산 또는 명령을 순차적으로 반복해야하는 경우
  - 순서가 있는 경우 사

##### 4) 반복문(while문)
  - 순서보다 조건이 중요할 때 사용

___

#### 📅 2023.01.05

##### 1) 매서드
  - 함수: 특정 기능을 정의한 코드들의 집합
  - 메서드: 함수의 종류 중 클래스 내부에 정의되어 있는 함수

##### 2) 객체지향언어
  - 객체: 세상에 존재하는 모든 것
  - 프로그래밍 관점에서는 객체들의 관계성을 사용하여 순차적으로 수행되는 프로그램 내에서 객체들 간에 관계를 형성하여 프로그램을 동작하게 함.
  - 특징
    - 상속: 상위 클래스의 모든 것을 상속받아 사용하는 것
    - 캡슐화: 데이터와 기능을 외부로부터 접근을 차단하고 권한 또는 절차 없이 데이터를 변경 또는 기능 수행을 할 수 없게 캡슐처럼 보호함 (데이터 은닉성)
    - 추상화: 추상적인 요소들을 묶어서 분류하는 것
    - 다형성: 객체의 기능이 다양한 형태를 가질 수 있음 (형 변환, 오버로딩, 오버라이드)
  - 장점
    - 재사용성: 상속을 통해 코드의 재사용을 높임
    - 생산성 향상: 클래스 단위의 부품들을 조립
    - 유지보수의 우수성: 구조화 된 소스코드 클래스 단위로 소스코드를 관리할 수 있음.
  - 단점
    - 객체를 세분화하여 설계해야함
    - 실행 속도가 절차지향 언어 대비 느림
    - 상속으로 인하여 관계가 많이 형성되면 코딩의 난이도가 높아짐.
  - 객체지향언어도 절차지향언어에 속하지만 객체의 관계가 추가된 것임.

##### 3) 클래스
  - 객체에 대하여 정의해 놓은 설계도 혹은 틀
  - 참조 자료형임.
  - 객체: 클래스를 통해 구현할 수 있는 모든 대상
  - 인스턴스: 객체가 실제로 구현된 것

##### 4) 생성자
  - 생성시에 호출됨.
  - 오버로딩이 가능
  - 기본 생성자는 기본적으로 활성화되면서 생략되어 있지만 오버로딩 시 비활성화됨. -> 비활성화 되면 다시 생성해서 사용가능
  - 기본생성자, AllArgsConstructor, 사용자 정의 생성자, RequiredArgsConstructor가 존재함.

___

#### 📅 2023.01.06

##### 1) 접근지정자
  - default: 동일 패키지 내에서만 참조가능
  - private: 동일 클래스에서만 참조가능
  - public: 모든 곳에서 참조가능
  - 데이터의 은닉성을 위해서 모든 멤버 변수들은 private를 선언해준다.
  - prviate 변수에 접근을 위해 getter와 setter를 생성해준다.
    - getter: 값을 확인할 때 사용
    - setter: 값을 수정할 떄 사용
   
##### 2) github
  - git: 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일 작업 조율하고 스냅샷 스트림 기반의 분산버전 관리 시스템
  - github 기본적인 사용
  - sourcetree 사용

___

#### 📅 2023.01.09

##### 1) 배열
  - 동일한 자료형의 데이터를 연속된 공간에 저장하기 위한 자료구조
  - 연관된 데이터를 그룹화하여 묶어줌.

##### 2) 리팩터링
  - 기존 소스코드를 정리하는 개념

___

#### 📅 2023.01.10

##### 1) 상속
  - 이미 구현된 클래스를 상속받아서 속성이나 기능을 확장하여 클래스 구현

##### 2) 추상클래스
  - 추상: 공통된 것을 묶어 두는 것
  - 추상 클래스: 추상적인 것들만 모아두는 클래스

##### 3) 인터페이스
  - 쉽게 생각하면 도구이다.
  - 인터페이스는 여러개 사용가능
  - 관계성을 잘보고 설계 해야함.

___

#### 📅 2023.01.11 ~ 2023.01.12

##### 1) Object 클래스
  - 가장 최상위 클래스
  - toString: 클래스의 정보를 출력함
  - hashCode: 데이터를 다루는 기법 중에 하나로 검색과 저장이 아주 빠르게 진행됨.
  - getClass: 생성된 객체의 주소값을 참조할 때 사용
  - equals: String을 비교할 때 사용
  - finalize: 소멸 시키고 싶지 않은 데이터가 있을 경우 소멸 후에 다시 그 객체를 생성해줌.

##### 2) static
  - 메모리 공간이 따로 존재해서 해당 메모리 공간은 모두가 공유하는 메모리 공간임.

##### 3) 싱글톤
  - 싱글톤을 사용할 때는 유일하게 하나만 존재하는 객체들

#### 📅 2023.01.13

##### 1) 제네릭
  - 데이터의 타입을 일반화 한다는 것을 의미함
  - 클래스나 메서드에서 사용할 내부 데이터 타입을 컴파일 시에 미리 지정하는 방법
  - 와일드카드: 어떠한 자료형이든 들어올 수 있음

##### 2) Lombok 사용
  - JAVA 라이브러리이며, 반복되는 getter, setter, toString 등의 메서드 작성 코드를 줄여주는 라이브러리
  - 어노테이션 기반으로 코드를 자동완성 해주는 라이브러리

___

#### 📅 2023.01.16

##### 1) 컬렉션
  - 프레임워크: 플레임(틀) + 워크(일) 틀안에서 일하는 것 -> 틀안에서 자유롭게 개발함(경력 유지 및 회사간의 현력에 용이함)
  - 컬렉션 프레임워크: 다수의 데이터를 쉽고 효과적으로 처리할 수 있는 표준화된 방법을 제공하는 클래스의 집헙
  - List, Set, Map 3가지가 대표적임
  - 프레임워크는 인터페이스이다.
  - List: 순서가 있는 데이터의 집합, 데이터 중복 허용
  - Set: 순서가 없는 데이터의 집합, 데이터 중복 허용 X
  - Map: 키와 값을 한쌍으로 이루어지는 데이터의 집합, 순서 X, 키는 중복 허용 X , 값은 중복 허용

##### 2) JSON
  - 속성-값이 쌍으로 되어 있음.
  - 인간이 읽을 수 있는 텍스트를 사용하는 개방형 표준 포멧
  - 모든 언어가 JSON을 사용함.

##### 3) 빌더 패턴
  - 변수에 넣고 싶은 값만 선택해서 넣을 수 있음.

___

#### 📅 2023.01.17 ~ 2023.01.18

##### 1) 예외
  - 개발자의 코딩 실수로 인해서 발생하는 프로그램 오류
  - 예외처리: 프로그램이 강제 종료되는 것을 막기 위해 예외처리를 해줌.
  - try-catch문 사용
    - try: 예외가 발생할 수도 있는 오픈소스
    - catch: 예외 발생 시 어떤 예외인지 파악하고 예외를 잡아줌.
    - finally: try-catch문이 실행되면 무조건 실행됨. (예외 유무 X)
  - Exception 클래스 사용
  - throws를 사용하면 예외를 미룰 수 있음

##### 2) 익명 클래스










