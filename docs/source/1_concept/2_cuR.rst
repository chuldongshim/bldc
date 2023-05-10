========================
개발환경
========================

------------------------
개발전략
------------------------

단계적 개발
------------------------
BLDC 위치제어를 최종 타겟으로 정의하며 단계적으로 개발을 진행합니다.

1. 1단계에서는 단순히 hall sensor를 사용하여 bldc 모터 정/역 회전을 구현하고,
2. 2단계에서는 sensorless를 사용하여 bldc 모터 정/역 회전을 구현한 다음
3. 3단계에서 위치제어를 구현합니다.
4. 4단계에서 제어 성능을 높이기 위한 알고리즘을 추가로 구현합니다.

개발전략
------------------------
본 제품개발 프로젝트는 기존에 수행된 3개의 프로젝트에 적용된 기술들을 이용하여 확장보드를 개발하는 컨셉으로 진행되었습니다.

기존에 수행된 작업
* BLDC 선행학습
* 와이퍼 알고리즘 개발
추가한 작업
* BLDC 제어기술 고도화
* BLDC 하드웨어 설계기술 학습/적용

------------------------
벤치마킹
------------------------

bldc driver
---------------------------

벤치마킹

* 아두이노 기반
* TI
* `BLDC Shield with TLE9879QXA40 for Arduino <https://www.infineon.com/dgdl/Infineon-BLDC_shield_user_manual-UM-v01_00-EN.pdf?fileId=5546d462696dbf120169a0bb25396e7d>`_

Janus Controller - Brushless motor driver for ESP32 (FOC)

* https://www.youtube.com/watch?v=tti3y8_cQ4o
* https://github.com/byDagor/Janus-Controller
* https://hackaday.io/project/173519-janus-brushless-controller
	
구동원리

* https://www.youtube.com/watch?v=uOQk8SJso6Q
* https://mikrodunya.wordpress.com/2021/08/25/esp32-bldc-alan-oryantasyonlu-kontrol-foc-1-bolum/
* https://mikrodunya.wordpress.com/2021/08/20/esp32-ile-fircasiz-dc-motor-bldc-kontrolu/


------------------------
타겟
------------------------

stm32와 tms320f28069 중 MBD로 가장 구현하기 쉬운 방법을 선택합니다.


Simulink + BLDC + Stm32
------------------------

* `Sensorless Field-Oriented Control of PMSM Using STM32 Processor Based Boards <https://kr.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ug/senorless-stm-example.html>`_
* mcb_open_loop_control_nucleo_f401re.slx, stm32f401re_pmsm_example.ioc

Simulink + BLDC + TI
------------------------

Field-Oriented Control with TI LAUNCHXL-F28069M, BOOSTXL-DRV8301 inverters and 2 PMS motors (현재 보유)

* `Dual Motor Control with TI LAUNCHXL-F28069M LaunchPad <https://kr.mathworks.com/matlabcentral/fileexchange/49109-dual-motor-control-with-ti-launchxl-f28069m-launchpad>`_


mathworks
------------------------

mathworks BLDC 모터 제어 알고리즘의 이해

* `BLDC 모터의 역학 <https://kr.mathworks.com/campaigns/offers/next/understanding-bldc-motor-control-algorithms.html>`_
* `제어기 연결 및 모터의 시뮬레이션 모델 구축 <https://kr.mathworks.com/campaigns/offers/next/understanding-bldc-motor-control-algorithms/motor-speed-control.html?s_tid=dl_prv_nxt>`_
* `시뮬레이션을 통해 모터 동작 살펴보기 <https://kr.mathworks.com/campaigns/offers/next/understanding-bldc-motor-control-algorithms/exploring-motor-behavior.html>`_



