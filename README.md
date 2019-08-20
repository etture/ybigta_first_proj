# ybigta_first_proj
YBIGTA 2019 여름방학 프로젝트

# 서버에 Git 연동 방법
- git clone https://github.com/etture/ybigta_first_proj.git
- cd ybigta_first_proj
- git checkout <자기 브랜치 이름>
===== 일단 설정 완료
- 파일 새로 작업하고 나서
- git add <바꾼 파일들>
- git commit -m "커밋 메시지, 그냥 뭐 작업했는지 짤막하게 기록하면 됨"
- git push origin <자기 브랜치 이름>
#### 끗!

#### XGBoost, LightGBM 

### 08/06
- ID, transaction merge한 상태로 NA 값 처리
- 준형: ID, 진우: transaction V 이외, 민태/의성: transaction V


### 08/17
- ##### YBIGTA 중간 발표 코멘트
- 불균형 수치 조정해봐라
	* 불균형한거 처리 안 하면 성능이 안 좋게 나올 수 있다
	* oversampling / undersampling

### 최종발표까지
- SMOTE 로 oversampling 해보기 (민태)
- Column 줄여야 할 것 같다 (진우, 준형)
- XX F1 Score 확인하는 코드 (진우) XX (필요없어짐, 공지방 )
- RFECV (민태)
	--> 1, 2번 둘다 해서 XGBoost 적용까지
- LightGBM / CatBoost (진우)
