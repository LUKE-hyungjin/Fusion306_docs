마일스톤 및 버전
=========

> \*_중요: \*_ 마일스톤은 Fusion 360 및 Fusion Team에서 사용됩니다. 단일 사용자 저장소 계정에는 사용할 수 없습니다. 마일스톤은 Fusion 360 [Manage Extension](https://help.autodesk.com/view/NINVFUS/KOR/?guid=EXT-MANAGE)의 기능인 프로세스 관리 리비전과 동일하지 않습니다.

디자인이 저장될 때마다 디자인 버전이 작성됩니다. 디자인 개발의 중요한 단계에서 모든 저장이 수행되는 것은 아닙니다.

마일스톤은 디자인의 개발 단계가 중요하다는 것을 식별하는 데 사용됩니다. 예를 들어, 부품을 작성하는 경우가 여기에 해당합니다. 여러 번 저장한 후 부품의 모든 피쳐를 추가했습니다. 이 버전이 원래 버전임을 나타내는 마일스톤을 작성합니다. 그런 다음, 대체 디자인을 계속 변경할 수 있습니다. 그런 다음, 두 번째 마일스톤을 작성하여 첫 번째 대체 디자인을 나타낼 수 있습니다. 마일스톤을 사용하면 여러 사용자가 동일한 프로젝트에서 쉽게 작업할 수 있습니다. 구성요소 및 하위 구성요소에 마일스톤이 사용되면 한 사용자가 하위 구성요소로 작업하고 디자인 프로세스 중에 작업을 저장할 수 있습니다. 하위 구성요소가 공유할 준비가 되면 마일스톤이 작성됩니다. 그러면 상위 수준 구성요소가 오래된 것으로 트리거됩니다. 그러면 구성요소로 작업하는 다른 사용자들은 사소한 변경이 수행될 때마다 디자인을 한 번만 업데이트할 수 있습니다.

마일스톤이 있는 부품 파일을 디자인에 삽입하면 부품의 마일스톤이 업데이트될 때만 디자인이 업데이트됩니다. 일반적으로 저장해도 두 번째 디자인에 대한 업데이트가 트리거되지 않습니다.

![부품 예](https://help.autodesk.com/cloudhelp/KOR/Fusion-Import/images/milestones-cover.png)

위의 예에서 구성요소 커버는 커버에 대해 새 마일스톤이 작성된 경우에만 디자인 금형에 대한 업데이트를 트리거합니다.

오래된 구성요소가 업데이트되면 마일스톤이 있는 구성요소에 디자인에서 마일스톤 버전을 사용하고 있음을 나타내는 플래그 아이콘이 표시됩니다.

![부품 예 2](https://help.autodesk.com/cloudhelp/KOR/Fusion-Import/images/milestones-cover1.png)

위의 예에서 커버 구성요소는 최신 마일스톤 버전을 사용하고 있습니다.

이전 마일스톤
-------

새로운 버전의 디자인을 마일스톤과 함께 저장할 때마다 기존 마일스톤은 이전 마일스톤으로 저장됩니다.

이전 마일스톤 아이콘은 검은색 마일스톤 아이콘과 다르게 회색으로 표시됩니다. 아이콘의 색상이 모든 위치에서 변경되고, 마일스톤 표식기가 Fusion 360 및 Fusion Team에 존재합니다.

![마일스톤 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Import/images/milestones-icons.png)

이 섹션의 페이지에서는 Fusion 360 및 Fusion Team에서 마일스톤 및 파일 버전으로 작업하는 방법에 대해 알아봅니다.

```{toctree}
create_milestones.md
edit_milestones.md
promote_milestones.md
choose_milestone.md
work_with_version_in_the_history_dialog.md
```
