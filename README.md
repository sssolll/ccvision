# CCVISION

## ocr 프로그래밍 정리

### 프로세스

1. 사전 생성
   1. 이미지 파싱
   2. 이미지 데이터화
2. 이미지 인식
   1. 확률을 이용한 인식



* 이미지 파싱

  * 이미지에서 각 문자를 하나씩 개별 이미지로 나누는 작업

  * 문자는 검은색/바탕은 흰색 ... 검은색을 기준으로 이미지의 문자 판독

  * 파싱 프로세스:

    * line (Y axis) -> letter(X axis) -> x/y control

      

* 이미지 데이터화
  * 이미지의 RGB 값 얻기
    * 이미지는 픽셀의 개수로 크기가 정해지고, 픽셀의 RGB값으로 색이 정해진다.