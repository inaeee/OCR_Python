# OCR  

#### 📢 tesseract 를 이용한 OCR 의 다양한 기능을 구현하였다.  
🖥️ 개발환경 : Python, tesseract   
📜 OCR : 광학 문자 인식 Optical Character Recognition 으로 인쇄된 문서를 디지털 이미지 파일로 변환하는 기술이다.  
* 텍스트 이미지를 기계가 읽을 수 있는 텍스트 포맷으로 변환하는 과정으로,
* 자동화된 데이터 추출을 통해 빠르게 변환할 수 있다.

📜 tesseract : 테서랙트는 다양한 운영 체제를 위한 광학문자 인식 엔진이다. Apache License / 무료 소프트웨어   
* 100개 이상의 언어를 지원하고 각 언어에 대한 트레이닝 데이터를 통해 인식 능력을 강화 할 수 있다.
* JPEG, PNG, GIF, BMP 등 다양한 이미지 파일 형식을 지원한다.
* Linux, Windows, maxOS 등 다양한 운영 체제에서 사용할 수 있다.   

<br>

1. use_pytesseract.py : Python 에서 tesseract 사용
2. pytesseract전처리.py : tesseract 를 사용하여 이미지 전처리
3. pytesseract_string.py : image to string 전환
4. pytesseract_boxes.py : 이미지의 문자를 인식 및 구분하여 문자 부분은 박스 형태로 표시
5. pytesseract_dataoutput.py : 이미지의 문자 출력
6. square_padding.py : 명함 padding
7. square_size.py : 명함 크기 조정
8. square_gray전처리.py : 명함을 gray 색으로 전처리
9. pytesseract_squaretextbox.py : 명함의 문자를 문장 혹은 어휘 단위로 잘라 텍스트 박스로 표현
10. select_전처리.py : 선택한 명함 전처리
11. select_string_textfile.py : 전처리가 완료된 명함을 문자 인식을 통하여 텍스트파일 형태로 출력
12. ocr_to_string.py : 이미지 전처리 후 문자 인식


