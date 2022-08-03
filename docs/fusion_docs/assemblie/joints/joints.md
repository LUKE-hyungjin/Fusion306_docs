접합
==

**디자인** 작업공간의 Fusion 360에서 조립품의 구성요소 사이에 접합을 작성할 수 있습니다.

**접합**은 조립품에서 두 구성요소 사이의 상대적 위치 및 동작을 정의하는 기계적 관계입니다.

움직이는 구성요소가 있는 조립품을 디자인할 때 동작 시뮬레이션은 프로토타입 제작 프로세스의 중요한 부분입니다.

Fusion 360에서 접합은 구성요소가 할 수 없는 일 대신 **할 수** 있는 일에 집중할 수 있도록 하여 구성요소 관계의 복잡성을 줄입니다. 이는 동작을 제한하기 위해 사용 가능한 자유도(DOF)를 잠그는 구속조건 또는 메이트와 같은 다른 접근 방식과는 다릅니다. 이렇게 하려면 조립품의 구성요소가 원하는 방식으로 이동하는지 확인하기 위해 관련된 기본 물리적 요소와 수학을 이해해야 합니다.

반면 접합은 구성요소 간의 동작을 정의하고 해당 동작을 작성하기 위해 필요한 자유도만 열어 둡니다. 이렇게 하면 물리적 요소를 이해할 필요가 줄어들고 동작과 결과 간의 이해가 가능해집니다.

접합 액세스 지점
---------

조립품에서 작성하는 접합과 상호 작용할 수 있는 세 가지 액세스 지점은 다음과 같습니다.

![접합에 대한 액세스 점](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/diagram/joints-overview.png)

*   **브라우저**의 **접합** 폴더 내
*   **캔버스**의 직접 구성요소에 있으며, **접합** 유형 아이콘으로 지정됩니다.
*   **타임라인**에서

주: **브라우저**에서 각 구성요소에는 고유한 **접합** 폴더가 있습니다.

**조립** 패널에서 다음 명령을 사용하여 접합을 작성 및 수정할 수 있습니다.

*   **접합** ![접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint.png): 서로 관련하여 아직 배치되지 않은 구성요소 간에 접합을 작성합니다.
*   **현재 위치에서 접합** ![현재 위치에서 접합 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/as-built-joint.png): 이미 서로 관련하여 배치된 구성요소 간에 접합을 작성합니다.
*   **접합 원점** ![접합 원점 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/joint-origin.png): 접합 원점을 작성하고 구성요소에 배치합니다.
*   **강체 그룹** ![강체 그룹 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/rigid-group.png): 조립품에서 함께 이동하도록 구성요소를 함께 잠급니다.
*   **접선 관계** ![접선 관계 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/tangent-relationship.png): 한 구성요소의 바디에 있는 면과 조립품 내 다른 구성요소의 바디에 있는 연결된 면 세트 간에 접선 관계를 작성합니다.
*   **접합 구동** ![접합 구동 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/drive-joints.png): 회전 각도 및 거리와 같은 접합 동작 입력을 수정하여 자유도를 제어합니다.
*   **동작 링크** ![동작 링크 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/motion-link.png): 두 접합의 동작을 함께 연결합니다.

캔버스 또는 브라우저에서 기존 접합을 마우스 오른쪽 버튼으로 클릭하고 다음 추가 명령을 사용하여 수정할 수 있습니다.

*   **접합 편집**: **접합 편집** 대화상자를 열어 접합과 연관된 모든 설정을 편집할 수 있습니다.
*   **접합 제한 편집**: **접합 제한 편집** 대화상자를 열고 접합의 최소, 최대 및 나머지 제한을 편집할 수 있습니다.
*   **잠금**: 접합의 현재 위치 및 설정을 잠급니다.
*   **억제**: 접합이 구성요소에 작용하지 않도록 일시적으로 제거합니다.
*   **접합 애니메이트**: 단일 접합을 애니메이트합니다.
*   **모형 애니메이트**: 조립품의 모든 접합을 애니메이트합니다.

```{toctree}
joint_types.md
joint_command.md
as_build_joints.md
joint_origin.md
edit_joints.md
joint_limits.md
insert_a_subassembly_and_create_joints.md
create_trangent_relationship.md
drive_joint_reference.md
motion_link_reference.md
rigid_grops.md
```
