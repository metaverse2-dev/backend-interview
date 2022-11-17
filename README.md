# 백엔드 채용 과제

## 주제

- Nest.JS를 사용해 커뮤니티 기능이 포함된 서버를 구현해주세요.

## 사용 기술

- 프레임워크는 Nest.JS 또는 Express.js를 사용합니다.
- 데이터베이스는 관계형 데이터베이스(RDB)중에서 하나를 사용해야 합니다. 이외의 NoSQL 시스템은 필요하다면 사용하셔도 좋습니다.
- ORM 사용 가능합니다. (Sequelize or TypeORM and so on...)

## 구현

1. JWT에 기반한 로그인 시스템이 있어야 합니다.
2. 사용자와 관련된 기본 기능이 API로 제공되어야 합니다. (회원가입, 로그인, 로그아웃, 회원탈퇴)
3. 커뮤니티 게시판은 카테고리 -> 게시글 -> 댓글 -> 대댓글의 구조를 가져야 합니다.
4. 데이터를 삽입해서 카테고리는 동적으로 추가될 수 있어야 합니다.
5. 카테고리를 조회할 수 있는 API가 있어야 합니다.
6. 게시글에 관한 CRUD가 모두 있어야 합니다. (게시글 리스트, 게시글 상세, 게시글 작성, 게시글 수정, 게시글 삭제)
7. 게시글에는 제목, 내용, 작성자 정보 등이 기본으로 포함되어야 합니다.
8. 게시글 리스트는 최소 3개 이상의 필터링이 구현되어야 하며, 페이지네이션이 가능해야 합니다. 그리고 2개 이상의 정렬 조건이 존재해야 합니다.
9. 댓글에 관한 CRUD가 모두 있어야 합니다. (댓글 리스트, 댓글 작성, 댓글 삭제)
10. 특정 댓글에 대한 대댓글을 작성할 수 있어야 히고, 댓글 목록에서도 나타나야 합니다.
11. 좋아요, 싫어요 등 유저 관련 기능이 1개 이상 포함되어야 합니다.

## 제출 방법

- 이 리포지토리를 fork한 상태에서 작성하고, Pull Request을 보내주세요.

## 목적
- RESTful API에 대한 이해도 검증
- SQL에 대한 이해도 검증
- 인증시스템에 대한 이해도 검증

## 문의 사항

- 과제를 수행하며 궁금한 점이 생기시면 [?]로 문의해주세요
