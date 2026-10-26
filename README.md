# 🎪 서커스 무대 — 3D 웹 서커스 디오라마

테이블 위에 놓인 미니어처 서커스 극장을 three.js로 만든 인터랙티브 3D 웹 디오라마입니다.
3D웹 서커스 디오라마 파블리옹 중간과제 · 제작 **정윤성** (2023137028)

## 보는 법
- 빛나는 캐릭터·오브젝트를 클릭하면 각자 공연을 시작합니다. 모두 깨우면 피날레!
- 광대를 12번 클릭하면 두 번째 주인공(로마 광대)과 교대합니다.
- 오른쪽 아래 버튼: 발표 모드(자동 카메라 투어) · 크레딧 · 전체화면
- 마우스 드래그로 회전, 휠로 확대/축소

## 로컬에서 실행
에셋을 fetch로 불러오기 때문에 파일을 더블클릭하면 동작하지 않습니다. 폴더에서 간단한 서버를 띄워 주세요.
```
python -m http.server 8000
# 브라우저에서 http://localhost:8000 접속
```
브라우저의 "그래픽 가속 사용"이 켜져 있어야 원래 화질로 부드럽게 보입니다.

## 크레딧

### AI 도구

- **Meshy AI** — 광대 칼리키노, 로마 광대, 대포(직접 제작), 악사, 색소폰 연주자, 심벌즈 원숭이, 아기버섯, 회사원K, 정대리, 종이봉투, 광대 모자 장식 — 모델링 · 리깅 · 춤 애니메이션
- **Suno** — 배경음 3곡 (Moonlit Ringmaster Waltz · Backstage Swing · Empty Big Top at Midnight)
- **ElevenLabs** — 광대 중얼거림 음성
- **Claude (Anthropic)** — three.js 코드 · 연출 구현

### 무료 3D 에셋

- **Low-poly animated rabbit** — Pneshik · CC BY 4.0 · Sketchfab
- **Low-poly cinema chair** — Batuhan13 · CC BY 4.0 · Sketchfab
- **[Unicycle from Poly by Google](https://sketchfab.com/3d-models/unicycle-from-poly-by-google-bc70dd033d6445c6ad7edb02cfac074a)** — IronEqual · CC BY 4.0 · Sketchfab
- **[Clown Hat](https://sketchfab.com/3d-models/clown-hat-0f5ef2e6205c4b438c593a979a3ccdae)** — PatelDev · CC BY 4.0 · Sketchfab
- **[Small Drum](https://sketchfab.com/3d-models/small-drum-e34246f2fcdd4c81b0d982a2053b854c)** — Y M C · CC BY 4.0 · Sketchfab
- **[Gift box 3](https://sketchfab.com/3d-models/gift-box-3-1be0f09f70cd422d87cff81073b3c2cb)** — Multipainkiller Studio · CC BY 4.0 · Sketchfab
- **[Top hat](https://sketchfab.com/3d-models/top-hat-acc9845b7c48479c9b23d93d3643612f)** — Filip · CC BY 4.0 · Sketchfab
- **[Monkey 3D model (rigged)](https://opengameart.org/content/monkey-3d-model-rigged-fbx)** — tomk · CC0 · OpenGameArt
- **[Microphone Stand](https://loafbrr.itch.io/microphone-stand)** — loafbrr · CC0 · itch.io
- **[Bandana](https://sketchfab.com/3d-models/bandana-b9c3493a4c374bcb87f5aa71cf134fdf)** — Gnossiennes · CC BY 4.0 · Sketchfab — 대포알 원숭이 선원 두건
- **[Pirate Hat](https://sketchfab.com/3d-models/pirate-hat-34fe9522c3d84f6f8f7bab3ef7d4bd9f)** — JessThe3dDemon · CC BY 4.0 · Sketchfab — 포수 원숭이 선장모자
- **[Trampoline](https://sketchfab.com/3d-models/trampoline-4c6f1f120c1446d6a28792f3eb0dd096)** — Spark · CC BY 4.0 · Sketchfab — 트램펄린과 비치볼
- **[Fedora](https://sketchfab.com/3d-models/fedora-fe4fceb5a7a544439278edf2181bc875)** — photon (that one larry) · CC BY 4.0 · Sketchfab — 관객 페도라 (색상 6종으로 재채색)

### 엔진 · 라이브러리

- **three.js r128** — MIT · 렌더링, FBX/GLTF 로더, 블룸 · SSAO 후처리
- **lil-gui** — MIT · 오른쪽 조정 패널
- **Google Fonts** — Jua · Gowun Dodum · IBM Plex Mono (OFL)
