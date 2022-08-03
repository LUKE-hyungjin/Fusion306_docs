---
layout: default
title: 튜토리얼-부분조립품 및 현재 위치에서 접합 작업
nav_order: 3
permalink: /docs/assemblies/tutorials/tutorial_Working_with_subassemblies_and_As-built_joints
parent: 튜토리얼
grand_parent: 조립품
---
튜토리얼: 부분조립품 및 현재 위치에서 접합 작업
===========================

이 튜토리얼에서는 동작을 활성화하는 조립품을 작성하기 위해 바디에서 구성요소를 작성하는 프로세스를 안내합니다.

이 튜토리얼에서는 다음 작업을 수행합니다.

*   바디에서 구성요소를 작성하고 부분조립품 내에서 구성요소를 구성합니다.
*   일련의 현재 위치에서 접합을 작성하여 조립품 내에서 동작을 활성화합니다.
*   조립품의 동작을 수정하고 구성요소를 복사하여 붙여넣어 조립품을 작성합니다.

![목표 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-goals.jpg)

_동작이 있는 완성된 피스톤 조립품_

팁: `S` 키를 눌러 **도구 상자**를 표시한 다음, 현재 작업공간에서 사용할 특정 명령을 검색합니다.
<details>
<summary>작업 1: 데이터세트를 가져와 횡단구성요소 작성</summary>
<div markdown="1">       

작업 1: 데이터세트를 가져와 횡단구성요소 작성
==========================

이 작업에서는 피스톤 조립품 모형을 열고 바디를 구성요소로 변환한 다음 피스톤 부분조립품을 작성합니다.

![모형 데이터세트](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/as-built-intro-model.png)

_완성된 피스톤 횡단구성요소_

필수 요건
-----

*   Fusion 360이 시작되었습니다.
*   데이터 파일 위치: **샘플 > 기본 교육 > 06 - 조립품 > 피스톤 연결**.

단계
--

1.  피스톤 연결 모형을 엽니다.
    
    a.  필요한 경우 **데이터 패널 표시** 를 클릭합니다. 프로그램 창의 왼쪽에 데이터 패널이 나타납니다.
    b.  데이터 패널의 **샘플** 아래에서 **기본 교육 > 06 - 조립품 > 피스톤 연결**를 엽니다.
2.  디자인은 읽기 전용이므로 개인 프로젝트에 사본을 저장합니다.
    
    a.  왼쪽 상단 구석에서 **파일 > 다른 이름으로 저장**을 클릭합니다.
    b.  **이름** 상자에서 이름이 **내 피스톤 연결**인지 확인합니다.
    c.  **위치** 상자의 오른쪽에 있는 아래쪽 화살표 아이콘을 클릭합니다.
    d.  기존 폴더를 선택하거나 **새 프로젝트**를 클릭하고 **내 모형 튜토리얼**을 입력한 다음 키보드의 **Enter** 키를 눌러 새 폴더를 작성합니다.
    e.  프로젝트 파일을 **프로젝트** 리스트에 저장하려면 원하는 폴더의 이름을 클릭하거나 **내 모형 튜토리얼** 폴더를 클릭합니다.
    f.  **저장**을 클릭합니다.
3.  바디를 구성요소로 변환합니다.
    
    a.  네 개의 바디 모두를 구성요소로 변환하려면 브라우저에서 **바디** 폴더를 마우스 오른쪽 버튼으로 클릭하고 **바디에서 구성요소 작성**을 클릭합니다.
        
    ![바디에서 구성요소 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-create-comp-from-bodies.jpg)
        
    b.  구성요소는 브라우저의 개별 폴더에 나타나야 합니다.
        
4.  피스톤 부분조립품을 작성합니다.
    
    a.  주 조립품에서 빈 구성요소를 작성하려면 주 조립품 분기를 마우스 오른쪽 버튼으로 클릭하고 **새 구성요소**를 클릭합니다.
        
    ![새 구성요소 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-create-new-component.jpg)
        
    b.  두 피스톤 구성요소를 새 부분조립품으로 끕니다.
        
    ![횡단구성요소로 끌기](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-drag-parts-into-subasm.jpg)
        
    c.  새 횡단구성요소의 이름을 바꾸려면 해당 폴더를 두 번 클릭하고 **피스톤 부분조립품**를 입력합니다. 구성요소 아이콘이 조립품 아이콘으로 전환되었습니다.
        
    ![횡단구성요소 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-subassembly-1.jpg)
        
    d.  주 조립품을 다시 활성화하려면 상단 노드(**피스톤 연결**)를 마우스 오른쪽 버튼으로 클릭하고 **활성화**를 클릭합니다.
        

작업 1 요약
-------

이 작업에서는 피스톤 조립품 모형을 열고 바디를 구성요소로 변환한 다음 피스톤 부분조립품을 작성했습니다.
![구성요소 및 부분조립품](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-bodies-to-comp-sub-asm.jpg)

</div>
</details>
<details>
<summary>작업 2: 현재 위치에서 접합 작성</summary>
<div markdown="1">       

작업 2: 현재 위치에서 접합 작성
===================

이 작업에서는 조립품 내에 일련의 회전 및 원통형 현재 위치에서 접합을 작성합니다.

![접합 완료](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-all-joints-complete.jpg)

_접합이 추가된 피스톤 조립품_

필수 요건
-----

*   바디를 구성요소로 변환하고 피스톤 부분조립품을 작성하기 위한 이전 작업이 완료되었습니다.

단계
--

1.  두 암 사이에 회전 현재 위치에서 접합을 추가합니다. 이 단계를 통해 두 팔이 공유된 피벗점을 중심으로 회전할 수 있습니다.
    
    a.  **디자인** 작업공간의 **솔리드** 탭에서 **조립 > 현재 위치에서 접합**을 클릭합니다.
        
    b.  암 부품 2개를 선택합니다.
        
    ![두 팔 모두 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-arms-revolute-selection.jpg)
        
    c.  접합 유형을 설정하려면 현재 위치에서 접합 대화상자에서 유형을 **회전**로 설정합니다.
        
    d.  위치를 정의하려면 두 팔이 서로 접촉하는 원형 모서리를 선택합니다.
        
    ![회전 현재 위치에서 접합 추가](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-revolute-as-built-joint-1.jpg)
        
    e.  작업을 완료하려면 현재 위치에서 접합 대화상자에서 **확인**을 클릭합니다.
        
2.  내부 및 외부 피스톤 구성요소 사이에 원통형 현재 위치에서 접합을 추가합니다. 이 단계를 통해 내부 피스톤 구성요소가 외부 구성요소 내에서 슬라이딩할 수 있습니다.
    
    a.  디자인 작업공간의 **솔리드** 탭에서 **조립 > 현재 위치에서 접합**을 클릭합니다.
        
    b.  다음 두 피스톤 구성요소를 선택합니다.
        
    ![피스톤 구성요소 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-piston-cylindrical-selection.jpg)
        
    c.  접합 유형을 설정하려면 현재 위치에서 접합 대화상자에서 유형을 **원통형**으로 설정합니다.
        
    d.  위치를 정의하려면 다른 피스톤이 슬라이딩되는 위치인 피스톤 - 외부 구성요소의 끝에 있는 면의 중심점을 선택합니다.
        
    중심점을 선택하려면 끝 곡면의 원형 모서리 위에 마우스를 놓고 **Ctrl** 키(Mac의 경우 **Cmd**)를 누른 채 중심점을 클릭합니다. Ctrl 키(Mac의 Cmd 키)를 사용하면 선택이 특정 면으로 잠기므로 관련 중심점을 훨씬 쉽게 선택할 수 있습니다.
        
    ![원통형 현재 위치에서 접합 추가](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-cylindrical-as-built-joint.jpg)
        
    e.  작업을 완료하려면 **확인**을 클릭합니다.
        
3.  피스톤 부분조립품과 하단의 암 사이에 회전 현재 위치에서 접합을 추가합니다.
    
    이 단계를 통해 암 및 피스톤 횡단구성요소를 사용하여 피스톤 횡단구성요소 하단의 공통 점을 기준으로 서로 상대적으로 회전할 수 있습니다.
    
    a.  주 조립품을 다시 활성화하려면 상단 노드(**피스톤 연결**)를 마우스 오른쪽 버튼으로 클릭하고 **활성화**를 클릭합니다.
        
    b.  **디자인** 작업공간의 **솔리드** 탭에서 **조립 > 현재 위치에서 접합**을 클릭합니다.
        
    c.  하단 암 구성요소 및 피스톤 - 내부 구성요소를 선택합니다.
        
    ![하부 암 및 피스톤 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-lower-arm-piston-selection.jpg)
        
    d.  접합 유형을 설정하려면 현재 위치에서 접합 대화상자에서 유형을 **회전**로 설정합니다.
        
    e.  위치를 정의하려면 피스톤의 내부 원통형 면에서 내부 원통형 면의 중심점을 선택합니다.
        
    중심점을 선택하려면 피스톤의 내부 원통형 곡면 - 내부 구성요소에 커서를 가져간 후 **Ctrl** 키(Mac의 경우 **Cmd**)를 누른 채 중심점을 클릭합니다.
        
    ![회전 현재 위치에서 접합 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-revolute-as-built-joint-2.jpg)
        
    f.  작업을 완료하려면 **확인**을 클릭합니다.
        
4.  상단의 피스톤 부분조립품과 암 사이에 회전 현재 위치에서 접합을 추가합니다.
    
    이 단계를 통해 암 및 피스톤 횡단구성요소를 사용하여 피스톤 횡단구성요소 상단의 공통 점을 기준으로 서로 상대적으로 회전할 수 있습니다.
    
    a.  **디자인** 작업공간의 **솔리드** 탭에서 **조립 > 현재 위치에서 접합**을 클릭합니다.
        
    b.  상단 암 구성요소 및 피스톤 - 외부 구성요소를 선택합니다.
        
    ![팔꿈치 윗부분 및 피스톤 선택](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-upper-arm-piston-selectoin.jpg)
        
    c.  접합 유형을 설정하려면 현재 위치에서 접합 대화상자에서 유형을 **회전**로 설정합니다.
        
    d.  위치를 정의하려면 피스톤의 내부 원통형 면에서 외부 구성요소의 중심점을 선택합니다.
        
    중심점을 선택하려면 피스톤 - 외부 구성요소의 내부 원통형 곡면 위에 마우스를 놓고 **Ctrl** 키(Mac의 경우 **Cmd**)를 누른 채 중심점을 클릭합니다.
        
    ![회전 현재 위치에서 접합 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-revolute-as-built-joint-3.jpg)
        
    e.  작업을 완료하려면 **확인**을 클릭합니다.
        
    f.  접합을 보려면 브라우저에서 **접합** 폴더를 마우스 오른쪽 버튼으로 클릭하고 **표시/숨기기**를 전환합니다. 가시성 그림문자는 활성 상태여야 합니다.
        
    ![가시적 접합](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-joint-visibility.jpg)
        

작업 2 요약
-------

이 작업에서는 조립품에서 부품의 동작을 서로를 기준으로 제어하기 위해 여러 개의 현재 위치에서 접합을 작성했습니다. 두 암 간의 회전 접합, 피스톤 구성요소 간의 원통형 접합, 위쪽 및 아래쪽 피스톤 구성요소와 해당 조립품 암 간의 회전 접합을 작성했습니다.

![접합 완료](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-all-joints-complete.jpg)

_접합이 추가된 피스톤 조립품_

</div>
</details>
<details>
<summary>작업 3: 구성요소 고정 및 부분조립품 추가</summary>
<div markdown="1">       

작업 3: 구성요소 고정 및 부분조립품 추가
========================

이 작업에서는 하부 암 구성요소를 고정하여 조립품의 동작을 수정합니다. 또한 피스톤 부분조립품의 다른 복제를 추가하고 현재 위치에서 접합을 작성하여 관련 동작을 정의함으로써 조립품을 구축합니다.

![조립품 완료](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-final-asm.jpg)

_동작이 정의된 완성된 피스톤 횡단구성요소_

필수 요건
-----

*   이전 단계에서는 두 암 구성요소, 두 피스톤 부분조립품 구성요소 및 피스톤 부분조립품과 암 사이에 현재 위치에서 접합을 작성하기 위해 완료했습니다.

단계
--

1.  팔꿈치 아랫부분 구성요소를 고정하여 공간의 모형을 고정합니다.
    
    a.  팔꿈치 아랫부분을 고정하려면 브라우저에서 **암(1)**을 마우스 오른쪽 버튼으로 클릭하고 **고정**를 클릭합니다.
        
    ![브라우저에서 명령 고정](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-ground-from-browser-ui.jpg)
        
    b.  조립품의 동작을 테스트하려면 상단 암 구성요소를 클릭하고 끕니다.
        
    ![고정 구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-ground.jpg)
        
    c.  조립품의 위치를 재설정하려면 **위치** 탭에서 **되돌리기**를 클릭합니다.
        
2.  피스톤 부분조립품을 복사하고 두 암의 반대쪽에 마운팅 구멍과 일직선이 되도록 배치합니다.
    
    a.  피스톤 횡단구성요소를 복사하려면 브라우저에서 **피스톤 횡단구성요소**를 마우스 오른쪽 버튼으로 클릭하고 **복사**를 클릭합니다.
        
    b.  피스톤 횡단구성요소의 사본을 붙여넣으려면 키보드 **Ctrl V**(또는 Mac의 경우 **Cmd V**)를 누릅니다.
        
    c.  새 횡단구성요소를 배치하려면 왼쪽 180mm로 끌어 피스톤 마운팅 구멍이 두 암과 일직선이 되도록 합니다.
        
    ![부분조립품 이동](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-move-piston-subassembly.jpg)
        
    d.  명령을 완료하려면 키보드의 **Enter** 키를 누릅니다.
        
    ![횡단구성요소 추가](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-subassembly-2.jpg)
        
3.  피스톤 부분조립품과 하단의 암 사이에 회전 현재 위치에서 접합을 추가합니다.
    
    a.  **디자인** 작업공간의 **솔리드** 탭에서 **조립 > 현재 위치에서 접합**을 클릭합니다.
        
    b.  새 피스톤 부분조립품에서 하단 암 구성요소 및 피스톤 - 내부 구성요소를 선택합니다.
        
    c.  접합 유형을 설정하려면 현재 위치에서 접합 대화상자에서 유형을 **회전**로 설정합니다.
        
    d.  위치를 정의하려면 피스톤의 내부 원통형 면에서 내부 원통형 면의 중심점을 선택합니다.
        
    중심점을 선택하려면 피스톤 - 내부 구성요소의 내부 원통형 곡면 위에 마우스를 놓고 키보드 **Ctrl** 키(Mac의 경우 **Cmd**)를 누른 채 중심점을 클릭합니다.
        
    ![회전 현재 위치에서 접합 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-revolute-as-built-joint-subasm2-lower.jpg)
        
    e.  작업을 완료하려면 현재 위치에서 접합 대화상자에서 **확인**을 클릭합니다.
        
4.  상단의 피스톤 부분조립품과 암 사이에 회전 현재 위치에서 접합을 추가합니다.
    
    a.  **디자인** 작업공간의 **솔리드** 탭에서 **조립 > 현재 위치에서 접합**을 클릭합니다.
        
    b.  새 피스톤 부분조립품에서 상단 암 구성요소 및 피스톤 - 외부 구성요소를 선택합니다.
        
    c.  접합 유형을 설정하려면 현재 위치에서 접합 대화상자에서 유형을 **회전**로 설정합니다.
        
    d.  위치를 정의하려면 피스톤의 내부 원통형 면에서 외부 구성요소의 중심점을 선택합니다.
        
    ![회전 현재 위치에서 접합 작성](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-revolute-as-built-joint-subasm2-upper.jpg)
        
    e.  작업을 완료하려면 현재 위치에서 접합 대화상자에서 **확인**을 클릭합니다.
        

주: 원래 부분조립품의 접합이 부분조립품과 함께 복사되었으므로 두 번째 피스톤 부분조립품의 구성요소 사이에 원통형 현재 위치에서 접합을 작성할 필요가 없습니다.

작업 3 요약
-------

이 작업에서는 하부 암 부품을 고정하여 조립품의 동작을 수정했습니다. 그런 다음 피스톤 부분조립품을 복사하고 암 부품의 다른 마운팅 구멍 세트에 사본을 정렬했습니다. 마지막으로, 회전 현재 위치에서 접합을 지정하여 새 횡단구성요소의 상대 동작을 정의했습니다.

![조립품 완료](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-final-asm.jpg)

_동작이 정의된 완성된 피스톤 횡단구성요소_

</div>
</details>
<details>
<summary>튜토리얼 결론: 부분조립품 및 현재 위치에서 접합 작업</summary>
<div markdown="1">       

튜토리얼 결론: 부분조립품 및 현재 위치에서 접합 작업
==============================

이 튜토리얼에서는 다음을 수행했습니다.

*   바디에서 구성요소를 작성하고 부분조립품 내에서 구성요소를 구성합니다.
*   조립품 내에서 동작을 활성화하기 위해 일련의 현재 위치에서 접합을 작성했습니다.
*   조립품의 동작이 고정되고 구성요소를 복사하고 붙여넣어 조립품을 만들었습니다.

![조립품 완료](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/tutorial/5-final-asm.jpg)

_완성된 피스톤 조립품_

</div>
</details>

