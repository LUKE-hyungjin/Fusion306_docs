---
layout: default
title: 접촉 세트
nav_order: 8
permalink: /docs/assemblies/contact_sets
has_children: true
parent: 조립품
---
접촉 세트
=====

접촉 세트는 디자인의 구성요소가 서로 접촉할 때만 이동하도록 디자인의 구성요소에 적용할 수 있습니다.

접촉 세트는 구성요소 간의 물리적 접촉을 사용하여 이동을 제한합니다. 간섭이 탐지되면 구성요소가 이동되지 않습니다. 이 방법을 사용할 경우 동작 접합보다 많은 계산이 필요합니다.

*   **접촉 세트 사용** ![접촉 세트 사용 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/contact-set.png): 접촉 세트의 구성요소 간 접촉 분석을 활성화합니다. 접촉 세트는 브라우저에서 관리됩니다.
*   **모든 접촉 사용 안 함** ![접촉 세트 사용 안 함 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/contact-set-disable.png): 모든 구성요소에 대한 접촉 분석을 끕니다.
*   **모든 접촉 사용** ![접촉 세트 사용 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/contact-set-all.png): 모든 구성요소에 대한 접촉 분석을 활성화합니다.
*   **새 접촉 세트** ![접촉 세트 사용 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/contact-set.png): 선택한 구성요소 간에 접촉 세트를 작성합니다. 접촉 분석에 포함할 바디 또는 구성요소를 선택합니다.

접촉 세트는 이동 시 접촉에 대해 평가되는 구성요소를 관리합니다.

접촉 세트는 구성요소가 서로를 통과할 수 없도록 구속하므로 실제와 같이 동작합니다. 예를 들어, 구성요소가 브래킷을 통과하지 않고 접합을 중심으로 회전하도록 구속할 수 있습니다.

**모든 접촉 사용** 명령은 접촉 세트에 관계없이 디자인에 있는 모든 구성요소 간의 접촉을 분석합니다. 조립품의 구성요소 수는 성능에 영향을 줍니다. **새 접촉 세트** 명령은 접촉 세트에 대해 지정한 구성요소를 구속합니다.

**새 접촉 세트** 명령은 선택한 구성요소 간 접촉 분석을 설정합니다. 접촉 세트는 부품이 서로 관통하지 않습니다.

**접합 구동** 명령은 동작이 발생하는 위치를 정확하게 표시하고 구성요소 조립품에서 구성요소의 이동 제한을 표시합니다.

```{toctree}
create_contract_sets.md
```