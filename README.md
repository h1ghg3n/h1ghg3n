<div align="center">

# SeokUng Yun

### System / Platform / Edge Software

`C++` · `Linux` · `Edge` · `Performance` · `Distributed Systems`

실제 실행 환경에서 발생하는  
**성능 · 자원 제약 · 네트워크 통신 · 비동기 처리 · 분산 시스템**에 관심이 있습니다.

개인 프로젝트를 통해  
**C++ Native Software와 Edge 환경**을 지속적으로 개발하고 있습니다.

</div>

---

## Featured Projects

### ⚙️ FlexRAW-public

**C++20 · Qt6 · CMake · TCP · SQLite**

> RAW 이미지의 Preview, Develop, Catalog, Export를 하나의 workflow로 제공하는  
> C++ 기반 데스크톱 애플리케이션

- RAW image processing workflow
- TCP 기반 Remote Render Worker
- Windows / ARM64 환경 검증
- Local / Remote execution
- Cancellation / failure state handling
- 실제 RAW workload 기반 profiling 및 성능 최적화
- 변경 전후 결과를 비교하는 regression verification

[**View Repository →**](https://github.com/h1ghg3n/FlexRAW-public)

---

### 🧭 Resource Router

**Python · FastAPI · SQLite · Docker · NVIDIA Jetson**

> 제한된 CPU·GPU·통합 메모리를 여러 workload가 공유하는 환경을 위한  
> Resource Admission Service

- SHARED / EXCLUSIVE Lease
- Telemetry와 기존 Lease를 함께 반영한 resource admission
- Lease renew / release / expiry
- 불확실한 상태에서 신규 작업을 승인하지 않는 fail-closed policy
- Edge device 환경의 자원 경쟁 관리

[**View Repository →**](https://github.com/h1ghg3n/resource_router)

---

### 🗃️ UMA-ST-2

**Python · discord.py · SQLAlchemy · MariaDB · Docker**

> 커뮤니티에서 운영되는 이벤트와 데이터를 통합 관리하는 서비스

- 분리된 이벤트 및 포인트 기능 통합
- Transaction 기반 데이터 변경
- 취소 / Rollback 등 실제 운영 예외 처리
- 상태 전이와 데이터 정합성 관리
- 운영 데이터의 복구 가능성을 고려한 구조

[**View Repository →**](https://github.com/h1ghg3n/UMA-ST-2)

---

## Currently Working On

```text
FlexRAW
├─ Processing performance optimization
├─ C++ concurrency / asynchronous execution
└─ System architecture

Edge / Platform
├─ Resource management
├─ Distributed / remote execution
└─ System software fundamentals
