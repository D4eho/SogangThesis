# SogangThesis

## 사용법

0. [Texmaker](http://www.xm1math.net/texmaker/)와 [TeX Live](https://www.tug.org/texlive/) 최적화이므로 참고 바랍니다.
1. thesis 파일 상단의 입력값을 알맞게 넣습니다.
2. 주석을 참고하여 필요 없는 항목은 제거합니다.
3. 그림은 pdf 포맷으로 ./figures에 저장합니다.
4. PdfLaTeX로 pdf를 생성합니다.
5. BibTeX는 ./bib/reference.bib에 저장합니다
6. BibTeX 사용시, PdfLaTeX -> BibTeX -> PdfLaTeX -> PdfLaTeX 순서로 complie 합니다.

## 매뉴얼

명령어 | 입력값 | 설명
-|-|-
%\phdfalse | | 석사 졸업논문으로 설정합니다.
\name{} | 홍 길 동 | 저자의 이름을 추가합니다.
\title{} | 제 목 | 제목을 추가합니다.
\category{} | 이 학 | 저자의 학과 계열을 추가합니다. 예) 이학, 공학 등
\department{} | 물 리 학 | 저자의 학과를 추가합니다.
\ayear{} | 2018년 12월 | 졸업하는 연도, 월을 추가합니다. 여름은 6월, 겨울은 12월 입니다.
\adate{} | 2018년 OO월 OO일 | 논문을 인준받은 날짜를 추가합니다.
\supervisor{} | 지 도 교 수 | 지도교수의 이름을 추가합니다.
\refone{} | 레 프 리 1 | 심사위원중에서 주심의 이름을 추가합니다.
\reftwo{} | 레 프 리 2 | 심사위원 이름을 추가합니다.
\refthr{} | 레 프 리 3 | 심사위원 이름을 추가합니다.
\reffou{} |	레 프 리 4 | 심사위원 이름을 추가합니다.
\reffiv{}	| 레 프 리 5 | 심사위원 이름을 추가합니다.
%\loffalse | | List of Figures를 제거합니다.
%\lotfalse | | List of Tables를 제거합니다.
%\ackfalse | | 감사의 글을 제거합니다.
%\acktitle{} | Acknowledgement | 감사의 글 제목을 변경합니다.
\acknowledgement{} | 본문 | 감사의 글을 합니다.
%\pubtrue | | 논문 목록을 추가합니다.
%\pubtitle{} | List of Publications | 논문 목록의 제목을 변경합니다.
%\publist{} | 본문 | 논문 목록을 입력합니다.
%\abefalse | | 영문 초록을 제거합니다.
%\abetitle{} | Abstract | 영문 초록 제목을 변경합니다.
\engabstract{} | 본문 | 영문 초록을 입력합니다.
%\abekeyfalse | | 영문 초록의 키워드를 제거합니다.
\engkeywords{} | Keywords1, Keywords2 | 영문 초록의 키워드를 추가합니다. 
%\abkfalse | | 국문 초록을 제거합니다.
%\abktitle{} | 초 록 | 국문 초록의 제목을 변경합니다.
\korabstract{} | 본문	| 국문 초록을 입력합니다.
%\abkkeyfalse | | 국문 초록의 주제어를 제거합니다.
\korkeywords{} | 키워드1, 키워드2 | 국문 초록의 주제어를 추가합니다.
