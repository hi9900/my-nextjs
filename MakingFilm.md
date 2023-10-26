## Create-Next-App

```bash
$ npx create-next-app --typescript [프로젝트_이름]
$
```

### 폴더 구조 수정

```
public/
  fonts/
    font.tts
    font.ts
  svgs/
    svg.svg
    index.ts
  images/
    image.png
src/
  app/
    layout.tsx
    page.tsx
    라우팅 관련 파일
    Routing/
  components/
    여러 페이지에서 사용할 수 있는 공통 컴포넌트
    Component.tsx
  containers/
    Routing/
      page.tsx 안에서 보여줄 모든 컨텐츠
      index.tsx
      style.module.css
  hooks/
    여러 페이지에서 사용되는 Custom Hooks
    hook.tsx
  services/
    API 요청
    api.ts
  states/
    전역 상태 관리
    atom.ts
  styles/
    공통 스타일 시트 관련 모든 요소들
    globals.css
  types/
    타입 스크립트 정의 파일
    index.ts
  utils/
    여러 곳에서 사용되는 유틸성 함수 관리
    function.ts

.env.local
```

## ESLint 및 Prettier 설정

### Prettier

- prettier-code formatter 를 설치

  파일 > 기본설정 > 설정으로 들어가서 Default Formatter 를 Prettier - Code formatter 로 설정한다. 필요하다면 자동저장을 켜준다.

- root 디렉토리에 `.prettierrc` 파일을 생성한 후 코드를 저장
