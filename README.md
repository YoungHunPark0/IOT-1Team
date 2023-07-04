# IOT-1Team
주차 및 재해 방재 디지털트윈 시스템 프로젝트
<br>
https://www.notion.so/e4ad059c53e849d2a713452ea5f8ea59

# 프로젝트 배경 및 목적

<aside>
💡 대한민국 전역은 수해로 인해 많은 인명 피해와 재산 피해를 입어왔고, 오늘 날에도 희생자가 나오고 있는 현실이다. 

이에 따라 행정안전부 및 지방자치단체는 침수 방지시설 설치 지원을 위한 조례표준안’을 배포해 수방 시설 설치를 권고, 지원하고 있으며 시설 설치 및 유지·관리를 소홀히 하는 경우에 대한 과태료를 부과하는 바, 차수 시설에 대한 수요는 앞으로 늘어날 것으로 예상된다. 

기존 차수막은 사람이 직접 무거운 시설물을 설치해야 하는 상황으로 우리는 사용자들로 하여금 직관적이고 신속하게 생명과 재산을 보호할 수 있는 시스템을 개발, 안전하고 편리한 지하 주차장 환경을 구성하기 위해 다음과 같이 개발을 진행한다.

</aside>

[아파트 지하주차장 물막이판 설치 의무화](http://www.ksilbo.co.kr/news/articleView.html?idxno=959064)

[서울시, 공동주택 지하주차장 '물막이판' 설치비 지원} | 서울특별시 미디어재단 TBS](http://tbs.seoul.kr/news/newsView.do?typ_800=7&idx_800=3491771&seq_800=20484474)

---

# 1. 지하주차장 방재 디지털트윈 시스템

### 실물 모형 제작

해당 지역은 부산광역시 연제구로 과거 침수 이력이 있는 지하주차장을 소형화 하여 제작

- 주차장 구현 - 라즈베리파이 기반
    - 엘리베이터
    - 번호판 인식, 출입구 차단
        - 카메라 모듈,  스탭 or DC 모터
    - 환기, 조명
        - 미세먼지 센서
    - 차수 및 배수
        - 워터펌프
        - 리니어 엑츄레이터 - 차수막
    - 주차장 현황 -  전용 주차 공간 및 빈자리 관리, 침수 데이터 수집
        - NFC 모듈, (비)접촉식 수위센서

# 2. DB 서버

### 입주 정보

- 입주 현황 - 차량 정보, 출입 정보
- 주차장 요금 결제

### OPEN API

- 하천 수위 및 침수 흔적도
- 예상 강수량

### 기상청 강수량 데이터

- 예상 강수량, 과거 강수량

# 3. 디지털트윈 시스템

### 유니티

- 관리자 메인 윈도우
    - 주차장 현황
    - 3D Map - 외부 하천 CCTV, 시뮬레이션, 재난 대비 안내
    - 시설 관리 - [환기]
    - 출입구 차단
    - 방수 및 배수
    - 입주자 안전 문자 발송 서비스

# 4. 편의 기능

### 아파트 어플리케이션

- 주차장 빈자리 예약 시스템
- 내 차량 위치 확인
- 전기차 충전 예약
- 아파트 커뮤니티, CCTV
- 미세먼지 / 대기질 정보

## 🚀  Stacks

---

<aside>
<img src="https://blog.kakaocdn.net/dn/bTslSR/btqS1WFdn35/T3AOCIr0VjKJ9kPiXneDU1/img.png" alt="https://blog.kakaocdn.net/dn/bTslSR/btqS1WFdn35/T3AOCIr0VjKJ9kPiXneDU1/img.png" width="40px" /> **C**

</aside>

<aside>
<img src="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/433b4146-2213-4ec9-a945-9fec8057e6bd/free-icon-c-sharp-6132221.png" alt="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/433b4146-2213-4ec9-a945-9fec8057e6bd/free-icon-c-sharp-6132221.png" width="40px" /> **C#**

</aside>

<aside>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHLN0RrPTmNUSMhl6MTeX0p_uIIj6Qzoxok9gjmzjELFRCeJaN34K8nOSaG56rrrw-evQ&usqp=CAU" alt="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHLN0RrPTmNUSMhl6MTeX0p_uIIj6Qzoxok9gjmzjELFRCeJaN34K8nOSaG56rrrw-evQ&usqp=CAU" width="40px" /> **Python**

</aside>

## 🛠  Tools

---

<aside>
**Unity**

</aside>

<aside>
**Git**

</aside>

<aside>
**MySQL**

</aside>

## 👥  Collaboration

---

<aside>
**GitHub**

</aside>

<aside>
**Notion**

</aside>

<aside>
**Kakao Talk**

</aside>

<aside>
**Figma**

</aside>

<aside>
**Google Drive**

</aside>

## 5. 예상 부품

- 아크릴판 (가내수공업)
- 경고용 스피커 : 밖 1개 , 안 1~2 개 (주차 잘못했을 때 안내)
- 차수막 (수직)
- 자동차 모형 사용 , 번호판
- 센서 종류
    - 카메라 3 대(출입구<1대>, cctv<2대>)
    - 빈자리 인식 : 거리 센서 (당연함)
    - 차 위치 찾기 : NFC 센서(전기차 충전과 일반 주차장 각 1개)
    - 미세먼지 : 미세먼지 센서(환기팬)
    - 수위 센서 : 입구(비접촉식)/ 안쪽(접촉식)
- 액츄레이터 : 리니어 엑츄레이터
- 릴레이 : 좀 더 알아봐야함 (모터땜시)
- 배수 - 워터펌프 (한계치 찼을때)
- 조명 : 지하주차장 당연한 부품(LED=싼거)
- 모터(출입구) : 스텝모터
- 엘리베이터: DC 모터 (이미 o)
    - 자석 홀센서
    - 스위치
    - 서보모터
