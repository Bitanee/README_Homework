# 📋 README_Homework
23.05.22 과제(깃헙 README 페이지 만들기)
---
<p align="center">
  <img src="https://github.com/Bitanee/README_Homework/assets/97078968/d68902cd-46e8-4457-88eb-3ef67c487c62">
</p>

<img src="https://img.shields.io/badge/C언어-A8B9CC?style=flat&logo=c&logoColor=white"/>

**리눅스 명령어 중에서 top, ps, jobs, kill 명령어에 대해서 조사해보자!**

>top: 시스템 프로세스/메모리 사용 현황을 실시간으로 출력한다.

>ps : 현재 실행중인 프로세스를 보여주는 리눅스 명령어

|명령어|설명|
|------|:---:|
|r|현재 실행중인 프로세서를 보여준다.|
|S|20초 미만으로 짧게 잠든다.|
|D|디스크 입출력 대기 같은 인터럽트할 수 없는 대기상태|
|T|일시 정지|
|Z|좀비(zombi) 프로세서|
- 좀비(zomb) 상태라는 것은 프로세서가 사라질 때 시그널 처리의 문제로 완전히 소멸되지 못한 상태를 말한다.
대개는 _aux 옵션을 많이 사용한다. 이 중 필요한 프로세스에 대한 결과만 선택적으로
보고자 한다면 grep 명령을 같이 사용한다. 
	1. e : 모든 프로세스를 보여 줍니다
	2. i : 상세내역을 보여준다.
	3. ef : 모든 프로세스의 모든정보

>jobs : 작업이 중지된 상태나 백그라운드로 진행 중인 상태를 표시.

>kill : 프로세스에 종료 시그널을 보낸다.(-9는 강제 종료)
	ps로 확인한 PID값으로 죽일 수 있다.
	(kill -PID값)<br>
killall : 프로세스 이름으로 종료하는 명령어.

🙏🙏
