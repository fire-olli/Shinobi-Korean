# Shinobi Korean Language Pack 🇰🇷

Natural Korean language pack for Shinobi CCTV.

## Features

- Natural Korean translation
- CCTV terminology
- Docker compatible
- Easy installation
- Open Source

## Installation

Copy `ko.json` to the Shinobi language folder.

Docker example:

```bash
docker cp ko.json shinobi:/home/Shinobi/languages/
docker restart shinobi
```

## Translation Style

| English | Korean |
|----------|---------|
| Monitor | 카메라 |
| Videos | 녹화 영상 |
| Detector | 움직임 감지 |
| Region Editor | 감지 영역 설정 |
| Storage | 저장공간 |

## License

MIT
