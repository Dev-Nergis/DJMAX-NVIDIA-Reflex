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
### AMD Radeon
NVIDIA Reflex 는 AMD Radeon 에서 작동하지 않습니다.
그대신 AMD Radeon Boost 를 사용할수 있습니다.

## 설정방법
1. NVIDIA 제어판에서 NVIDIA 초저지연 모드: 울트라
![nvidia-reflex-control-panel-low-latency-ultra-mode](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/nvidia-reflex-control-panel-low-latency-ultra-mode.png)
2. NVIDIA 제어판에서 전력 관리 모드: 최고 성능 선호
![nvidia-reflex-control-panel-prefer-maximum-performance-mode](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/nvidia-reflex-control-panel-prefer-maximum-performance-mode.png)
3.DJMAX 인게임 설정에서 활성화
![djmax-in-game-setting](https://raw.githubusercontent.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/main/images/djmax-in-game-setting.png)

## Test Setup
- NVIDIA GeForce GTX 1050
- MAX FPS 240

## 결과
> __**FPS**__
>>
>> OFF: 230/fps
>>
>> ON: 140/fps
>>
>> ON+BOOST: 130/fps
>>
> __**LATENCY**__
>>
>> OFF: 11~13/ms
>>
>> ON: 10~13/ms
>>
>> ON+BOOST: 10~12/ms

~~1ms의 차이를 느낄 기계없나요~~

## 버그
### 해결되면 ✅ 가 생김니다.
- [X] Test
- [ ] 수직동기화 적용 안됨
[](https://github.com/Dev-Nergis/DJMAX-NVIDIA-Reflex/issues/3)
- [ ] 검은 배경

## 이 문서에 도움주기
### Pull 및 자료 재공, 태스트 수치 기여
`CONTRIBUTING.md` 파일 참고

### 기여자 목록
`CONTRIBUTORS.md` 파일 참고
