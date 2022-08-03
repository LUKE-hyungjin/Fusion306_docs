---
layout: default
title: 튜토리얼-수동으로 접합 추가
nav_order: 2
permalink: /docs/assemblies/tutorials/tutorial_manually_adding_joints
parent: 튜토리얼
grand_parent: 조립품
---
튜토리얼: 수동으로 접합 추가
================

상향식 전략을 사용할 때 조립품의 구성요소는 동일한 디자인에 삽입되기 전에 서로 독립적으로 만들어집니다. 동일한 디자인에서 구성요소를 올바르게 배치하고 수동으로 접합을 추가하여 구성요소가 서로 상대적으로 이동하는 방식을 정의할 수 있습니다.

이 튜토리얼에서는 클램프 조립품의 구성요소에 접합을 추가하여 클램프가 이동하는 방식을 제어합니다.

![조립된 클램프](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-finished-asy-moved-2-loc.png)

조립된 모든 구성요소와 부품이 이동하는 방식을 나타내는 접합을 포함하는 클램프

필수 요건
-----

1.  ![대체](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/common/data-panel.png) **데이터 패널 > 새 프로젝트**를 클릭하고 프로젝트 **메뉴얼 접합**을 입력하여 프로젝트 폴더를 작성합니다. 이 프로젝트에서 클램프를 조립합니다.
2.  ![대체](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/common/data-panel.png) **데이터 패널 > 기본 교육 > 06 - 조립품**을 클릭합니다. 다음 부품을 두 번 클릭하여 엽니다.
    *   기준
    *   클램프
    *   커넥터
    *   그립
    *   레버
    *   샤프트
3.  **파일 > 다른 이름으로 저장**을 클릭하고 **메뉴얼 접합** 프로젝트에서 각 부품을 저장합니다.
4.  새 위치에 저장한 후 각 부품을 닫습니다.
5.  **메뉴얼 접합** 프로젝트를 두 번 클릭하여 열고 파일이 프로젝트에 있는지 확인합니다.
6.  제목 없는 새 디자인이 열려 있는지 확인합니다.
7.  **저장**을 클릭하여 **메뉴얼 접합** 위치에 **클램프 접합** 이름으로 디자인을 저장합니다.

<details>
<summary>작업: 클램프 조립 및 접합 추가</summary>
<div markdown="1">       

작업: 클램프 조립 및 접합 추가
==================

이 작업에서는 부품을 **클램프 접합** 디자인에 삽입하고 접합을 추가하여 부품의 동작과 전체 디자인을 나타냅니다.

1.  **기준**을 클램프 접합 디자인에 삽입하고 삽입했던 위치에 **고정**합니다.
    
    a.  데이터 패널에서 **기준** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **현재 디자인에 삽입**을 선택합니다.
        
    b.  베이스가 디자인에 배치될 때 열리는 이동/복사 대화상자에서 **확인**을 클릭하여 기본 위치를 승인합니다.
       
    c.  브라우저에서 **기준** 노드를 마우스 오른쪽 버튼으로 클릭하고 **고정**을 선택하여 기준을 현재 위치에 고정합니다.
        
    ![고정 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-ground.png)
        
2.  **레버**를 삽입하고 **회전** 접합을 사용하여 베이스에 부착합니다.
    
    a.  데이터 패널에서 **레버** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **현재 디자인에 삽입**을 선택합니다.
        
    b.  이동/복사 대화상자의 Z 이동 조작기를 사용하여 레버를 베이스 밖으로 이동하고 **확인**을 클릭합니다.
        
    ![이동 레버](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-move-lever.png)
        
    c.  **솔리드 > 조립 > 접합**을 클릭합니다.
        
    d.  접합 대화상자에서 동작 유형을 **회전**으로 설정합니다. 이 접합은 회전 자유도를 하나만 허용합니다.
        
    e.  첫 번째 구성요소 선택의 경우 **레버**에서 핀의 중심을 클릭합니다. 스냅 위치는 삼각형 그림문자이며 핀 내부에 있기 때문에 보기 어렵습니다.
        
    ![레버 핀 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-lever-pin.png)
        
    f.  두 번째 구성요소를 선택하려면 **기준**에서 핀 구멍의 중심을 클릭합니다. 스냅 위치는 삼각형 그림문자입니다. 구멍의 내부 벽 위에 마우스를 놓아 구멍을 강조 표시합니다. **Ctrl** 키를 누른 다음 중심 스냅 위치를 선택합니다.
        
    ![기준 레버 구멍 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-base-lever-pin-hole.png)
        
    g.  접합 대화상자에서 **반전**을 클릭하여 부품 방향을 올바르게 지정합니다.
        
    h.  **확인**을 클릭하여 접합을 마칩니다.
        
    ![베이스에 조립된 레버](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-asy-base-lever.png)
        
3.  **레버**의 열린 구멍 중간에 접합 원점을 작성합니다.
    
    a.  브라우저에서 **레버** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **열기**를 선택합니다.
        
    ![레버 면 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-browser-open.png)
        
    b.  **솔리드 > 조립 > 접합 원점**을 클릭합니다.
        
    c.  **유형**을 **두 면 사이**로 설정합니다.
        
    d.  레버 암의 내부 면을 두 면으로 선택합니다.
        
    ![레버 면 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-lever-faces.png)
        
    5.  구멍 중 하나의 모서리를 선택하여 평면 사이의 구멍 중심에 접합 원점을 정의합니다.
        
    6.  **확인**을 클릭하여 접합 원점을 마칩니다.
        
    7.  **레버** 디자인을 저장합니다.
        
4.  **클램프 접합** 디자인에 **커넥터**를 추가할 준비를 합니다.
    
    a.  **클램프 접합** 디자인으로 돌아갑니다.
        
    클램프 접합 디자인에서 레버는 기한이 만료되어 브라우저의 레버 노드에 노란색 삼각형 아이콘이 표시되어 접합 원점을 추가했기 때문에 표시됩니다.
        
    b.  브라우저에서 레버 노드를 마우스 오른쪽 버튼으로 클릭하고 **업데이트 가져오기**를 선택합니다. 주: 상황에 맞는 메뉴에 **최신 버전 가져오기**가 표시될 수 있습니다.
        
    c.  레버를 클릭하고 앞쪽 위치로 이동합니다. 정확한 위치는 중요하지 않습니다.
        
    ![이동 레버](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-move-lever-to-location.png)
        
5.  **커넥터**를 삽입하고 **회전** 접합을 사용하여 작성된 접합 원점을 사용하여 레버에 부착합니다.
    
    a.  데이터 패널에서 **커넥터** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **현재 디자인에 삽입**을 선택합니다.
        
    b.  이동/복사 대화상자의 Y 이동 조작기를 사용하여 레버를 베이스 밖으로 이동하고 **확인**을 클릭합니다.
        
    ![커넥터 이동](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-move-connector.png)
        
    c.  **솔리드 > 조립 > 접합**을 클릭하고 접합 대화상자에서 동작 유형을 **회전**으로 설정합니다.
        
    d.  커넥터의 현재 위치를 사용하려는 경우 대화상자에서 **위치 캡처**를 클릭합니다.
        
    e.  첫 번째 구성요소를 선택하려면 **커넥터**에서 핀의 중심을 클릭합니다.
        
    ![커넥터 핀 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-connector-center-pin.png)
        
    f.  두 번째 구성요소 선택에 대해 작성한 접합 원점을 클릭하고 **확인**을 클릭합니다.
        
    ![원점 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-lever-joint-origin.png)
        
    g.  커넥터가 레버에 제대로 조립되어 있는지 확인합니다.
        
    ![조립 커넥터-레버](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-asy-Connector-lever.png)
        
6.  **샤프트**를 삽입하고 **원통형** 접합을 사용하여 밑면에 부착합니다. 원통형 접합을 사용하면 부품을 회전하여 한 축 주위로 변환할 수 있습니다.
    
    a.  데이터 패널에서 **샤프트** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **현재 디자인에 삽입**을 선택한 다음 **확인**을 클릭하여 삽입 위치를 승인합니다.
        
    b.  **솔리드 > 조립 > 접합**을 클릭하고 접합 대화상자에서 동작 유형을 **원통형**으로 설정합니다.
        
    c.  샤프트의 끝에 마우스를 놓고 첫 번째 구성요소 선택의 중심을 선택합니다.
        
    ![원점 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-shaft-end.png)
        
    d.  기준 끝에 있는 샤프트 구멍을 선택하여 두 번째 구성요소를 선택하고 **확인**을 클릭합니다.
        
    ![원점 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-base-shaft-hole.png)
        
    e.  샤프트가 베이스에 제대로 조립되어 있는지 확인합니다.
        
    ![베이스에 결합된 샤프트](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-asy-base-shaft.png)
        
7.  **회전** 접합을 사용하여 **샤프트**를 **커넥터**에 결합합니다.
    
    a.  **솔리드 > 조립 > 접합**을 클릭하고 접합 대화상자에서 동작 유형을 **회전**으로 설정합니다.
        
    b.  구성요소가 이동되었음을 나타내는 대화상자가 표시되면 **위치 캡처**를 클릭합니다.
        
    c.  첫 번째 구성요소를 선택하려면 **샤프트**에서 구멍의 삼각형 중심 그림문자를 클릭합니다.
        
    ![샤프트 구멍 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-shaft-hole.png)
        
    d.  **Ctrl** 키를 누른 다음 **커넥터**에서 두 번째 구성요소를 선택할 핀의 삼각형 중심 그림문자를 선택하고 **확인**을 클릭합니다.
        
    ![커넥터 핀 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-connector-center-pin2.png)
        
    e.  샤프트가 커넥터에 제대로 조립되어 있는지 확인합니다.
        
    ![커넥터 및 샤프트 결합](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-asy-Connector-shaft.png)
        
8.  **클램프**를 삽입하고 **볼** 접합을 사용하여 베이스에 부착합니다. 볼 접합을 사용하면 부품을 세 축 주위로 회전할 수 있습니다.
    
    a.  데이터 패널에서 **클램프** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **현재 디자인에 삽입**을 선택합니다.
        
    b.  **솔리드 > 조립 > 접합**을 클릭하고 접합 대화상자에서 동작 유형을 **볼**으로 설정합니다.
        
    c.  구성요소가 이동되었음을 나타내는 대화상자가 표시되면 **위치 캡처**를 클릭합니다.
        
    d.  첫 번째 구성요소 선택을 위해 클램프에서 볼 소켓의 중심을 선택합니다.
        
    ![클램프 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-clamp.png)
        
    e.  두 번째 구성요소로 사용할 샤프트 볼의 중심을 선택하고 **확인**을 클릭합니다.
        
    ![샤프트 볼 끝 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-shaft-ball.png)
        
    f.  클램프가 샤프트에 제대로 조립되어 있는지 확인합니다.
        
    ![샤프트 볼 끝 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-asy-Clamp-shaft.png)
        
9.  **강체** 접합을 사용하여 **레버**에 \*\* 그립\*\*을 결합합니다.
    
    a.  데이터 패널에서 **그립** 디자인을 마우스 오른쪽 버튼으로 클릭하고 **현재 디자인에 삽입**을 선택한 다음 **확인**을 클릭하여 삽입 위치를 승인합니다.
        
    b.  **솔리드 > 조립 > 접합**을 클릭하고 접합 대화상자에서 동작 유형을 **강체**로 설정합니다.
        
    c.  구성요소가 이동되었음을 나타내는 대화상자가 표시되면 **위치 캡처**를 클릭합니다.
        
    d.  스냅점이 아닌 내부 그립 면을 클릭합니다. 그러면 스냅 점의 선택이 이 면의 스냅점으로만 제한됩니다.
        
    ![내부 면 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-inside-grip-face.png)
        
    e.  그립 상단의 반지름 중심을 나타내는 스냅점을 클릭합니다.
        
    ![내부 중심점 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-inside-grip-center-pt.png)
        
    f.  선택한 그립 위치에 해당하는 레버 핸들 반지름의 중심을 클릭하고 **확인**을 클릭합니다.
        
    ![핸들 중심 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-select-lever-handle.png)
        
    g.  그립이 레버에 제대로 조립되어 있는지 확인합니다.
        
    ![결합 그립 및 레버](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-asy-grip-lever.png)

</div>
</details>
<details>
<summary>튜토리얼 결론: 수동으로 접합 추가</summary>
<div markdown="1">       
튜토리얼 결론: 수동으로 접합 추가
===================

이 튜토리얼에서는 클램프 조립품의 구성요소에 접합을 적용하여 클램프가 이동하는 방식을 제어했습니다. 적용한 접합 유형은 다음과 같습니다.

*   해상도
*   원통형
*   볼
*   강체

![조립된 클램프](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/asy-t4-finished-asy-moved-2-loc.png)

조립된 모든 구성요소와 부품이 이동하는 방식을 나타내는 접합을 포함하는 클램프

</div>
</details>
