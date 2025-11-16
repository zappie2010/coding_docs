```
PR 입력 -> AI 리뷰 및 리포트 작성 -> 리뷰어는 리포트르 기반으로 리뷰


프로젝트 문제점 및 해결방안
1. 자동화 방법
Cline : Workflow
Cursor : Command

2. PR 정보 추출 -> GitHub CLI 를 사용

3. 리뷰 항목
PR 의 변경사항
체크리스트 기반
...

4. 실행 환경
Cline : Linux + Cline builtin tools
Cursor : Window ( ??? Shell) + Cursor tools





## 1. Cursor Composer

- Cursor 의 첫 자체 에이전틱(Agentic) 코딩 모델
- 비슷한 지능의 모델보다 4배 빠르고, 대부분의 턴을 30초 이내에 처리하도록 최적화
- 코드베이스 전역 시맨틱 검색 등 강력한 도구로 학습해 대규모 레포에서의 이해/편집 성능을 끌어올렸다고 밝힘
Composer is a frontier model that is 4x faster than similarly intelligent models.
The model is built for low-latency agentic coding in Cursor, completing most turns in under 30 seconds.
자세한 내용은 아래 링크 참조
https://cursor.com/blog/composer
 
## 2. Multi Agent Interface
동일한 문제를 여러 에이전트를 서로 간섭하지 않고 병렬로 작업
git worktree 를 사용해서 병렬로 작업 할 수 있다.


## 3. In App Browser
내장 브라우저 기능
- 브라우저 로그가 파일로 기록되어 Cursor 가 grep 으로 검색함 -> 토큰 사용 감소
- 레이아웃과 UI 요소를 더 정확히 파악






```







