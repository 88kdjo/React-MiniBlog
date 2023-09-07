React Mini Blog
=

본 프로젝트는 React로 만들어진 미니 블로그(Mini Blog)입니다.

패키지
=

* react-router-dom

* styled-components

* serve

명령어
-

```npm install --save react-router-dom styled-components```

* * *

```npm install -g serve```

* * *

기능
=

> 글 목록 보기 기능 (리스트 형태)
> > PostList, PostListItem

> 글 보기 기능
> > Post

> 댓글 보기 기능
> > CommentList, CommentListItem

> 글 작성 기능
> > PostWrite

> 댓글 작성 기능
> > CommentWrite

폴더
=

> src
> > component
> > > list
> > > > 리스트와 관련된 Component들을 모아놓은 폴더

> > > page
> > > > 페이지 Component들을 모아놓은 폴더

> > > ui
> > > > UI Component들을 모아놓은 폴더



빌드
=

명령어
-

```npm run build```

* * *

```serve -s build```

* * *