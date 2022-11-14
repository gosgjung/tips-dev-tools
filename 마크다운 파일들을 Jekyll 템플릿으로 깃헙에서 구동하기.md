# 마크다운 파일들을 Jekyll 템플릿으로 깃헙에서 구동하기

구체적인 생략은 패스.<br>

CLI만 정리하기로 했다.<br>

<br>

**ruby 버전 확인 & 설치**<br>

```bash
$ ruby -v
```

<br>

만약 ruby 가 안깔려있다면 설치하자. 윈도우의 경우에는 바이너리를 다운받아서 설치하면 된다. 또는 chocolatey를 이용해서 설치해도 된다.<br>

맥os 설치 방법은 나중에 정리할 예정...<br>

<br>

**jekyll 의존성 설치 & jekyll 프로젝트 생성**<br>

```bash
# jekyll 의존성 설치
$ gem install jekyll bundler

# jekyll 프로젝트 생성
$ jekyll new gosgjung
// jekyll new [깃헙 계정명]

# 프로젝트 디렉터리로 이동
$ cd gosgjung
// cd [프로젝트 명]
```

<br>

**jekyll 프로젝트 실행 (로컬호스트)**<br>

```bash
// 만약 다른 PC에서 내가 작성한 블로그 리포지터리를 clone을 뜬 후에 구동하려면
// 아래처럼 의존성들을 모두 설치한 후
$ bundle install

// 서버를 구동한다.
$ bundle exec jekyll serve
```

<br>

**깃헙에서의 작업**<br>

`[깃헙계정 id].github.io` 라는 이름의 리포지터리를 개설한다.<br>

몇분 지나서 `[깃헙계정명].github.io` 로 접속하면 페이지가 로딩된다.<br>

<br>

**참고했던 자료들**<br>

알고보니 pages 를 만들라는 것은 내가 하려는 것과는  맞지 않는 내용이었다.

- https://blog.illunex.com/%EA%B9%83%ED%97%88%EB%B8%8C-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0%EC%A7%80%ED%82%AC-jekyll/

이래 저래 도움 많이 된 자료

- https://supermemi.tistory.com/144

 





