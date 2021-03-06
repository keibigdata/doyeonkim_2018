# 딥러닝 기반 환경이슈 감성분류기 개발 : 기후변화 중심으로
  
  본 연구는 기후변화 주제의 SNS와 뉴스 댓글 데이터 기반 딥러닝을 이용한 감성분류기를 개발하는 연구입니다
  
  본 repository에서 제공하는 data 및 code에 대한 설명은 다음과 같습니다.

## 01_ 기후변화 사전
- 기후변화에 따른 현상을 4개의 범주(온도, 강수, 토지, 해양) 분류 후 구축

## 02_ 감성분류 학습 데이터
- 약 5만 건 단문 데이터에 7개 감성을 사람의 주관적인 판단으로 수작업으로 태깅 후 5명의 작업자가 크로스 체크 작업을 수행
- 약 5만 건 단문 데이터 : 4개 채널(Facebook, Instagram, News_comment, Twitter)에서 본 연구에서 구축한 기후변화 사전을 이용하여 수집함
- 7개 감성 : 1.황홀/기쁨 2.기대/관심 3.감탄/존경 4.분노/짜증 5.두려움/공포 6.슬픔/수심 7.중립
>  주의 : Windows 환경에서 학습 데이터 다운로드 시 이모지(Emoji)가 깨져서 보일 수 있음

## 03_ SNS 데이터 전처리 알고리즘
 - 이모지 한글로 변환 알고리즘 : 약 1,200개 이모지를 한글로 변환함

 - 기타 전처리 알고리즘 :  
> 1. 정규화(Normalization) 
> 2. Document Term Matrix(DTM) 생성 
> 3. 말뭉치(Corpus) 생성 
> 4. Sarse Terms 삭제 
> 5. Data Frame 형태로 변환

## 04_ 감성분류 알고리즘
- SVM(Support Vector Machine), Naive Bayes 
- DeepLearning method : CNN(Convolution Neural Network), Bi-LSTM(Bidirectional Long Short-Term Memory)
