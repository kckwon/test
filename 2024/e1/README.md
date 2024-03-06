# PicTree - 나만의 앨범 만들기

## 프로젝트 개요

1. 제안배경

- 개인용 스마트기기의 대중적인 보급으로 인하여 인물 중심의 사진을 대량으로 보유하게 됨
- 개인 사진의 상당 부분이 인물 사진이며, 인물의 구체적인 식별 정보와 그에 따른 자동 분류는 사진 정리에 큰 도움을 주리라 기대

2. 주요내용

- 사진으로부터 인물 정보 추출, 기존 정보와 유사도 비교하여 추천 혹은 신규 태깅
- 앨범 자동 생성, 편집 등의 기능 및 앨범 추천 기능

## 주요기능

| 기능 | 설명 |
| --- | --- |
| 회원 관리 | 회원 가입/탈퇴 등 회원 관리 기능, 회원 별 앨범, 사진 등 관리 |
| 인물 인식 | 사진으로부터 인물을 인식하여 인물 중심의 데이터를 추출 |
| 인물 식별 | 인식한 인물 데이터로부터 미리 정의한 인물 목록 중 개별 인물을 식별 |
| 앨범 관리 | 인물 중심의 앨범을 자동 생성 후 편집 등의 관리 기능 제공 |
| 인물 추천 | 인물 데이터로부터 기존 인물과 유사한 인물 및 앨범을 추천 |
| 사진 업로드 | 사진 업로드 |

## 핵심기술

| 기술 | 설명 |
| --- | --- |
| Web(Front End) | 이미지 뷰어, 태깅, 앨범 관리 기능(생성, 편집 등) 개발 |
| Backend | Web과 Vision AI API 간의 연계 |
| Vision AI | 객체 인식, Custom Training, 이미지 유사도 분석 등 |

## 참고사항

[Yolo v5 Github](https://github.com/ultralytics/yolov5)

[Yolo v5 Documentation](https://docs.ultralytics.com/yolov5/)

[Yolo v5 Documentation - Train Custom Data](https://docs.ultralytics.com/yolov5/tutorials/train_custom_data/)

[GitHub Skills](https://skills.github.com/)

[GitHub Docs](https://docs.github.com/)
