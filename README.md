# OS

Windows

## First Class (1. Git, Github, and Markdown)

1. Git, Github, Markdown 공부하기
2. Git 설치하기

## Second Class (2. My very first blog (feat. Github Pages))

1. Github에 Reveroftrillion.github.io란 이름의 저장소 생성
2. Local_Remote Repository를 연동시킨다.
    1. Remote Repository의 주소를 복사한다.
    2. git clone <repository name> <path> 를 통해 Local Repository로 clone 해온다.
3. 예시 문서(index.html)를(을) 작성한다.
4. commit을 남긴다.
    1. git status를 통해 현재 상태를 확인한다.
    2. git add를 통해 변경한 문서를 추가한다.
    3. git commit -m "message"를 통해 commit message를 남긴다.
5. git push를 통해 원격 저장소(Github)에 반영한다.
    1. git branch -M main을 통해 현재 branch의 이름을 main으로 바꾼다.
    2. git status를 통해 현재 상태를 확인한다.
    3. git add를 통해 변경한 문서를 추가한다.
    4. git push를 통해 원격 저장소에 반영한다.
    5. 바로 추가가 되지 않는 경우, PAT(Personal Access Token)을 생성해 Password를 요구하는 부분에 넣어준다.
6. reveroftrillion.github.io로 접속해서 index.html의 내용이 등장하는지 확인한다.
  
## Third Class (3. Add theme on blog)
  
1. Build Jekyll Project
    1. Jekyll, Ruby 설치하기
    2. Second Class에서 만든 index.html을 지운다.
    3. 하나의 Directory를 만들고, 그 안에 Jekyll을 설치한다.
    4. bundle exec jekyll serve를 실행하고, 127.0.0.1:4000(즉, localhost:4000)에 접속한다.
    5. 블로그의 속성 중 대부분이 _config.yml에 존재하니, 이를 수정한다.
    6. bundle exec jekyll serve를 실행하고, 127.0.0.1:4000(즉, localhost:4000)에 접속한다.
    7. commit을 남긴다.
    8. git push를 통해 원격 저장소에 반영하기 위해 명령어 git push origin main을 사용한다.
    9. reveroftrillion.github.io로 접속해서 변경점이 반영되었는지 확인한다.
2. Upload Post
    1. 블로그에 포스팅하는 작업은 _posts 폴더에서 진행한다.
    2. YYYY-MM-DD-TITLE.md 형태로 새로운 문서를 생성한다.
    3. 주어진 형식(layout, title, date, categories)를 작성해서 문서를 시작한다.
    4. 문서 작성할 때 markdown 형태를 활용한다.
    5. Local Repository에 commit으로 반영한 후, push로 Remote Repository에도 반영시킨다.
    6. reveroftrillion.github.io로 접속해서 변경점이 반영되었는지 확인한다.
3. Add Theme
    1. 테마 폴더를 하나 생성한다.
    2. 원하는 테마(내 경우에는 깔끔한 Lanyon 테마)를 clone해서 테마 폴더에 받아온다.
    3. _posts와 _config.yml을 제외하고 테마에 있는 정보로 덮어씌운다.
    4. Local Repository에 commit으로 반영한 후, push로 Remote Repository에도 반영시킨다.
    5. reveroftrillion.github.io로 접속해서 변경점이 반영되었는지 확인한다.

## Fourth Class (4. Customize my blog)

- 댓글 기능을 구현하기 위해, 수업 시간에는 disqus를 사용했으나, 저는 utterances를 사용했습니다.
1. Github에서 신규 Repository를 생성한다.
    - Repository의 이름이 고민될 수는 있으나, 간단하게 (블로그 이름)-comment로 지어보자.
2. utterances.json 파일을 생성한다.
    - origins에서 기능을 사용할 URL을 적는다.
    - 이 때, https와 http 두 가지 버전을 적는게 편리하다.
3. utterances를 설치한다.
4. 원하는 설정에 맞춰 선택하고 코드를 생성한다.
    - 저는 theme을 github-light에서 icy-dark로 변경했습니다.
5. 댓글 구현을 하고 싶은 글에 복사한 코드를 붙여준다.
6. 3분 정도 지난 후, reveroftrillion.github.io로 접속해서 변경점이 반영되었는지 확인한다.
