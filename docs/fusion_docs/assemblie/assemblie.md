# 조립품
조립품 개요
======

권장되는 워크플로우뿐만 아니라 조립품의 요소를 포함하여 Fusion 360의 조립품에 대해 알아봅니다.

**조립품**은 Fusion 360에서 단일 디자인으로 작동하는 구성요소의 집합입니다.

![구성요소 - 조립품 일러스트레이션](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/illustration/components-to-assembly.png)

_왼쪽: 구성요소, 오른쪽: 조립품_

Fusion 360에는 조립품에 대한 특별한 파일 유형이 없으므로 각 디자인에 다음이 포함될 수 있습니다.

*   바디로 구성된 단일 구성요소입니다.
*   구성요소 및 내포된 하위 구성요소의 조립품.

Fusion 360 디자인에서 새 구성요소를 작성하면 해당 구성요소는 조립품이 됩니다.

Fusion 360의 위치, 접합 및 동작 피쳐를 사용하여 디자인의 구성요소 간 관계를 정의할 수 있습니다.

조립품의 요소
-------

조립품은 **브라우저**에 구성됩니다.

![조립품 개요](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/overview/browser-assembly.png)

1.  **구성요소**: 디자인 요소를 포함하고 구성합니다. 모든 구성요소에는 원점, 구성 형상, 스케치, 바디 및 접합 원점이 포함될 수 있습니다.
    1.  ![조립품 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/assembly.png) **기본 구성요소**: 모든 디자인의 상단 구성요소입니다. 모든 구성요소에 포함될 수 있는 요소 외에도, 기본 구성요소에는 전체 조립품에 대한 문서 설정, 명명된 뷰, 분석 및 접합도 포함되어 있습니다.
    2.  ![구성요소 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component.png) **내부 구성요소**: 현재 디자인 내에 완전히 포함됩니다.
    3.  ![구성요소 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component.png)![구성요소 링크 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component-link.png) **외부 구성요소(xref)**: 별도의 디자인에 포함되어 있으며 현재 디자인의 조립품에 참조됩니다. **내부 편집** 중에 작성된 조립품 컨텍스트를 포함할 수 있습니다.
2.  ![설정 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/settings.png) **문서 설정**: 조립품의 단위를 제어합니다.
3.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **명명된 뷰**: 조립품에 대한 모든 표준 및 사용자 명명된 뷰를 포함합니다.
4.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **원점**: 구성요소와 연관된 XY/XZ/YZ 평면, X/Y/Z 축 및 원점을 포함합니다.
5.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **분석**: **단면 분석** 명령 및 곡면 분석 명령으로 작성된 분석을 포함하여 조립품에서 작성된 분석을 포함합니다.
6.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **접합 원점**: 구성요소와 연관된 접합 원점이 포함됩니다.
7.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **접합**: 구성요소 간의 관계 및 동작을 정의하는 데 사용되는 조립품과 연관된 접합을 포함합니다.
8.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **바디**: 구성요소와 연관된 3D 바디가 포함됩니다.
9.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **스케치**: 바디를 구동하고 정의하는 구성요소와 연관된 디자인 스케치를 포함합니다.
10.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) **구성**: 스케치 및 바디 작성 프로세스를 지원하는 구성요소와 연관된 구성 형상을 포함합니다.
11.  ![조립품 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/assembly.png) **부분조립품**: 추가 구성요소가 내포된 모든 구성요소. 최상위 구성요소는 **상위 구성요소**입니다. 내포된 구성요소는 **하위 구성요소**입니다.
12.  ![예약 배지 포함 아바타 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/avatar-reservation-badge.png) **아바타**(**예약 배지 포함**): 프로젝트 멤버가 디자인 또는 외부 구성요소를 편집하고 있으며 프로젝트 멤버가 디자인 충돌을 방지하기 위해 예약했습니다.
13.  ![구성요소 활성화 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/activate-component.png) **활성화된 구성요소**: 현재 작업 중인 구성요소. 구성요소 옆의 라디오 버튼을 클릭하여 활성화합니다.
14.  ![내부 편집 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/edit-in-place.png) **내부 편집**: 현재 디자인을 종료하지 않고 컨텍스트에서 외부 구성요소를 활성화하고 편집합니다.
15.  ![폴더 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/folder.png) ![동기화되지 않은 내부 편집 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/edit-in-place-out-of-sync.png) **조립품 컨텍스트**: 구성요소와 연관된 조립품 컨텍스트가 포함되어 있으며, 이 컨텍스트는 **내부 편집** 중에 구성요소 간의 관계를 정의합니다.
        1.  ![내부 편집 컨텍스트 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/edit-in-place-context.png) **로컬 컨텍스트**: 외부 구성요소를 자체 문서 탭에서 열 경우 디자인이 표시되는 것처럼 나타냅니다. 하위 구성요소에 대한 고유한 위치 세트를 유지합니다.
        2.  ![내부 편집 컨텍스트 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/edit-in-place-context.png) **조립품 컨텍스트**: 특정 시점에서 상위 디자인과 외부 구성요소 간의 연결입니다. 조립품과 관련된 위치 정보를 유지합니다.
        3.  ![내부 편집 컨텍스트 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/edit-in-place-context.png) ![동기화되지 않은 내부 편집 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/edit-in-place-out-of-sync.png) **동기화되지 않은 조립품 컨텍스트**: 마우스 오른쪽 버튼을 클릭하고 **조립품 컨텍스트 동기화**를 선택하여 연관 디자인 변경 사항을 업데이트합니다.

조립품의 가시성
--------

**브라우저**에서 가시성 아이콘 ![가시성 아이콘 표시](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/visible.png) / ![가시성 아이콘 숨김](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/hidden.png)을 사용하여 Fusion 360의 디자인에서 객체의 가시성을 제어할 수 있습니다.

조립품에서 **내부 구성요소**의 가시성과 그 안에 있는 객체를 활성 디자인에서 직접 제어할 수 있습니다.

조립품에 참조되는 **외부 구성요소**는 외부 디자인에서 가시성을 상속합니다.

### 가시성 재지정

조립품 환경에서 **외부 구성요소** 및 이 구성요소 내의 객체의 가시성을 재지정할 수 있습니다.

외부 구성요소에서 객체의 가시성을 조정하면 해당 객체의 가시성이 조립품에서 재지정됩니다.

외부 디자인에서는 가시성이 변경되지 않습니다. 다른 조립품에서 외부 구성요소가 참조되는 경우 다른 조립품에서도 가시성을 재지정하지 않는 한 기본 가시성은 외부 디자인에서 계속 상속됩니다.

재지정할 수 있는 객체:

*   구성요소
*   바디
*   스케치
*   구성 형상
*   폴더(**바디**, **스케치** 및 **구성**에만 해당)

재지정할 수 없는 객체:

*   **원점** 폴더
*   **접합** 폴더

객체 옆에 있는 가시성 아이콘 위에 마우스를 놓으면 조립품에서 가시성이 재지정되면 툴팁이 표시됩니다.

가시성 아이콘을 클릭하여 특정 가시성 재지정을 제거하거나 **브라우저**의 상황에 맞는 메뉴에서 **가시성 재지정 제거** 명령을 사용하여 조립품에서 모든 가시성 재지정을 한 번에 제거할 수 있습니다.

![가시성 재지정 애니메이션](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/animation/visibility-overrides.gif)

조립품 모델링의 워크플로우
--------------

조립품을 작성하려는 경우 다음을 수행하는 것이 가장 좋습니다.

*   형상 작성을 시작하기 전에 **새 구성요소** 명령을 사용하여 디자인 프로세스 초기에 구성요소를 작성합니다.
*   작업할 구성요소를 활성화합니다.
*   시작 부분부터 속하는 구성요소 내부에 스케치 및 바디를 작성합니다.

이 워크플로우는 각 구성요소에 대해 체계적이고 정돈된 디자인 히스토리를 유지하는 데 도움이 되며, 구성요소를 다른 디자인에서 쉽게 재사용할 수 있도록 하는 방식으로 설정합니다.

복잡한 조립품에서 관계를 작성하기 위한 전략
------------------------

복잡한 조립품 내에서 구성요소를 배치하는 프로세스를 단순화하기 위해 여러 개의 작은 조립품을 작성할 수 있습니다. 필요에 따라 접합, 강체 그룹 및 접촉 세트 관계를 적용한 다음 각 관계를 별도의 디자인으로 저장합니다. 이 방법을 사용하면 부분조립품을 업스트림 조립품의 단일 단위로 배치할 수 있습니다.

구성요소를 부분조립품으로 그룹화하면 둘 이상의 조립품에서 구성요소를 재사용하는 프로세스도 단순화됩니다.