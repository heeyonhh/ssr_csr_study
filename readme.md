# 서버 사이드 렌더링 (Server-Side Rendering, SSR)

SSR은 웹 페이지 초기 렌더링을 서버에서 처리하는 방식

서버는 클라이언트 요청에 대한 초기 HTML 콘텐츠를 생성하고 반환

이후 클라이언트 측 javascript 코드가 실행되며 페이지는 동적인 컨텐츠를 로드하고 처리하는데

SSR을 통해 검색 센인 최적화(SEO)가 개선되고 초기 페이지 로딩 속도가 향상 될수 있다.

예를 들어, Next.js와 같은 프레임워크는 리액트 애플리케이션의 서버 사이드 렌더링을 지원

# 클라이언트 사이드 렌더링 (Client-Side Rendering, CSR)

CSR은 초기 HTML 콘텐츠를 서버에서 제공받아 클라이언트 측 javascript 코드가 동적으로 페이지를 렌더링 하는 방식

웹페이지의 초기 로딩 시 빈페이지나 로딩 스피너만 표시되며

페이지의 구조와 콘텐츠는 javascipt 코드가 실행되고 api 요청을 통해 가져와서 렌더링 된다.

CSR은 웹 애플리케이션의 인터페이스와 사용자 경험을 개선할 수 있다.

대표적으로 CRA(Create React App)를 비롯한 많은 리액트 프로젝트가 이 방식을 사용
