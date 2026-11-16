# RDataScience-Youtube

유튜버 영상 데이터를 R로 분석해 콘텐츠 종류별 조회수·좋아요 경향을 살펴본 수업 팀 프로젝트입니다. 원본 저장소는 [SamuelKihoon/RDataScience-Youtube](https://github.com/SamuelKihoon/RDataScience-Youtube)입니다.

- 경희대학교 빅데이터응용학과, 2022년 2학기
- 팀: 기훈, 대영, 소륜, 준서 (4인)

## 내 역할 (김소륜)

`SRread.R`을 작성했습니다.

- 엑셀 데이터 읽기와 좋아요 비율 변수 생성
- 콘텐츠별 조회수·좋아요 수 박스플롯, 평균 이상 영상 추출
- 조회수와 좋아요의 관계(산점도, 막대그래프), 콘텐츠 비중 원그래프
- macOS 한글 깨짐 문제 해결

## 파일

| 파일 | 내용 |
|---|---|
| `SRread.R` | 콘텐츠별 조회수·좋아요 분석과 시각화 (김소륜) |
| `DYgit.R`, `KHgitWEB.R` | 팀원 작성 분석·웹 연동 코드 |
| `RYoutube.Rmd`, `RYoutube.html` | 분석 보고서 |
| `elegant/` | 결과를 보여 주는 웹 페이지 |
