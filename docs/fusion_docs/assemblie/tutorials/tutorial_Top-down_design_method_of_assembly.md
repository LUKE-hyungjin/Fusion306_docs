---
layout: default
title: 튜토리얼-하향식 조립품 디자인 방법
nav_order: 1
permalink: /docs/assemblies/tutorials/tutorial_Top-down_design_method_of_assembly
parent: 튜토리얼
grand_parent: 조립품
---
튜토리얼: 하향식 조립품 디자인 방법
====================

하향식 디자인은 동일한 디자인에서 구성요소를 작성하는 디자인 방법입니다. 하향식 디자인을 사용하면 부품 간의 관계를 쉽게 작성하고 관리할 수 있습니다.

Fusion 360에는 다음과 같은 두 가지 유형의 접합 명령이 있습니다.

*   **현재 위치에서 접합** 명령으로, 이미 위치에 있고 구성요소를 결합해야 하는 구성요소에 사용합니다.
*   **접합** 명령 - 올바른 위치에 있지 않은 구성요소에 사용합니다. **접합** 명령은 일반적으로 분산된 디자인에 사용되지만 하향식 디자인에도 사용할 수 있습니다.

[여기](https://help.autodesk.com/view/NINVFUS/KOR/?guid=GUID-A83EFB3E-E7C4-4B78-A842-59069004BDC0)를 클릭하여 **현재 위치에서 접합**과 **접합** 간의 차이점에 대해 알아보십시오.

이 튜토리얼에서는 하향식 디자인 방법을 사용하여 다음을 수행합니다.

*   구성요소를 작성하고 현재 위치에서 접합을 추가합니다.
    
*   구성요소에 접합 및 현재 위치에서 접합을 추가합니다.
    
    ![현재 위치에서 접합이 있는 세 가지 구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-3-sketched-component.png)  
      
    작업 1 - 구성요소 생성 및 현재 위치에서 접합 추가
    
    ![현재 위치에서 접합 및 접합이 있는 카메라 장착](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-tripod-assembly.png)  
      
    작업 2 - 구성요소에 접합 및 현재 위치에서 접합 추가
<details>
<summary>작업 1: 구성요소 작성 및 현재 위치에서 접합 추가</summary>
<div markdown="1">       

작업 1: 구성요소 작성 및 현재 위치에서 접합 추가
=============================

이 작업에서는 하향식 디자인 방법을 수행하고 다음을 수행하여 구성요소를 조립합니다.

*   세 개의 구성요소에 대해 2D 프로파일 스케치
    
*   **밀고 당기기** 명령을 사용하여 프로파일을 구성요소로 돌출시킵니다.
    
*   구성요소 고정(큰 상자)
    
*   작은 상자 및 원통형 구성요소에 현재 위치에서 접합을 적용하여 해당 위치를 고정하고 해당 동작을 지정합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-activity-1-component-list.png)
    
    큰 상자 구성요소(1), 원통형 구성요소(2), 작은 상자 구성요소(3)
    

필수 요건
-----

*   단위가 **인치** 대신 **mm**로 설정되어 있는지 확인합니다.

단계
--

1.  XZ(상단) 평면에서 스케치를 시작합니다.
    
    a.  필요한 경우 작업공간 전환기를 클릭하고 **디자인**을 선택하여 디자인 작업공간으로 들어갑니다.
        
    b.  필요한 경우 새 디자인을 엽니다. 새 디자인을 열려면 **파일 > 새 디자인**을 클릭합니다.
        
    c.  **솔리드 > 작성 > 스케치 작성**을 클릭합니다.
        
    d.  스케치할 XZ(상단) 평면을 선택합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-top-plane.png)
        
    평면을 선택한 경우 일반적으로 사용되는 스케치 도구가 포함된 스케치 상황별 탭을 입력합니다. 현재 작업 또는 현재 선택한 스케치 도면요소와 관련된 옵션을 나열하는 스케치 팔레트도 사용할 수 있습니다.
        
2.  세 구성요소의 2D 스케치를 작성합니다. 원 스케치는 나중에 위치를 이동할 것이므로 완전히 정의되지 않았습니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-2d-sketch-components.png)
    
    a.  **스케치 > 작성 > 직사각형 > 2점 직사각형**을 클릭합니다.
        
    b.  스케치의 원점(또는 중심) 위에 커서를 놓습니다. 커서가 이 위치로 자동으로 스냅됩니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-hover-origin.png)
        
    c.  한 번 클릭하여 직사각형의 첫 번째 점 배치를 시작합니다.
        
    d.  마우스를 멀리 끌어 직사각형 스케치를 시작한 다음 **50mm x 120mm**가 되면 다시 클릭하여 직사각형 스케치를 완료합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-sketch-main-rectangle.png)
        
    e.  **스케치 > 작성 > 선**을 클릭합니다.
        
    f.  직사각형의 왼쪽 모서리에서 **40mm** 떨어진 수직선을 스케치합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-sketch-main-line.png)
        
    g.  수직선에 가까운 원을 스케치하고 직사각형의 하단 모서리에서 **25mm**이고 지름이 **40mm**인지 확인합니다. 원 스케치는 튜토리얼의 후반부에서 위치를 이동하므로 완전히 정의되지 않습니다. **스케치 마무리**를 클릭합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-sketch-main-circle.png)
        
3.  첫 번째 구성요소(큰 상자)를 작성하여 높이를 **20mm**로 지정합니다. **바디**가 아닌 **새 구성요소**를 작성했는지 확인합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-first-extrude.png)
    
    a.  **솔리드 > 수정 > 밀고 당기기**를 클릭합니다.
        
    b.  오른쪽에서 스케치 프로파일을 선택합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-right-sketch-profile.png)
        
    c.  **작업** 리스트에서 **새 구성요소**를 선택합니다.
        
    d.  **거리**로 **20mm**를 입력합니다. **확인**을 클릭합니다.
        
    e.  스케치의 나머지 부분이 사라지면 **브라우저**에서 스케치 폴더를 찾고 ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/hidden.png) 아이콘을 클릭하여 스케치가 보이도록 합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-sketch-make-visible.png)
        
4.  원통 구성요소가 스케치의 양쪽에서 **30mm** 연장되도록 작성합니다. **바디**가 아닌 **새 구성요소**를 작성했는지 확인합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-extrude-cylinder-30mm.png)
    
    a.  **솔리드 > 수정 > 밀고 당기기**를 클릭합니다.
        
    b.  원을 만드는 두 개의 스케치 프로파일을 선택합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-circle-sketch-profile.png)
        
    c.  **방향** 리스트에서 **대칭**을 선택합니다.
        
    d.  **작업** 리스트에서 **새 구성요소**를 선택합니다.
        
    e.  **거리**로 **30mm**를 입력합니다. **확인**을 클릭합니다.
        
    f.  이제 둘 이상의 구성요소가 있으므로 **검사 > 화면표시 구성요소 색상** ![구성요소 색상 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/common/display-component-colors.png)(`Shift+F`)을 클릭하여 캔버스에서 서로 다른 구성요소를 구분합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-component-colour-toggle.png)
        
    **주**: 색상이 자동으로 지정됩니다. 색상이 이 튜토리얼에 표시된 색상과 일치하지 않아도 됩니다. 원하는 경우 [색상 코딩](https://help.autodesk.com/view/NINVFUS/KOR/?guid=GUID-4969CAA2-5C5F-4E84-B046-92EB480D5024)을 변경할 수 있습니다.
        
5.  스케치 위로 **5mm**가 확장되고 스케치 아래로 **10mm**가 확장되도록 최종 구성요소를 작성합니다. **바디**가 아닌 **새 구성요소**를 작성했는지 확인합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-extrude-small-box.png)
    
    a.  **솔리드 > 수정 > 밀고 당기기**를 클릭합니다.
        
    b.  왼쪽에서 프로파일을 선택합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-left-sketch-profile.png)
        
    c.  **방향** 리스트에서 **두 면**을 선택합니다.
        
    d.  **작업** 리스트에서 **새 구성요소**를 선택합니다.
        
    e.  **측면 1** 아래에서 **거리**로 **5mm**를 입력합니다.
        
    f.  **측면 2** 아래에서 **거리**에 대해 **10mm**를 입력합니다. **확인**을 클릭합니다.
        
    주: 이제 브라우저에 세 개의 구성요소가 있습니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-3-components.png)
        
6.  두께가 2mm가 되도록 구성요소를 쉘링합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-2mm-shell.png)
    
    a.  **솔리드 > 수정 > 쉘**을 클릭합니다.
        
    b.  각 구성요소의 상단 면을 클릭합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-shell-top-faces.png)
        
    c.  **내부 두께**에 **2mm**를 입력합니다. **확인**을 클릭합니다.
        
7.  원통형 구성요소가 현재 두 상자 사이에 있는 큰 상자 내부에만 있도록 스케치를 수정합니다.
    
    a.  **브라우저**에서 작성한 스케치를 마우스 오른쪽 버튼으로 클릭하고 **스케치 편집**을 클릭합니다. 2D 스케치가 나타납니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-edit-sketch.png)
        
    b.  원의 중심점을 클릭하고 오른쪽으로 끌어 두 구성요소가 더 이상 겹치지 않도록 합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-drag-circle.png)
        
    c.  **스케치 팔레트**에서 **스케치 마무리**를 클릭합니다. 하향식 디자인의 이점을 보여 주는 예로, 동일한 스케치에서 세 개의 구성요소가 모두 작성되었기 때문에 모형의 업데이트된 버전이 나타납니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-new-arrangement.png)
        
8.  큰 상자 구성요소를 공간에 고정합니다. **브라우저**에서 **구성요소1:1**을 마우스 오른쪽 버튼으로 클릭한 다음 **고정**을 클릭합니다. 이제 고정되었으므로 공간에서 더 이상 구성요소 1을 자유롭게 이동할 수 없습니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-ground.png)
    
    주: 공간에서 구성요소를 수정하기 전에 원래 위치에서 이동된 구성요소가 없는지 확인합니다. 이동한 경우 리본의 **위치** 패널에 **되돌리기** 버튼이 나타나 다시 제 위치로 이동할 수 있습니다. 필요한 경우 **되돌리기** 버튼 ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-revert-position.png)을 클릭합니다.
    
9.  강체 현재 위치에서 접합을 사용하여 더 큰 상자(고정됨)를 기준으로 더 작은 상자의 위치를 고정합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-rigid-joint.png)
    
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다.
    b.  **유형** 리스트에서 **강체**를 선택합니다.
    c.  큰 상자 구성요소를 선택한 다음 작은 상자 구성요소를 선택합니다. 캔버스에서 강체 동작 애니메이션 미리보기를 표시합니다. **확인**을 클릭합니다. **팁**: **현재 위치에서 접합 대화상자**에서 ![애니메이션](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-play.png) 옆에 있는 **대체**를 클릭하여 접합 동작을 다시 미리 볼 수 있습니다.

10.  회전 현재 위치에서 접합을 사용하여 원통의 위치를 고정합니다.
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-rigid-joint.png)  
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다.  
    b.  **유형** 리스트에서 **회전**을 선택합니다.  
    c.  원통형 구성요소를 선택한 다음 큰 상자 구성요소를 선택합니다.  
    d.  필요한 경우 **위치** ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-active-position.png) 옆에 있는 버튼을 클릭하여 활성 상태인지 확인합니다.  
    e.  **위치**에 대해 원통형 구성요소의 상단 외부 모서리를 선택합니다. 캔버스에서 회전 모션 애니메이션 미리보기가 표시됩니다. **확인**을 클릭합니다.  
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-revolute_joint.gif)
        

작업 1 요약
-------

이 작업에서는 하향식 디자인 방법을 수행하고 다음을 수행하여 세 개의 구성요소를 조립했습니다.

*   세 개의 구성요소에 대해 2D 프로파일 스케치
*   **밀고 당기기** 명령을 사용하여 프로파일을 구성요소로 돌출시킵니다.
*   구성요소 고정(큰 상자)
*   작은 상자 및 원통형 구성요소에 현재 위치에서 접합을 적용하여 해당 위치를 고정하고 해당 동작을 지정합니다.

</div>
</details>
<details>
<summary>작업 2: 구성요소에 접합 및 현재 위치에서 접합 추가</summary>
<div markdown="1">       

작업 2: 구성요소에 접합 및 현재 위치에서 접합 추가
==============================

이 작업에서는 하향식 방법을 사용하여 디자인된 카메라 스탠드를 조립합니다.

*   올바른 위치에 있는 구성요소에 현재 위치에서 접합 추가
    
*   올바른 위치에 없는 구성요소에 접합 추가
    
    ![현재 위치에서 접합 및 접합이 있는 카메라 장착](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-tripod-assembly.png)
    
    다중 접합 및 현재 위치에서 접합이 카메라 스탠드에 추가됨
    

필수 요건
-----

*   데이터 파일 위치: **기본 교육 > 06 - 조립품 > 06\_tripod**

단계
--

1.  캔버스에서 삼각대 데이터 파일을 엽니다.
    
    a.  데이터 패널이 현재 표시되지 않으면 화면 상단에서 **데이터 패널 표시** ![데이터 패널 표시](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-show-data-panel.png)를 클릭합니다.
        
    b.  데이터 패널에서 **샘플**에 도달할 때까지 아래로 스크롤합니다.
        
    c.  **기본 교육** 폴더를 두 번 클릭하여 엽니다.
        
    d.  **06 - 조립품** 폴더를 두 번 클릭하여 엽니다.
        
    e.  **파일 > 다른 이름으로 저장**을 클릭하고 사본을 원하는 위치에 저장하여 원하는 위치에서 작업할 수 있습니다.
        
    f.  삼각대가 아래에 표시된 색상 코딩으로 나타나지 않으면 **검사 > 구성요소 색상 표시** ![구성요소 색상 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/common/display-component-colors.png)(`Shift+F`)을 클릭합니다.
        
    ![현재 위치에서 접합 및 접합이 있는 카메라 장착](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-tripod-colour-scheme.png)
        
    ![구성요소 순환 전환](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-toggle-colours.png)
        
2.  **빨간색 설비**, 빨간색 설비의 **나사** 및 **흰색 카메라 마운트**를 클릭하고 측면으로 끌어 새 위치를 캡처합니다.
    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-components-moved.png)
    
    **팁**: 실수로 다른 구성요소를 다른 위치로 이동한 경우 구성요소를 다시 제 위치로 이동할 수 있도록 리본의 **위치** 패널에 **되돌리기** 버튼이 나타납니다. 필요한 경우 **되돌리기** 버튼 ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-revert-position.png)을 클릭합니다.
    
    a.  빨간색 설비를 클릭하고 측면으로 끕니다.
        
    b.  흰색 카메라 마운트를 클릭하고 드래그하여 옆으로 이동합니다.
        
    c.  고정 나사를 클릭하고 끌어서 측면으로 이동합니다.
        
    d.  **위치 캡처**를 클릭하여 모든 구성요소의 현재 위치를 기본 위치로 설정합니다.
        
    ![구성요소 순환 전환](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-capture-position.png)
        
3.  스탠드 브래킷을 고정합니다. 구성요소를 고정하면 현재 위치에서 잠깁니다. 일반적으로 조립품에서 하나 이상의 구성요소를 고정합니다.
    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-ground-component.png)
    
    a.  **브라우저**에서 **스탠드:1**을 확장합니다.  
    b.  **구성요소25:1**을 마우스 오른쪽 버튼으로 클릭하고 **고정**을 클릭합니다.
4.  다리와 하우징 사이에 현재 위치에서 접합용 슬라이더를 추가합니다.
    
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다. **현재 위치에서 접합 명령**인지, **접합 명령**인지 확인합니다.
        
    b.  **유형** 리스트에서 **슬라이더**를 선택합니다.
        
    c.  회색 원통을 첫 번째 구성요소로 클릭합니다.
        
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-select-gray-cylinder.png)
        
    d.  흰색 원통을 두 번째 구성요소로 클릭합니다.
        
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-select-white-cylinder.png)
        
    e.  필요한 경우 **위치** ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-active-position.png) 옆에 있는 버튼을 클릭하여 활성 상태인지 확인합니다.
        
    f.  **위치**에 대해 흰색 원통의 아래쪽 원형 모서리를 선택합니다. 캔버스에서 슬라이더 동작 애니메이션을 미리 봅니다. **확인**을 클릭합니다.
        
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-slider-position.png)
        
    **주**: 다리는 동일한 횡단구성요소의 세 가지 복제입니다. 하나의 복제에 접합을 적용하면 세 복제 모두에 해당 접합이 추가됩니다.
        
    g.  필요한 경우 **되돌리기** 버튼 ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-revert-position.png)을 클릭하여 슬라이더 모션을 테스트하기 전에 있었던 구성요소 정렬로 돌아갑니다.
        
5.  하단 끝마감과 회색 원통 다리 사이에 강체 현재 위치에서 접합을 추가합니다.
    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-rigid-leg-end-cap.png)
    
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다.  
    b.  **유형** 리스트에서 **강체**를 선택합니다.  
    c.  하단 끝막음 중 하나와 여기에 연결된 회색 다리 중 하나를 선택합니다. 캔버스에서 강체 동작 애니메이션 미리보기를 표시합니다. **확인**을 클릭합니다. **주**: 끝마감은 다리 부분조립품의 일부이기도 합니다. 끝막음 중 하나에 접합을 적용하면 세 끝막음 모두에 접합이 적용됩니다.
6.  상단 끝마감과 흰색 원통 사이에 강체 현재 위치에서 접합을 추가합니다.
    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-rigid-top-end-cap-leg.png)
    
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다.  
    b.  **유형** 리스트에서 **강체**를 선택합니다.  
    c.  상단 끝막음 중 하나와 여기에 부착된 흰색 원통 중 하나를 선택합니다. 캔버스에서 강체 동작 애니메이션 미리보기를 표시합니다. **확인**을 클릭합니다.
7.  상단 끝마감과 커넥터 사이에 강체 현재 위치에서 접합을 추가합니다. 커넥터는 다리를 스탠드 브래킷에 연결하는 툼스톤 쉐이프 구성요소입니다.
    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-rigid-tombstone.png)
    
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다.
    b.  **유형** 리스트에서 **강체**를 선택합니다.
    c.  상단 끝막음 중 하나와 여기에 부착된 툼스톤 커넥터를 선택합니다. 캔버스에서 강체 동작 애니메이션 미리보기를 표시합니다. **확인**을 클릭합니다.
8.  커넥터와 스탠드 브래킷 사이에 회전 현재 위치에서 접합을 추가합니다.
    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-revolute-connector-bracket.png)
    
    a.  **솔리드 > 조립 > 현재 위치에서 접합**을 클릭합니다.
        
    b.  **유형** 리스트에서 **회전**을 선택합니다.
        
    c.  툼스톤 커넥터 중 하나와 브래킷을 구성요소로 선택합니다.
        
    d.  필요한 경우 **위치** ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-active-position.png) 옆에 있는 버튼을 클릭하여 활성 상태인지 확인합니다.
        
    e.  스탠드 브래킷의 구멍 외부 모서리 위에 마우스를 놓고 **Ctrl** 키를 누릅니다. **Ctrl** 키를 누르고 있으면 그림 문자 ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-glyph.png)를 화면에 유지하여 선택할 수 있습니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-select-glyph.png)
        
    f.  **Ctrl** 키를 계속 누른 상태에서 그림문자를 클릭하여 커넥터가 회전할 기준 위치로 선택합니다. 캔버스에서 회전 모션 애니메이션 미리보기가 표시됩니다. **확인**을 클릭합니다. **주**: 이 접합은 다리 부분조립품 중 하나와 주 조립품의 구성요소 사이의 접합이므로 선택한 부분조립품에만 적용됩니다. 다음으로 이 프로세스를 반복하여 다른 두 다리를 결합합니다.
        
    g.  다른 두 다리에 대해 **a**~**f** 단계를 반복합니다. **팁**: 언제든지 구성요소를 실수로 이동하여 원래 위치로 되돌리려면 **되돌리기** 버튼 ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-revert-position.png)을 클릭합니다. 이미 추가한 모션은 제거되지 **않습니다**.
        
9.  나사와 스탠드 브래킷 사이에 강체 접합을 추가합니다.
    
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-screw-and-bracket-joint.png)
    
    a.  **솔리드 > 조립 > 접합**을 클릭합니다. 사용하던 **현재 위치에서 접합**이 아닌 **접합** 명령을 사용해야 합니다.
        
    b.  **유형** 리스트에서 **강체**를 선택합니다.
        
    c.  나사 캡 밑면의 플랫 면을 첫 번째 구성요소로 선택합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-underside-screw.png)
        
    d.  스탠드 브래킷에서 구멍의 하단 모서리를 두 번째 구성요소로 선택합니다. **확인**을 클릭합니다.
        
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-bracket-bottom-edge.png)
        
10.  빨간색 설비와 스탠드 브래킷 사이에 강체 접합을 추가합니다.
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-rigid-red-stand.png)  
    a.  **솔리드 > 조립 > 접합**을 클릭합니다.  
    b.  **유형** 리스트에서 **강체**를 선택합니다.  
    c.  빨간색 설비의 하단 면 위에 마우스를 놓고 첫 번째 구성요소로 면 중심에 있는 그림문자를 클릭합니다. ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-red-comp1.png)  
    d.  스탠드 브래킷의 플랫 면 위에 마우스를 놓고 **Ctrl** 키를 누릅니다. **Ctrl** 키를 누르고 있으면 표시되는 위치로 스냅할 수 있습니다.   
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-mouse-over-flat-face.png)  
    e.  **Ctrl** 키를 누른 채 커서를 구멍 중심으로 이동하고 클릭하여 중심에 있는 그림문자를 두 번째 구성요소로 선택합니다. 캔버스에서 강체 동작 애니메이션 미리보기를 표시합니다. **확인**을 클릭합니다.  
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-center-top-face.png)

11.  빨간색 설비와 카메라 장착 사이에 볼 접합을 추가합니다.  
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-ball-joint.png)  
    a.  **솔리드 > 조립 > 접합**을 클릭합니다.
    b.  **유형** 리스트에서 **볼**을 선택합니다.  
    c.  카메라 마운트의 하단에 있는 공을 첫 번째 구성요소로 선택합니다.  
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-mount-bottom.png)  
    d.  빨간색 설비 내부의 볼 중공을 두 번째 구성요소로 선택합니다. 캔버스에서 볼 모션 애니메이션 미리보기가 표시됩니다. **확인**을 클릭합니다.     
    ![alt](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-ball-cavity.png)
        
        **주**: Fusion 360에서는 접촉 세트를 설정하지 않는 한 재질 간섭을 탐지하지 않습니다.
        
12.  스탠드 다리의 슬라이더 이동, 다리와 브래킷 간의 회전 이동 및 마운트의 볼 이동을 테스트합니다.
    a.  슬라이더 모션을 테스트합니다. 스탠드의 두 원통 사이에 있는 슬라이더 아이콘을 두 번 클릭합니다.      
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-slider-test.png)       
    b.  화살표가 나타납니다. 원통을 따라 위아래로 화살표를 드래그하여 이동을 테스트합니다.      
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-slider-joint.gif)      
    **팁**: 회색 원통을 클릭하여 캔버스의 흰색 원통에서 슬라이드할 수도 있습니다.      
    c.  회전 모션을 테스트합니다. 다리 중 하나에서 REVOLUTE 접합 아이콘을 두 번 클릭합니다.     
    d.  캔버스의 조작기를 사용하여 브래킷을 중심으로 다리를 회전합니다.    
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/revolute-leg-joint.gif)      
    e.  볼 모션을 테스트합니다. 빨간색 설비에서 REVOLUTE 접합 아이콘을 두 번 클릭합니다.      
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/2-test-revolute.png)      
    f.  캔버스의 조작기를 사용하여 해당 중공 내에서 카메라 마운트를 회전합니다.      
    ![대체 문자](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/ball_joint.gif)  
        

작업 2 요약
-------

이 작업에서는 하향식 방법을 사용하여 디자인된 카메라 스탠드를 조립했습니다.

*   올바른 위치에 있는 구성요소에 현재 위치에서 접합(강체, 회전 및 슬라이더)을 추가합니다.
*   올바른 위치에 있지 않은 구성요소에 접합(강체 및 볼)을 추가합니다.

</div>
</details>
<details>
<summary>튜토리얼 결론: 하향식 디자인</summary>
<div markdown="1">       

튜토리얼 결론: 하향식 디자인
================

이 튜토리얼에서는 하향식 디자인 방법을 사용하여 다음을 수행했습니다.

*   구성요소 작성 및 현재 위치에서 접합 추가
    
*   구성요소에 접합 및 현재 위치에서 접합을 추가합니다.
    
    ![현재 위치에서 접합이 있는 세 가지 구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-3-sketched-component.png)
    
    작업 1 - 구성요소 생성 및 현재 위치에서 접합 추가
    
    ![현재 위치에서 접합 및 접합이 있는 카메라 장착](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/1-tripod-assembly.png)
    
    작업 2 - 구성요소에 접합 및 현재 위치에서 접합 추가

</div>
</details>

