# Data-Youth-campus

# 1. 프로젝트
- 수어 동작 인식 시스템을 활용한 수어 교육 서비스 "AI 수어 학교"
- 사용자의 수어 동작을 인식하여 해당 수어가 나타내고자하는 단어를 잘 나타내고 있는 지 정답여부를 판단하는 시스템입니다. 

# 2. 서비스 구성

![Home](https://user-images.githubusercontent.com/80680069/186882734-a642024d-b24d-492e-8014-3622739af7ed.png)
![Home – 1](https://user-images.githubusercontent.com/80680069/186882766-eed193b3-749a-456f-b978-10142fe65295.png)
![Category](https://user-images.githubusercontent.com/80680069/186882781-4a26dad5-2f65-4b1e-8184-0b7a4c4066e6.png)
![Recognition](https://user-images.githubusercontent.com/80680069/186882876-f7b7ecfa-058e-4802-ab38-67c05a30cc9a.png)
![Result – 1](https://user-images.githubusercontent.com/80680069/186882846-7306fa8f-e374-449d-9be0-d4574ab5f346.png)
![Result](https://user-images.githubusercontent.com/80680069/186882893-891392a3-bc53-4246-8713-33d3bfe7f137.png)

-  사용자의 첫 사용 시, 초기 테스트를 하여 사용자의 수어 능력을 분석한 후 테스트 결과에 따라 사용자 수준별 맞춤 교육 커리큘럼을 제공합니다. 사용자는 동물, 식생활, 종교 등 주제, 단어, 문장 카테고리 중 학습을 원하는 카테고리를 하나 선택해 수어 공부를 시작하게 됩니다.

-  화면에 주어진 단어를 보고 사용자가 그에 맞는 수어 동작을 하면, 서비스는 수어 동작을 인식하여 정답 결과와 해설 영상을 보여줍니다. 하나의 학습 과정을 완료하면 보상과 함께 더 많은 학습 커리큘럼에 접근할 수 있게 됩니다.

#  

# 3. 빌드 가이드

## 1. 데이터 수집

  'Crawling' 폴더 내
  
  "Crawling.ipynb" : 영상 데이터 크롤링
  
  (국립국어원 한국수어사전 영상 크롤링 
  https://sldict.korean.go.kr/front/main/main.do)
  
  ##
  
## 2. 데이터 전처리

  'EDA_hands' 폴더 내
  
  "National_korea_EDA.ipynb"
  
  : EDA
  
  
  
  'Augmentation' 폴더 내
  
  "Augmentation_정리.ipynb" 
  
  : Data Augmentation
  
  (참고 : https://github.com/okankop/vidaug/tree/master/vidaug/augmentors
  https://github.com/danielgatis/rembg.git)
  
  ##
  
## 3. 모델링

  'CRNN' 폴더 내
  
  "CRNN.ipynb"
  
  : 다양한 CRNN 모델 시도
  
#
  
# 4. 발표자료

[7조_최종발표자료.pdf](https://github.com/Data-campus-2022/team_7/files/9432518/7._.pdf)

#

# 5. 팀원
