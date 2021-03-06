# UAVCAN 기수 부여 및 설정

> **Note** 아래와 같이 'Enable UAVCAN' 확인 상자에 표시하여 기본 모터 출력 버스로서 UAVCAN을 활성화하십시오. 또는, *QGroundControl* 매개변수 편집기에서 UAVCAN_ENABLE 매개변수를 '3'으로 설정할 수 있습니다. '2'로 설정하면 CAN을 가동할 수 있으나, PWM 모터 출력 설정이 남습니다.

[QGroundControl](../qgc/README.md)을 활용하여 설정 보기로 전환하십시오. 좌측의 전원 설정을 선택하십시오. 'start assignment' 단추를 누르십시오.

처음 비프음이 울린 다음에는 처음 ESC의 프로펠러를 올바른 회전 방향으로 재빨리 돌리십시오. ESC는 기수를 부여할 때마다 비프음을 냅니다. [모터 맵](../airframes/airframe_reference.md)에 나타난대로 이 단계를 모든 모터 컨트롤러에 순서대로 반복하십시오. ESC를 구동하는 Sapog 펌웨어에 새 기수 ID를 적용하려면 다시 부팅해야합니다. 이 과정은 한번만 진행하면 되며, 펌웨어 업그레이드 진행 후 반복할 필요가 없습니다.

![UAVCAN 기수 부여 제어 (그림 우측 하단)](../../assets/uavcan-qgc-setup.png)