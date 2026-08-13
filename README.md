# SpendWorld

SpendWorld는 일상의 지출을 하나의 지도로 모아 보여주는 Android 가계부입니다.

이 저장소에는 공식 홈페이지가 들어 있습니다.

## 로컬에서 보기

정적 파일이므로 빌드가 필요 없습니다.

```bash
python3 -m http.server 4173
```

브라우저에서 `http://localhost:4173` 을 엽니다.

## 구성

| 경로 | 설명 |
| --- | --- |
| `index.html` | 랜딩 페이지 |
| `privacy.html` | 개인정보 처리방침 |
| `css/styles.css` | 스타일 |
| `js/main.js` | 언어 전환, 출시 알림 폼 |
| `assets/` | 로고·파비콘 |

출시 알림 이메일은 서버로 보내지 않고, 브라우저 `localStorage`에만 저장됩니다.

## GitHub Pages

저장소 Settings → Pages에서 이 브랜치의 루트를 배포 소스로 지정하면 홈페이지가 공개됩니다.
