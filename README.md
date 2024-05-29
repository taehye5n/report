## top
`top` 명령어는 시스템의 프로세스와 메모리 사용 상태를 실시간으로 보여줍니다.

![top 예시](<img width="662" alt="ex_top" src="https://github.com/taehye5n/report/assets/171117901/b72862bc-022c-42bb-ad81-27b78e4899a1">)

## ps
`ps` 명령어는 현재 실행 중인 프로세스의 스냅샷을 보여줍니다.

| 옵션 | 설명 |
| --- | --- |
| `-e` | 모든 프로세스를 보여줍니다. |
| `-f` | 풀 포맷으로 보여줍니다. |

## jobs
`jobs` 명령어는 현재 쉘 세션에서 실행되고 있는 작업의 목록을 보여줍니다.

- 일시 정지된 작업: `[1]+  Stopped                 command`
- 백그라운드에서 실행 중인 작업: `[2]-  Running                 command &`

## kill
`kill` 명령어는 프로세스에 시그널을 보내어 종료시킵니다.

`kill [옵션] [프로세스ID]`

- `-9`: 강제 종료
