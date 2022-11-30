---
layout: post
title: "How to install Jekyll-admin"
date: 2022-11-28 16:47:01 +0900
categories: jekyll update
---

## Step to follow

1. Gemfile을 찾는다.
2. "gem 'jekyll-admin', group: :jekyll_plugins"를 Gemfile의 가장 마지막에 추가해준다.
3. cmd창을 실행시킨다.
4. cmd창에서

   <pre>
   <code>
   bundle install
   </code>
   </pre>
   
   을 실행시킨다.
5. cmd창에서
   
   <pre>
   <code>
   jekyll serve
   </code>
   </pre>
   
   를 실행시킨다.
6. <localhost:4000/admin>으로 접속해 관리 화면이 뜨는지 확인한다.

<script src="https://utteranc.es/client.js"
        repo="Reveroftrillion/Reveroftrillion.github.io"
        issue-term="pathname"
        theme="icy-dark"
        crossorigin="anonymous"
        async>
</script>