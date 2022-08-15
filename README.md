# 넘블 [모바일뱅크 플랫폼 리서치] 케이뱅크 앱 리뷰 분석
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)

- 참고: https://heytech.tistory.com/293
- 참고: https://undeadkwandoll.tistory.com/3
- 참고: https://github.com/Jimin980921/Text_mining

## 1. 2주차: 앱 리뷰 크롤링을 통한 데이터 수집
- App 사용자 리뷰 데이터 수집(`src/Kbank_App_review.ipynb`)
  - 리뷰 등록일
  - 작성자 닉네임
  - 리뷰 평점
  - 리뷰 내용

- Parsing 한 html 데이터 저장(`dataset/data_html.html`)
- 수집한 데이터는 데이터프레임 형태로 포맷팅(`dataset/review_dataset.csv`)

## 2. 3주차: 텍스트 데이터 전처리
- 수집한 리뷰 데이터의 텍스트 전처리(`src/Kbank_App_review_preprocessing.ipynb`)
- 감성분석을 위한 test, train set 분리

### 전체 파일구조
``` bash
├─Kbank_playstore_review_crawler
│ README.md
│ chromedriver
│  ├─src
│  │      Kbank_App_review.ipynb
│  │      Kbank_App_review_preprocessing.ipynb
│  └─dataset
│         review_dataset.csv
│         data_html.html
```
