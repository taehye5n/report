## top
`top` 명령어는 실행 중인 프로세스와 시스템 자원 사용 현황을 실시간 보여줌. 리눅스의 작업관리자 느낌

<img width="746" alt="top" src="https://github.com/taehye5n/report/assets/171117901/d0cd2d68-3e3b-423b-a6de-5441de44e866">

| 옵션  | 설명 |
|-------|------|
| `-n`  | 종료하기 전에 업데이트할 횟수를 지정 |
| `-b`  | 비대화형 모드로 `top`을 실행 |
| `-d`  | 업데이트 사이의 지연 시간을 초 단위로 설정 |

## ps
`ps` 명령어는 현재 실행 중인 프로세스에 대한 정보를 표시

<img width="637" alt="스크린샷 2024-05-29 153619" src="https://github.com/taehye5n/report/assets/171117901/6d078793-fe34-405e-8ce6-ddef4051a178">

| 옵션   | 설명 |
|--------|------|
| `-e`   | 모든 프로세스를 보여줌 |
| `-f`   | 풀 포맷으로 보여줌 |
| `-u`   | 특정 사용자가 소유한 프로세스를 표시 |
| `-aux` | 모든 사용자의 모든 프로세스에 대한 자세한 정보를 표시 |

## jobs
`jobs` 명령어는 현재 쉘 세션에서 실행 중이거나 중지된 작업을 보여줌.

<img width="443" alt="jobs" src="https://github.com/taehye5n/report/assets/171117901/ff43cd92-2a6e-4c81-bfd0-74ce5cce353e">

| 옵션  | 설명 |
|-------|------|
| `-l`  | 작업과 함께 프로세스 그룹 ID(PGID)를 표시 |
| `-n`  | 상태가 변경된 작업만 표시|
| `-p`  | 각 작업의 프로세스 ID(PID)만 출력|

- 일시 정지된 작업: `[1]+  Stopped                 command`
- 백그라운드에서 실행 중인 작업: `[2]-  Running                 command &`

## kill
`kill` 명령어는 프로세스에 시그널을 보내어 종료

<img width="596" alt="image" src="https://github.com/taehye5n/report/assets/171117901/71ceca53-0524-4f43-b3c5-51b1c3bb4760">

| 옵션  | 설명 |
|-------|------|
| `-9`  | SIGKILL 신호를 보내 강제로 프로세스를 종료 |
| `-15` | SIGTERM 신호를 보내며, 이는 기본 종료 신호, 안전하게 종료 가능 |
| `-l`  | 사용 가능한 모든 신호 이름을 나열함 |

`kill [옵션] [프로세스ID]`

