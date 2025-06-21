# [인프런] 김영한 실전 자바 입문편

# 왜 자바인가?
<details>
<summary>접기/펼치기</summary>
<br>

다른 많은 프로그램 사이에서 Java를 배우는 이유는 실무에서 많이 사용되기 때문이다.

## 개발자 분야 및 수요(비중)
- 10%: 앱 개발자 (아이폰, 안드로이드 등)
- 90%: 웹 개발자
  - 20%: 프론트엔드 개발자
  - 30%: 백엔드 개발자

위와 같이 백엔드 개발자가 수요가 제일 많으며, 네이버 카카오를 포함한 국내 메이저 회사들의 백엔드 시스템은 대부분 자바를 기반으로 개발한다.  
때문에 당장 취업을 하거나 좋은 회사에 가는 게 아니더라도 자바로 꾸준하게 실력을 쌓아 두면 메이저 회사에 갈 가능성이 다른 언어를 사용하는 것보다는훨씬 높아진다.  

</details>
<br>

# 자바 프로그램 실행
<details>
<summary>접기/펼치기</summary>
<br>

## [HelloJava.java](src%2FHelloJava.java)
```java
public class HelloJava { // HelloJava 클래스의 범위 시작

      public static void main(String[] args) {
          System.out.println("Hello Java");
      }

}
```
### 실행 결과
```text
Hello Java
```
### 코드 분석
  - `public class HelloJava`
    - HelloJava는 클래스이다.
      - 클래스라는 개념이 존재하며, 지금은 단순히 `HelloJava.java`라는 파일을 생성했다고 이해한다.
    - 파일명과 클래스 이름이 같아야 한다.
    - {} 블록을 사용하여 클래스의 시작과 끝을 나타낸다.
  - `public static void main(String[] args)`
    - main 메서드 이다.
      - 함수, 메서드의 개념이 존재한다.
    - 자바는 `public static void main(String[] args)` 메소드를 찾아서 ***프로그램***을 실행한다.
      - 프로그램의 시작점 이다.
    - {} 블록으로 시작,끝 범위를 지정한다.
  - `System.out.println("Hello Java")`
    - `System.out.println()`: 값을 콘솔에 출력하는 기능이다.
    - `Hello Java`: 자바는 문자열을 사용할때 `"` 쌍따옴표를 사용한다.
      - 쌍따옴표 사이에 원하는 문자열을 감싸면 된다.
    - `;`: 자바는 세미콜론으로 문장을 구분한다.
      - 문장이 끝나면 세미콜론을 필수로 넣어줘야 한다.



## 블록 예시
  ```java
  public class HelloJava { // HelloJava 클래스의 범위 시작
  
      public static void main(String[] args) { // main() 메서드의 범위 시작
          System.out.println("Hello Java");
      } // main() 메서드의 범위 끝
  
  } // HelloJava 클래스의 범위 끝
  ```
  - 들여쓰기
    - 블록이 시작되고 끝날 때 마다 들여쓰기가 적용되어 있다.
    - 코드를 쉽게 구분하고 이애하도록 도와주는 관례이다.
    - 블록이 중첩될 때 마다 들여쓰기의 깊이가 추가된다.
    - 들여쓰기는 보통 스페이스 4회(Tab)이다.
    - 들여쓰기를 하지 않아도 프로그램은 작동하지만, 코드 가독성에 좋지 않다.

## [HelloJava2.java](src%2FHelloJava2.java)
```java
public class HelloJava2 {
    public static void main(String[] args) {
        System.out.println("Hello Java1");
        System.out.println("Hello Java2");
        System.out.println("Hello Java3");
    }
}
```
### 실행 결과
```
Hello Java1
Hello Java3
Hello Java3
```
프로그램은 main()을 시작으로 위에서 한 줄 씩 순차적으로 실행된다


</details>
<br>


# 템플릿
<details>
<summary>접기/펼치기</summary>
<br>


## 
<details>
<summary>접기/펼치기</summary>
<br>

</details>


</details>
<br>
