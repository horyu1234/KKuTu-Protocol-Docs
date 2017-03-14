# KKuTu-Protocol-Docs
* 모든 통신 내용은 JSON 으로 이루어져 있습니다.

<br>

<!--
편집시 안내 사항
※ 통신 목록에 존재하는 타입별로 .md 파일을 생성하여 링크를 걸어주세요.
※ 테이블 작성은 http://www.tablesgenerator.com/markdown_tables 를 이용하면, 쉽게 가능합니다.
-->
### 통신 목록
| 방향             | 타입           | 종류              | 대상             |
|------------------|----------------|-------------------|------------------|
| Server -> Client | welcome        | 채널 입장         | 개인             |
| Server -> Client | conn           | 채널 입장         | 채널에 있는 모두 |
| Server -> Client | disconn        | 채널 퇴장         | 채널에 있는 모두 |
| Server -> Client | connRoom       | 방 입장           | 방에 있는 모두   |
| Server -> Client | disconnRoom    | 방 퇴장           | 방에 있는 모두   |
| Server -> Client | yell           | 공지              | 채널에 있는 모두 |
| Server -> Client | dying          | 채널 오류         | 채널에 있는 모두 |
| Server -> Client | tail           |                   |                  |
| Server -> Client | chat           |                   |                  |
| Server -> Client | roomStuck      |                   |                  |
| Server -> Client | preRoom        | 방 생성           | 개인             |
| Server -> Client | room           |                   |                  |
| Server -> Client | user           | 유저 설정         |                  |
| Server -> Client | friends        | 친구 목록         |                  |
| Server -> Client | friend         |                   |                  |
| Server -> Client | friendAdd      |                   |                  |
| Server -> Client | friendAddRes   | 친구 추가 요청    |                  |
| Server -> Client | friendEdit     |                   |                  |
| Server -> Client | starting       | 게임 시작 중      |                  |
| Server -> Client | roundReady     | 라운드 준비       |                  |
| Server -> Client | turnStart      | 턴 시작           |                  |
| Server -> Client | turnError      | 턴 오류           |                  |
| Server -> Client | turnHint       | 턴 힌트           |                  |
| Server -> Client | turnEnd        | 턴 종료           |                  |
| Server -> Client | roundEnd       | 라운드 종료       |                  |
| Server -> Client | kickVote       | 방 추방 투표 진행 | 방에 있는 모두   |
| Server -> Client | kickDeny       | 방 추방 투표 부결 | 방에 있는 모두   |
| Server -> Client | invited        | 방 초대 수신      | 개인             |
| Server -> Client | inviteNo       | 방 초대 거절      | 방의 방장        |
| Server -> Client | okg            | 오끄감 버프       | 개인             |
| Server -> Client | obtain         |                   |                  |
| Server -> Client | expired        |                   |                  |
| Server -> Client | blocked        | 임시 기능 차단    | 개인             |
| Server -> Client | test           |                   |                  |
| Server -> Client | error          | 오류 발생         |                  |
| Client -> Server | yell           |                   |                  |
| Client -> Server | refresh        |                   |                  |
| Client -> Server | talk           |                   |                  |
| Client -> Server | friendAdd      |                   |                  |
| Client -> Server | friendAddRes   |                   |                  |
| Client -> Server | friendEdit     |                   |                  |
| Client -> Server | friendRemove   |                   |                  |
| Client -> Server | enter          |                   |                  |
| Client -> Server | setRoom        |                   |                  |
| Client -> Server | leave          |                   |                  |
| Client -> Server | ready          |                   |                  |
| Client -> Server | start          |                   |                  |
| Client -> Server | practice       |                   |                  |
| Client -> Server | invite         |                   |                  |
| Client -> Server | inviteRes      |                   |                  |
| Client -> Server | form           |                   |                  |
| Client -> Server | team           |                   |                  |
| Client -> Server | kick           |                   |                  |
| Client -> Server | kickVote       |                   |                  |
| Client -> Server | handover       |                   |                  |
| Client -> Server | wp             |                   |                  |
| Client -> Server | setAI          |                   |                  |
| Client -> Server | caj            |                   |                  |
| Client -> Server | test           |                   |                  |
|                  | seek           |                   |                  |
|                  | narrate-friend |                   |                  |
