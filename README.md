# music
음악 추천 시스템과 관련된 데이터셋과 코드를 모아둔 repository 입니다.

* [dataset](https://github.com/ysen7-aihub/music/tree/main/dataset)
    - data_o.csv : 원본데이터 / kaggle의 Spotify Dataset
    - finalData01.csv : 전처리가 완료된 약 13만 개의 음악을 3차원의 공간에 위치시킬 수 있는 데이터
    - musicInfoWhole.csv : 최종적으로 database에 저장한 음악 정보 데이터
* [preprocessing](https://github.com/ysen7-aihub/music/tree/main/preprocessing)<br/>
  데이터를 분석하고 전처리하는 코드
* [recommendation](https://github.com/ysen7-aihub/music/tree/main/recommendation)<br/>
   추천시스템을 구축하기 위한 코드
* [annoy](https://github.com/ysen7-aihub/music/tree/main/annoy)
    - annoyBuilds.ipynb: annoy 모델 생성 코드
    - annoyUses.ipynb: annoy 모델 서빙 코드

* musicInput.ipynb : NLP모델과 CNN모델에서 나온 output을 음악 추천 모델의 input에 맞게 3차원 벡터로 만드는 함수
