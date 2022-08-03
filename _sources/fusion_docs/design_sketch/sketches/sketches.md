Fusion 360의 스케치
===============

**스케치**는 Fusion 360의 디자인에서 3D 형상의 기초를 형성하는 형상 프로파일입니다.

디자인에서 3D 객체를 작성하려면, 먼저 디자인을 구성하는 파라메트릭 솔리드, 곡면 또는 T-Spline 바디의 전체 쉐이프를 구동하는 기본 스케치 프로파일을 작성해야 합니다. 스케치는 이후의 모든 파라메트릭 모델링의 토대입니다. 견고한 스케치 프로파일을 작성하는 경우 워크플로우를 개선하고 디자인의 잠재적인 하위 공정 문제를 최소화할 수 있습니다.

평면이나 바디의 기존 평면 면에 스케치를 작성하고 **XY**, **YZ** 및 **ZX** 평면을 기준으로 형상을 작성하거나 3D 공간의 임의 점에서 형상을 작성할 수 있습니다.

스케치는 선, 원, 호, 점 및 스플라인과 같은 2D 형상으로 구성됩니다. 스케치 형상을 그리거나 기존 형상에서 스케치 평면으로 모서리를 형상 투영할 수 있습니다.

또한 매개변수, 구속조건 및 치수를 사용하여 스케치 형상을 완전히 정의할 수 있습니다. 이렇게 하면 스케치에서 작성하는 3D 바디의 형태를 제어할 수 있습니다.

![3D 스케치 개요](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/3d-sketch.png)

스케치 프로파일
--------

Fusion 360에는 두 가지 유형의 스케치 프로파일이 있습니다.

*   **열린 프로파일**은 닫힌 경계를 형성하지 않는 일련의 연결된 2D 형상입니다.
    *   열린 프로파일을 사용하여 곡면 바디를 작성하거나, 얇은 솔리드 피쳐를 돌출시키거나, **로프트**와 같은 일부 모델링 작업을 안내할 수 있습니다.
*   **닫힌 프로파일**은 닫힌 경계를 형성하는 일련의 연결된 2D 형상입니다.
    *   스케치 프로파일은 닫힐 때 파란색으로 음영처리되며 3D 쉐이프를 **돌출**하거나 **결합**, **절단** 및 **교차**와 같은 3D 부울 연산을 수행하는 데 사용할 수 있습니다.

|프로파일 유형|예|용도|||
|:---:|:---:|:---:|:---:|:---:|
|열린|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/profile-open.gif)|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/profile-open-surface-extrude.gif)|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/profile-open-solid-thin-extrude.gif)|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/profile-open-surface-loft.gif)|
|닫힌|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/profile-closed.gif)|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/profile-closed-solid-extrude-cut.gif)|||

구속되지 않은 스케치 및 구속된 스케치
---------------------

**스케치** 환경에서는 구속되지 않았거나, 부분적으로 구속되었거나, 완전히 구속된 스케치를 작성할 수 있습니다.

**구속되지 않은 스케치**에는 여전히 공간에서 자유롭게 이동할 수 있는 형상이 포함되어 있습니다. 스케치가 구속조건 및 치수에 의해 완전히 잠기지는 않습니다.

*   **브라우저**에서 스케치 옆의 아이콘 ![구속되지 않은 스케치 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/icon/skt/timeline-sketch.png)은 스케치가 구속되지 않았음을 나타냅니다.
*   구속되지 않은 스케치는 디자인 프로세스 초기에 유용합니다. 구속되지 않은 스케치는 초기 형상 디자인 선택에서 실험해가면서 유연하게 작업하기를 원할 때 이상적입니다. 디자인을 발전시키면서 스케치에 구속조건과 치수를 점차적으로 추가할 수 있습니다. 그러나 하위 공정 디자인 피쳐에서 구속되지 않은 스케치 형상을 참조하면 예기치 않은 결과가 발생할 수 있으며 복잡한 파라메트릭 조립품이 발생할 수 있습니다.

**구속된 스케치**에는 구속조건 및 치수에 의해 제자리에 잠긴 형상이 포함되어 있습니다.

*   **브라우저**에서 스케치 옆의 아이콘 ![완전히 구속된 스케치 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/icon/browser/fc-sketch.png)은 스케치가 완전히 구속되었음을 나타냅니다.
*   구속된 스케치 형상을 캔버스에서 끌려고 하면 이동할 수 없습니다. 구속된 스케치는 디자인의 정확한 상세 정보를 알고 있고 디자인 의도를 확신할 때 유용합니다. 파라메트릭 디자인에서의 동작을 보다 쉽게 예측할 수 있습니다. 그러나 구속된 스케치는 디자인 프로세스 초기에 필요로 하는 것보다 피쳐를 보다 강력하게 잠글 수 있습니다. 디자인 프로세스 초기에 스케치에 구속조건과 치수를 너무 많이 추가하지 않도록 주의하십시오.

![구속되지 않음 구속됨 애니메이션](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/animation/unconstrained-constrained.gif)

형상 유형
-----

스케치에서 형상을 작성할 때 사용할 수 있는 여러 가지 다른 선종류를 작성할 수 있습니다.

|형상 유형|설명|예|
|:---:|:---:|:---:|
|스케치 형상|스케치에서 형상을 작성하는 데 사용되는 기본 선종류입니다.</br></br>스케치 프로파일에 영향을 줍니다.</br></br>구속되지 않은 경우 파란색 실선으로 표시됩니다.|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/geometry-sketch.png)|
|구성 형상|스케치 형상, 구속조건 및 치수에 대한 참조로 사용되는 선종류입니다.</br></br>스케치 프로파일에는 영향을 주지 않습니다.</br></br>구속되지 않은 경우 대시 오렌지색 형상으로 표시됩니다.|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/geometry-construction.png)|
|중심선 형상|스케치 프로파일을 회전하거나 대칭을 정의하는 데 사용되는 선종류입니다.</br></br>스케치 프로파일에 영향을 줍니다.</br></br>구속되지 않은 경우 대시 오렌지색 중심선 형상으로 표시됩니다.|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/geometry-centerline.png)|
|투영 형상|스케치 평면에 형상 투영되는 스케치 외부의 2D 또는 3D 형상 프로파일에 대한 연관 참조입니다.</br></br>스케치 프로파일에 영향을 줍니다.</br></br>자주색 형상으로 표시됩니다.참조된 형상에 대한 변경 사항을 반영하도록 업데이트됩니다.|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/geometry-projection.png)|
|고정 형상|고정/비고정 구속조건을 사용하여 제자리에 잠근 모든 스케치, 구성 또는 중심선 형상입니다.</br></br>스케치 프로파일에 영향을 줍니다.</br></br>초록색 형상으로 표시됩니다.</br></br>고정 형상을 편집하거나 이동해야 하는 경우 고정/비고정 구속조건을 사용하여 고정 형상을 잠금해제합니다.|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/geometry-fixed.png)|
|구속된 형상|이동할 수 없는 방식으로 구속되거나 치수가 기입된 모든 형상입니다.</br></br>검은색 형상으로 표시됩니다.|![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/geometry-constrained.png)|

2D 및 3D 스케치
-----------

2D 스케치는 스케치 형상을 작성할 때 스케치 작성 시 선택한 스케치 평면으로 구속합니다.

*   XY, YZ 또는 ZX 원점 평면
*   평면 면
*   구성 평면

3D 공간의 아무 곳에서나 스케치 평면을 선택할 수 있지만 스케치 형상은 선택한 평면으로 제한됩니다.

**3D 스케치**를 사용으로 설정하면 평면형 제한이 제거되며 3D 공간의 모든 위치에서 스케치 형상을 작성할 수 있습니다.

*   2D 스케치를 사용하여 돌출 및 회전과 같은 피쳐에 대한 평면형 스케치 형상을 작성할 수 있습니다.
*   **3D 스케치**를 사용하여 튜빙, 스윕 및 로프트의 경로를 작성하거나 곡면 모서리를 작성할 수 있습니다.

![3D 스케치 스윕](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/3d-sketch-sweep.png)

3D 스케치 조작기
----------

**3D 스케치 조작기**를 사용하면 3D 공간에서 스케치 형상을 작성하는 위치를 제어할 수 있습니다. 3D를 사용할 수 있는 모든 스케치 명령에 공통적으로 해당됩니다.

**3D 스케치 조작기**는 다음 세 가지 구성요소로 구성됩니다.

|조작기 구성요소|용도|
|:---:|:---:|
|평면|임시 스케치 평면으로 사용됩니다.|
|축|모든 방향에서 직교 스케치 형상을 작성할 수 있습니다.|
|회전 핸들|스케치 평면을 특정 각도로 회전하거나 기본 방향으로 재설정할 수 있습니다.|

이러한 각 구성요소를 활용하여 3D 공간에서 스케치 형상을 작성할 수 있습니다.

![3D 스케치 조작기](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/example/3d-sketch-manipulator.png)

스케치 상황별 탭
---------

새 스케치를 작성하거나 ![스케치 작성 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/icon/skt/create.png) 기존 스케치를 편집할 때 도구막대의 다른 도구막대 탭과 함께 **스케치** 상황별 탭이 표시됩니다.

**스케치** 상황별 탭에는 디자인의 3D 형상을 구동하는 2D 및 3D 스케치를 작성, 수정 및 구속할 수 있는 도구가 포함되어 있습니다.

![디자인 작업공간 - 스케치 탭](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/toolbar/design-sketch.png)

활성 스케치를 편집하는 동안 **솔리드** 및 **곡면**과 같이 표시되는 다른 도구막대 탭에 계속 액세스하여 **돌출**과 같은 명령을 사용할 수 있습니다. 그러나 활성 스케치를 편집하는 동안 3D 모델링 명령을 호출하면 스케치가 자동으로 완료되고 **스케치** 탭이 사라집니다.

스케치 팔레트 대화상자
------------

새 스케치를 작성하거나 ![스케치 작성 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/icon/skt/create.png) 기존 스케치를 편집하면 **스케치 팔레트** 대화상자가 캔버스에 표시됩니다.

![스케치 팔레트 대화상자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Sketch/images/dialog/sketch-palette.png)

**스케치 팔레트** 대화상자에서 다음 옵션을 제어할 수 있습니다.

*   **피쳐 옵션**: 활성 스케치 명령과 관련된 옵션을 표시합니다.
*   **선종류**: 선택한 스케치 형상을 다른 선종류로 변환합니다.
    *   **구성**: 스케치 프로파일의 경계에 영향을 주지 않고 참조할 수 있는 구성 형상을 작성합니다.
    *   **중심선**: 중심선 형상을 작성합니다. 중심선은 스케치 프로파일의 경계에 영향을 줍니다.
*   **보기**: 활성 스케치 평면을 직접 볼 수 있도록 카메라를 회전합니다.
*   **스케치 그리드**: 캔버스에서 스케치 그리드를 표시하거나 숨깁니다.
*   **스냅**: 스케치 그리드로 스냅하는 기능을 사용하거나 사용하지 않도록 설정합니다.
*   **슬라이스**: 활성 스케치 평면과 교차하는 바디를 일시적으로 절단합니다.
*   **프로파일 표시**: 닫힌 스케치 프로파일에 파란색 음영을 표시하거나 숨깁니다.
*   **점 표시**: 스케치 점을 표시하거나 숨깁니다.
*   **치수 표시**: 스케치 치수를 표시하거나 숨깁니다.
*   **구속조건 표시**: 스케치 구속조건을 표시하거나 숨깁니다.
*   **형상 투영된 형상 표시**: 활성 스케치에서 형상 투영된 형상을 표시하거나 숨깁니다.
*   **3D 스케치**: 3D에서 스케치하는 기능을 사용하거나 사용하지 않도록 설정합니다.

```{toctree}
create_a_sketch.md
start_a_sketch_on_a_place_or_face.md
create_construction_geometry.md
create_centerline_geometry.md
finish_a_sketch.md
edit_a_sketch.md
copy_a_sketch.md
redefine_a_sketch_plane.md
save_as_DXF.md
sketch_palette_dialog.md
supported_3d_sketch_commands.md
supported_3d_sketch_constraints.md
```