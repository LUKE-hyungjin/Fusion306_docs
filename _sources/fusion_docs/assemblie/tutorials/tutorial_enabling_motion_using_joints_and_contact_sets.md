---
layout: default
title: 튜토리얼-접합 및 접촉 세트를 사용하여 동작 활성화
nav_order: 4
permalink: /docs/assemblies/tutorials/tutorial_enabling_motion_using_joints_and_contact_sets
parent: 튜토리얼
grand_parent: 조립품
---
튜토리얼: 접합 및 접촉 세트를 사용하여 동작 활성화
=============================

이 튜토리얼에서는 제네바 드라이브의 구성요소를 조립하는 프로세스를 안내합니다. 조립된 경우 구성요소를 이동하여 기어 매커니즘의 동작을 시각화할 수 있습니다.

이 튜토리얼에서 수행한 작업은 다음과 같습니다.

*   회전자 부분조립품의 모든 구성요소에 강체 그룹을 적용합니다.
*   회전 접합을 추가하여 프레임 부분조립품 내에 로터 부분조립품을 배치합니다.
*   접촉 세트를 사용하도록 설정한 다음 교차 부분조립품의 휠과 로터 부분조립품의 핀 사이에 접촉 세트를 작성합니다.

![동작](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-motion.gif)

_작동 기어 메커니즘을 갖춘 조립된 제네바 드라이브_

팁: 명령을 찾는 데 문제가 있는 경우 `S` 키를 클릭하고 [**도구 상자**](https://help.autodesk.com/view/fusion360/KOR/?contextId=GS-ACCESS-COMMANDS-TOOLBOX)를 사용하여 명령을 검색하십시오.

필수 요건
-----

*   **디자인** 작업공간이 활성 상태입니다.
    
*   **제네바 드라이브** 디자인 파일이 열려 있습니다.
    
    1.  필요한 경우 **데이터 패널 표시** ![데이터 패널 표시](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/common/data-panel.png)를 클릭합니다. 프로그램 창의 왼쪽에 **데이터 패널**이 나타납니다.
    2.  **샘플** 아래에서 **기본 교육 > 06 - 조립품 > 제네바 드라이브**를 두 번 클릭합니다.
    3.  **데이터 패널**을 닫습니다.

<details>
<summary>작업: 강체 그룹을 적용하고, 회전 접합을 추가하고, 접촉 세트를 작성합니다.</summary>
<div markdown="1">       

작업: 강체 그룹을 적용하고, 회전 접합을 추가하고, 접촉 세트를 작성합니다.
===========================================

이 작업에서는 디자인 파일의 사본을 저장하고, 회전자 부분조립품을 구성하는 모든 구성요소에 강체 그룹을 적용하고, 회전 접합을 추가하여 프레임 부분조립품 내에 로터 부분조립품을 배치하고, 접촉 세트를 사용하도록 설정한 다음, 횡단구성요소의 휠과 로터 부분조립품의 핀 사이에 접촉 세트를 작성합니다.

![부분조립품](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-1-subassemblies.png)

_회전자, 교차 및 프레임 부분조립품_

단계
--

1.  **제너바 드라이브** 디자인 파일의 사본을 저장합니다.
    
    a.  **파일 > 다른 이름으로 저장**을 클릭합니다.
    b.  **이름**을 입력합니다.
    c.  **위치** 옆의 ![아래쪽 화살표](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/save-as-arrow-down.png)를 클릭합니다.
    d.  **프로젝트**에서 프로젝트를 찾아 선택합니다. 또는 프로젝트를 작성하려면 **새 프로젝트**를 클릭합니다.
    e.  프로젝트에서 폴더를 찾아 선택합니다. 또는 폴더를 작성하려면 **새 폴더**를 클릭합니다.
    f.  **저장**을 클릭합니다.
2.  회전자 부분조립품을 구성하는 모든 구성요소에 강체 그룹을 적용합니다.
    
    a.  **솔리드 > 조립 > 강체 그룹** ![강체 그룹](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/rigid-group.png)을 클릭합니다. **강체 그룹** 대화상자가 표시됩니다.
        
    주: 캔버스에서 하나 이상의 구성요소를 이동한 경우 현재 위치를 캡처할지 아니면 이전 위치에서 계속할지 묻는 메시지가 표시됩니다. **계속**을 클릭합니다.
        
    b.  **브라우저**에서 **로터** 부분조립품을 확장한 다음 다섯 개의 구성요소를 선택합니다.
        
    ![회전자 횡단구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-2-rotor-subassembly.png)
        
    c.  대화상자에서 **하위 구성요소 포함**이 선택되어 있는지 확인한 다음 **확인**을 클릭합니다. 이렇게 하면 구성요소의 상대 위치가 잠기고 하나의 구성요소로 취급됩니다.
        
3.  회전 접합을 추가하여 프레임 부분조립품 내에 로터 부분조립품을 배치합니다.
    
    a.  **솔리드 > 조립 > 접합**을 클릭합니다. **접합** 대화상자가 표시됩니다.
        
    b.  캔버스에서 ViewCube의 아래쪽 구석 아이콘을 클릭하여 횡단구성요소 뷰의 방향을 다시 정합니다.
        
    ![ViewCube](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-8-view-cube-lower-corner.png)
        
    c.  `Ctrl` 키를 누른 채 로터 조립품 아래쪽의 원형 면을 클릭합니다.
        
    ![로터 원형 면](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-3-rotor-circular-face.png)
        
        회전자 횡단구성요소의 색상이 변경됩니다.
        
    ![로터 원형 면 선택됨](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-9-rotor-circular-face-selected.png)
        
    d.  ViewCube에서 홈 아이콘을 클릭하여 횡단구성요소 뷰의 방향을 원래 상태로 다시 조정합니다.
        
    ![ViewCube](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-10-view-cube-home.png)
        
    e.  `Ctrl` 키를 누른 채 프레임 부분조립품에서 흰색 디스크를 클릭합니다.
        
    ![프레임 디스크](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-4-frame-disk.png)
        
        회전자 횡단구성요소는 프레임 횡단구성요소 내의 위치로 이동합니다.
        
    f.  대화상자의 **모션** 영역에서 **회전**의 **유형** 옵션을 선택합니다.
        
    g.  **Z축**의 **회전** 옵션이 선택되어 있는지 확인한 다음 **확인**을 클릭합니다.
        
4.  접촉 세트를 사용하도록 설정한 다음 횡단구성요소의 휠과 로터 부분조립품의 핀 사이에 접촉 세트를 작성합니다.
    
    a.  횡단구성요소 휠의 둥근 모서리가 로터 횡단구성요소의 원형 면에 대해 위쪽에 있는지 확인합니다. 그렇지 않은 경우 올바른 위치에 올 때까지 로터를 클릭하여 끕니다.
        
    ![면에 대한 모서리](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-5-edge-against-face.png)
        
    b.  **솔리드 > 조립 > 접촉 세트 사용** ![접촉 세트 사용](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/contact-set.png)을 클릭합니다. **접촉: 세트** 폴더가 **브라우저**에 추가됩니다.
        
    c.  **브라우저**에서 **접촉: 세트** 폴더를 마우스 오른쪽 버튼으로 클릭하고 **새 접촉 세트**를 선택합니다. **새 접촉 세트** 대화상자가 표시됩니다.
        
    d.  캔버스에서 횡단구성요소의 파란색 휠을 클릭합니다.
        
    ![휠 선택됨](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-6-wheel-selected.png)
        
    e.  **브라우저**에서 **프레임:1** 옆에 있는 ![표시](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/visible.png)를 클릭하여 캔버스에서 프레임 부분조립품을 숨깁니다.
        
    f.  캔버스에서 회전자 부분조립품에 있는 흰색 핀의 외부 면을 클릭합니다.
        
    ![핀 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-7-pin-selected.png)
        
    프레임 부분조립품이 다시 나타납니다.
        
    ![휠 및 핀 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-11-wheel-pin-selected.png)
        
    g.  대화상자에서 **확인**을 클릭합니다.
        
5.  로터를 클릭하여 이동하여 핀이 십자선의 휠 슬롯에 들어갈 수 있도록 한 다음 핀이 슬롯에서 나올 때까지 점차적으로 이동하여 매커니즘이 작동하는지 확인합니다.

</div>
</details>
<details>
<summary>튜토리얼 결론: 접합 및 접촉 세트를 사용하여 동작 활성화</summary>
<div markdown="1">       

튜토리얼 결론: 접합 및 접촉 세트를 사용하여 동작 활성화
================================

이 튜토리얼에서는 기어 매커니즘의 동작을 시각화할 수 있도록 제네바 드라이브의 구성요소를 조립하는 프로세스를 안내했습니다.

이 튜토리얼에서 수행한 작업은 다음과 같습니다.

*   회전자 부분조립품의 모든 구성요소에 강체 그룹을 적용했습니다.
*   프레임 부분조립품 내에 로터 부분조립품을 배치하기 위한 회전 접합이 추가되었습니다.
*   접촉 세트를 사용하도록 설정한 다음 교차 부분조립품의 휠과 로터 부분조립품의 핀 사이에 접촉 세트를 작성했습니다.

![동작](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/6-motion.gif)

_작동 기어 메커니즘을 갖춘 조립된 제네바 드라이브_

</div>
</details>


