https://esbook.kimjmin.net/

## 프로젝트 목록
- 지능형 행위기반 영상정보 분석기법 연구 (2019.10~2021.08) *국방과학기술연구소 위탁과제*
- Semantic Scene Graph Generation Using RDF Model and Deep Learning 논문 작성(2020.09~2020.12)  *연구실 프로젝트*
- 이미지 어노테이션을 위한 토픽 모델링 연구 (2020.06~2020.08) *연구실 프로젝트*
- 나무위키 데이터를 이용한 Semantic Network Analysis (2022.01 ~) *개인 프로젝트*



## 지능형 행위기반 영상정보 분석기법 연구 *국방과학기술연구소 위탁과제* (2019.10~2021.08)

  ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1030f1c9-1168-4c14-b03e-4ef634e003cc/Untitled.png)

  **목표: 딥러닝, 온톨로지 및 빅데이터 기술을 활용한 행위기반 영상정보 분석 신뢰도 향상**

  사용 언어 및 프레임워크: `Python`, `Pytorch`, `Pyhwp`, `Decab`, `Matplotlib`

  **Description**

  - 딥러닝 기반 개체/관계 인식 기술 개발 (2020.01~2020.08)
      - CNN 기반 이미지 개체 인식 및 지식베이스를 활용한 관계 인식 기술 개발
  - 딥러닝 기반 영상 분석 보고서 문장 추천 시스템 개발(2020.09~2021.08)
      - 영상 분석 보고서 데이터 전처리
          - 한글 파일 형식에서 txt 파일 형식 데이터 구조화
          - 데이터 클리닝 및 형태소 분석
          - OOV(Out-Of-Vocabulary)에 강한 FastText를 사용한 단어 임베딩 방법 제안
          - 논문 개제를 통한 성과 발표 (해당 논문 작성 총괄)
      - 영상 분석 보고서 문장 추천 시스템 개발
          - 오프라인 환경에서 딥러닝 적용을 위한 서버 환경 구축
          - 문장 생성을 위한 모델 개발 및 Top-k개 만큼 추천하기 위해 Beam-Search 도입
          - 논문 개제를 통한 성과 발표 (모델 구축, 단어 기반 문장 생성을 기반 디코딩 방법 파트 작성)
    
    ---
    
2. **Semantic Scene Graph Generation Using RDF Model and Deep Learning 논문 작성(2020.09~2020.12) *연구실 프로젝트***
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cbfc163b-b26d-4f1e-8a36-a6c00cf1cd6c/Untitled.png)
    
    **목표: CNN을 활용한 이미지 개체 인식 및 RNN 계열 모델과 RDF를 적용한 관계 인식 기술**
    
    사용 기술: `Python`, `Pytorch`, `Nltk`, `Matplotlib`
    
    **Description**
    
    - CNN과 RNN 계열 모델을 적용한 Scene Graph Generation 개발
    - n-triple <subject-predicate-object> 데이터에서 Sequential Data 적용을 위해 <subject-object-predicate> 형태로 데이터 재구성하는 아이디어 제안
    - 논문 모델, 실험 파트 (Creating a Deep Learning-Based Scene Graph*,* System Implementation and Testing) 작성
    
    ---
    
3. **이미지 어노테이션을 위한 토픽 모델링 연구 (2020.06~2020.08) *연구실 프로젝트***
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8afa6783-03b5-44ae-9f08-cd219707dad5/Untitled.png)
    
    **목표: 이미지의 주제를 추출하기 위한 토픽 모델링을 적용한 연구**
    
    사용 기술: `Python`, `Pandas`, `Nltk`, `Numpy`, `Matplotlib`
    
    **Description**
    
    - nltk 라이브러리에서 Stemming을 이용한 데이터 전처리
    - 토픽 모델링 알고리즘 PLSA, LDA 구현
    - 기존 element 연산에서 matrix 연산을 적용한 PLSA 모델 성능 개선
    - 토픽 분석을 위한 AIC, BIC, CAIC 구현
    
    ---
    
4. **나무위키 데이터를 이용한 Semantic Network Analysis (2022.01 ~) *개인 프로젝트***
    
    **목표: 문서 사이의 관계를 표현하는 Semantic Network Analysis 텍스트 데이터 분석 프로젝트를 진행 중**
    
    모든 나무위키의 문서를 지식 그래프로 연결하여 검색/추천 시스템을 개발하는 것을 최종 계획
    
    사용 기술: `Python`, `Networkx`, `Matplotlib`, `Pyvis`, `Plotly`, `mpld3`, `ijson`
    
    - 위키 문법이 포함된 텍스트 데이터를 정규식을 이용한 데이터 전처리
    - 쿼리 문서에 대한 서브 그래프 추출
    - 문서간 가중치 및 유사도 구현을 위한 TF-IDF, cosine similiarity 적용
    - 중요 노드를 파악하기 위한 Node Centrality, Clustering Coefficient 적용
    - Interactive한 그래프 시각화 구현
