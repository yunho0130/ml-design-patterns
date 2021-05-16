*본 레파지토리는 구글의 공식 제품이 아닙니다.*

# ml-design-patterns
O'Reilly 책과 함께 제공되는 소스코드: <br/>
**제목**: 머신러닝 디자인 패턴 Machine Learning Design Patterns <br/>
**저자**: Valliappa (Lak) Lakshmanan, Sara Robinson, Michael Munn <br/>
**역자**: 맹윤호, 임지순 <br/> 

<img src="mldp_cover_color.jpg" height="300"></img><br/>

`머신러닝 디자인 패턴` 한국 독자들을 위한 소스코드 저장소입니다. 각 장마다 새로운 코드들이 업데이트 되고 있으며, 최신 원본 코드는 아래의 링크에서 확인하실 수 있습니다. <br/>
[<img src="https://deepnote.com/buttons/try-in-a-jupyter-notebook-white.svg">](https://deepnote.com/launch?url=https://github.com/GoogleCloudPlatform/ml-design-patterns)

# 목차

* 서문 Preface
* [머신러닝 디자인 패턴의 필요성](./01_need_for_design_patterns) The Need for ML Design Patterns
* [데이터 표현 디자인 패턴](./02_data_representation) Data representation design patterns
  * #1 특징 해시 Hashed Feature
  * #2 임베딩 Embedding
  * #3 특징 교차 Feature Cross
  * #4 멀티모달 입력 Multimodal Input
* [문제 표현 디자인 패턴](./03_problem_representation) Problem representation design patterns
  * #5 리프레이밍 Reframing
  * #6 멀티레이블 Multilabel
  * #7 앙상블 Ensemble
  * #8 캐스케이드 Cascade
  * #9 중립 클래스 Neutral Class
  * #10 리밸런싱 Rebalancing
* [학습 모델 수정 패턴](./04_hacking_training_loop) Patterns that modify model training
  * #11 Useful overfitting
  * #12 Checkpoints
  * #13 Transfer Learning
  * #14 Distribution Strategy
  * #15 Hyperparameter Tuning
* [탄력성 패턴](./05_resilience) Resilience patterns
  * #16 스테이트리스 서빙 함수 Stateless Serving Function
  * #17 배치 서빙 Batch Serving
  * #18 연속 모델 평가 Continuous Model Evaluation
  * #19 2단계 예측 Two Phase Predictions
  * #20 키 기반 예측 Keyed Predictions
* [재현성 패턴](./06_reproducibility) Reproducibility patterns
  * #21 트랜스폼 Transform
  * #22 반복가능한 분할 Repeatable Splitting
  * #23 브릿지 스키마 Bridged Schema
  * #24 윈도우 추론 Windowed Inference
  * #25 워크플로우 파이프라인 Workflow Pipeline
  * #26 특징 저장소 Feature Store
  * #27 모델 버전 관리 Model Versioning
* [책임있는 AI](./07_responsible_ai) Responsible AI
  * #28 휴리스틱 벤치마크 Heuristic benchmark
  * #29 설명가능한 예측 Explainable Predictions
  * #30 공정성 렌즈 Fairness Lens
* [연결 패턴](./08_connected_patterns) Connected Patterns
* 요약 Summary
