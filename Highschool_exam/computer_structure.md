# 기말고사와 함께하는 컴퓨터 구조

참고 : https://www.youtube.com/watch?v=Fg00LN30Ezg&ab_channel=bRd3D

## 마이크로 컴퓨터

- `마이크로 컴퓨터` : 하나의 칩 속에 `중앙처리장치`가 들어 있는 것으로, 1971년 인텔사가 처음으로 개발하였음
- `마이크로프로세서`에 `LSI(Large Scale Integration)`에 의한 연산처리장치, 기억장치, 입출력장치 등을 부가한 컴퓨터
- 개인용 컴퓨터, 산업용 로봇, 자동차 엔진, 가정용 기기 등에서 **제어장치**로 이용
- `마이크로프로세서` : CPU 혹은 중앙 처리 장치. 컴퓨터에서 기억, 해석, 연산, 제어라는 4대 주요 기능 관할
- `LSI(Large Scale Integration)` : 고밀도 집적회로

## 컴퓨터의 특성

- `신속성` : 입출력 속도와 연산 속도가 빨라서 많은 양의 데이터를 **신속하게 처리**할 수 있음
- `대용량성` : **많은 양의 데이터**를 기억하고 처리할 수 있음
- `신뢰성` : 컴퓨터의 **처리 결과 신뢰** 가능. 주어진 환경 아래에 요구되는 기능을 **원활히 수행**할 수 있음
- `정확성` : **오류 및 오차 최소화**. 정확한 계산 및 정확한 처리 결과
- `범용성` : **많은 분야**에서 다양한 업무 처리 (과학 기술용, 사무 처리용이나 교육 등)

## 그레이 코드 변환 과정

- `그레이 코드` (Gray Code) : 한 번에 한 비트씩 변화 (미지근~하게 변해서 회색 코드라는 뜻)
- 그레이 코드는 아날로그와 디지털 간에 코드를 변환할 때 사용함 
- 아래는 `2진수`를 `그레이 코드`로 변환하는 방법
- 과정1 : 2진수의 `최상위 비트`는 그대로 그레이 코드의 `최상위 비트`
- 과정2 : 2진수의 최상위 비트와 다음 비트를 `더한` 후
- 과정3 : 자리 올림수를 제거한 나머지를 `그레이 코드`로 취함.
- 이하 같은 방법

![image](https://user-images.githubusercontent.com/80818534/145031006-6ca624dd-9add-4291-b0ea-217883f9567f.png)

- 아래는 `그레이 코드`를 `2진수`로 변환하는 방법
- 과정1 : 그레이 코드의 `최상위 비트`는 그대로 2진수의 최상위 비트
- 과정2 : 2진수와 그레이 코드의 다음 비트와 더하여
- 과정3 : 자리 올림수를 제거한 나머지를 `2진수`로 취함.
- 이하 같은 방법

![image](https://user-images.githubusercontent.com/80818534/145032569-bc3da5c7-3a82-4cce-904a-d23ef3279696.png)

## 고급 언어

- `고급언어` : 프로그래밍 언어 (C, PYTHON, JAVA 등)
- `어셈블리어` : 사람이 이해하기 쉬운 단어로 바꾼 것 (MOV, ADD, STA, LDA 등)
- `기계어` : 컴퓨터가 사용하는 언어 (0과 1)

## 소프트웨어 종류

![image](https://user-images.githubusercontent.com/80818534/145032825-24ad4a55-cecd-4473-8ef1-84f64428afa7.png)

- `시스템 소프트웨어` : 하드웨어를 컨트롤할 수 있는 소프트웨어
- `응용 소프트웨어` : 시스템 소프트웨어의 도움을 받아 사용자가 원하는 작업 처리
- `운영체제` : 하드웨어 관리 등 담당. 하드웨어와 사용자 간의 인터페이스 제공
- `유틸리티` : 운영체제 제공 외에 **추가 기능 제공**하여 사용자의 편의를 지원하는 소프트웨어
- `범용 프로그램` : 다수의 사용자가 일반적으로 사용하는 프로그램 ex) MS office, Photoshop, game
- `특수 목적용 소프트웨어` : 기업, 학교, 연구소, 공공 기관 등 특정 분야의 고유 업무 처리를 위한 소프트웨어 ex) 성적 처리, 인사 관리 프로그램

## 하드웨어 구성 요소

- `메인보드` (main board) : 컴퓨터의 부품들을 하나로 연결해주는 회로와, 밖으로 신호를 보내는 출력 포트 가지고 있음
- `CPU` : 중앙처리장치. 컴퓨터에서 기억, 해석, 연산, 제어를 관할하는 장치
- `GPU` : 컴퓨터 시스템에서 **그래픽 연산**을 빠르게 처리하여 결과값 모니터에 출력하는 연산장치
- `주기억장치` : 컴퓨터 메모리. 수치/명령/자료 등 기억하는 장치
- `광 저장장치` : CD-ROM. 광 레이저 기술 이용하여 멀티미디어 정보를 저장/재생
- `HDD, SSD` : 보조기억장치. 비휘발성이며 오프라인 저장 장치.

![image](https://user-images.githubusercontent.com/80818534/145034457-ef6d73a2-94f6-4ca6-89d6-698be2280a7a.png)

## 연산장치 구성요소

- `연산 장치` : 데이터 처리를 위한 **연산**이 이루어지는 곳
- 연산에 사용될 데이터를 받아 제어 장치가 지시하는 순서에 따라 데이터 `산술 연산` 및 `논리 연산` 실행
- 그 결과를 `레지스터(register)` 혹은 `누산기(accumulator)`에 저장
<br><br>
- `데이터 레지스터` : 주기억 장치로부터 **가져온 데이터를 보관**하는 기억 장소
- `가산기` (adder) : 누산기와 레지스터의 **값을 더하여** 그 결과를 누산기에 보관하는 회로
- `누산기` (accumulator) : 연산 장치를 구성하는 중심이 되는 레지스터. 연산의 **중간 결과 기억**
- `오버플로 검출기` : 가산기의 결과가 해당 **레지스터의 용량 초과** 시 검출해 주는 회로
- `상태 레지스터` : 연산 결과의 부호 입력 자리 올림수(carry in), 오버플로, 인터럽트 발생 여부 등 **상태 정보 저장**

![image](https://user-images.githubusercontent.com/80818534/145036025-c250c954-faba-4c6e-9b7a-5c5d8ffb3f18.png)

- 연산 과정
- 1. 제어 장치의 `제어 신호`를 받음
- 2. 주기억 장치에서 데이터를 가져와 `레지스터에 저장`
- 3. 새로운 데이터가 있을 경우에는 주기억 장치에서 가져와 저장
- 4. `누산기`에 있는 값과 `데이터 레지스터`에 있는 값을 이용하여 `연산` 실행
- 5. 상태 정보를 확인, `상태 레지스터`에 상태 정보 저장
- 6. 가산 결과를 `누산기`에 저장
- 7. `주기억 장치`로 결과 저장

## 논리 회로 (논리게이트)

- `논리 연산` : 논리합, 논리곱, 논리부정, 분기, 비교, 시프트, 변환 등
- `논리 연산 회로` : 입력 데이터에 대해 논리 연산을 실행하도록 하는 조합 논리 회로로 만들어진 회로
- 논리 연산에서는 데이터를 비트 또는 바이트 단위로 취급
- `논리곱(AND)` : 주어진 복수 명제 `모두가 참`이어야 결과가 참이 되는 연산
- `논리합(OR)` : 주어진 복수 명제에 `적어도 1개 이상의 참`이 있으면 결과가 참이 되는 연산
- `논리부정(NOT)` : 주어진 명제의 참과 거짓을 `부정`하는 것
<br><br>
- `AND 게이트` : 두 개 이상의 입력이 모두 1일 때 출력이 1인 게이트. (논리곱 회로)
- `OR 게이트` : 두 개 이상의 입력 중 하나 이상 입력이 1일 때 출력이 1인 게이트. (논리합 회로)
- `NOT 게이트` : 입력이 0이면 출력이 1, 입력이 1이면 출력이 0인 게이트. (논리부정 회로)
- `NAND 게이트` : NOT + AND 게이트로써 AND 게이트 출력의 반대가 출력
- `XOR 게이트` : 배타적 논리합(eXclusive OR) 회로로 입력 값이 `서로 다를 때` 출력이 1인 회로

![image](https://user-images.githubusercontent.com/80818534/145044804-382bed23-0680-40b3-9e1c-d15896766818.png)
![image](https://user-images.githubusercontent.com/80818534/145045035-372db7d3-a8c8-418d-ae47-97e861e155c0.png)

## 진수 변환 (2진수, 8진수, 16진수, 10진수)

- 10진수에서 2진수로 변환
![image](https://user-images.githubusercontent.com/80818534/145045930-4825f7a3-b44e-4077-96e4-c701f41c3462.png)

- 10진수에서 8진수로 변환<br>
![image](https://user-images.githubusercontent.com/80818534/145046088-15a69e1d-e764-4731-a47f-d55f6ce9775c.png)

- 10진수에서 16진수로 변환
![image](https://user-images.githubusercontent.com/80818534/145046170-4cc727f0-8149-4e87-94ce-c2a67acbb6a7.png)

- 8진수 <-> 2진수 <-> 16진수
- `8진수`는 2진수에서 `3자리`씩 변환
- `16진수`는 2진수에서 `4자리`씩 변환
- 2진수를 8진수, 16진수로 변환하는 것은 위 과정 역으로 수행

## 제어장치 역할

- 입력 장치에서 입력된 데이터를 `기억 장소에 저장`
- 기억 장치에 있는 데이터를 `연산 장치로 이동`
- 연산 장치에서 연산 완료 시 결과를 `기억 장치로 이동`
- 기억 장치에 저장된 데이터를 `출력 장치로 이동, 출력`
- 입력장치 <-> 기억장치 <-> 연산장치 <-> 기억장치 <-> 출력장치

## 제어장치 구성요소

- `주소 레지스터` (MAR; Memory Address Register) : 주기억 장치에 명령이나 자료가 기억되어 있는 `주소를 보관`
- `기억 레지스터` (MBR; Memory Buffer Register) : 명령어 계수기가 지정하는 주기억 장치의 `내용을 임시 보관`
- `명령어 레지스터` (IR; Instruction Register) : 현재 실행 중인 `명령을 기억`하는 레지스터. 연산 코드와 주소부로 구성
- `명령어 계수기` (PC; Program Counter) : `다음에 실행`할 명령어가 기억되어 있는 주기억 장치의 `주소를 기억`
- `명령어 해독기` (Decoder) : 명령어 레지스터의 `명령 코드를 해독`하여 필요한 실행 신호 발생시킴
- `주소 처리기` (Address Processor) : 피연산자를 인출할 경우 그 `주소를 계산`하거나, 수행될 명령 순서가 바뀔 때 다음에 수행할 명령의 주소 계산
- `순서기` (Sequencer) : 정해진 순서에 따라 `동작 순서를 제어`

![image](https://user-images.githubusercontent.com/80818534/145049089-35fbd92d-09fa-4b42-a912-a499eba20b80.png)

## 제어장치 수행 과정

- 명령어 주소 전송을 위해 `명령어 계수기(PC)`에 기억된 주소를 `MAR`으로 보냄
- `주기억 장치`의 내용을 임시 보관하는 `MBR`에서 읽어온 명령어를 `명령어 레지스터(IR)`에 저장, `명령어 계수기` 1 증가
- 명령어 코드(op Code) 필드와 주소 필드를 각각 `해독기`와 `주소 처리기`로 보냄
- `주소 처리기`는 연산 자료 인출 시 **피연산자의 주소**를 계산. 수행 명령어 바뀔 때는 **다음 명령어 주소를 계산**하여 `명령어 계수기`에 기억시킴
- `제어 신호 발생기`가 **연산자를 해독**하여, 명령어 수행을 위한 제어 신호 발생. 만약 수행 순서 변경 시 `주소 처리기` 동작시켜 명령어 주소 계산
- 다음 명령 수행 위해 위 과정 반복. 현재 `명령어 레지스터`에 있는 명령어의 수행 끝나면 증가된 `명령어 계수기`의 값을 `MAR`에 보내 다음 명령어 실행

## 명령어 형식

- `모드(mode)` : 피연산자의 주소가 **직접 주소**인지 **간접 주소**인지 구분
- `명령 코드부(op code)` : 실행할 동작 지시 (연산자)
- `주소부(operand)` : 피연산자가 저장된 주기억 장치의 **주소** 나타냄
- 명령어 형식은 `주소부(operand)`의 주소 수에 따라 구분할 수 있음 (주기억 장치의 위치 나타내는 법 여러 가지)

참고) 직접 주소는 **기억 장소를 주소부에 직접 지정**하는 것이고, 간접 주소는 **데이터가 저장된 주소를 저장하고 있는 기억 장소의 주소를 저장**하는 것이다.

![image](https://user-images.githubusercontent.com/80818534/145127551-af4b90be-703a-4608-b919-b56be3f8325a.png)

### 0-주소 명령어 형식

- `스택(stack) 구조 컴퓨터`에서 사용되는 명령어 형식
- 입력 자료들의 출처와 연산 결과를 기억시킬 **장소가 고정**됨
- 명령어 내에서 **자료의 주소를 지정할 필요가 없는** 명령어 형식
- 주소의 사용 없이 스택에 연산자와 피연산자를 넣었다 꺼내어 연산한 후 결과를 다시 스택에 넣으면서 연산하기 때문에 원래의 자료가 남지 않음
- `TOS`는 Top Of Stack으로, 스택 구조의 최상단을 의미

### 1-주소 명령어 형식

- `단일 누산기 구조의 컴퓨터`에서 사용됨
- 명령어의 수행은 `누산기(AC) 레지스터`에서 이루어짐
- 하나의 주소부를 가지며, 연산에 사용되는 피연산자는 **주소부에 의하여 얻어지는 피연산자**와 **누산기에 기억되어 있는 피연산자**임
- 연산 결과도 누산기에 저장되므로 원래의 자료가 남지 않음

### 2-주소 명령어 형식

- `범용 레지스터 구조의 컴퓨터`에서 사용. 가장 많이 사용됨
- 각 주소부는 `레지스터`나 `주기억 장치`의 주소 지정
- 연산 후 자료 보존 필요 없으면 연산 결과를 **두 자료가 기억된 곳 중 한 레지스터**에 기억시키는 방식

### 3-주소 명령어 형식

- `범용 레지스터 구조의 컴퓨터`에서 사용. 세 개의 주소를 지정
- 각 주소부는 `레지스터`나 `주기억 장치`의 주소 지정
- 프로그램 길이 짧고, 연산 후 **입력 자료가 레지스터에 보존**되는 장점
- 하나의 명령을 수행하기 위해 자주 기억장치에 접근해야 함. 수행 시간이 길어지므로 특수 목적 외에는 사용 X

![image](https://user-images.githubusercontent.com/80818534/145128325-ddc28922-978c-4af0-8d5f-2d629f7fc2e2.png)

## 주소 지정 방식

- 연산에 사용될 데이터를 `주기억 장치`의 어디에서 가져올 것인가를 지정하는 방식
- 명령어의 **명령 코드**(op code)는 수행할 명령 표시
- 명령은 **레지스터나 주기억 장치의 데이터**를 대상으로 수행
- 명령어 수행 중 **피연산자 주소 지정 방법**은 `명령어 주소 지정 방식`에 따라 결정됨

참고) 오퍼랜드(operand)는 피연산자이다.

### 묵시적 주소 지정 방식

- 명령어의 정의에 따라 주소가 **암시적으로 정해**지는 방식
- `누산기`를 사용하는 연산에 사용됨
- ex) 누산기에 저장된 값의 보수를 취하라는 명령은 피연산자가 누산기에 있기 때문에 묵시적 주소 지정 방식이 됨
- ex) 스택 구조 컴에서 `0-주소 명령어`는 피연산자가 스택의 맨 위를 지정하기 때문에 묵시적 주소 지정 방식이 됨

### 즉시 주소 지정 방식

- 피연산자가 **명령어 자체 내에 포함**된 형태 (실제 데이터)
- 명령 인출과 동시에 기억 장치의 데이터도 **자동 인출**
- 명령어의 실행이 바로 이루어지는 방식

![image](https://user-images.githubusercontent.com/80818534/145220952-0e3eb342-9980-4bf8-b9a9-7940bafa3e3b.png) 

### 직접 주소 지정 방식

- 오퍼랜드 내의 주소를 **실제 데이터 주소**로 직접 표현하는 방식
- **분기 형식**의 명령에서 주로 사용됨
- 장점은 프로그램이 **간결하게 작성**되고(기억 장치의 주소와 프로그램 상의 주소가 일치), 간접 주소 지정 방식에 비해 속도가 빠름
- 단점은 기억 장치 용량이 큰 경우 **오퍼랜드의 길이가 길어져** 융통성 부족

![image](https://user-images.githubusercontent.com/80818534/145221019-7a54e81d-8155-46fe-a530-7d932bfeb740.png)

### 간접 주소 지정 방식

- 오퍼랜드의 주소부에 **실제 피연산자가 있는 유효 주소**가 기억되는 방식
- 오퍼랜드의 주소부에 의해 기억 장치 내의 주소로 찾아간 후, 그 주소의 내용이 나타내는 주소에 실제 데이터가 기억됨
- 실제 유효 주소를 구하기 위해 한 번은 `유효 주소`를 가져오고, 한 번은 `실제 데이터`를 가져오는 **두 번의 메모리 참조 수행**
- 장점은 오퍼랜드의 짧은 길이로 긴 주소 접근 가능하여, 기억 장치의 **용량이 큰 경우도 융통성 보장**
- 단점은 기억 장치에 두 번 이상 접근해야 하기에 **데이터 처리 속도 느림**

![image](https://user-images.githubusercontent.com/80818534/145221078-53dd6f13-b62a-4f9e-a8bc-da60c66687c7.png)

### 레지스터 주소 지정 방식

- 중앙 처리 장치 내의 `레지스터`에 실제 데이터가 기억되는 방식
- 명령어의 주소부는 지정된 **레지스터의 번호**를 가짐
- 데이터 인출을 위해 주기억 장치 접근 X, 명령어 **실행 시간 빨라짐**
- 내부 레지스터들도 **제한**되어 사용됨

![image](https://user-images.githubusercontent.com/80818534/145221121-ad9c107c-4ea5-4fb5-bdc7-a31331a5a9fa.png)

### 레지스터 간접 주소 지정 방식

- `간접 주소 지정 방식` + `레지스터 주소 지정 방식`
- 오퍼랜드가 레지스터를 저장, 그 레지스터의 값이 실제 데이터의 주소를 지정

![image](https://user-images.githubusercontent.com/80818534/145221230-950b4377-bc17-4aa2-97ff-7f444036cfe9.png)

### 상대 주소 지정 방식

- 명령어 주소부에 명령 계수기 값이 더해져, 유효 주소가 결정되는 방식
- 기준 주소는 `명령어의 주소`이고, `명령 계수기의 값`이 상대적 변위임

![image](https://user-images.githubusercontent.com/80818534/145221271-3406a7a1-c4cc-42d2-9771-b1b24ff60e5e.png)

## 마이크로 명령

- 컴퓨터의 기계어 명령을 실행하기 위해 수행되는 **더욱 낮은 수준의 명령어**
- 이에 대해 원래 기계어 명령을 `매크로 명령`이라고 함
- 중앙 처리 장치(CPU) 내의 `각종 게이트를 구동하는 비트 신호`로 이루어짐. CPU 내의 `제어 기억 장치`에 저장
- CPU 내의 제어부가 마이크로 명령을 꺼내 각 게이트에 **신호**를 줌

## 메이저 사이클

- `메이저 상태` : 중앙 처리 장치가 무엇을 하는지 나타내는 것 (해당 사이클 동안 무엇을 위해 기억 장치에 접근하는가)
![image](https://user-images.githubusercontent.com/80818534/145583339-abd23d0d-3884-42b3-a207-d4ab75ec8cb9.png)

## 명령어 인출과 실행

### 명령어 인출

- `명령어 인출(instruction fetch)` : 명령어 해독을 위해 해독할 명령을 `주기억 장치`에서 `제어 장치`로 가져오는 것
- `명령어 인출 주기` : 일정한 행위가 반복적으로 일어날 때 하나의 구간
- 1. 주기억 장치에서는 인출할 명령어의 주소를 `명령 계수기`가 가리킴
- 2. 이 내용이 `주소 레지스터`로 옮겨져 그 주소에 기억된 명령이 `기억 레지스터`로 이동
- 3. `명령 계수기`는 다음 명령이 기억된 주소를 가리키도록 증가
- 4. `기억 레지스터`에 기억된 명령은 명령 코드와 주소부로 분리되어 명령 코드와 형식이 각각 `명령 레지스터`, `형식 레지스터`로 이동
- 5. `형식 레지스터`의 내용을 검사하여 **직접 주소 형식**이면 실행 단계로 진행
- 6. **간접 주소 형식**의 명령어는 주소 값을 가져오기 위해 `기억 레지스터`에서 주소부를 `주소 레지스터`로 옮김
- 7. `주소 레지스터`가 가리키는 곳의 내용을 `기억 레지스터`에 옮기는 작업을 수행한 후 실행 단계를 진행

![image](https://user-images.githubusercontent.com/80818534/145584955-feca8e60-0019-445b-81e8-5a9416dd8720.png)


### 명령어 실행

- 실행 단계에서는 이미 명령 코드가 `명령어 레지스터`에 기억되어 있음
- `기억 레지스터`에는 연산될 데이터의 주소가 기억되어 있음
- 1. `기억 레지스터`에 기억된 명령 코드는 `명령어 해독기`에서 해독됨
- 2. `누산기`에 기억된 피연산 데이터와 `명령어 해독기`에서 해독되어 기억된 연산 데이터인 기억 레지스터의 내용을 `가산기`로 보내어 연산
- 3. 연산 결과는 `누산기`에 옮겨져 기억되는 것으로 하나의 명령 실행이 끝남
- 4. 명령을 실행하기 위해 명령어 인출 단계로 진행

![image](https://user-images.githubusercontent.com/80818534/145584980-96c7d7b6-9908-4484-bbe9-5a886e7b2d1a.png)


## 주소지정방식에서 따른 명령어 처리 과정
?

## 어셈블리 명령어

- `LOAD` : 인출
- `ADD` : 덧셈
- `STORE(혹은 STA)` : 저장
- `JUMP` : 분기

## CPU 기능 (명령어 사이클)

- `명령어 인출` (Instruction Fetch) : 기억 장치로부터 명령어를 읽어온다
- `명령어 해독` (Instruction Decode) : 수행해야 할 동작을 결정하기 위해 명령어 해독
- CPU는 명령어 `인출`, `해석`, `실행` 과정을 거쳐 명령어를 수행함

## 기억 장치

![image](https://user-images.githubusercontent.com/80818534/145310921-6a3f0aea-7812-4a05-a62f-d8d0264acd2d.png) 

### 주기억 장치

- `주기억 장치`는 실행할 프로그램과 데이터(입력 내용, 생성 자료, 출력 내용)를 임시 저장
- `중앙 처리 장치`는 주기억 장치에 저장된 프로그램을 읽어서 실행
- `보조 기억 장치`나 `외부 기억 장치`에 있는 데이터는 처리되기 전 주기억 장치로 읽혀져 들어와야 함
- 주기억 장치는 `자기 코어 방식 기억 장치`와 `반도체형 기억 장치`로 나눌 수 있음
- 기억 장치에 들어오는 주소와 선은 여러 곳에서 들어오고, 여러 곳으로 나갈 수 있음

### 보조 기억 장치

- 용량이 큰 자료를 장기간 저장할 때 사용
- `주기억 장치`보다 용량이 크지만, 속도는 많이 느림
- 비휘발성
- 용도에 따라 다양한 형태의 보조 기억 장치 존재
- `직접 접근 기억 장치` : 물리적 순서와 관계없이 특정 기억 장소에 직접 데이터 기록, 읽음
- `순차 접근 기억 장치` : 기록된 데이터의 순서대로 처음부터 접근하여 원하는 데이터 위치 찾음

### 특수 기억 장치

- 속도가 **매우 빠르**거나 `중앙 처리 장치`의 **특별한 용도**로 사용
- 중앙 처리 장치 내부에서 사용되는 `레지스터`, `캐시 메모리`, `연관 기억 장치` 등이 있음
- `레지스터` : CPU 내부의 계산을 위해 일시적으로 **자료나 명령 등을 저장**하는 장치 (가장 빠른 기억 장치)
- `캐시 메모리` : CPU와 주기억 장치의 **속도 차**를 줄이기 위한 고속 메모리
- `연관 메모리` : CPU가 찾는 주기억 장치 메모리가 캐시 메모리 어디에 있는지 **빠르게 검색**할 수 있게 해주는 메모리

## 반도체형 기억 장치 (주기억장치)

- `IC(Integrated Circuit)칩`으로 되어 있음
- 반도체 기억 장치 칩에는 데이터를 읽고 쓸 수 있는 `제어 신호`가 있고, 기억 장치 안에는 임시로 데이터를 저장하는 `레지스터`가 있음
- 전원이 꺼지면 자료가 없어지는 `RAM(Random Access Memory)`와 자료가 보존되는 `ROM(Read Only Memory)`로 나뉨

![image](https://user-images.githubusercontent.com/80818534/145306889-03e7f772-2688-4c98-8538-df5d05643c6c.png)

### RAM (Random Access Memory)

- 임의의 기억 장소에 사용자가 작성한 프로그램이나 데이터를 저장할 수 있음
- 프로그램 실행 시 그 내용 읽음, 변경할 수도 있음
- `RWM(Read Write Memory)`라고 부르기도 함
- 전원이 없으면 기억 내용이 사라지는 **휘발성**임

#### SRAM(Static RAM)

- 기억을 유지시키기 위해 `플립플롭`으로 만들어짐
- 전원을 끄지 않는 한 내용 유지, 고속 액세스 타임
- 속도가 빠른 대신 가격이 비싸서 `캐시 메모리`로 많이 사용

#### DRAM(Dynamic RAM)

- 기억 소자가 `커패시터(capacitor)` 형태로 이루어짐, 그래서 전원을 끊으면 내용 사라짐
- `회생(refresh)` : 전원 공급에도 커패시터 특성상 내용이 사라져서, 수 ms마다 다시 충전 필요. 자동적으로 회생되도록 메모리 주변에 `회생 회로`가 있어야 함
- SRAM에 비해 구조가 단순하여 가격 저렴
- DRAM -> FPMRAM -> SDRAM -> DRDRAM -> DDR1 -> DDR2 -> DDR3 -> DDR4

### ROM (Read Only Memory)

- `마스크 롬(Mask ROM)` : 사용자가 요청한 내용을 **생산 단계**에서 롬에 기록하여 생산. (같은 내용의 롬을 대량 생산할 때 적합)
- `PROM(Programmable ROM)` : 개인 사용자가 **한 번**은 데이터를 써 넣을 수 있는, 프로그램이 가능한 롬 (쓴 내용을 지울 수 있는 것, 지울 수 없는 것이 있다)
- `EPROM(Erasable and Programmable ROM)` : `ROM writer`로 쓰고, `ROM eraser`로 지울 수 있는 롬
- `EEPROM(Electrically EPROM)` : 별도의 ROM writer나 ROM eraser 없이 `전기 신호`를 사용하여 자료 기록 수정 가능 (하지만 횟수 한정)
- `Flash Memory` (USB Memory) : 읽고 쓰기가 가능한 `EEPROM`을 변형한 것. 전원 공급이 없어도 **내용 보존**(ROM), 임의로 기록 혹은 수정 가능(RAM)
- `Flash Memory`의 속도는 `RAM`과 `EEPROM`에 비해 느림. 또한 특정 공간에 10만 번 이상 기록 시 그 공간 파손

![image](https://user-images.githubusercontent.com/80818534/146007320-f32c9a22-0c89-447a-9a99-586f0cde1341.png)
참고) ROM Writer













