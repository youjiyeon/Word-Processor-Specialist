# PC 기본 상식

# 1. 컴퓨터(EDPS)

컴퓨터

- 특징: 자동성, 정확성, 범용성, 신속성, 호환성, 대용량성
- 데이터 마이니: 대량의 데이터를 분석하여 일정한 패턴을 찾아내어 가치 있는 정보를 추출하는 기술
- 애니악 → 애드삭 → 애드박 → 유니박
- GIGO: 잘못된 자료가 입력되면 잘못된 자료가 나온다(수동성)

컴퓨터 세대별 특징

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/d02e2c3c-7f00-4d08-ab21-f5ea205c9342)

자료(데이터)에 따른 분류(디지털, 아날로그, 하이브리드)

- 디지털: 셀 수 있는 자료 취급
- 아날로그: 셀 수 없는 자료 취급
- 하이브리드: 디지털 + 아날로그 장점

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/414dac07-3890-4bda-8288-646260b67574)

처리 능력에 따른 분류(슈퍼, 메인, 미니, 워크스테이션)

- 슈퍼: 높은 정밀도, 정확한 계산, 인공위성, 일기예보, 우주 항공 산업에 이용
- 메인: 대규모
- 미니: 중규모
- 워크스테이션: RISC 프로세서, 서버 역할
- 데스크톱: CISC(일반적인 개인용 컴퓨터)
- HZ: 1초에 1번 주기가 반복됨(1KHZ: 1초에 1000번)
- MIPS: 1초에 백만개의 명령어 실행
- FLOPS: 초당 부동소수점 연산횟수
- 자료구성의 단위:
    - 비트-바이트(문자를 표현)-워드(단어를 표현)-필드(특정 항목)-레코드(자료)-블록(레코드의 모임)-파일-데이터베이스(자료의 최종 목적)
- 컴퓨터 연산 속도 단위

![Untitled (3)](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/22a0c13d-c16e-4ed1-8e54-6957f4981987)

자료 표현 코드

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/b1c29ba3-a4b5-4a55-8fb8-57805bf56a16)

---

# 2. 컴퓨터 시스템

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/f3a7f748-9428-4844-a8d0-61bc763f933e)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/2d79a2dd-95bd-4679-9e10-d725c381cc6f)

누산기: ACC

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/24bbbb46-ed20-4e48-8236-593de90cde92)

주기억장치

- ROM: 비 휘발성 메모리오, 입-출력 시스템(BIOS), 글자 폰트, 자가 진단 프로그램(POST)저장
- RAM: 휘발성 메모리로, 현재 사용중인 프로그램이나 데이터 저장

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/6cf0df89-2208-41bf-bedd-91e81e742af6)

- 플래시 메모리(EEPROM): MP3 플레이어, PDA, 디지털카메라, SD카드, 전기를 이용해서 여러 번 읽고 쓰기 가능
- 캐시 메모리(SRAM): CPU와 주기억장치 사이에 위치, 속도를 향상
- 가상 메모리: 보조 기억 장치(하드디스크)를 주 기억 장치처럼 사용
- 버퍼 메모리: 데이터를 주고 받을 때 속도 차이를 해결하는 임시 기억 공간
- 펌웨어: 하드웨어의 동작을 지시하는 소프트웨어, 주로ROM에 저장
    - 하드웨어 교체없이 SW 업그레이드로 성능을 높일 수 있다.

보조 기억 장치: 비휘발성, 주기억장치에 비해 속도가 느림, 대용량, 단위당 가격 저렴

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/91451cc6-76fb-4d41-ab05-b2917d1e62f3)

- IDE: 2개, EIDE: 4개, SCSI: 7개, 현재는 SATA방식에 외장형 하드디스크 증가 추세
- 자기디스크 관련 용어
    - 트랙: 동심원, 섹터: 트랙을 일정하게 나눈 구역
    - 실린더: 같은 위치에 있는 트랙의 모임
    - 클러스터: 여러 개의 섹터를 묶은 것, 파일 저장의 기본 단위
    - Access Time: SEEK + SEARCH + Transmission
- RAID: 여러 개 하드디스크를 한 개의 하드디스크처럼 관리하는 방법
    - 미러링: 2개의 디스크에 동일하게 기록
    - 스트라이핑: 나누어서 기록
    - 패리티: 장애 발생 시 패리티 사용으로 복구
- SSD: 충격에 강함(배드섹터 발생 X), 발열-소음-전기가 적게 든다.
    - AHCI: SSD 하드디스크 속도를 높이기 위해 핫 플러그인을 사용할 수 있도록 하는 기술
- 광 디스크: DVD 영화 저장, CD-R: 한번만 기록 가능

입출력 장치

- 입력 장치: OMR(답안지), 디지타이저(설계도면 입력), OCR(공공요금청구서), MICR(수표)
- 출력 장치: 플로터(설계도면 출력), OLED(전류가 흐르면 스스로 빛을 내는)
    - 레이저 프린터: 복사기의 원리
    - 감열 프린터: 감열지에 열을 가해(대기 순번표)
- 표시 장치
    - 해상도(선명도): 픽셀, 화소 수에 따라 결정
    - 주파수 대역폭: 높을수록 눈의 부담이 적어짐(Hz)
    - 화면 주사율: 낮을수록 눈의 피로도가 적다.
    - 점 간격: 숫자가 작을수록 해상도 높아짐
    

기타 장치

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/27aba046-4e3f-41d0-8965-dd8f7a16ec2d)

관련 용어

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/f4d4f96b-3ce3-4374-8718-c08780d48d30)

시스템 소프트웨어(운영 체제, OS)

- 처리 능력 향상, 응답 시간 단축, 사용 가능도 증대, 신뢰도 향상
- 제어 프로그램(감시, 작업 관리, 데이터 관리) _ 처리 프로그램(언어 변역, 서비스, 문제 처리)
    - 발전 단계: 일괄처리>실시간 처리>다중 프로그램>시분할 처리>다중 처리>분산 처리 시슽ㅁ

운영 체제 운영 방식

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/65dbcf36-62fe-43ce-8046-67f86f3f52f6)

언어 번역 과정

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/859e84b3-c2e7-4994-8234-4ce4f9305eb9)

응용 소프트웨어: 특정 업무를 수행할 수 있게 만들어진 앱

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/f2db3319-8cf5-4661-9945-774c1cc9959d)

데이터베이스 관리 시스템(DBMS)

- 중복성, 종속성 문재를 해결하기 위해 제안
- 백업과 회복 절차가 복잡
- 관계형(RDBMS): MS-SQL

소프트웨어 분류

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/27e8ebd1-a25f-403e-bfbb-530f5f5c2d90)

---

# 3. PC 유지 보수

전원 관리 장치

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/ed46d142-00f2-4263-8ace-cfa39dfaf5fd)

PC 에러

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/bb71973a-96fc-4287-abd4-c4f67e99c409)

업그레이드

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/9ee38655-a6ca-45ec-8a55-9deb5064d1a9)

---

# 4. 멀티미디어

멀티미디어

- 텍스트, 그래픽, 사운드 등의 매체를 디지털로 통합
- 디지털화, 쌍방향성, 비선형성, 정보의 통합성

멀티미디어 관련 용어

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/20d193d0-6417-46de-8a1c-7d0ba61fbf12)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/ad741e3f-363c-453c-a5e7-cbc362f32f57)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/56d52243-9001-425f-818c-87f22fca23f5)

---

# 5. 정보 통신/인터넷

통신망 운용 방식

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/df1680bf-f61d-46f8-8ab5-6b789ab17b2f)

통신망의 종류

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/b4b8d561-8ceb-41bb-bbb7-0ae380afc539)

통신망의 구성 형태

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/9d45e092-3f27-47bd-be28-fbb21d7ec430)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/542f15d9-45d9-4cd2-9e2f-f166be10fd2e)

정보 통신 관련 용어

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/b87d6d84-0ca6-43e6-9dde-847599a710e9)

인터넷

- TCP/IP 프로토콜을 사용, 유닉스(UNIX)운영 체제 기반

인터넷 주소

- IPv4: 32비트, 대규모 통신망, E클래스(실험용)
- IPv6: 16비트씩 8부분, 콜론, 16진수, 총 128비트, 유니캐스트(1:1), 멀티캐스트(1:다), 애니캐스트(1:1)
- 도메인 네임: 주소 관리 고유 국내(KRNIC), 전세계(ICANN)
- DNS: 문자 주소를 숫자 주소로 변환하는 기번

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/1f9dc683-c3fb-45ce-bfc2-dd101c777085)

웹 브라우저

- 웹 페이지에 접근하면 http 프로토콜을 이용해 해당 웹 문서를 사용자에게 보여주는 프로그램

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/041ec371-abc4-4757-9fc0-a378d1d65ea7)

인터넷 익스플로러 인터넷 옵션

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/cbaef6d2-b943-4bcd-832e-6657913d4979)

인터넷 관련 용어

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/1dfd875e-54f4-4297-b3f9-703f1df39ba0)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/eb0ace6e-7776-47ea-804e-0113b838c53b)

E-MAIL(전자 우편, 7비트 아스키 코드, ID@호스트주소)

- 전자 우편 프로토콜: SMTP(전송), POP3(수신), MIME
    - 받는 사람에 여러 사람 주소들은 ;를 이용
- 숨은 참조는 수신자 표시 X
- 첨부, 회신, 전달, 동보(동일한 메일 여러 사람한테 전송)

웹 프로그래밍 언어

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/a55e49e6-b34d-4527-90f0-4ddf7dc49d5f)

---

# 6. ICT 신기술

ICT 신기술 관련 용어

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/ad5f1cec-9abf-411f-838a-c2b0bbe20547)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/8ade463d-0c8c-4be8-8dc2-e9f6af58442d)
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/b80864e0-4344-44b9-b2d2-a97ae87164d2)

---

# 7. 정보 사회/보안/개인 정보 보호

정보 사회와 보안

- 다 품종, 소량 시스템으로 변화

정보 사회의 부작용

- 정보의 과다로 인한 혼란과 이에 따른 계층간의 정보 차이 발생
- VDT 증후군: 장시간 모니터를 보면서 생겨나는 증상(불안감)

저작권법

- 저작인접권: 실연자, 음반 제작자, 방송 사업자

저작권 보호 기간(2013년 7월1일부터 시행)

- 저작재산권은 저작자의 사망 후 70년간 존속하는 것이 원칙

보안 위협 형태

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/9003b502-d3ec-4b43-958d-9237c0c51699)

보안 요건

![Untitled (1)](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/589ba868-e3fc-489f-b528-d2f59a52272f)

방화벽: 외부의 불범 침입으로 부터 막아줌

- 역 추적 기능이 있어 외부 침입자의 흔적을 찾을 수 있음

암호화

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/6207aefe-1293-4b18-881c-e3c1daca6fca)

정보 보안 기법

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/1f891940-627a-4f87-a437-fef5bf914736)

보안 프로토콜

![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/142d29df-dfcc-41ed-afdb-98c4aadb3617)

컴퓨터 범죄 예방 및 대책

- 백신의 기능 3가지: 검사, 치료, 예방

바이러스 종류
![image](https://github.com/youjiyeon/Word-Processor-Specialist/assets/57094856/987f5af8-db7d-451b-895b-297d280067df)
