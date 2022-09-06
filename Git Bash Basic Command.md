 
- Simbol

$ (Prompt) : 명령어를 받아들일 준비가 되어 있다는 기호
/ (Root directory) : 모든 파일/폴더의 최상위 폴더
~ (Home diretory) : 사용자(계정)에게 할당된 폴더
. : 현재 위치한 폴더
.. : 현재 위치한 폴더 기준으로 상위 폴더

 
- Key

Tab : 파일/폴더 이름 자동완성 기능
Ctrl + c (cancel) : 실행중인 프로세스 취소
Ctrl + l (clear) : 터미널 창 정리하기
Shift + Insert : 붙여넣기
↑ ↓ : 이전에 입력한 명령어 기록 탐색

 
- 기본 명령어

pwd : 현재 터미널에서 내 위치 확인
ls : 현재 위치한 폴더 내부의 파일/폴더 출력
ls -a : 현재 위치한 폴더 내부의 모든 파일/폴더 출력 (숨김 파일 포함)
touch <filename> : <filename>으로 파일 생성 (확장자 표기 필수)

$ touch README.md

start <filename> : 파일을 지정된 응용프로그램으로 실행 (GUI의 더블 클릭과 같음, mac에서는 open)

# 계정명 폴더로 이동
$ start .

# 원하는 파일 열기
$ start README.md

rm <filename> : 파일 삭제

$ rm README.md

mkdir <dirname> : <dirname>으로 폴더 생성

$ mkdir practice

cd <dirname> : 지정한 폴더로 이동
cd .. : 현재 위치한 폴더의 상위 폴더로 이동
rm -r <dirname> : 지정한 폴더 및 파일 삭제
rm -rf <dirname> : 지정한 폴더 및 파일 강제(force) 삭제
출처: https://hyunse0.tistory.com/214 [데이터분석_공부기록:티스토리]
