# ILLUTRATOR

### lecture 1_basic & selection
```
- 이미지를 표현하는 방식
vector-점과 점을 연결하여 수학적 공식에 의해 만들어진 선.
크기조절이 자유로워 객체를 늘이거나 줄여도 해상도에 지장이 없다.
로고 폰트 캐릭터에 유용 컬러구현이 선명 인쇄물 제작에 주로사용 사실적으로 이미지를 편집 보정에는 부적합 ex)일러스트레이터

bitmap-작은 정사각형의 픽셀이 모여 하나의 이미지를 만든다. 
다양하고 정교하게 사실적표혀 가능, 이미지 확대시 계단모양의 픽셀이 나타나 품질이 떨어짐 ex)포토샵

```

```
- 컬러모드
 RGB(red green blue)-가산혼합방식 빛의 3원색 색이 섞일수록 명도가 높아짐 빛으로 보여지는 TV 모니터 모바일 등이 해당
 
 CMYK(cyan magenta yello black)-감산혼합방식 색의 3원색 자신의 최종 결과물이 인쇄물일 경우.
```

```
window -> control : option bar
window -> workspace -> new workspace :작업 환경 저장
artboard : 종이의 수
bleed : 도련 - 인쇄 할 때 밀림 현상이 일어날 경우를 대비
ctrl+n : 새로운 파일
color mode : RGB, CMYK
raster effects(해상도) : 웹(72ppi), 일반프린터(150ppi), 고급인쇄(300ppi)
crtl+0 : 화면에 이미지 맞추기
ctrl+1 : 이미지의 크기를 100%로 맞춤 (실제크기)
V : 선택도구
A : 직접선택도구
ctrl + shift + B : bounding box
ctrl + G : 그룹화
ctrl + shift + G : 그룹해제
```

### lecture 2_figure
```
-면색상과 선색상 구분
click + drag + 방향키 : 모서리 조절
shift + drag : 정
alt + drag : 가운데 축
다각형 + 방향키 : 모서리 추가
별모양 그릴 때 alt + shift : 반듯한 별
arc 툴 + 방향키 : 곡선값 조절
닫힌 패스 : 사방이 막혀있는 패스, 패스의 시작점과 끝점이 일치한다.
열린 패스 : 패스의 시작점과 끝점이 일치하지 않는다.
ctrl + y : 아웃라인 보기(외곽선)
☉ : 모서리의 둥근 정도를 조절
ctrl + f10 : stroke --> 선 조절
shift + ctrl + ] : bring to front
ctrl + ] : brint forward
shift + ctrl + [ : send to back
ctrl + [ : send backward
```

### lecture 3_TransForm
```
select + rotate -> alt + click(축을 선택) : 회전하기
ctrl + d : 연속 복사
scale tool + alt + click : 수치로 크기를 조절
uniform/ non-uniform : 정비례 / 가로 세로의 비율 조절
scale stroke & effects : 객체와 선의 크기를 조절
reflect tool + alt: 축이 되는 지점을 클릭 -> 반전
shear tool + alt: 축이 되는 지점을 클릭 -> 기울이기
객체 선택 + free transform tool : 자유변형
```

### lecture 4_Color&Gradient
```
RGB CMYK 를 구분하자
window -> color or swatches(new swatch:사용하는 색이나 그라디언트를 저장할 수 있다.) : 색상에 대한 패널
window -> Gradient(ctrl+f9) :그라디언트 색상 조절(패널 안의 bar 활용하여 색상 추가,삭제 위치조절 가능) / 선형 원형 자유형 사용가능
ctrl + shift + d : 투명배경
```

### lecture 5_Arrange & Align
```
arrange -> 앞,뒤로 한단계 또는 맨 앞, 맨 뒤로 보낼 수 있다.
align object -> 정렬(2개 이상의 오브젝트를 선택시 정렬 할 수 있다.)
align to -> 선택시 아트보드와 오브젝트의 기준을 정할 수 있다.
distribute object -> 기준을 중심으로 일정한 간격을 지정할 수 있다.
---> ex)어플리케이션 목업 또는 단말기 표현 시 어플리케이션 정렬 또는 포스터, 메뉴판
```

### lecture 6_Pathfinder 
```
Pathfinder(shift+ctrl+f9):객체를 붙이거나 잘라주는 기능(두 가지 이상의 오브젝트 필요)
자동으로 그룹화 따라서 그룹해체 후 확인 필요, 아웃라인 이용
면과 선을 합치는 것 보다 면과 면, 선과 선이 용이하다.
선->면 : 선을 선택하고 object에서 expand 선택
divide: 선을 기준으로 또는 면을 기준으로 객체를 나눌 수 있다.
```