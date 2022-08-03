구성요소
====

Fusion 360에서는 컨텍스트에서 디자인의 모든 구성요소를 작성하고, 단일 환경 내에서 이러한 구성요소 간의 기계적 관계와 동작을 정의할 수 있습니다.

**구성요소**는 스케치, 구성 형상, 바디, 접합, 원점 및 기타 구성요소와 같은 디자인 요소에 대한 컨테이너입니다.

![구성요소 일러스트](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/hig-illustration/component.png)

다음과 같은 두 가지 유형의 구성요소가 있습니다.

*   ![구성요소 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component.png) **표준**
*   ![판금 구성요소 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component-sheet-metal.png) **판금**

각 구성요소는 동작할 수 있으며 고유한 특성을 갖습니다.

*   원점
*   좌표계
*   타임라인
*   부품 리스트에 표시될 이름, 번호 및 설명

모든 구성요소에는 다음 요소가 포함될 수 있습니다.

*   원점
*   구성 형상
*   스케치
*   바디
*   접합 원점
*   기타 구성요소

**제조업체** 및 **도면** 작업공간에서 제조 또는 문서화 도구를 사용하려는 경우 구성요소가 필요합니다.

기본 구성요소
-------

**브라우저**의 상단 노드는 모든 디자인에 있는 **기본 구성요소**입니다.

![브라우저 - 기본 구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/browser/components-default.png)

다른 구성요소에 나타날 수 있는 모든 요소 외에 다음 요소는 항상 기본 구성요소에 있습니다.

*   문서 설정
*   명명된 뷰
*   분석
*   접합
*   접촉 세트
*   동작 학습

내부 구성요소
-------

**내부 구성요소**는 현재 디자인 내에 완전히 포함된 구성요소입니다.

![내부 구성요소 모노 일러스트](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/hig-illustration/internal-components-mono.png)

![브라우저 - 내부 구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/browser/components-internal.png)

외부 구성요소
-------

**외부 구성요소** 또는 **외부 참조**는 별도의 디자인에 포함되어 현재 디자인의 조립품에 참조되는 구성요소입니다.

![외부 구성요소 모노 일러스트](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/hig-illustration/external-components-mono.png)

![브라우저 - 외부 구성요소](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/browser/components-external.png)

외부 구성요소를 사용하면 다음을 보다 쉽게 수행할 수 있습니다.
*   구성요소 재사용
*   복잡한 조립품에 대해 팀 멤버와 동시에 협업
*   구성요소 대체

외부 구성요소를 편집하면 외부 구성요소가 참조되는 모든 조립품에 변경 사항이 표시됩니다.

**내부 편집** ![eip 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/edit-in-place.png)을 사용하여 상황에 맞는 외부 구성요소를 편집하고 조립품에 있는 외부 구성요소와 다른 구성요소 간의 관계를 설정할 수 있습니다.

**구성요소 대체**를 사용하여 조립품에 있는 외부 구성요소의 복제 하나 또는 모두를 대체할 수 있습니다. **파라메트릭 모델링 모드**에서 패턴의 복제인 구성요소를 선택하면 패턴의 모든 복제가 대체됩니다.

![구성요소 대체 애니메이션](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/animation/replace-component.gif)

### 구성요소 해석

미리보기

이 기능은 미리보기입니다. 미리보기를 통해 개념 단계에 있는 기능에 미리 액세스할 수 있습니다. [자세히 알아보기](https://help.autodesk.com/view/fusion360/KOR/?contextId=PRE-OVERVIEW).

다음을 포함하여 해석되지 않은 외부 구성요소의 몇 가지 원인이 있습니다.

*   보관된 프로젝트
*   권한 변경
*   업로드 또는 변환 실패

해석되지 않은 외부 구성요소가 있는 디자인을 열고 참조를 해석하거나 제거할 수 있습니다.

**브라우저**에서 **해석되지 않은 구성요소** 아이콘은 해석되지 않은 각 외부 구성요소 옆에 표시됩니다. 위에 마우스를 놓으면 수행할 수 있는 작업과 이유가 툴팁에 나열됩니다.

![브라우저 - 해석되지 않은 외부 참조](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/browser/unresolved-xref-tooltips.png)

권장 워크플로우 및 모범 사례
----------------

자신과 함께 일하는 모든 사람이 서로 다른 요소, 특히 복잡한 디자인에서 관계 관계를 신속하게 이해할 수 있도록 디자인에서 구성요소를 구성하는 것이 중요합니다.

모범 사례

*   먼저 디자인 내에서 구성요소를 작성합니다.
*   그런 다음 구성요소를 활성화합니다.
*   그런 다음 형상을 정의하기 시작합니다.

주: **브라우저**에서 한 구성요소를 다른 구성요소로 끌어 조립품의 계층구조를 제어할 수 있습니다.

이렇게 하면 구성요소의 타임라인 내에 내포된 구성요소별 변경 사항이 유지됩니다. 따라서 디자인이 잘 구성되어 있고 사용자 및 다른 사용자가 타임라인을 쉽게 이해하고 상호 작용할 수 있습니다.

[![Reference objects in Fusion 360](https://embed-ssl.wistia.com/deliveries/698a6fe480439487f6f33ff899fa9a39.jpg?image_play_button_size=2x&amp;image_crop_resized=640x360&amp;image_play_button=1&amp;image_play_button_color=000000e0)](https://help.autodesk.com/view/NINVFUS/KOR/?guid=ASM-COMPONENTS&amp;wvideo=w6ub8ge5qb)


```{toctree}
bodies.md
create_new_components.md
activate_a_component.md
edit_internal_components.md
replace_external_components.md
copy_and_reuse_components.md
capture_or_revert_position_of_components.md
position_bodies_and_components.md
visibility_of_components.md
effects_of_assembly_structure.md
resolve_external_components.md
circular_references.md
new_component_reference.md
revert_reference.md
```