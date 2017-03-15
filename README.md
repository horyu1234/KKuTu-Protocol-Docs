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

| 타입         | 종류              | 대상             |
|--------------|-------------------|------------------|
| welcome      | 채널 입장         | 개인             |
| conn         | 채널 입장         | 채널에 있는 모두 |
| disconn      | 채널 퇴장         | 채널에 있는 모두 |
| connRoom     | 방 입장           | 방에 있는 모두   |
| disconnRoom  | 방 퇴장           | 방에 있는 모두   |
| yell         | 공지              | 채널에 있는 모두 |
| dying        | 채널 오류         | 채널에 있는 모두 |
| tail         |                   |                  |
| chat         |                   |                  |
| roomStuck    |                   |                  |
| preRoom      |            |              |
| room         |                   |                  |
| user         | 유저 설정         |                  |
| friends      | 친구 목록         |                  |
| friend       |                   |                  |
| friendAdd    |                   |                  |
| friendAddRes | 친구 추가 요청    |                  |
| friendEdit   |                   |                  |
| starting     | 게임 시작 중      |                  |
| roundReady   | 라운드 준비       |                  |
| turnStart    | 턴 시작           |                  |
| turnError    | 턴 오류           |                  |
| turnHint     | 턴 힌트           |                  |
| turnEnd      | 턴 종료           |                  |
| roundEnd     | 라운드 종료       |                  |
| kickVote     | 방 추방 투표 진행 | 방에 있는 모두   |
| kickDeny     | 방 추방 투표 부결 | 방에 있는 모두   |
| invited      | 방 초대 수신      | 개인             |
| inviteNo     | 방 초대 거절      | 방의 방장        |
| okg          | 오끄감 버프       | 개인             |
| obtain       |                   |                  |
| expired      |                   |                  |
| blocked      | 임시 기능 차단    | 개인             |
| test         |                   |                  |
| error        | 오류 발생         |                  |

#### Client -> Server

| 타입           | 종류               |
|----------------|--------------------|
| yell           | 공지               |
| refresh        |                    |
| talk           | 채팅               |
| friendAdd      |                    |
| friendAddRes   |                    |
| friendEdit     |                    |
| friendRemove   |                    |
| enter          | 방 입장            |
| setRoom        | 방 설정            |
| leave          | 방 퇴장            |
| ready          | 게임 준비          |
| start          | 게임 시작          |
| practice       | 게임 관전          |
| invite         | 방 초대            |
| inviteRes      | 방 초대 결과       |
| form           |                    |
| team           |                    |
| kick           |                    |
| kickVote       |                    |
| handover       | 방 방장 양도       |
| wp             |                    |
| setAI          | 봇 설정            |
| caj            | 셧다운제 연령 확인 |
| test           |                    |

#### 알 수 없음

| 타입           |
|----------------|
| seek           |
| narrate-friend |

<!--
| 방향             | 타입           | 종류               | 대상             |
|------------------|----------------|--------------------|------------------|
| Server -> Client | welcome        | 채널 입장          | 개인             |
| Server -> Client | conn           | 채널 입장          | 채널에 있는 모두 |
| Server -> Client | disconn        | 채널 퇴장          | 채널에 있는 모두 |
| Server -> Client | connRoom       | 방 입장            | 방에 있는 모두   |
| Server -> Client | disconnRoom    | 방 퇴장            | 방에 있는 모두   |
| Server -> Client | yell           | 공지               | 채널에 있는 모두 |
| Server -> Client | dying          | 채널 오류          | 채널에 있는 모두 |
| Server -> Client | tail           |                    |                  |
| Server -> Client | chat           |                    |                  |
| Server -> Client | roomStuck      |                    |                  |
| Server -> Client | preRoom        | 방 생성            | 개인             |
| Server -> Client | room           |                    |                  |
| Server -> Client | user           | 유저 설정          |                  |
| Server -> Client | friends        | 친구 목록          |                  |
| Server -> Client | friend         |                    |                  |
| Server -> Client | friendAdd      |                    |                  |
| Server -> Client | friendAddRes   | 친구 추가 요청     |                  |
| Server -> Client | friendEdit     |                    |                  |
| Server -> Client | starting       | 게임 시작 중       |                  |
| Server -> Client | roundReady     | 라운드 준비        |                  |
| Server -> Client | turnStart      | 턴 시작            |                  |
| Server -> Client | turnError      | 턴 오류            |                  |
| Server -> Client | turnHint       | 턴 힌트            |                  |
| Server -> Client | turnEnd        | 턴 종료            |                  |
| Server -> Client | roundEnd       | 라운드 종료        |                  |
| Server -> Client | kickVote       | 방 추방 투표 진행  | 방에 있는 모두   |
| Server -> Client | kickDeny       | 방 추방 투표 부결  | 방에 있는 모두   |
| Server -> Client | invited        | 방 초대 수신       | 개인             |
| Server -> Client | inviteNo       | 방 초대 거절       | 방의 방장        |
| Server -> Client | okg            | 오끄감 버프        | 개인             |
| Server -> Client | obtain         |                    |                  |
| Server -> Client | expired        |                    |                  |
| Server -> Client | blocked        | 임시 기능 차단     | 개인             |
| Server -> Client | test           |                    |                  |
| Server -> Client | error          | 오류 발생          |                  |
| Client -> Server | yell           | 공지               |                  |
| Client -> Server | refresh        |                    |                  |
| Client -> Server | talk           | 채팅               |                  |
| Client -> Server | friendAdd      |                    |                  |
| Client -> Server | friendAddRes   |                    |                  |
| Client -> Server | friendEdit     |                    |                  |
| Client -> Server | friendRemove   |                    |                  |
| Client -> Server | enter          | 방 입장            |                  |
| Client -> Server | setRoom        | 방 설정            |                  |
| Client -> Server | leave          | 방 퇴장            |                  |
| Client -> Server | ready          | 게임 준비          |                  |
| Client -> Server | start          | 게임 시작          |                  |
| Client -> Server | practice       | 게임 관전          |                  |
| Client -> Server | invite         | 방 초대            |                  |
| Client -> Server | inviteRes      | 방 초대 결과       |                  |
| Client -> Server | form           |                    |                  |
| Client -> Server | team           |                    |                  |
| Client -> Server | kick           |                    |                  |
| Client -> Server | kickVote       |                    |                  |
| Client -> Server | handover       | 방 방장 양도       |                  |
| Client -> Server | wp             |                    |                  |
| Client -> Server | setAI          | 봇 설정            |                  |
| Client -> Server | caj            | 셧다운제 연령 확인 |                  |
| Client -> Server | test           |                    |                  |
|                  | seek           |                    |                  |
|                  | narrate-friend |                    |                  |
-->
