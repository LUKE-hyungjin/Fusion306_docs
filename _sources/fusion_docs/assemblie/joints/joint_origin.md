접합 원점
=====

**접합 원점**은 둘 이상의 구성요소를 Fusion 360의 접합과 연결하는 데 사용할 형상을 정의합니다.

![접합 원점 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-origin.png)

*   **접합** 명령은 특정 접합의 컨텍스트 내에서 접합 원점을 작성합니다.
*   **접합 원점** 명령은 독립 접합 원점을 작성하여 보다 복잡한 접합 위치를 용이하게 합니다.

접합을 작성할 때 아이콘은 **접합 원점** ![접합 원점 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin.png)을 나타냅니다. 이는 접합이 조립되는 방식을 이해하는 데 도움이 되는 시각적 표현입니다.

접합을 작성할 때 구성요소 또는 구성 형상으로 스냅하여 각 구성요소에 접합 원점을 배치합니다.

각 접합 원점을 좌표계로 간주할 수 있습니다. 여기서 **접합 원점** 아이콘 ![접합 원점 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin.png)의 평면형 면은 **XY 평면**을 나타냅니다.

*   빨간색 축은 양의 방향으로 **X축**을 나타냅니다.
    
*   초록색 축은 양의 방향으로 **Y축**을 나타냅니다.
    
    ![접합 원점 - 크게](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-origin-64.png)
    
*   **접합 원점** 아이콘의 흰색 면은 양의 방향으로 **Z축**을 나타냅니다.
    
    ![접합 원점 양수](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-origin-positive.png)
    
*   **접합 원점** 아이콘의 주황색 면은 음의 방향으로 **Z축**을 나타냅니다.
    
    ![접합 원점 음수](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-origin-negative.png)
    

모드
--

다음 세 가지 접합 원점 모드 중에서 선택할 수 있습니다.


|접합 원점 모드|설명|
|:---:|:---:|
|![접합 원점 - 단순 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin-simple.png) **단순**|면, 모서리 또는 점에서 접합 원점을 작성하여 구성요소를 정렬합니다.|
|![ 접합 원점 - 두 면 사이 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin-between-two-faces.png) **두 면 사이**|두 면 사이에 구성요소를 중심에 둘 접합 원점을 작성합니다.|
|![접합 원점 - 두 모서리 교차 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin-two-edge-intersection.png) **두 모서리 교차**|접합 원점을 작성하여 두 모서리의 연장된 교차점에서 구성요소를 정렬합니다.|


가시성
---

캔버스 하단의 **탐색** 막대에서 **화면표시 설정 > 객체 가시성 > 접합 원점**을 클릭하여 활성 디자인에서 접합 원점의 가시성을 전환합니다.

**화면표시 설정 > 객체 가시성 > 접합 원점 축**을 클릭하여 활성 디자인의 접합 원점에 있는 축의 가시성만 전환합니다.
<details>
<summary>접합 원점 작성</summary>
<div markdown="1">       

접합 원점 작성
========

**접합 원점** 명령을 사용하여 Fusion 360에서 구성요소의 독립 접합 원점을 작성하는 방법을 알아봅니다.

![접합 원점 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-origin.png)

1.  **디자인 > 솔리드 > 조립 > 접합 원점** ![접합 원점 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin.png)을 클릭합니다.
    
    **접합 원점** 대화상자가 표시됩니다.
    
2.  대화상자에서 접합 원점 **모드**를 선택합니다.
    
    *   **단순** ![ 접합 원점 - 단순 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin-simple.png): **스냅** 점을 선택하여 접합 원점을 배치합니다.
        
    *   **두 면 사이** ![접합 원점 - 두 면 사이 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin-between-two-faces.png): **평면 1**과 **평면 2**를 선택하여 접합 원점을 그 사이의 중심에 배치한 다음 **스냅** 점을 선택합니다.
        
    *   **두 모서리 교차** ![접합 원점 - 두 모서리 교차 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin-two-edge-intersection.png): **모서리 1**과 평행하지 않은 **모서리 2**를 선택하여 연장된 교차점에서 접합 원점을 찾습니다.
        
        팁: 면 위에 마우스를 놓은 다음 `Ctrl`(Windows) 또는 `Command`(MacOS) 키를 누른 상태로 해당 면의 점에 스냅합니다.
        
3.  접합 원점 **정렬** 설정 조정:
    
    *   **각도**: 회전 조작기 핸들을 끌거나 정확한 회전 각도를 입력합니다.
    *   **간격띄우기 X**: 이동 조작기 핸들을 끌거나 정확한 거리를 입력합니다.
    *   **간격띄우기 Y**
    *   **간격띄우기 Z**
    *   **반전**: 접합을 작성할 때 접합 원점을 반전하여 구성요소를 정렬하려면 클릭합니다.
    *   **방향 전환**: 클릭하여 접합 원점의 방향을 다시 조정할 두 축을 선택합니다.
    *   **Z축**: 면 또는 모서리를 클릭하여 축 방향을 다시 정합니다.
    *   **X축**
4.  **확인**을 클릭합니다.
    

새 접합 원점이 캔버스에 표시됩니다.

팁
-

*   캔버스 하단의 **탐색** 막대에서 **표시 설정 > 객체 가시성 > 접합 원점** 또는 **접합 원점 축**을 클릭하여 활성 디자인의 접합 원점에 있는 축만 표시하거나 숨깁니다.

</div>
</details>
<details>
<summary>접합 원점 참조</summary>
<div markdown="1">       

# 접합 원점 참조
**접합 원**점 명령은 접합 원점을 Fusion 360의 구성요소에 배치합니다. 접합 원점은 접합의 구성요소를 관련시키는 데 사용되는 형상을 정의합니다.
디자인 > 조립 > 접합 원점![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin.png)

![img](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-origin.png)
## 모드
형상을 선택하여 접합 원점을 정의합니다.
|접합 원점 모드|정의|
|:---:|:---:|
|단순|면, 모서리 또는 점에서 접합 원점을 작성하여 구성요소를 정렬합니다.|
|두 면 사이|두 면 사이에 구성요소를 중심에 둘 접합 원점을 작성합니다.|
|두 모서리 교차|접합 원점을 작성하여 두 모서리의 가상 교차점에 구성요소를 정렬합니다.|

## 평면, 모서리 및 스냅
형상을 선택하여 접합 및 접합 원점을 정의합니다.
|옵션|동작|
|:---:|:---:|
|평면 1|면 선택|
|평면 2|두 번째 면 선택|
|모서리 1|모서리 선택|
|모서리 2|평행하지 않은 모서리 선택|
|스냅|스냅점을 선택하여 접합 원점 배치|

## 선형 횡단
접합의 각도, 간격띄우기 및 방향을 조정하여 정렬합니다.

## 각도, 간격띄우기, 반전 및 방향 전환
|옵션|동작|
|:---:|:---:|
|각도|접합 원점의 참조 좌표계를 회전하여 접합을 작성할 때 구성요소 정렬|
|간격띄우기 X|X 축을 따라 접합 원점 간격띄우기|
|간격띄우기 Y|Y축을 따라 접합 원점 간격띄우기|
|간격띄우기 Z|Z 축을 따라 접합 원점 간격띄우기|
|반전|접합 원점을 반전하여 접합을 작성할 때 구성요소 정렬|
|방향 다시정하기|접합 원점의 방향을 다시 정하려면 두 축을 선택합니다.|
|Z축|Z축 선택|
|X축|X축 선택|

</div>
</details>
