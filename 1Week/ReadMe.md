# JVM 이란?
1. JAVA Virtual Machine, 자바 가상 머신의 약자를 줄여서 부르는 용어이다.
2. JVM의 역할은 자바 애플리케이션을 클래스 로더를 통해 읽어들여 자바 API와 함께 실행하는 것이다.
3. JVM은 JAVA 와 OS 사이에서 중개자 역할을 수행하여 JAVA 가 OS에 구애받지 않고 재사용을 가능하게 해준다.
4. 가장 중요한 메모리관리, Garbage Collection을 수행한다.
5. JVM은 스택기반의 가상 머신이다. ARM 아키텍쳐 같은 하드웨어는 레지스터 기반으로 동작하는데 비해 JVM은 스택기반으로 작동한다.

참고 : https://asfirstalways.tistory.com/158

# 컴파일 하는 방법 and 실행하는 방법

1. cmd 창 실행
2. cmd 창에서 자바 파일 경로로 이동
3. javac 자바파일명.java 를 이용하여 컴파일을 진행
4. java 자바클래스파일명 실행

참고 : https://as-i-am-programing.tistory.com/2

# 바이트코드란?

자바 가상머신이 이해할 수 있는 언어로 변환된 자바 소스코드를 의미.
자바 컴파일러에 의해 변환되는 코드의 명령어 크기가 1바이트라서 자바 바이트 코드라고 불림.
이러한 자바 바이트 코드의 확장자는 .class이다.
자바 바이트 코드는 자바 가상 머신만 설치되어 있으면 어떤 운영체제에서라도 실행가능.

# JIT 컴파일러란 무엇이며 어떻게 동작하는지

프로그램이 실행중인 런타임에 실제 기계어로 변환해주는 컴파일러를 의미.
동적 번역(Dynamic Translation)이라고도 불리는 이 기법은 프로그램의 실행속도를 향상시키기 위하여 개발되었음.
즉, JIT 컴파일러는 자바 컴파일러가 생성한 자바 바이트 코드를 런타임에 바로 기계어로 변환하는데 사용함.

# JVM 구성요소

1. 자바 인터프리터(Interpreter)
2. 클래스 로더(Class Loader)
3. JIT 컴파일러(Just - In - Time Compiler)
4. 가비지 컬렉터 (Garbage Collector)

참고 : http://www.tcpschool.com/java/java_intro_programming

# JDK와 JRE 의 차이
JDK 는 JAVA 플랫폼에서 JAVA 응용프로그램을 개발하는데 사용되는 소프트웨어 개발환경
JRE 는 JAVA 응용프로그램을 실행하는데 필요한 최소 요구사항을 제공하는 JDK의 

