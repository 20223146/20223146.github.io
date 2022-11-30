---
layout: post
title: "About Google Analytics"
date: 2022-11-28 12:12:30 +0900
categories: jekyll update
---

## About Google Analytics

- 웹사이트 트래픽을 추적하고 보고하는 구글이 제공하는 웹 애널리틱스 서비스이다.
- 웹에서 가장 널리 사용되는 웹 애널리틱스 서비스이다.
- 구글의 Urchin 인수 후 제공된 서비스이다.
- 구글의 빅쿼리와의 연동이 존재하는데, 이를 통해 무료 사용자들이 더 넓은 클라우드 제공 기능과 연동할 수 있게 하려는 구글의 노력을 엿볼 수 있다.

## How to apply

1. <https://analytics.google.com/analytics/web/provision/?hl=ko&pli=1#/provision>에 접속해서 측정 시작을 눌러준다.
2. 계정 설정, 속성 설정, 비즈니스 정보를 차례대로 입력해준다.
3. 개정 생성을 완료한 후, 3가지 옵션 중 웹을 선택해준다.
4. 웹사이트 URL과 스트림 이름을 입력한 후 스트림을 만들어준다.
5. 측정 ID를 복사한 후, "_config.yml" 파일에 들어가 측정 ID를 입력해준다.
6. 애널리스틱 대시보드에서 카운팅 되는 것을 확인해준 후 마무리를 해준다.
7. 만약 5번까지 실행했음에도 카운팅이 되지 않는다면,구글 애널리틱스 홈페이지에서 "카운팅이 안되나요?" 버튼을 클릭하면 나오는 코드를 복사해서 "_includes/head.html" 파일 가장 마지막에 붙여주자.

<script src="https://utteranc.es/client.js"
        repo="Reveroftrillion/Reveroftrillion.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>