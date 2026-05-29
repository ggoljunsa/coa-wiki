# 컴구위키 (COA Wiki)

DGIST Computer Organization and Architecture (COA) 기말고사 범위를 나무위키 스타일로 정리한 단일 페이지 위키.

**라이브 데모**: https://ggw.github.io/coa-wiki/

## 시험 정보

- **일시**: 2026-06-09 (월) 13:00 ~ 14:30
- **장소**: E7 236호
- **형식**: 객관식 사지선다 + 계산 + 손코딩

## 범위

1. **RECAP** — 성능 지표, 디지털 로직, Verilog
2. **MIPS ISA** — R/I/J 포맷, 함수 호출 규약
3. **Pipeline** — Hazards, Exception
4. **Advanced uarch** — OoO, Superscalar, ROB/ISQ
5. **Multithreading** — FGMT/CGMT/SMT, VLIW
6. **Cache** — 매핑, 정책, MSHR, MSI
7. **Virtual Memory** — Paging, TLB, PIPT/VIVT/VIPT
8. **IO (ch13)** — PIO/MMIO, DMA/IOMMU, Doorbell, AMBA

## 사용법

`index.html`을 브라우저에서 열면 됩니다. 좌측 사이드바에서 문서 선택, 우측 사이드바에 자동 목차, 상단 검색창으로 빠른 탐색.

문서끼리 `[[하이퍼링크]]`로 연결되어 있어서 클릭하며 돌아다닐 수 있습니다.

## 구조

```
.
├── index.html       # 단일 HTML 파일 (CSS/JS 인라인, 66개 문서 임베드)
├── images/          # 강의 PDF에서 캡처한 51장의 다이어그램
└── README.md
```

## 특징

- **66개 문서** — 핵심 문서 17개 + stub 49개로 cross-link 네트워크 구성
- **PDF 캡처 이미지 51장** 임베드 (실제 강의 슬라이드)
- **검색** + **자동 목차** + **카테고리 분류**
- **나무위키 스타일** 박스 (참고/주의/팁/여담)

## 출처

본 위키의 강의 슬라이드 이미지는 DGIST Computer Organization 강의 자료(Prof. Hyokeun Lee)의 캡처이며, 교육 목적의 학습 정리용으로 사용되었습니다.

## License

학습 목적 비상업적 사용. 강의 자료의 저작권은 원저작자에게 있습니다.
