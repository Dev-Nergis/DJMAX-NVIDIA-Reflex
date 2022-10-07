# DJMAX NVIDIA Reflex 에대한 고찰
> __**주의 사항**__
>> 사용자의 환경마다 다를수 있음

## NVIDIA Reflex 란?
시스템(인/아웃) 레이턴시가 가능한 한 최소화됩니다.
- **Before**
![nvidia-reflex-system-latency-pipeline-before-addition-of-reflex](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/nvidia-reflex-system-latency-pipeline-before-addition-of-reflex.png)
- **After**
![nvidia-reflex-system-latency-pipeline-with-reflex](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/nvidia-reflex-system-latency-pipeline-with-reflex.png)

- __**시스템 요구사항**__
- Nvidia GTX 900 시리즈 이상
- Nvidia Reflex와 함께 작동하는 게임 (여기에서는 DJMAX)
- __선택사항__
- NVIDIA G-SYNC

## 설정방법
1. NVIDIA 제어판에서 NVIDIA 초저지연 모드: 활성화
![nvidia-reflex-control-panel-low-latency-ultra-mode](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/nvidia-reflex-control-panel-low-latency-ultra-mode.png)
2. NVIDIA 제어판에서 전력 관리 모드: 최고 성능 선호
![nvidia-reflex-control-panel-prefer-maximum-performance-mode](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/nvidia-reflex-control-panel-prefer-maximum-performance-mode.png)
3.DJMAX 인게임 설정에서 활성화
![djmax-in-game-setting](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/djmax-in-game-setting.png)

## Test Setup

- NVIDIA GeForce GTX 1050
- MAX FPS 240

# 결과
> __**FPS**__
>> OFF: 230
>> ON: 140
>> ON+BOOST: 130
> __**LATENCY**__
>> OFF: 11~13
>> ON: 10~13
>> ON+BOOST: 10~12

### 다른거 필요없고 결과만!!
> OFF : 평균 5ms
>
> ON : 평균 4.5ms
>
> ON+BOOST : 4ms

~~1ms의 차이를 느낄 기계없나요~~

