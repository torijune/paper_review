# LIGHTRAG
**해당 논문은 기존 RAG의 한계점을 다양한 방법으로 해결한 논문으로 기존의 RAG 방법론보다 좋은 성능으로 SOTA를 달성한 논문입니다.**

### 기존 RAG의 한계점
1. 평면적(flatted) 데이터만을 다뤄 복잡한 데이터를 구조화하지 못함
2. 다중 문서에서 검색된 정보들을 통합적이고 일관된 형태로 결합 및 인식하지 못함
3. 오로지 Text-embedding & vector-based matching(Cosine similarity)에 의존하는 검색 알고리즘으로 인한 낮은 검색 정확도
4. RAG 시스템에서 새로운 문서를 통합하여 활용 시, 새로운 데이터 통합 및 적용에 어려움이 있음
5. One-hop(직접 연결) 관계만 다루기 때문에 복잡한 질의나 다차원 상호작용을 요하는 질의에 응답하는데 어려움이 있음

### 기존 RAG의 한계점을 보완하기 위해 LIGHTRAG에서 제시한 방법론
