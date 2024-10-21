# kotlin-calculator-precourse
#### 과제 진행 요구사항
- [ ] 미션은 문자열 덧셈 계산기 저장소를 포크하고 클론하는 것으로 시작한다.
- [ ] 기능을 구현하기 전 README.md에 구현할 기능 목록을 정리해 추가한다.
- [ ] Git의 커밋 단위는 앞 단계에서 README.md에 정리한 기능 목록 단위로 추가한다.
    - AngularJS Git Commit Message Conventions을 참고해 커밋 메시지를 작성한다.
- [ ] 자세한 과제 진행 방법은 프리코스 진행 가이드 문서를 참고한다.

#### 기능요구사항
입력한 문자열에서 숫자를 추출하여 더하는 계산기
- [ ] 입력값을 받아서 숫자를 추출하여 더한다.
    - [ ] 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한다
    - [ ] 분리한 문자열을 숫자로 변환한다.
    - [ ] 빈 문자열인 경우 0을 반환한다.
    - [ ] 숫자를 더한다.
    - [ ] 커스텀 구분자여부 확인
      - [ ] 커스텀 구분자인경우 커스텀 구분자를 기준으로 나눈다.
- [ ] 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료된다.


### 출력값 
```
결과 : 6
```

### 실행 결과 예시
```
덧셈할 문자열을 입력해 주세요.
1,2:3
결과 : 6
```

#### 프로그래밍 요구 사항
- [ ] Kotlin 1.9.24에서 실행 가능해야 한다.
- [ ] Java 코드가 아닌 Kotlin 코드로만 구현해야 한다.
- [ ] 프로그램 실행의 시작점은 Application의 main()이다.
- [ ] build.gradle.kts 파일은 변경할 수 없으며, 제공된 라이브러리 이외의 외부 라이브러리는 사용하지 않는다.
- [ ] 프로그램 종료 시 System.exit() 또는 exitProcess()를 호출하지 않는다.
- [ ] 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 등의 이름을 바꾸거나 이동하지 않는다.
- [ ] 코틀린 코드 컨벤션을 지키면서 프로그래밍한다.
    - 기본적으로 Kotlin Style Guide를 원칙으로 한다.