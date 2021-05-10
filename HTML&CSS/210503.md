# HTML & CSS & JS
> 1. HTML (Hyper Text Markup Language) 
```
페이지의 제목, 문단, 표, 이미지, 동영상 등 웹의 구조를 담당.
```

> 2. CSS(Cascading Style Sheets)
```
실제 화면에 표시되는 방법(색상, 크기, 폰트, 레이아웃 등)을 지정해 콘텐츠를 꾸며주는 시각적인 표현(정적)을 담당.
```

> 3. JS(JavaScript)
```
콘텐츠를 바꾸고 움직이는 등 페이지를 동작시키는 동적처리를 담당.
```
<br/>

# 웹 표준과 브라우저
> 1. 웹 표준(Web Standard)
```
'웹에서 사용되는 표준 기술이나 규칙'을 의미, W3C의 표준화 제정 단계의 '권고안(REC)'에 해당하는 기술.
```

>> 1-1. W3C의 표준화 제정 단계
```
1) 초안(Working Draft, WD)
2) 후보권고안(Candidate Recommendation, CR)
3) 제안권고안(Proposed Recommendation, PR)
4) 권고안(W3C Recommendation, REC)
```
> 2. 크로스 브라우징(Cross Browsing)
```
크로스 브라우징이란 조금은 다르게 구동되는 여러 브라우저에서, 동일한 사용자 경험(같은 화면, 같은 동작 등)을 줄 수 있도록 제작하는 기술, 방법.
ex) 크롬, 엣지, 파이어폭스, 오페라, 스윙, 웨일, IE, 사파리
```

> 3. 브라우저의 기본적인 인터페이스
```
1) 창(Window)
2) 탭(Tab)
3) 주소창(Address bar)
4) 뷰포트(Viewport) : 웹 페이지가 출력되는 영역.
```
<br/>

# 웹에서 사용하는 이미지
> 1. 비트맵(Bitmap)
```
픽셀이 모여 만들어진 정보의 집합.
레스터(Raster) 이미지라고도 부름.
ex) .jpeg .gif .png
```

> 2. 벡터(Vector)
```
점, 선, 면의 위치(좌표), 색상 등 수학적 정보의 형태(Shape)로 이루어진 이미지.
ex) .svg
```
<br/>

# 비트맵과 벡터의 특징
| 이미지 종류 | 장점 | 단점 |  
|:---: | :---: | :---: |  
| 비트맵 (Bitmap) | 정교하고 다양한 색상을 자연스럽게 표현.| 확대/축소 시 계단 현상, 품질저하.|  
| 벡터 (Vector) | 확대/축소에서 자유로움, 용량 변화가 없음.| 정교한 이미지(인물, 풍경 사진 같은)를 표현하기 어려움.|
<br/>

# JPG (JPEG)
```
JPG(Joint Photographic coding Experts Group)는 Full-color와 Gray-scale의 압축을 위해 만들어졌으며, 압출률이 훌륭해 사진이나 예술 분야에서 많이 사용.
```
+ __손실__  압축
+ 표현 색상도(<b>24비트</b>, 약 1600만 색상)가 뛰어남
+ 이미지의 품질과 __용량을 쉽게 조절__ 가능
+ 가장 널리 쓰이는 이미지 포맷
<br>

# PNG
```
PNG(Portable Network Graphics)는 Gif의 대체 포맷으로 개발됨.
```
+ __비손실__  압축
+ 8비트(256색상)/(<b>24비트</b>, 약 1600만 색상) 컬러 이미지 처리
+ Alpha Channel 지원(<b>투명도</b>)
+ W3C 권장 포맷
<br>

# GIF
```
GIF(Graphics Interchange Format)는 이미지 파일 내에 이미지 및 문자열 같은 정보들을 저장.
```
+ 비손실 압축
+ 여러 장의 이미지를 한 개의 파일에 담을 수 있음
+ (<b>움짤, 애니메이션</b>)
+ <b>8비트 색상</b>만 지원(다양한 색상 표현에는 적합하지 않음)
<br>

# WEBP
```
JPG, PNG, GIF를 모두 대체할 수 있는 구글이 개발한 이미지 포맷
```
+ 완벽한 손실/비손실 압축 지원
+ GIF 같은 애니메이션 지원
+ Alpha Channel 지원(손실,비손실 모두)
<br>

# SVG
```
SVG(Scalable Vector Graphics)는 마크업 언어(HTML/XML) 기반의 벡터 그래픽을 표현하는 포맷.
```
+ __해상도의 영향에서 자유로움__
+ CSS와 JS로 제어 가능
+ 파일 및 코드 삽입 가능
<br>

