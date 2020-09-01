# 성균관대학교 컴퓨팅사고와SW코딩, 문제해결과 알고리즘 채점용 TDD코드
 
## 개발배경
  성균관대학교에서 2020년 2학기 기준 두번째 조교를 맡고 있는 고준서입니다.
  
  1학기에 매주 최소 80명 가량의 코드를 보고 여러 조건에서 실행해봐야 했습니다.
  
  코드를 채점하는 데에는 30초의 시간밖에 걸리지 않지만 코드를 실행하고 타이핑하는데 1분 이상의 시간이 소모됩니다.
  
  매주 2시간 가량을 채점하고 입력하는데 시간을 소비했습니다.
  
  이런 불필요한 시간소모를 줄이고자 간단하게 코드를 짜봤습니다.
  
  
  다른분이 이미 짜고 사용하시는 중일지도 모르겠지만, 제가 편하게 사용할 수 있도록 개발했습니다.
  
  버전 2로 한화면에 한개의 내용만 보이고 엑셀에 정답인지 오답인지 적을 수 있도록 하는 코드를 추가하고 있습니다.
  
  채점하다가 화나면 완성할 예정이라 언제쯤 될지는 모르겠습니다.
  
  
## 코드 구성
  우선 핵심코드는 TESTING_CODE.py 입니다.
  
  TEST_CASE1과 TEST_CASE2는 두가지 케이스에 대응하기 위해 만들었습니다.
  
  TEST_CASE1은 디렉토리 안에 바로 .py파일이 있는 경우
  
  TEST_CASE2는 디렉토리 안에 학생이름의 폴더가 있고 그 안에 .py이 있는 경우 입니다.
  
  
## TESTING_CODE.py 설명
  이 코드는 2가지 TEST_CASE에 모두 대응하였습니다.
  
  두 케이스 모두 .py파일만 실행하게 되고 다른 확장자는 무시합니다.
  
  별도의 명령어 없이 폴더 내에 아무 파일이나 까봤을 때,
  
  폴더면 하나를 더 열고 .py파일이면 실행하는 식으로 짰습니다.
  
  그렇기 때문에 파일구조가 TEST_CASE 두개 중 하나와는 일치하여야 합니다.
  
  
## 실행방법
  실행방법은 매우 간단합니다.
  
  python3 --data_path TEST_CASE1 
  
  와 같은 방법으로 터미널에서 실행하시면 됩니다.
  
  test_path는 다운받아서 바로 실행해볼 수 있도록 하기 위한 것이고,
  
  실제 사용시에는 본인의 채점파일이 있는 곳의 상대경로를 적어주시길 바랍니다.
  
  윈도우에서 실행방법은 다른분께서 검색해서 알려주시길 바랍니다.(추가하겠습니다)
  
  sta06167@naver.com
  
  
## 유의사항
  두가지 유의사항이 있습니다.
  
  첫번째, 최대한 TEST_CASE와 파일구조를 일치시켜주십시오.
  
  두번째, 컴사, 문알 수업 채점 이외에 본인이 변형하여 사용하였다면, 변형한 파일을 다른 branch를 열어서 테스트 케이스와 함께 공개해주세요.
