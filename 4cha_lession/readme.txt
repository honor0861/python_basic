자료실
http://192.168.0.119/
수업 타입테이블
오전수업
09:00~09:50
10:00~10:50
11:00~11:50
점심(50분)
11:50~12:40
오후수업
12:40~13:30
13:40~14:30
14:40~15:30
15:40~16:30
16:40~17:30

----------------------------------------------
전체 과정
1. 개요
 - 파이썬을 기반
 - 데이터 분석(통계적, 시각적), 수집, 전처리등등.
 - 머신러닝, 딥러닝 =>  AI분야(한가지만 잘하는)
   -> nvidia vs amd
   -> nvidia의 cupa가 윈도우와 리눅스 지원(맥은 배제)
 - 빅데이터 처리 => 하둡 클러스터 ~ 시스템,...
 - 파이널 프로젝트

2. 개발 환경
 - OS : window(현재), macos, linux
 - python : 
        - 버전
          - 2.7 <- 맥 기본 설치 버전, 리눅스 기본설치버전
          - 3.x <- 개발 (3.7 or 3.6), 항상 최신버전이 
                     좋은것은 아니다(다른 지원여부 체크) 
        - 설치
          - python.org (파이썬만 깔린다, 가볍다)
            -> 현재 PC에 3.7을 깔았다 => 3.5 필요하다?
                지우고깔아야 한다!!
          - 한 PC에서 여러 버전을 쓸수 있다면
            -> 가상환경을 구축해서 각각 영향을 주지 않고 사용
            -> 이런 요구사항을 간편히 수행할수 있는 
                풀패키지 인스톨러 -> anaconda
            -> https://www.anaconda.com/
            -> 아나콘다의 라이트버전(커맨드 버전)
                miniconda
 - IDE: 개발통합환경
         - 전용툴 :  python IDE(불편), 파이참(무겁다),  
                       파이데브, 스파이더, 
                       jupyter notebook(아주중요)->브라우저코딩
                        L ipython(커맨드스타일 분석툴)+웹(flask)
         - 범용툴 : 기존의 개발환경+ 플러그인 추가
                      vs code + python + anaconda + jupyter
 - 공정관리
         - github.com/ 회원가입 및 대학생이면 인증(차후)
           - 대학생 혜택(private 기능 무료 사용)
             https://limetimeline.tistory.com/277
         - 개발  PC에 git 설치 
           https://git-scm.com/download/win

3. 설치
 - anaconda -> git -> vs code 순으로 
   서로 상관없음
 - 아나콘다 경로
   C:\Users\a\Anaconda3
   Anvanced Options에서 path 체크 할것(주의)

4. vs code 설정
 - 프로젝트를 원하는 위치에 폴더 생성
   - python_projects
   - 해당 폴더를 드레그 해서, vs code에 드롭
   - 해당 위치로 vs code 재오픈
- 에디터 설정
   - File > preferecnces > settings
   - 검색(인덱싱) > 항목 찾아서 수정
      thema > Color Theme > Default Light +
      font > 수치 조정
      전체 줌 ctrl + or ctrl -
      termianl > font 조정(필요하면)
   - 왼쪽 메뉴
      - file exploper
      - 검색, 대체
      - 공정관리:소스 컨트롤
      - 디버깅(코드가 오류가 있을때 잡는 방법)
      - 플러그인 검색 및 설치
   - 파이썬을 설치한 후에 파이썬 파일 한개를 생성하면
      - ./basic/p1.py
      - vs code가 해당 파일을 인식하고, python 경로를 잡거나
        extention을 설치하라고 유도
        -> vs code  재가동
        -> 왼쪽 메뉴 5번째 extentions 항목에서 python 검색
           python, python for vs code, python extention pack
           설치   
     




