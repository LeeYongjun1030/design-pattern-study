# Strategy Pattern  
## Introduce 
서울대학교에 다니는 많은 학생들은 다양한 방법으로 학교에 통학한다.  
집이 가깝거나 기숙사에 사는 학생들은 직접 걸어서 학교에 온다.  
집이 멀거나 자취를 하는 학생들은 버스나 자동차를 이용해 학교에 온다.  

즉, 학생들은 환경에 따라 여러 가지 등교 전략을 수립한다.  
하지만 처음 정한 전략을 끝까지 유지하는 것은 아니다.  
상황에 따라 등교 전략을 바꿀 수도 있다.  


## Definition
전략 패턴이란 행동을 클래스로 캡슐화하여 동적으로 행동 전략을 바꿀 수 있게 해주는 디자인 패턴이다.  
코드 블럭 내부를 일일이 수정하지 않고도 손쉽게 전략을 바꿀 수 있다.  


## Structure  
전략 패턴은 다음과 같은 구조를 가진다.

![strategyPatternStructure](https://user-images.githubusercontent.com/78812317/142611871-e7141037-f618-488c-b2e7-29353de75749.PNG)