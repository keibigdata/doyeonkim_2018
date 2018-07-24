# 딥러닝 기반 환경이슈 감성분류기 개발 : 기후변화 중심으로
  
  본 연구는 기후변화 주제의 SNS와 뉴스 댓글 데이터 기반 딥러닝을 이용한 감성분류기를 개발하는 연구입니다
  
  본 repository에서 제공하는 data 및 code에 대한 설명은 다음과 같습니다.

## **1. 기후변화 사전**
- 기후변화에 따른 현상을 4개의 범주(온도, 강수, 토지, 해양) 분류 후 구축

## **2. 감성분류 학습 데이터**
- 약 5만 건 단문 데이터에 7개 감성을 사람의 주관적인 판단으로 수작업으로 태깅 후 5명의 작업자가 크로스 체크 작업을 수행
- 약 5만 건 단문 데이터 : 4개 채널(Facebook, Instagram, News_comment, Twitter)에서 본 연구에서 구축한 기후변화 사전을 이용하여 수집함
- 7개 감성 : 긍정(황홀/기쁨, 기대/관심, 기타 긍정), 부정(분노/짜증, 두려움/공포, 기타 부정), 중립

## **3. 감성분류 알고리즘**
- 다양한 기계학습 기반 분류 알고리듬 성능 평가를 통해 선정 (SVM, Naive Bayes, CNN, RNN)
