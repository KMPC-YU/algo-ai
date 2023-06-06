1. Model_Train 
  ALGo의 딥러닝 모델 학습하는 용도로 사용된 폴더이다.
1.1. Recommendation Model
1.1.1. ALGo_Recommendation_Model_Train.ipynb
  해당 ipynb는 추천시스템 모델을 학습하는 파일이다.
1.1.2. User_Item_Rating.csv
  해당 csv는 추천시스템 모델을 학습할때 사용되는 학습데이터이다.
1.2. Food Classification
1.2.1. ALGo_food_classification_train_code.ipynb
  해당 ipynb는 식품 분류 모델을 학습하는 파일이다.
1.3. Hate_speech
1.3.1. ALGo_Hate_speech_train_train_code.ipynb
  해당 ipynb는 비속어 탐지 모델을 학습하는 파일이다.

2. ALGo_AI
2.1. 해당 폴더는 ALGo의 딥러닝 모델을 실행시키는 용도로 사용된 폴더이다.
2.2. cmd를 킨 후 해당 폴더로 이동한다. 
2.2.1. ex) cd C:\Users\wodon\OneDrive\Desktop\ALGo_AI\ALGo_AI
2.3. 폴더안에 start.bat를 실행하여 ALGo_AI 서버를 킨다.
2.4. 서버를 킨 ip로 allergy, favorites, recently_viewed를 파라미터로 넣은 후 get요청을 보내어 추천을 받는다.
2.4.1. ex) http://127.0.0.1:8000/recommend?allergy=11010100000100001000&favorites=[1,2,3,4,5,6]&recently_viewed=[11,22,33,44,55,66]
### 식품 분류, 비속어 탐지, 레시피 추천시스템의 연결은 2학기에 진행할 예정입니다.

