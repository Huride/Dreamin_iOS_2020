# Dreamin_iOS_2020
드림인 iOS 아카데미 개인 노트

---

# Week 1

## 아두이노와 라즈베리파이의 차이점
- OS(운영체제)의 사용유무(라즈베리파이는 OS를 설치해야 함
> 라즈베리파이는 application 프로그램 사용 및 외부기기 제어까지 가능
- 아두이노는 C언어 기반 / 라즈베리 파이는 C뿐만 아니라 아른 언어(Python, Java 등) 사용 가능
> 아두이노 : 마이크로 컨트롤러(주변 장치가 있기 때문에 외부기기를 직접 제어)
>> 센서, LCD, 모터와 같은 외부 장치 제어에 적함
> 라즈베리파이 : 마이크로 프로세서(주변장치가 없어 내부에 트렌지스터를 이용해 외부기기를 제어)
>> 카메라, 비디오 등 복잡한 수치 계산과 그래픽 처리에 적함
- **결론, 아두이노는 외부제어 / 라즈베리파이는 데이터 처리에 적합**



## HDD와 SDD의 장단점
- HDD
> 장점 : 
> 1. 용량당 가격이 저렴(TB단위에서는 독무대
> 1. 데이터 장기보존이 가능(SSD의 경우 방전으로 데이터 유실 가능성 존재)
> 단점 : 
> 1. 소음 및 전력 문제, 발열
> 1. 진동이나 충격의 영향을 많이 받음
> 1. 느린 속도

- SSD
> 장점 : 
> 1. 빠른 속도(플레시 메모리를 사용하여 빠른 속도를 보임)
> 1. 견고함(구동 부분이 없어 소리가 나지 않고 진동이나 충격에 영향을 받지 않음)

> 단점 : 
> 1. HDD대비 비싼 가격과 적은 용량(용량대비 높은 단가)
> 1. 덮어쓰기 횟수의 제한(짧은 수명)


## Git을 왜 사용해야 할까? 실제 사용에서 Git과 유사한 경험을 한적은?
- 팀작업시에 누가 무엇을 변경했는지 기록이 남기 때문에 팀원간 공동작업에 도움이 됨 - 공동작업시 어떤 부분이 수정되었는지 확인이 필요한 부분이 있고, 신규 업데이트 버젼이 오류가 있을 경우 전 버젼과의 비교가 필요하기 때문에 변경 기록을 계속해서 저장하는 것이 공동작업을 하는 데 용이함 - 구글드라이브를 활용해서 문서작업을 공유하거나 마이크로 소프트 팀즈를 통해 파일공유와 파일 수정등을 동시해 진해본 적 있음



## Git과 Github의 차이점
- Git : 변경사항 추적 시스템
> 파일의 변화기록을 전부 저장해 놓을 수 있어, 버젼관리에 용이
> 이전 버젼으로 돌아가거나 다른 사람들이 변경 기록을 쉽게 확인 할 수 있음
- GitHub : 변경사항을 저장할 수 있는 클라우드 서비스
> Git을 클라우드에 저장해 데이터 유실에 대비할 수 있고, 비주얼적으로 볼 수 있다는 장점
