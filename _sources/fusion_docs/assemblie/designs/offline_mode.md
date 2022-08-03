오프라인 모드
=======

신뢰할 수 있는 인터넷 연결에 액세스할 수 없거나 인터넷 연결이 끊어진 경우 Fusion 360에서 오프라인 모드를 사용하는 방법을 알아봅니다.

Fusion 360에서는 다음과 같은 경우 자동으로 오프라인 모드가 됩니다.

*   **서비스 유지 관리:** 서비스 유지 관리를 위해 일정 기간 동안 Fusion 360을(를) 오프라인 상태로 유지해야 하는 경우가 있습니다. 이 일정은 유지 관리가 시작되기 72시간 전에 제품 내 배너를 통해 전달됩니다. 유지 관리가 시작되면 Fusion 360이(가) 오프라인 상태가 됩니다. 또한 작업 상태 아이콘이 ![작업 유지 관리 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-maintenance.png)으로 변경되고 뒤에 "현재 서비스를 업데이트 중입니다"라는 메시지가 표시됩니다.
*   **예기치 않은 중단:** 예상치 못한 중단이 감지되면 Fusion 360에서는 자동으로 비상 안전 모드인 오프라인 모드로 전환됩니다. 또한 작업 상태 아이콘이 ![작업 유지 관리 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-maintenance.png)으로 변경되고 뒤에 "현재 서비스를 업데이트 중입니다"라는 메시지가 표시됩니다.
*   **인터넷에 연결되어 있지 않음:** Fusion 360에서 인터넷에 연결되어 있지 않음을 감지하면 작업 상태 아이콘이 ![작업 유지 관리 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-maintenance.png)으로 변경되고, 그 뒤에 "인터넷에 연결되어 있지 않습니다"라는 메시지가 표시됩니다.
*   **오프라인으로 전환:** 수동으로 오프라인 모드로 전환하는 경우 아래 절차를 참조하십시오.

오프라인 모드는 오른쪽 위 구석에 있는 ![오프라인 모드 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/offline-mode.png) 작업 상태 아이콘으로 표시됩니다.

디자인을 열면 디자인 파일이 다운로드되어 로컬로 캐시됩니다. 이렇게 하면 파일에서 작업할 수 있습니다. Fusion 360이(가) 오프라인 상태가 되면 여전히 캐시된 모든 디자인에서 작업할 수 있지만, 캐시되지 않은 파일에서는 작업할 수 없습니다.

![온라인/오프라인 전환](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/cached-designs.png)

오프라인일 경우 업로드와 같은 특정 파일 작업을 수행할 수 없습니다. 또한 새 폴더를 작성하거나 마일스톤을 작성할 수 없습니다. 필요한 경우 최대 2주 동안 오프라인으로 작업할 수 있습니다. 그런 다음 Fusion 360은(는) 최신 버전을 유지할 수 있도록 다시 온라인 상태로 동기화해야 합니다.

수동으로 오프라인 모드로 전환하려면 다음을 수행합니다.

1.  ![작업 상태 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/job-status.png) 작업 상태 아이콘을 클릭합니다.
2.  ![온라인으로 작업 중](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-online.png) 온라인으로 작업 중 아이콘을 클릭하면 빨간색 ![오프라인으로 작업 중 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-offline.png)이 표시됩니다.

![온라인/오프라인 전환](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/example/online-offline-toggle.png)

온라인 모드
------

Fusion 360은(는) 다음과 같은 경우 자동으로 다시 온라인으로 돌아갑니다.

*   인터넷 연결이 탐지될 때
*   예기치 않은 중단이 해결된 경우
*   서비스 유지 관리가 완료된 경우
*   아래 절차를 사용하여 수동으로 온라인으로 이동합니다.

온라인 모드로 수동으로 전환하려면

1.  ![오프라인 모드 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/offline-mode.png) 작업 상태 아이콘을 클릭합니다.
2.  ![오프라인으로 작업 중 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-offline.png) 오프라인으로 작업 중 아이콘을 클릭하면 녹색 ![오프라인으로 작업 중 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/working-online.png)이 표시됩니다.

오프라인 모드에서 변경되고 저장된 문서는 자동으로 업데이트되어 데이터 패널에 업로드됩니다. 오프라인 모드에서 저장하는 동안 Fusion 360은(는) "마지막 저장 후" 기반으로 작동합니다. 각 디자인의 한 버전만 캡처되고 이 버전이 디자인의 "마지막 저장" 버전이 됩니다. 최종 버전만 대시보드에 동기화됩니다. 오프라인 모드에서 작업을 저장하는 동안 기본 설정의 캐시 시간 제한에 따르지 않는 대기열이 작성됩니다.

주: 참조된 모형으로 작업할 때 원하는 버전의 모형을 선택할 수 없습니다. 다시 온라인 모드로 전환하면 마지막으로 저장된 모형 상태만 가장 실제 버전으로 업로드됩니다.

예기치 않은 대기 시간 알림
---------------

인터넷 연결(클라우드 렌더링, 클라우드 시뮬레이션 등)에 의존하는 Fusion 360의 일부 영역을 느리게 할 수 있는 서비스 지연 시간을 감지하면 Fusion 360에서 작업 상태 아이콘 ![유지 관리 모드 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/maintenance-mode.png)에 노란색 점이 표시됩니다. 온라인 상태가 되며 파일 캐싱을 제외하고 온라인에서와 같이 모든 파일 및 디자인 작업을 계속 수행할 수 있습니다.

업로드 과정 중에 인터넷 연결이 끊어지면 파일은 어떻게 됩니까?
-----------------------------------

파일을 업로드할 때 인터넷 연결이 끊어지거나 실수로 Fusion 360을(를) 닫는 경우가 있습니다. 데이터가 손실되지 않습니다. 인터넷에 다시 연결되면 업로드 프로세스가 계속되고 파일이 클라우드에 완전히 업로드됩니다.

오프라인으로 작업한 후 데이터를 가져오는 방법
-------------------------

오프라인 모드에서 변경된 문서는 온라인 모드에 있으면 자동으로 업데이트되고 데이터 패널에 업로드됩니다.
