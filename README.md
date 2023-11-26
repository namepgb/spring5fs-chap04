[![JIHO's GitHub stats](https://github-readme-stats.vercel.app/api?username=namepgb&include_all_commits=true&theme=nord&hide_border=true&count_private=true)](https://github.com/namepgb/github-readme-stats)

## Preview
`초보 웹 개발자를 위한 스프링 5 프로그래밍 입문` 서적에서 안내된 예제 프로젝트를 생성하고 `Spring`을 학습합니다.
> 
> 이 프로젝트의 개발 환경
>
> <img src="https://img.shields.io/badge/IntelliJ IDEA:2020.3 Ultimate Edition-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
> <img src="https://img.shields.io/badge/OpenJDK:17-437291?style=for-the-badge&logo=openjdk&logoColor=white">
> <img src="https://img.shields.io/badge/Gradle:8.4-02303A?style=for-the-badge&logo=gradle&logoColor=white">

> 이 프로젝트에서는 다음 내용을 포함합니다.
> * Chapter 3 의존 자동 주입
>   * 예제 프로젝트 준비
>   * @Autowired 어노테이션을 이용한 의존 자동 주입
>     * 일치하는 Bean이 없는 경우
>   * @Qualifier 어노테이션을 이용한 의존 객체 선택
>     * Bean 이름과 기본 한정자
>   * 상위/하위 타입 관계의 자동 주입
>   * @Autowired 어노테이션의 필수 여부
>     * 생성자 초기화와 필수 여부 지정 방식 동작 이해
>   * 자동 주입과 명시적 의존 주입 간의 관계

## sp5-chap04/src/main/java/chap04
> * `자동 의존 주입`에 대해서 이해하고 예제 코드를 작성합니다.
> * `@Autowired`를 사용해 자동 의존 주입을 실행합니다.
> * `@Qualifier`를 사용해 자동 의존 주입의 대상이 되는 Bean을 한정합니다.
> * 자동 의존 주입이 필수적이지 않을 때 `@Autowired(required=false)`로 설정합니다.
> * 또는 `@Nullable`과 `java.util.Optional`을 사용해 자동 의존 주입의 필수 여부를 설정합니다.
> * `@Autowired(required=false)`와 `@Nullable`의 실행 차이를 이해합니다.
> * `자동 의존 주입`과 `명시적 DI`가 동시에 실행되는 경우 `자동 의존 주입`이 더 높은 우선 순위로 처리됩니다.
> 
> 블로그 참고 문서
> * [Spring 5 입문: Chapter 04A. 자동 의존 주입](https://namepgb.tistory.com/235)
