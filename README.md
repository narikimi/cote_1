# CAPTIMA_cote_1
### [chapter 01] 코딩 테스트 개요

**1. 코딩 테스트 준비를 돕는 서비스**
> 
> * **코드업**
>   * 난이도가 낮은 문제가 많아 처음 공부하는 사람에게 적합
>   * 기초 100제: 알고리즘 문제 풀이에서 자주 사용하는 기본 코드 유형과 관련된 문제
>   * 코딩 테스트 초보자는 코드업에서 경험을 쌓은 뒤 백준 온라인 저지로 넘어가는 것을 추천
>
> * **백준 온라인 저지**
>   * 가장 전형적인 코딩 테스트 형식(ACM-ICPC 형식)
>   * 국내 사용자가 많아 사용자 간의 질답 활발
>   * 문제 순서는 난이도와 무관
>   * solved.ac: 백준 온라인 저지 문제에 대한 난이도 정보 손쉽게 확인 가능
>   * [문제]-[알고리즘 분류] 탭으로 이동하면 '유형별 알고리즘'을 선택해서 풀 수 있음
>   * 삼성 SW 역량테스트 대비 문제집 제공
>
> * **프로그래머스**
>   * 카카오 공채 문제 모두 제공
>   * 다른 사람의 풀이 코드 열람 가능
>
> * **SW Expert Academy**
>   * 삼성 공식 알고리즘 학습 사이트
>   * '상시 SW 역량테스트' 제도 운영
>   * 난이도가 낮은 A형부터 응시 추천
>   * DFS/BFS를 활용하는 탐색과 시뮬레이션 문제 유형 자주 출제


**2. 코딩 테스트 언어**
> * **C/C++**
>   * 실행 시간이 다른 언어에 비해 빠름
>   * 하드웨어에 더 가까운 언어
>   * 알고리즘 대회 사이트에서 C++이 유리할 수 있음
>   * C++을 공부하는 과정에서 컴퓨터의 내부 동작 구조까지 더 자세히 알 수 있으며, 여러 산업에서 C++을 오래 사용한 만큼 인터넷에 참고할 양질의 자료가 많음
>  
>  * **Python**
>    * 배우기 쉽고 변칙적인 유형에 대응하기 쉬움
>    * C++이나 JAVA에 비해 코드가 짧고 직관적임
>    * 몇몇 알고리즘 구현에는 라이브러리를 추가할 필요 없이 소스코드 작성 가능
>    * 파이썬을 이용한 응시자 비율은 급격히 증가하는 추세
>    * 통상적인 기업 코딩 테스트 난이도의 기본 알고리즘 문제 풀이에는 파이썬이 유리하다는 인식 존재

**3. 복잡도**
```
복잡도는 알고리즘의 성능을 나타내는 척도이다.
```
**(1) 시간 복잡도**
  * 알고리즘을 위해 필요한 연산의 횟수 (알고리즘이 얼마나 오래 걸리는가)
    
**(2) 공간 복잡도**
  * 알고리즘을 위해 필요한 메모리의 양 (알고리즘이 얼마나 많은 메모리를 차지하는가)
```
보통 시간 복잡도와 공간 복잡도는 일종의 '거래 관계(반비례)'가 성립함
이때 메모리를 더 소모하는 대신 얻을 수 있는 시간적 이점이 매우 큰 경우가 종종 있는데, 이를 '메모이제이션 기법'이라 
```
**[시간 복잡도]**

알고리즘 문제를 풀 때 단순히 '복잡도'라고 하면 보통은 시간 복잡도를 의미함

**빅오(Big-O) 표기법**
  * 가장 빠르게 증가하는 항만을 고려하는 표기법
  * 함수의 상한만을 나타냄
