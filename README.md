# ProDS_asso

- 실습 코드 공유 공간입니다.
- 시험 관련 정보: (멀티캠퍼스 자격검정 서비스) https://certi.multicampus.com/main
  
  □ Python
    - 윈도우 64bit, python 3.7.4 기반 jupyter notebook 환경
    - 전체 패키지 목록 : requirements_py.txt

  □ python 시험 버전(3.7.4) 다운로드 링크
    - [파이썬 설치] https://www.python.org/downloads/ 접속 -> Python 3.7.4 (July 8, 2019) 다운로드 후 설치
    - [아나콘다 설치] https://repo.anaconda.com/archive/ 접속 -> (윈도우 64bit 기준) Anaconda3-2019.10-Windows-x86_64.exe 다운로드 후 설치
    - [VS Code 설치] https://code.visualstudio.com/download (필요할 경우 다운로드)
   
  □ 설치 패키지 목록 활용하여 시험 환경 구성
   > pip install -r requirements_py.txt
   
  □ 주피터 노트북 바탕화면에 바로가기 아이콘 만들기
   1. 마우스 우클릭하여 나타나는 메뉴에서 [새로 만들기(W)] > [바로가기(S)] 메뉴 선택
   2. "항목 위치 입력(T)" 아래에 위치한 입력칸에 주피터 노트북 실행 명령어 입력
      - 다음 명령어 입력 방법 중 택일
      - 기본 : cmd /k jupyter notebook
      - 워킹디렉토리 지정 후 작동: cmd /k cd {주피터 노트북 기준 경로} & jupyter notebook
        - (예시) cmd /k cd C:\Users\{사용자명}\Documents & jupyter notebook 
