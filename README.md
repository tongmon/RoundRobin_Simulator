# RoundRobin_Simulator
RoundRobin Simulator build with C++ made by tongstar

라운드 로빈 시뮬레이터 입니다.
Debug 폴더 내의 RoundRobin_C++.exe로 실행합니다.
시뮬레이션할 타임 퀀텀을 정하고 작업들 정보가 담긴 텍스트 파일 명을 입력해 줍니다.
단!! 작업 정보가 담긴 텍스트 파일은 아래 양식을 지켜주세요

`````````````````````````````````````````````
Process     CpuCycle(ms)     ArrivalTime(ms)
---------------------------------------------
A                 8                   0
B                 4                   1
C                 9                   2
D                 5                   3
`````````````````````````````````````````````

프로세스 id, 작업량, 작업 도착 시간 순서 대로 적어주세요
예시들이 task_n.txt 파일로 존재합니다.
결과 파일은 RR_파일 생성 시각.txt로 생성됩니다.

자세한 내용은 How_to_use.txt를 읽어보세요
