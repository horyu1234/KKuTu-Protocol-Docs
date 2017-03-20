# KKuTu-Protocol-Docs
* 모든 통신 내용은 JSON 으로 이루어져 있습니다.

<br>

<!--
편집시 안내 사항
※ 통신 목록에 존재하는 타입별로 .md 파일을 생성하여 링크를 걸어주세요.
※ 테이블 작성은 http://www.tablesgenerator.com/markdown_tables 를 이용하면, 쉽게 가능합니다.
-->
### 통신 목록
#### Server -> Client

| 타입                                                | 종류              | 대상             |
|-----------------------------------------------------|-------------------|------------------|
| [welcome](/Server%20to%20Client/welcome.md)         | 채널 입장         | 개인             |
| [conn](/Server%20to%20Client/conn.md)               | 채널 입장         | 채널에 있는 모두 |
| [disconn](/Server%20to%20Client/disconn.md)         | 채널 퇴장         | 채널에 있는 모두 |
| [connRoom](/Server%20to%20Client/connRoom.md)       | 방 입장           | 방에 있는 모두   |
| [disconnRoom](/Server%20to%20Client/disconnRoom.md) | 방 퇴장           | 방에 있는 모두   |
| [yell](/Server%20to%20Client/yell.md)               | 공지              | 채널에 있는 모두 |
| [dying](/Server%20to%20Client/dying.md)             | 채널 오류         | 채널에 있는 모두 |
| tail                                                |                   |                  |
| chat                                                |                   |                  |
| roomStuck                                           |                   |                  |
| preRoom                                             |                   |                  |
| room                                                | 방 업데이트       | 채널에 있는 모두 |
| user                                                | 유저 업데이트     | 채널에 있는 모두 |
| friends                                             | 친구 목록         |                  |
| friend                                              |                   |                  |
| friendAdd                                           |                   |                  |
| friendAddRes                                        | 친구 추가 요청    |                  |
| friendEdit                                          |                   |                  |
| starting                                            | 게임 시작 중      |                  |
| [roundReady](/Server%20to%20Client/roundReady.md)   | 라운드 준비       |                  |
| turnStart                                           | 턴 시작           |                  |
| turnError                                           | 턴 오류           |                  |
| turnHint                                            | 턴 힌트           |                  |
| [turnEnd](/Server%20to%20Client/turnEnd.md)         | 턴 종료           |                  |
| roundEnd                                            | 라운드 종료       |                  |
| kickVote                                            | 방 추방 투표 진행 | 방에 있는 모두   |
| kickDeny                                            | 방 추방 투표 부결 | 방에 있는 모두   |
| [invited](/Server%20to%20Client/invited.md)         | 방 초대 수신      | 개인             |
| [inviteNo](/Server%20to%20Client/inviteNo.md)       | 방 초대 거절      | 방의 방장        |
| okg                                                 | 오끄감 버프       | 개인             |
| obtain                                              |                   |                  |
| expired                                             |                   |                  |
| blocked                                             | 임시 기능 차단    | 개인             |
| test                                                |                   |                  |
| error                                               | 오류 발생         |                  |

#### Client -> Server

| 타입                                                  | 종류               |
|-------------------------------------------------------|--------------------|
| yell                                                  | 공지               |
| refresh                                               |                    |
| [talk](/Client%20to%20Server/talk.md)                 | 채팅               |
| friendAdd                                             |                    |
| friendAddRes                                          |                    |
| [friendEdit](/Client%20to%20Server/friendEdit.md)     |                    |
| [friendRemove](/Client%20to%20Server/friendRemove.md) |                    |
| enter                                                 | 방 입장            |
| setRoom                                               | 방 설정            |
| [leave](/Client%20to%20Server/leave.md)               | 방 퇴장            |
| ready                                                 | 게임 준비          |
| [start](/Client%20to%20Server/start.md)               | 게임 시작          |
| practice                                              | 게임 관전          |
| [invite](/Client%20to%20Server/invite.md)             | 방 초대            |
| [inviteRes](/Client%20to%20Server/inviteRes.md)       | 방 초대 결과       |
| form                                                  |                    |
| team                                                  |                    |
| kick                                                  |                    |
| kickVote                                              |                    |
| handover                                              | 방 방장 양도       |
| wp                                                    |                    |
| setAI                                                 | 봇 설정            |
| caj                                                   | 셧다운제 연령 확인 |
| test                                                  |                    |

#### 알 수 없음

| 타입           |
|----------------|
| seek           |
| narrate-friend |
