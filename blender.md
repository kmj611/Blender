# Blender
###### 출처:[youtube](https://youtube.com/playlist?list=PLjJclwOF6pOfy1hNnzaLhNzfnSzH_2Vy0)

## Viewport
- 마우스 휠:회전
- 마우스 휠+Shift&마우스 이동:패닝
- 마우스 휠 회전:줌 인-아웃
- 키패드 .:선택된 오브젝트에 시점 고정
- ~:원하는 View로 이동
- 특정 View로 이동
    -키패드 7:Top View
    - 키패드 9:Bottom View
    - 키패드 1:Front View
    - 키패드 3:Right View
    - Ctrl+키패드 1/3/7/9:해당 View의 반대View로 이동
- 키패드 5번:Perspective와 Orthographic모드 전환

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
    - 원하는 선들을 선택하고 F:면 채우기
    - Blender 상단 중앙의 Proportional Editing모드
        - 휠을 통해 범위 조절
- 위치 정확하게 이동
    - 뷰포트 상단 중앙에 자석모양 아이콘
        - 기본값:1m 단위로 이동(Increment)
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
- Array
    - 배열
    - Count값, Factor X/Y값을 바꿔 원하는 모양으로 
- Displace
    - 질감 변형

## 모델링 순서
1. 만들고자 하는 물체와 가장 비슷한 Mesh 생성
2. Object Mode에서 대략적인 형태를 잡고 Edit Mode에서 점-선-면을 편집
3. 기본 Mesh에서 L-I-E로 디테일을 추가하고 G-R-S로 조정

## PBR Texture
- PBR(Physically Based Rendering):물리 기반 렌더링
- 여러 이미지를 통해 표면 빛의 반사를 물리적으로 계산하는 기법
- 무료 PBR Texture 다운 사이트
    - Poly Haven
    - ambientCG[ambientCG](https://ambientcg.com/)
    - Textures.com 
-PBR Texture Map
    - Color Map:색상에 대한 정보
    - Roughness Map:Texture의 고유한 빛 반사에 대한 정보
    - Normal Map:재질의 높이에 대한 정보(실제로는 평면)
        - OpenGL(GL)
        - DirectX(DX)
    - Displacement Map:재질의 높이에 대한 정보(Mesh에 변형을 가해 실제로 높이 구현)
        -Blender에서 Displacement Map을 적용하려면 Displace Modifier를 적용해야 함

## Texturing
- Blender 상단의 Shading 탭
    - Texturing하기에 적합한 UI 제공
- NODE Editor(Blender 중앙 하단)
    - 상세한 Material 세팅 가능
    - 마우스 휠을 통해 화면 패닝, 줌 인-아웃 가능
    - 자세한 설명:[youtube](https://youtu.be/rDLb0xizzrU?t=283)

