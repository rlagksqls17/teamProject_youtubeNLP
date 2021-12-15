# Evereview 

![Imgur](https://imgur.com/wMoheXq.jpg)

### 무슨 서비스일까?

**프로젝트 주제** 

: 유튜버가 업로드한 영상에 달린 시청자 댓글을 상세 분석해주는 서비스입니다.

**타겟 이용자**

: 개인 유튜버

**문제 정의**

: 유튜브 채널을 운영하는 개인 유튜버들의 영상에 달린 댓글들은 양이 많아서 그 댓글을 하나하나 읽어보기에 시간이 모자랄 수 있습니다. 따라서 시청자들이 주로 원하는 컨텐츠가 무엇이고, 어떤 불평이 제일 많은지에 대해 객관적으로 파악하기에는 무리가 있다고 생각하였습니다.

**주요 기능**

: 영상에 달린 댓글의 뉘앙스를 파악해 이를 분류하고, 공통된 의견을 군집화하여 시각화합니다.

**서비스 이용자가 얻는 인사이트**

: 채널에 빨리 반영되어야 할 의견(칭찬, 불평, 콘텐츠 요구 등)을 그래프, 혹은 테이블 형식으로 보여줌으로써 사용자의 컨텐츠 기획을 돕습니다.        



## 어떤 기능들이 구현되어 있을까?

#### 구글 로그인 연동 및 사용자의 유튜브 채널 정보 수집  

1. 구글 로그인 연동 : 구글 로그인 버튼으로 로그인 및 회원가입
2. 분석을 위한 유튜버 정보 수집 : 처음 로그인하는 경우 설문 진행하여 영상 업로드 주기와 업로드 컨텐츠 종류 수집 (여기서 수집된 정보는 사용자 댓글 분석 시 사용됩니다.)
3. 분석 실시 : 로그인 후, 대시보드 버튼을 클릭 시 해당 페이지로 넘어가서, 영상 댓글 분석이 시행되며, 영상을 업로드하는 주기에 따라 분석되는 영상의 개수가 달라집니다.
4. 분석 결과 제시 : 분석이 종료된 후 대시보드 페이지에서 해당 결과를 시각화하는 그래프가 반응형으로 제시됩니다.

![Imgur](https://imgur.com/tJcoo5F.jpg)

#### 사용자의 유튜브 채널에 달린 댓글 분석 후 대시보드 형태로 시각화  

1. 피드백 분석 시행

: 피드백으로 분류된 댓글을 긍정, 부정으로 분류하여, 분류된 댓글별로 겹치는 의견들을 군집화하여 그래프로 시각화합니다.

: 개요페이지에서는 해당 분석 결과가 막대그래프로 표시됩니다. 분류된 댓글들 중 공통적으로 겹치는 의견들을 그룹화하여, 각 그룹별로 속하는 댓글 수와 좋아요 수가 표시됩니다.  

![Imgur](https://imgur.com/hisUbKq.jpg)

2. 사용자 컨텐츠 요구 분석  

: 컨텐츠 요구로 분류된 댓글들을 군집화하여 그래프로 시각화합니다.

: 개요페이지에서는 해당 분석 결과가 파이차트로 표시됩니다. 컨텐츠 요구로 분류된 댓글들 중 공통적으로 겹치는 의견들을 그룹화하여, 각 그룹별로 대표 키워드와 댓글이 차지하는 비율이 표시됩니다.

![Imgur](https://imgur.com/evLLSwL.jpg)  

3. 개요 페이지

: 대시보드 페이지 중 데이터 분석 결과를 한눈에 보기 쉽도록 구현된 개요페이지 입니다. 

: 이후 각 분석 결과를 클릭할 시 해당 상세 분석 페이지로 이동하여 자세한 결과를 보여주도록 구현할 예정입니다.  

![Imgur](https://imgur.com/VjtH5RR.jpg)

#### **댓글 분석 필터를 적용하여 사용자가 원하는 분석결과를 시각화**

1. 영상별 분석 필터 적용하여 분석

: 사용자가 업로드한 영상 리스트에서, 검색과 클릭을 통해 사용자가 직접 영상을 선택 가능합니다. 이후 선택된 영상에 따른 댓글을 분석 및 시각화합니다.  

![Imgur](https://imgur.com/NNipGWN.jpg)

2. 댓글 기간별 분석 필터 적용하여 분석

: 사용자가 달력에서 특정 기간을 선택하면, 선택된 기간동안의 댓글들을 모든 영상에서 찾아내어 분석 및 시각화합니다.  

![Imgur](https://imgur.com/qhEOnIE.jpg)





#### 현재까지 사용한 기술 및 라이브러리는?  

![Imgur](https://imgur.com/wgYa0uJ.jpg)  

## 참고 자료

인공지능 사용 기술 도식화 : [해당 링크 접속하기](https://bit.ly/3IbUKDE)



## 팀원 역할 분담  

![Imgur](https://imgur.com/fZAJ4BM.jpg)