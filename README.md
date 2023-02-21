# medidream-project

## 프로젝트 소개
약 검색을 **자동화 수준**으로 향상 시키기 위한 프로젝트
→ **이미지 인식**으로 간편하게 알아보는 약 정보
- **이약이조 프로젝트 소개**
    
    **기획 배경**
    
    - 현재 국내에서 유통되는 약은 약 22,000가지
    - 정확한 처방전이나 설명서가 없는 경우,
    가정 내 비상약 보관 후 의약품 포장 박스를 분실하거나 지시 사항을 확인하지 못한 경우,
    무분별한 약 복용의 위험성은 오로지 복용하는 환자 몫
    - 현재, 일부 약 검색 지원 사이트가 있으나 세부 사항을 사용자가 일일이 선택, 입력해야 함
    - 이러한 문제점을 해결하고 약 검색 수준을 자동화하기 위한 초석으로 이 프로젝트를 진행함
    
    **서비스 대상**
    
    1. 약사나 의료인의 경우, 회수한 알약을 재 분류하는 작업 진행 시 이용가능
    → 육안 확인으로 인한 오류 최소화
    2. 약 성분 확인이 필요한 이용자
    3. 구비 약품을 구분하려는 이용자
    4. 알약 특징 구분이 어려운 사람들을 대상으로 서비스 필요성 부각
        - 알약 복용 시 부작용 위험이 큰 경우
        - 다수의 알약 복용으로 인해 알약 구분이 필요한 경우
        - 처방 받은 시간이 경과한 뒤, 재복용 하고자 하는 경우
        - 처방전 또는 조제 봉투를 분실한 경우
        
    
    **예상 구현 방향**
    
    1. 알약 이미지 업로드 > 인식 > 해당 약 정보 제공
    2. 로그인 시 > 검색한 알약 정보 저장 기능 제공
    3. 로그인 시 > 폐의약품처리장소 및 위치 정보 제공
<br>

## 개발 기간
22.11.07 ~ 22.12.16

### 맴버 구성
<br>
🤠 **류준현 (팀장)**

- 검색 기록 기능 개발
- 로그인 시큐어 코딩 적용

😀 **서지수**

- 로그인 기능 개발
- Bootstrap 프론트엔드 기능 개발

😎 **이원우 (DE 리더)**

- 검색 기능 개발
- 검색 기능 시큐어 코딩 적용

😀 **이형민**

- 데이터 수집, 전처리
- CNN 모델, VGG16(6:2:2)
- 배경 제거 시도

😎 **이영인 (DS 리더)**

- 데이터 수집, 전처리
- CNN 모델, VGG16(8:1:1)

😀 **이찬미 (서기)**

- 데이터 수집, 전처리
- CNN 모델, ResNet50V
- 글자 추출 시도
