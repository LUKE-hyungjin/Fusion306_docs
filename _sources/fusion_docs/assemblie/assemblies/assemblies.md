조립품
===

Fusion 360에서 **조립품**은 단일 디자인으로 작동하는 구성요소의 집합입니다. 두 개 이상의 구성요소를 포함하는 모든 디자인은 조립품으로 간주됩니다.

디자인 요구에 따라 다양한 전략을 활용하는 조립품을 작성할 수 있습니다. 경우에 따라 사용자는 다음을 수행할 수 있습니다.

*   모든 내부 구성요소, 모든 외부 구성요소 또는 두 구성요소 유형의 혼합으로 구성된 조립품을 작성합니다.
*   프로젝트를 시작할 때 또는 디자인을 발전시킬 때 조립품의 구조 및 관계를 정의합니다.
*   전체 조립품에 하향식 또는 상향식 접근 방식을 사용하거나 특정 구성요소 및 부분조립품에 대한 접근 방식을 변경합니다.
*   디자인에서 단독으로 작업하거나 다른 프로젝트 멤버와 공동작업을 수행할 수 있습니다.
*   다른 프로젝트 멤버와 동시에 또는 비동기적으로 공동 작업을 수행합니다.

분산된 디자인
-------

분산된 디자인은 조립품에 참조된 하나 이상의 외부 구성요소가 있는 디자인입니다.

![외부 구성요소 그림](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/hig-illustration/external-components-mono.png)

분산된 디자인을 통해 여러 프로젝트 멤버는 동시에 조립품의 여러 구성요소를 편집할 수 있습니다. 각 프로젝트 멤버가 컨텍스트에서 구성요소를 편집하면 전체 조립품이 변경 사항을 반영하여 업데이트됩니다. 각 구성요소를 편집하고, 프로젝트 멤버가 구성요소를 저장할 때 구성요소 버전을 업데이트하고, 모든 사용자가 항상 조립품에 있는 각 구성요소의 최신 버전으로 작업할 수 있도록 할 수 있습니다.

![분산 디자인 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/distributed-design.png)

조립품의 업데이트
---------

**오래된 버전** 아이콘 ![오래된 버전 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component-out-of-date.png)은 프로젝트 멤버가 조립품에 새 버전의 디자인 또는 외부 구성요소를 저장할 때 다음 위치에 표시됩니다.

*   **응용프로그램** 막대에서
*   **브라우저**에서 기본 구성요소 옆에 배치
*   **브라우저**에서 외부 구성요소 옆에 배치

외부 구성요소 내에 내포된 하위 구성요소가 오래된 경우 **하위 구성요소 오래된 버전** 아이콘 ![하위 구성요소 오래된 버전 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/browser/component-out-of-date-sub.png)이 상위 외부 구성요소 옆에 표시됩니다.

![브라우저 - 구성요소가 오래됨](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/browser/components-out-of-date.png)

활성 디자인 및 오래된 외부 구성요소를 모두 한 번에 또는 개별적으로 업데이트할 수 있습니다.

```{toctree}
edit_a_desing.md
edit_in_place.md
adjust_visibility_of_objects_in_an_assembly.md
update_components_in_an_assembly.md
save_a_version_of_a_design_as_the_latest_version.md
derived_design_features.md
break_the_link_between_an_external_component_and_the_assembly.md
```