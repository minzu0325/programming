# Maven Project 소스 구조
  | src | main | java : 개발하는 java 코드
               | resources : 서버가 실행될 때 필요한 파일들의 경로
        | test | java : 테스트 전용 경로
               | resources : 테스트 시에만 사용되는 파일들의 경로
  | src | main | webapp | resources 
                        | WEB-INF | classes
                                  | spring | appServlet : 스프링 설정 파일의 경로
                                  | views : JSP 파일 경로
  | pom.xml : Maven 설정 파일
