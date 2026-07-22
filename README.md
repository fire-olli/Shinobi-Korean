# Shinobi 한국어 번역 (Shinobi Korean Language Pack) 🇰🇷

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Language](https://img.shields.io/badge/Language-Korean-blue.svg)
![Shinobi](https://img.shields.io/badge/Shinobi-Language%20Pack-orange.svg)

> 🇰🇷 Shinobi CCTV/NVR를 위한 한국어 번역(Language Pack)입니다.
>
> **이 프로젝트는 Shinobi 공식 프로젝트가 아니며, 한국어 번역 파일을 제공하기 위한 저장소입니다.**

---

## ✨ 특징

- 자연스러운 한국어 번역
- CCTV 환경에 맞는 용어 사용
- Docker 환경 지원
- 간편한 설치
- 지속적인 번역 개선
- 오픈소스

---

## 📥 설치 방법

1. GitHub에서 `ko.json` 파일을 다운로드합니다.
2. Shinobi의 `languages` 폴더에 `ko.json`을 덮어씁니다.

### Docker 예시

```bash
docker cp ko.json shinobi:/home/Shinobi/languages/
docker restart shinobi
```

---

## 🇰🇷 한국어 적용 방법

`ko.json` 파일만 교체해서는 한국어가 적용되지 않을 수 있습니다.

`conf.json` 파일을 열어 아래 항목을 추가하거나 수정하세요.

```json
"language": "ko",
```

예시

```json
{
  "port": 8080,
  "language": "ko",
  "isFailover": false
}
```

Shinobi를 재시작합니다.

```bash
docker restart shinobi
```

브라우저에서 **Ctrl + Shift + R**(강력 새로고침)을 하거나 로그아웃 후 다시 로그인하면 한국어가 적용됩니다.

> **참고**
>
> `ko.json` 파일만 교체하면 번역이 적용되지 않을 수 있습니다.
> 반드시 `conf.json`에 `"language": "ko"`를 설정해야 합니다.

---

## 📝 번역 예시

| 영어 | 한국어 |
|------|---------|
| Monitor | 카메라 |
| Videos | 녹화 영상 |
| Detector | 움직임 감지 |
| Region Editor | 감지 영역 설정 |
| Storage | 저장공간 |
| Dashboard | 대시보드 |
| API Keys | API 키 |
| Timelapse | 타임랩스 |
| Event Filter | 이벤트 필터 |
| Disk Usage | 저장공간 사용량 |

---

## 📸 스크린샷

> 한국어가 적용된 화면은 아래와 같습니다.

*(스크린샷을 여기에 추가하세요.)*

```
docs/screenshot.png
```

---

## 🤝 기여하기

더 자연스러운 번역이나 오역을 발견하셨다면 **Issue** 또는 **Pull Request**를 등록해 주세요.

모든 의견을 검토하여 더 나은 한국어 번역을 만들어가겠습니다.

---

## ⭐ 프로젝트가 도움이 되셨나요?

이 프로젝트가 도움이 되었다면 GitHub의 **⭐ Star**를 눌러주세요!

번역 개선에 큰 힘이 됩니다. 😊

---

## 📄 라이선스

MIT License
