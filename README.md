<div align="center">

# 질문 중심 수업과 서·논술형 평가

**질문으로 가르치고 배우기 · 정답을 넘어 더 깊은 생각으로**

![슬라이드 143장](https://img.shields.io/badge/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C-143%EC%9E%A5-6356A2?style=flat-square)
![구성 6개 장](https://img.shields.io/badge/%EA%B5%AC%EC%84%B1-6%EA%B0%9C_%EC%9E%A5-E85297?style=flat-square)
![정적 HTML](https://img.shields.io/badge/%EB%B9%8C%EB%93%9C-%EC%A0%95%EC%A0%81_HTML_%C2%B7_%EB%AC%B4%EC%84%A4%EC%B9%98-3688C9?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/%ED%98%B8%EC%8A%A4%ED%8C%85-GitHub_Pages-231815?style=flat-square)
![주관 대전광역시교육청 초등교육과](https://img.shields.io/badge/%EC%A3%BC%EA%B4%80-%EB%8C%80%EC%A0%84%EA%B4%91%EC%97%AD%EC%8B%9C%EA%B5%90%EC%9C%A1%EC%B2%AD_%EC%B4%88%EB%93%B1%EA%B5%90%EC%9C%A1%EA%B3%BC-4A3E8F?style=flat-square)

### ▶ [발표 자료 바로 보기](https://tigerjk9.github.io/question-teaching-assessment/)

<img src="assets/og-image.jpg" alt="질문 중심 수업과 서·논술형 평가 발표 자료 미리보기" width="720">

</div>

---

## 한눈에

2026 학생 질문 중심 수업·평가 역량 강화 연수의 발표 자료를 웹으로 공유합니다. 학생이 스스로 질문을 만들어 배우는 수업과, 학생의 사고 과정이 드러나는 서·논술형 평가를 다룹니다. 슬라이드 143장을 장별로 넘겨 보거나 PDF로 내려받을 수 있습니다.

발표자는 프로젝터로 슬라이드를 띄우고, 참석자는 화면의 QR을 찍어 같은 자료를 각자 휴대전화로 엽니다. 영상이 들어가는 슬라이드는 공유용 웹에서 재생되지 않으니 실제 발표에서 시청합니다.

## 두 가지 보기 모드

상단에서 보기 모드를 고릅니다.

| 모드 | 입장 | 보이는 것 |
|------|------|-----------|
| **수강자용** | 비밀번호 없이 바로 | 발표 슬라이드 143장, 장별 목차, PDF 내려받기, QR |
| **강의자용** | 비밀번호 필요 | 위 자료 전부 + 강사 준비 자료 |

강의자용 비밀번호는 연수 담당자에게 별도로 공유합니다. 정적 페이지이므로 이 잠금은 화면 표시를 나누는 용도이며, 민감 정보 보호 수단은 아닙니다.

## 담긴 내용 (6개 장)

1~3장은 질문 중심 수업, 4~6장은 서·논술형 평가입니다.

| 장 | 주제 | 슬라이드 |
|----|------|:--------:|
| 01 | 왜 질문인가 | 1–21 |
| 02 | 질문 초점과 생성 (질문형성기법 1~2단계) | 22–49 |
| 03 | 개선·우선순위·활용 (질문형성기법 3~5단계) | 50–84 |
| 04 | 서·논술형 평가의 이해와 설계 원리 | 85–100 |
| 05 | 평가 유형과 문항 개발 | 101–133 |
| 06 | 채점기준표와 마무리 | 134–143 |

## 강의자용에 더해지는 자료

- **현장 강의용 대본 (PDF)** — 3시간 연수의 진행 순서와 발화 대본
- **캔바 템플릿** — `joo.is/질문선도교사`, 새 탭에서 바로 편집
- **학교별 연수 일정표** — 15개교·신청 교원 340명, 학교·장소·일시·강사를 한 표로. 표를 누르면 크게 봅니다.
- **연수 후 제출 안내** — 만족도 조사 결과, 연수등록부, 사진 2매를 담당 장학사에게 업무포털 내부 메일로 제출하는 체크리스트

## 주요 기능

- 143장 갤러리 — 장별 필터, 제목·장 검색, 라이트박스 확대(좌우 화살표·스와이프·`Esc`)
- 배포 주소로 자동 생성되는 QR, 프로젝터용 전체화면 QR (`Q` 키)
- 라이트/다크 모드 자동 대응, 모바일까지 반응형
- 메뉴와 버튼을 뺀 A4 인쇄·PDF 저장
- 외부 프레임워크 없이 HTML·CSS·바닐라 JS 한 파일로 동작

## 로컬에서 열기

빌드 과정이 없습니다. 저장소를 내려받아 정적 서버로 엽니다.

```bash
git clone https://github.com/tigerjk9/question-teaching-assessment.git
cd question-teaching-assessment
python -m http.server 8000   # http://localhost:8000
```

`index.html`을 파일로 바로 열어도 되지만, QR과 일부 기능은 `http://`로 열어야 정상 동작합니다.

## 폴더 구조

```
question-teaching-assessment/
├─ index.html                # 페이지 전체 (구조·스타일·스크립트)
├─ assets/
│  ├─ slides/                # 발표 슬라이드 이미지(webp)
│  ├─ thumbs/                # 갤러리 썸네일
│  ├─ fonts/                 # Pretendard
│  ├─ vendor/                # qrcode.js
│  ├─ dje-signature.png      # 대전광역시교육청 시그니처
│  └─ og-image.jpg           # 공유 미리보기 이미지
└─ pdf/
   ├─ question-teaching-assessment-slides.pdf   # 발표 슬라이드 143장
   └─ field-lecture-script.pdf                  # 현장 강의용 대본(강의자용)
```

## 주관

**대전광역시교육청 초등교육과**

발표 자료는 2026 학생 질문 중심 수업·평가 역량 강화 연수에서 발췌했습니다.
