# spring-boot-gradle

### gradle과 spring-boot 테스트 프로젝트

### 1일차
* 작업
   * 프로젝트 생성 및 github 업로드

* 삽질
   * gradle을 처음써봐서 최신 버전을 쓰려고 했는데 intellij에서 계속 빌드 실패함.   
     이유는 인텔리제이 버그라고함...하오 빡치네..이것때메 30분 버림
     https://stackoverflow.com/questions/53702038/android-gradle-5-0-updatecause-org-jetbrains-plugins-gradle-tooling-util/53765185   
     위 url 두번째 댓글   
     ```
        I have same problem after upgrading to Gradle Wrapper 5.0. 
        Now I switch back to 4.10.3 which just released 5 December 2018 based on Gradle documentation,
        and use Android Gradle Plugin: 3.2.1 (the latest stable version).
        
        대충 해석해보면 4.10.3으로 돌리니 빌드 성공했다~ 라고 해서 나도 5.4.1 버전에서 내리니 빌드 됨... 개빡
      ```
      

### 참고 사이트
[그래들](https://gradle.org/releases/)   
[스프링 프로젝트 생성](https://start.spring.io/)
