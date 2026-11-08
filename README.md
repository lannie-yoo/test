# 클래스원 영어학원 홈페이지

위례 클래스원 영어학원 홍보용 정적 홈페이지입니다. 빌드 과정 없이 Vercel에 바로 배포할 수 있습니다.

## 파일 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 홈페이지 본문 (HTML·CSS·JS 한 파일) |
| `favicon.svg` | 브라우저 탭 아이콘 |
| `vercel.json` | Vercel 설정 (깔끔한 URL, 보안 헤더) |

## 배포 방법 1: GitHub + Vercel (추천, 프로그램 설치 불필요)

1. https://github.com 에 로그인한 뒤 오른쪽 위 **+** → **New repository**를 누릅니다.
2. 이름(예: `classone-academy`)을 입력하고 **Create repository**를 누릅니다.
3. **uploading an existing file**을 눌러 이 폴더의 파일 4개를 끌어다 놓고 **Commit changes**를 누릅니다.
4. https://vercel.com 에 GitHub 계정으로 로그인한 뒤 **Add New… → Project**를 누릅니다.
5. 방금 만든 저장소 옆의 **Import**를 누릅니다.
6. Framework Preset은 **Other**로 두고 **Deploy**를 누릅니다.

배포가 끝나면 `https://classone-academy.vercel.app` 같은 주소가 생성됩니다.
이후 GitHub에서 파일을 수정하면 Vercel이 자동으로 다시 배포합니다.

## 배포 방법 2: Vercel CLI

[Node.js](https://nodejs.org)를 설치한 뒤 이 폴더에서 실행합니다.

```bash
npm i -g vercel
vercel          # 미리보기 배포 (로그인·프로젝트 설정 질문에 답하기)
vercel --prod   # 운영 주소로 배포
```

## 도메인 연결

Vercel 프로젝트의 **Settings → Domains**에서 보유한 도메인을 추가하고, 안내되는 DNS 값을 도메인 업체에 등록합니다.

## 내용 수정

모든 문구는 `index.html`에 있습니다. 상담 예약 링크를 바꾸려면 `https://m.site.naver.com/1SPRw`를 파일 전체에서 찾아 바꾸세요.
