# 블랜더
###### 출처:[youtube](https://youtube.com/playlist?list=PLjJclwOF6pOfy1hNnzaLhNzfnSzH_2Vy0)

## 시점
- 마우스 휠&마우스 이동:시점 회전
- 마우스 휠+Shift&마우스 이동:시점 이동
- 키패드 .:선택된 오브젝트에 시점 고정
- ~:Orthographic(원근감 무시)모드 활성화

## 오브젝트
- 오브젝트 생성:Shift+A
    - 3D커서 위치에 생성됨    (Shift+우클릭으로 커서 위치 지정 가능)
- 이동:G
- 회전:R
    - R을 누르고 숫자를 입력하면 원하는 값만큼 회전 가능
- 크기:S
- (x/y/z 키를 눌려 축 지정 가능)
    - 뷰포트 상단 중앙에서 Global축에서 다른 축으로 변환 가능
    - Shift+x/y/z:해당 축을 제외한 축 지정
- Shift+D:오브젝트 복제 활성화
-Edit Mode
    - Ctrl+R:Loof cut(Vertex 추가)
        - 마우스 휠로 Loof cut 선 개수 변경 가능
        - Alt를 누른 상태로 마우스 클릭:Loop Select
        - 크기를 조정할 때 Shift를 누른 상태로 움직이면 조금 더 정확하게 편집 가능
    - 면을 선택한 상태에서 I:Inset(새로운 면 생성)
    - 면을 선택한 상태에서 E키:Extrude(면 밀어내기)
- 위치 정확하게 이동
    - 뷰포트 상단 중앙에 자석모양 아이콘
        - 기본값:1m 단위로 이동(Increment)


## 오브젝트 지정
- Z키를 눌려서 Wireframe/Rendered/Solid/Material Previer 모드 선택 가능
    - Wireframe:뼈대만 보기
    - Rendered:실제 Rendering 결과 보기
        - Object 선택&Properties 탭의 구 모양 아이콘:재질 선택
            - 자세한 설명:[youtube](https://youtu.be/-Xi2Y7GkDqU?t=148)
    - Solid:기본값
- C키를 눌려 Circle Select 활성화

## Modifier
- Subdivision Surface
    - 표면 다듬기
    - Object를 선택하고 Ctrl+숫자를 누르면 해당하는 단계의 Subdivision Surface 적용

## 모델링 순서
1. 만들고자 하는 물체와 가장 비슷한 Mesh 생성
2. Object Mode에서 대략적인 형태를 잡고 Edit Mode에서 점-선-면을 편집
3. 기본 Mesh에서 L-I-E로 디테일을 추가하고 G-R-S로 조정