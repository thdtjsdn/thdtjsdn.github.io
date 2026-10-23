# [thdtjsdn.github.io](https://thdtjsdn.github.io/)

본 저장소는 **고성능 주식, 코인 데이터 분석 엔진**과 **저지연 인터랙티브 그래픽 시스템**을 구축하기 위한 개인 기술 대시보드입니다. 외부 프레임워크에 의존하지 않고 브라우저 표준 API와 저수준 최적화 기술을 결합하여 극한의 런타임 성능을 지향합니다.

---

## 핵심 기술 아키텍처 (Core Technical Architecture)

### Financial Computing & Real-time Data
실시간 시장 데이터 스트리밍과 복잡한 통계 연산을 처리합니다.
* **WebSocket Stream:** 서버와의 양방향 통신을 통해 KOSPI, NASDAQ 및 암호화폐 시세를 실시간으로 수신 및 동기화합니다.
* **Statistical Analysis:** 종목별 등락률, 거래량 변동성 및 수급 동향을 정밀하게 산출합니다.
* **Data Integrity:** 엄격한 JSON 데이터 파싱과 정규화를 통해 데이터 시각화의 신뢰도를 보장합니다.

### Parallel & High-Performance Graphics
브라우저 자원을 최대로 활용하는 고성능 시각화 환경을 구현합니다.
* **WebGL Rendering:** GPU 가속을 활용하여 수만 개의 정점을 가진 복잡한 그래픽스와 쉐이더 효과를 처리합니다.
* **WebAssembly (Wasm):** 연산 집약적인 물리 시뮬레이션 및 데이터 프로세싱 로직을 네이티브 수준의 속도로 실행합니다.
* **Web Workers:** 메인 스레드와 분리된 병렬 처리를 통해 대용량 데이터 분석 및 캔버스 렌더링 시 UI 프리징을 방지합니다.
* **Creative Physics:** HTML5 Canvas와 TypedArray를 최적화하여 진자 운동, 파티클 시스템 등 고정밀 물리 법칙을 적용합니다.

---

## 서비스 철학 (Engineering Philosophy)

* **No-Framework Minimalism:** React, Tailwind CSS, TypeScript 등 외부 라이브러리를 배제하고 Vanilla JavaScript 본연의 성능과 제어권을 확보합니다.
* **Professional Interface:** 시각적 노이즈를 최소화한 Deep Black (#000000) 테마를 활용하여 데이터 집중도를 극대화합니다.
* **Resource Optimization:** 메모리 관리와 실행 효율을 위해 고정된 구조와 엄격한 명명 규칙을 준수합니다.

---

## 기술 스택 요약 (Technical Stack)

| 구분 | 기술 항목 |
| :--- | :--- |
| **Core** | Vanilla JavaScript (ES6+), WebAssembly (Wasm) |
| **Graphics** | WebGL, HTML5 Canvas API, TypedArrays |
| **Concurrency** | Web Workers (Multi-threading) |
| **Networking** | WebSocket (Real-time), JSON-based API |
| **Interface** | CSS3 (Deep Black Theme, High-fidelity UI) |
| **Hosting** | GitHub Pages, Private Remote Server |

---

## 접속 정보 (Deployment)

* **Primary Service:** [https://thdtjsdn.github.io/](https://thdtjsdn.github.io/)
* **Mirror Domain:** [http://thdtjsdn.com/](http://thdtjsdn.com/)
* **Node.js Endpoint:** [https://thdtjsdn.com:49311/](https://thdtjsdn.com:49311/)

---
본 서비스는 지속적인 알고리즘 업데이트와 그래픽 실험을 통해 확장되고 있습니다.

---
---
---

---

# [thdtjsdn.github.io](https://thdtjsdn.github.io/)

This repository is a personal technical dashboard for building a **high-performance stock, coin data analysis engine** and a **low-latency interactive graphics system**. It aims for extreme runtime performance by combining standard browser APIs with low-level optimization techniques, without reliance on external frameworks.

---

## Core Technical Architecture

### Financial Computing & Real-time Data
Processes real-time market data streaming and complex statistical computations.
* **WebSocket Stream:** Synchronizes real-time quotes for KOSPI, NASDAQ, and cryptocurrencies through bi-directional communication with the server.
* **Statistical Analysis:** Precisely calculates price fluctuation rates, volume volatility, and supply/demand trends.
* **Data Integrity:** Ensures high reliability in data visualization through rigorous JSON parsing and normalization.

### Parallel & High-Performance Graphics
Implements a high-performance visualization environment that maximizes browser resource utilization.
* **WebGL Rendering:** Handles complex graphics and shader effects with tens of thousands of vertices using GPU acceleration.
* **WebAssembly (Wasm):** Executes computationally intensive physics simulations and data processing logic at near-native speeds.
* **Web Workers:** Prevents UI freezing during heavy data analysis and canvas rendering via parallel multi-threading.
* **Creative Physics:** Applies high-precision physical laws, such as pendulum motion and particle systems, by optimizing HTML5 Canvas and TypedArrays.

---

## Engineering Philosophy

* **No-Framework Minimalism:** Rejects external libraries like React, Tailwind CSS, and TypeScript to secure the inherent performance and control of Vanilla JavaScript.
* **Professional Interface:** Maximizes data focus by utilizing a Deep Black (#000000) theme that minimizes visual noise.
* **Resource Optimization:** Adheres to fixed structures and strict naming conventions for efficient memory management and execution.

---

## Technical Stack Summary

| Category | Technology |
| :--- | :--- |
| **Core** | Vanilla JavaScript (ES6+), WebAssembly (Wasm) |
| **Graphics** | WebGL, HTML5 Canvas API, TypedArrays |
| **Concurrency** | Web Workers (Multi-threading) |
| **Networking** | WebSocket (Real-time), JSON-based API |
| **Interface** | CSS3 (Deep Black Theme, High-fidelity UI) |
| **Hosting** | GitHub Pages, Private Remote Server |

---

## Deployment

* **Primary Service:** [https://thdtjsdn.github.io/](https://thdtjsdn.github.io/)
* **Mirror Domain:** [http://thdtjsdn.com/](http://thdtjsdn.com/)
* **Node.js Endpoint:** [https://thdtjsdn.com:49311/](https://thdtjsdn.com:49311/)

---
This service is continuously expanding through algorithmic updates and graphical experimentation.