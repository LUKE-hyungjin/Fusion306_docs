접합 유형
=====

Fusion 360의 접합 유형에 대해 알아봅니다.

Fusion 360에는 7가지 유형의 접합이 있습니다. **접합** 및 **현재 위치에서 접합** 명령을 사용하여 접합을 작성할 수 있습니다. 각 접합 유형은 다른 자유도를 사용하여 동작을 정의합니다.

![img](../../asset/images/joints.png)

주: 접합을 작성할 때 파라메트릭 모델링에서 변경할 수 있는 매개변수도 작성합니다.

주: 접합을 작성할 때 자유도를 최소로 유지하면 조립품을 더 빠르게 테스트하는 데 도움이 됩니다.

![강체 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-rigid.png) 강체
---------------------------------------------------------------------------

**강체** 접합 유형은 구성요소를 함께 잠그고 모든 자유도를 제거합니다.

### 동작

제어할 동작이 없으므로 조정할 추가 설정이 없습니다.

### 예

*   구성요소 함께 용접
*   동작이 허용되지 않도록 여러 구성요소를 여러 위치에 함께 볼트

![강체 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-rigid.png)

![회전 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-revolute.png) 회전
------------------------------------------------------------------------------

**회전** 접합 유형을 사용하면 구성요소가 추가 변환 없이 **접합 원점**을 중심으로 회전할 수 있습니다.

### 동작

**회전:** 구성요소가 회전할 기준이 되는 축을 정의합니다.

### 예

*   연결 작업
*   단일 점 주위로 볼트 구성요소 회전

![회전 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-revolute.png)

![슬라이더 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-slider.png) 슬라이더
--------------------------------------------------------------------------------

**슬라이더** 접합 유형을 사용하면 구성요소가 추가 회전 없이 단일 축을 따라 이동할 수 있습니다.

### 동작

\*_슬라이드: \*_ 구성요소가 이동할 축을 정의합니다.

### 예

*   회전 없이 로드의 위 및 아래로 구성요소 이동

![슬라이더 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-slider.png)

![원통형 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-cylindrical.png) 원통형
-----------------------------------------------------------------------------------

**원통형** 접합 유형을 사용하면 구성요소가 단일 축을 중심으로 회전하고 이동할 수 있습니다.

### 동작

*   **축:** 구성요소가 이동하고 회전할 기준이 되는 축을 정의합니다.

### 예

*   구멍을 통해 구성요소 스레딩
*   로드의 이동 표시

![원통형 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-cylindrical.png)

![핀-슬롯 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-pin-slot.png) 핀-슬롯
----------------------------------------------------------------------------------

**핀-슬롯** 접합 유형을 사용하면 구성요소가 한 축을 중심으로 회전하고 다른 축을 따라 이동할 수 있습니다.

### 동작

*   **회전:** 구성요소가 이동할 축을 정의합니다.
*   **슬라이드:** 구성요소가 회전할 기준이 되는 축을 정의합니다.

주: **회전** 및 **슬라이드** 둘 다에 대해 동일한 축을 선택할 수는 없습니다. **회전** 축을 선택하면 선택한 축이 **슬라이드** 축 리스트에서 제거됩니다(그 반대의 경우도 마찬가지).

### 예

*   핀 슬롯 내에서 구성요소의 회전 및 이동 표시

![핀 슬롯 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-pin-slot.png)

![평면 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-planar.png) 평면
----------------------------------------------------------------------------

**평면** 접합 유형을 사용하면 구성요소가 두 축을 따라 이동하고 단일 축을 중심으로 회전할 수 있습니다.

### 동작

*   **법선:** 구성요소가 회전할 기준이 되는 평면에 수직인 축을 정의합니다.
*   **슬라이드:** 평면형 이동을 위한 축을 정의합니다.

주: **일반** 축을 선택하면 **슬라이드** 축이 자동으로 공제됩니다.

### 예

*   추가 자유도를 제한하지 않고 동일한 평면을 따라 두 구성요소 연결
*   테이블 상단으로 상자 이동
    *   상자의 하단 면을 테이블의 상단 면에 닿도록 유지합니다.
    *   테이블 상단을 따라 상자를 이동하고 테이블 상단의 법선을 기준으로 회전합니다.

![평면 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-planar.png)

![볼 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/joint-ball.png) 볼
------------------------------------------------------------------------

**볼** 접합 유형을 사용하면 변환 없이 짐벌 시스템(3개의 내포된 회전)을 사용하여 구성요소가 3개 축 주위를 회전할 수 있습니다.

### 동작

*   **피치:** 구성요소가 회전할 때 기준으로 사용할 측면 축을 정의합니다.
*   **좌우:** 구성요소가 회전할 때 기준으로 사용할 수직 축을 정의합니다.

주: **피치**와 **좌우**에 대해 동일한 축을 선택할 수는 없습니다. **피치** 및 **좌우**를 정의할 때 **롤**(세로 축)도 정의합니다. 이를 통해 예상 회전 방향 및 이동 방향과 연관된 값을 설정하는 방법을 정의할 수 있습니다.

### 예

*   완전한 회전 자유도가 필요하지만 회전 점은 이동하지 않아야 함

![볼 접합 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/joint-ball.png)

축 정의
----

*   **X축**, **Y축** 및 **Z축**을 사용하면 **접합 원점**을 교차하는 미리 정의된 축을 선택할 수 있습니다.
*   **사용자 정의 축**을 사용하면 **접합 원점**에서 떨어진 축을 선택할 수 있습니다.