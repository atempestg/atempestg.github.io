# Product & Systems Portfolio

직접 설계하고 구현한 도구와 제품의 케이스 스터디를 모은 Astro 정적 사이트입니다.

- 사이트: https://atempestg.github.io/
- 공개된 프로젝트: AI Note, Personal Hub, File Browser, Flowgram

모든 스크린샷은 로컬 환경에서 가상 데이터로 촬영했으며, 실제 사용자·회의·사내 문서 내용은 포함하지 않습니다.

## 로컬 실행

```bash
npm ci
npm run dev      # http://localhost:4321
npm run build    # dist/ 정적 빌드
```

## 배포

`main` 브랜치에 push하면 `.github/workflows/deploy.yml`이 빌드 후 GitHub Pages에 배포합니다.
