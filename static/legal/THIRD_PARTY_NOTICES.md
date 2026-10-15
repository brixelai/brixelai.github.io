# Third-Party Notices — Brixel AI Editor

브릭셀AI 편집기에 들어 있는 제3자 구성요소와 그 라이선스. 브릭셀이 만든 부분은 `LICENSE`(독점)를 따른다.
이 목록은 2026-10-15 조사(라이선스 사본 `dev-logs/license_bsd_20261014/` C·D·F 보고서) 기준이다 — 구성요소를 더하거나 바꾸면 갱신할 것.

## 1. Scratch 3.0 (BSD 3-Clause) — 2024-11-25 이전 공개판에서 가져온 부분

| 패키지 | 바탕 판 |
|---|---|
| scratch-vm | 4.8.115 |
| scratch-gui | 4.1.7 |
| scratch-render | 1.2.126 |
| scratch-svg-renderer | 2.5.46 |
| scratch-storage | 3.0.39 |
| scratch-l10n | 4.0.46 (번역 데이터 포함) |
| scratch-paint | 2.2.518 |
| scratch-audio | 1.0.332 |
| scratch-parser | 5.2.1 |
| scratch-sb1-converter | 1.0.324 |

```
Copyright (c) 2016, Massachusetts Institute of Technology
All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list
   of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this
   list of conditions and the following disclaimer in the documentation and/or other
   materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be
   used to endorse or promote products derived from this software without specific
   prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT
SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH
DAMAGE.
```

«Scratch» 이름·로고·Scratch Cat 은 Scratch Foundation 의 상표다. 이 소프트웨어는 Scratch Foundation·MIT 와 관계가 없고 그들의 보증을 받지 않았다.

## 2. Apache License 2.0
scratch-blocks · TensorFlow.js(4.22.0, 1.3.1) 및 tfjs-models(MobileNet·PoseNet·BodyPix·face-detection) · Teachable Machine 라이브러리 ·
MediaPipe(Solutions·Tasks Vision 및 모델) · esptool-js · ESP-IDF · TensorFlowLite_ESP32 · SheetJS(xlsx) · @xenova/transformers ·
NanoTrack 모델(출처 확인 필요) · Qwen3(로컬 LLM 바탕).  원문: https://www.apache.org/licenses/LICENSE-2.0

## 3. MIT / BSD / ISC 계열
qrcode.js(Kazuhiko Arase) · matter-js(liabru) · onnxruntime-web · chart.js · jszip(MIT 선택) · qrcode · JsBarcode · @zxing/browser · ml-svm ·
face-api(@vladmandic) · papaparse · dapjs · microbit-universal-hex · Leaflet(BSD-2) · @vernier/godirect(BSD-3) ·
scratch-translate-extension-languages(BSD-3) 및 npm 의존성(MIT·ISC·BSD). 각 패키지의 LICENSE 를 따른다.

## 4. 글꼴
Griffy · Knewave · Noto Sans · Source Serif Pro · Handlee — SIL Open Font License 1.1 / Grand9K-Pixel — CC BY-SA 3.0 /
Scratch.ttf — «Distribute freely»(비공식 표기, 확인 필요).

## 5. 미디어
- 스크래치 라이브러리의 그림·소리(스프라이트·배경·소리) — 스크래치 이용약관상 CC BY-SA 2.0(Scratch Cat·Gobo 등 마스코트는 제외·상표).
  ⚠️ 마스코트 스프라이트(Cat, Gobo, Giga, Pico, Nano, Tera)는 상표라 이 판에서 뺀다.
- 브릭셀이 만든 그림·소리 — 브릭셀 독점.

## 6. 제한 조건이 있는 데이터·모델
- FlyWire 초파리 연결지도(「초파리 전뇌 실험실」 카드) — **CC BY-NC 4.0(비상업)**. 상업적 이용 시 별도 허락 필요. 화면에 출처 표기.
- Supertonic 3 TTS 모델(PC 에이전트) — BigScience OpenRAIL-M(사용 제한 조항).
- ⛔ Ultralytics YOLOv8(AGPL-3.0) — 이 판에서 제거함(사물 인식 «고성능» 모드 없음).

## 7. 펌웨어(보드에 굽는 .hex/.bin)
아두이노·ESP32·마이크로비트 펌웨어는 GPL/LGPL 라이브러리(AccelStepper·SD·RadioHead·VirtualWire — GPL / Firmata·Servo·RCSwitch·
WebSockets·arduino-esp32 등 — LGPL-2.1)와 링크돼 있다. 해당 라이브러리 조건에 따라 **펌웨어의 해당 소스와 빌드 방법을 요청 시 제공한다**
(펌웨어는 편집기 코드와 별개의 프로그램이다). 문의: [운영자 연락처 기입]
