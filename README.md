![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=EastHun%20Lee%20%7C%20VLM%20%C2%B7%20Agent%20%C2%B7%20Edge%20AI&fontSize=32&fontColor=fff&animation=twinkling&fontAlignY=35)

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=Gmail&logoColor=white)](mailto:easthun828@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=LinkedIn&logoColor=white)](https://linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/EastH88)

</div>

---

### 👋 About Me

**VLM·Agent를 실제 라인·엣지에 배포하는 풀스택 AI 엔지니어**

일본 로봇기업, 국내 보안 대기업, 완성차, 방산·에너지 대기업에 AI 시스템을 납품해왔고, 2025년부터는 LangGraph 기반 멀티모달 RAG와 AI-Augmented Development로 영역을 확장하여 사내 영업 자동화를 직접 운영 중이며 서울시청에 외부 강사로 출강 중입니다. 연구가 아니라 **비즈니스 문제를 푸는 시스템**을 만드는 데 강점이 있고, 빠른 실행과 배포 후 개선 사이클을 선호합니다.

---

### 🚀 Featured Project — SecureDoc Core

> LangGraph 기반 멀티모달 RAG 시스템 · 단독 설계·구현 · 2025.11 ~ 현재

PDF 문서를 업로드하면 텍스트·이미지·표를 파싱하고, 질문에 대한 답변과 근거(citation)를 제공하는 End-to-End 멀티모달 RAG 파이프라인을 단독 설계·구현.

**What I built**
- **LangGraph 3단계 에이전트** — 질문 분류(simple/multi-hop/visual) → 답변 생성 → Faithfulness 검증 → 임계값(0.7) 미달 시 재검색 루프
- **Hybrid Retrieval** — BGE-M3 Dense Embedding + BM25 Sparse + RRF Fusion + Reranker, 한국어는 Kiwi 형태소 분석
- **듀얼 GPU 서빙** — VLM(Qwen2-VL-7B-AWQ, GPU 0)으로 이미지 캡셔닝, LLM(Qwen2.5-14B-AWQ, GPU 1)로 추론·검증 분리 운영 (vLLM)
- **관측성** — Langfuse로 트레이스 수집, FastAPI 게이트웨이, Docker Compose 전체 스택 운영

**Stack:** `LangGraph` · `vLLM` · `ChromaDB` · `BGE-M3` · `Qwen2.5-14B` · `FastAPI` · `Docker`

[![SecureDoc Core](https://img.shields.io/badge/SecureDoc_Core-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/EastH88/SecureDoc_Core)

---

### 💼 Production Experience

#### 🏭 산업용 비전 검사 시스템 — 완성차 + 방산·에너지 대기업
`한맥콘트롤즈 · 2024–2025` · YOLO · Segmentation · AOI · C# / WPF
- 자동차 도어트림 비전 검사 — 50여 개 부품 자동 검사 산업용 비전 장비 전체 개발 주도, YOLO + Semantic Segmentation 멀티스테이지 파이프라인 + C#(WPF) 검사 SW 직접 구현하여 생산 라인 배포·안정화
- FCEV 금속분리판 AOI — 미세 크랙·표면 결함 검출, 복합영상 기반 결함 탐지 알고리즘 → **특허 출원 완료** (공동발명자)

#### 🤖 실시간 객체 탐지 · 이상행동 감지 — 일본 로봇기업 납품
`피아스페이스 · 2025` · YOLO · Edge AI · Streaming
- 공항·역사·도서관 등 공공장소 휠체어 탐지 + 침입·배회 검출 비전 시스템
- 요구사항 정의부터 납품까지 단독 주도, YOLO 커스텀 학습 + 영상 스트리밍 최적화 + 현장 테스트 대응

#### 👁 VLM 기반 가전·로봇용 이상 상황 감지 — LG C-Lab Outside
`피아스페이스 · 2025` · ViT · CLIP · DINO · Qwen · LoRA
- ViT · CLIP · Meta PE · Qwen · DINO 등 비전-언어 모델을 조합한 화재·쓰러짐·연기 탐지 알고리즘 설계
- LoRA Fine-tuning + 경량화로 엣지 환경 실시간 추론 가능하도록 최적화

#### 🛡 CCTV 비식별화 · Re-ID 시스템 — 국내 보안 대기업
`피아스페이스 · 2025` · De-ID · Re-ID · Multi-camera Tracking
- CCTV 실시간 얼굴 De-ID 파이프라인 설계·납품
- 멀티카메라 환경 동일 인물 추적 Re-ID 알고리즘 + 모자이크 복호화 방지 기술 구현

---

### 💪 Skills

**LLM / Agent**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=LangChain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=LangChain&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B0082?style=flat-square&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=OpenAI&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-191919?style=flat-square&logo=Anthropic&logoColor=white)

**VLM / Vision Models**

![Qwen2--VL](https://img.shields.io/badge/Qwen2--VL-7C3AED?style=flat-square&logoColor=white)
![CLIP](https://img.shields.io/badge/CLIP-412991?style=flat-square&logoColor=white)
![DINO](https://img.shields.io/badge/DINO-228B22?style=flat-square&logoColor=white)
![ViT](https://img.shields.io/badge/ViT-FF6F00?style=flat-square&logoColor=white)
![SAM](https://img.shields.io/badge/SAM-4B0082?style=flat-square&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=YOLO&logoColor=black)
![Ultralytics](https://img.shields.io/badge/Ultralytics-111F68?style=flat-square&logo=Ultralytics&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA-DC143C?style=flat-square&logoColor=white)

**AI / Deep Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=ONNX&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white)

**Specialties**

![Object Detection](https://img.shields.io/badge/Object%20Detection-FF6347?style=flat-square&logoColor=white)
![Segmentation](https://img.shields.io/badge/Segmentation-32CD32?style=flat-square&logoColor=white)
![Tracking](https://img.shields.io/badge/Tracking-FF8C00?style=flat-square&logoColor=white)
![ReID](https://img.shields.io/badge/Re--Identification-1E90FF?style=flat-square&logoColor=white)
![Quantization](https://img.shields.io/badge/Quantization-8B008B?style=flat-square&logoColor=white)
![Pose Estimation](https://img.shields.io/badge/Pose%20Estimation-DC143C?style=flat-square&logoColor=white)
![Multimodal RAG](https://img.shields.io/badge/Multimodal%20RAG-7C3AED?style=flat-square&logoColor=white)
![Agent Orchestration](https://img.shields.io/badge/Agent%20Orchestration-1C3C3C?style=flat-square&logoColor=white)

**Edge / Optimization**

![Jetson](https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=NVIDIA&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=NVIDIA&logoColor=white)
![AWQ](https://img.shields.io/badge/AWQ-FF4500?style=flat-square&logoColor=white)
![INT8/FP16](https://img.shields.io/badge/INT8%2FFP16-005CED?style=flat-square&logoColor=white)
![Pruning](https://img.shields.io/badge/Pruning-8B008B?style=flat-square&logoColor=white)
![NPU](https://img.shields.io/badge/NPU-0078D4?style=flat-square&logoColor=white)

**AI-Augmented Dev**

![Claude Code](https://img.shields.io/badge/Claude%20Code-191919?style=flat-square&logo=Anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/OpenAI%20Codex-412991?style=flat-square&logo=OpenAI&logoColor=white)

**Tools & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=NVIDIA&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=Amazon%20Web%20Services&logoColor=white)

---

### 🎤 Talks & Activities

- **서울시청 외부 강사** — AI-Augmented Development (Vibe Coding) 교육 진행 중
- **사내 영업 자동화 에이전트 운영** — 제안서·견적서 RAG 자동화 (피아스페이스)
- **주간 논문 세미나 주도** — CVPR / ECCV / NeurIPS 최신 트렌드 사내 전파

---

### 📜 Publications & Patents

- 📄 **[논문]** 신제품 개발을 위한 GAN 기반 생성모델 성능 비교 (제1저자) — JCCT Vol.8 No.6, 2022.11 · KCI 등재
- 🏅 **[특허]** FCEV 스택용 금속분리판 복합영상 결함 및 불량검출 AOI 시스템 — 공동발명자 · 출원 완료

---

### 📊 GitHub Stats

<div align="center">

</div>

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=EastH88&theme=tokyonight&hide_border=true)](https://github.com/EastH88)

</div>

---

<div align="center">


</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer)
