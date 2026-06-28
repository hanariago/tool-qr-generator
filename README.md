# QR 코드 생성기 (QR Code Generator)

URL 또는 텍스트를 QR 코드로 변환. 워터마크 없이 PNG·SVG 무료 다운로드.

🔗 **바로 쓰기**: https://hanariago.github.io/tool-qr-generator/

## 기능
- URL / 텍스트 → QR 코드 실시간 생성 (입력 즉시 미리보기)
- 다운로드 크기 선택 (128 / 256 / 512 / 1024px)
- 전경색 · 배경색 커스터마이징 + 배경 투명 옵션
- 오류 보정 레벨 선택 (L / M / Q / H)
- 여백(quiet zone) 조절
- **PNG 다운로드** (워터마크 없음, 무제한)
- **SVG 벡터 다운로드** (인쇄·확대용)
- 이미지 클립보드 복사
- 다국어 지원 (한·영·일·중간·중번·스페인)
- 서버 전송 없음 — 모든 처리는 브라우저에서만

## 사용법
입력창에 URL이나 텍스트를 넣으면 즉시 QR 코드가 생성됩니다. 크기·색상·오류 보정 레벨을 고른 뒤 PNG 또는 SVG로 내려받으세요. 인쇄·대형 출력은 화질 손실이 없는 SVG, 화면·SNS 공유는 PNG를 권장합니다.

## 기술 스택
- 순수 HTML/CSS/JS (단일 파일)
- 서버 전송 없음 (브라우저에서만 동작)

## 사용한 오픈소스 / 에셋
- [node-qrcode](https://github.com/soldair/node-qrcode) — QR 코드 생성 (PNG/SVG), MIT License

---
Made by [Lena](https://x.com/thezenvoid) · License: MIT
