# KKuTu-Protocol-Docs
* 모든 통신 내용은 JSON 으로 이루어져 있습니다.

<br>

<!--
편집시 안내 사항
※ 통신 목록에 존재하는 타입별로 .md 파일을 생성하여 링크를 걸어주세요.
※ 테이블 작성은 http://www.tablesgenerator.com/markdown_tables 를 이용하면, 쉽게 가능합니다.
-->
### 통신 목록
| 방향             | 타입           | 행동      | 대상             |
|------------------|----------------|-----------|------------------|
| Server -> Client | welcome        | 채널 입장 | 개인             |
| Server -> Client | conn           | 채널 입장 | 채널에 있는 모두 |
| Server -> Client | disconn        | 채널 퇴장 | 채널에 있는 모두 |
| Server -> Client | connRoom       | 방 입장   | 방에 있는 모두   |
| Server -> Client | disconnRoom    | 방 퇴장   | 방에 있는 모두   |
| Server -> Client | yell           |           |                  |
| Server -> Client | dying          |           |                  |
| Server -> Client | tail           |           |                  |
| Server -> Client | chat           |           |                  |
| Server -> Client | roomStuck      |           |                  |
| Server -> Client | preRoom        |           |                  |
| Server -> Client | room           |           |                  |
| Server -> Client | user           |           |                  |
| Server -> Client | friends        |           |                  |
| Server -> Client | friend         |           |                  |
| Server -> Client | friendAdd      |           |                  |
| Server -> Client | friendAddRes   |           |                  |
| Server -> Client | friendEdit     |           |                  |
| Server -> Client | starting       |           |                  |
| Server -> Client | roundReady     |           |                  |
| Server -> Client | turnStart      |           |                  |
| Server -> Client | turnError      |           |                  |
| Server -> Client | turnHint       |           |                  |
| Server -> Client | turnEnd        |           |                  |
| Server -> Client | roundEnd       |           |                  |
| Server -> Client | kickVote       |           |                  |
| Server -> Client | kickDeny       |           |                  |
| Server -> Client | invited        |           |                  |
| Server -> Client | inviteNo       |           |                  |
| Server -> Client | okg            |           |                  |
| Server -> Client | obtain         |           |                  |
| Server -> Client | expired        |           |                  |
| Server -> Client | blocked        |           |                  |
| Server -> Client | test           |           |                  |
| Server -> Client | error          |           |                  |
| Client -> Server | yell           |           |                  |
| Client -> Server | refresh        |           |                  |
| Client -> Server | talk           |           |                  |
| Client -> Server | friendAdd      |           |                  |
| Client -> Server | friendAddRes   |           |                  |
| Client -> Server | friendEdit     |           |                  |
| Client -> Server | friendRemove   |           |                  |
| Client -> Server | enter          |           |                  |
| Client -> Server | setRoom        |           |                  |
| Client -> Server | leave          |           |                  |
| Client -> Server | ready          |           |                  |
| Client -> Server | start          |           |                  |
| Client -> Server | practice       |           |                  |
| Client -> Server | invite         |           |                  |
| Client -> Server | inviteRes      |           |                  |
| Client -> Server | form           |           |                  |
| Client -> Server | team           |           |                  |
| Client -> Server | kick           |           |                  |
| Client -> Server | kickVote       |           |                  |
| Client -> Server | handover       |           |                  |
| Client -> Server | wp             |           |                  |
| Client -> Server | setAI          |           |                  |
| Client -> Server | caj            |           |                  |
| Client -> Server | test           |           |                  |
|                  | seek           |           |                  |
|                  | narrate-friend |           |                  |
