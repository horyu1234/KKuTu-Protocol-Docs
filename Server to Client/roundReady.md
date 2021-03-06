* 본 패킷 타입은 게임 타입에 따라 JSON 내용이 달라집니다.

## classic
```json
{  
   "round":1,
   "char":"계",
   "mission":null,
   "profile":{  },
   "type":"roundReady"
}
```
| 종류    | 타입    | 설명             | 비고              |
|---------|---------|------------------|-------------------|
| round   | Integer | 시작하는 라운드  |                   |
| char    | String  | 시작하는 글자    |                   |
| subChar | String  | 대체 가능한 글자 | 없을 시 표시 안함 |
| mission | String  | 미션 글자        | 없을 시 null      |
| profile | JSON    | 대상 프로필      |                   |
| type    | String  | 패킷 타입        |                   |


## crossword
```json
{  
   "seq":[  ],
   "profile":{  },
   "type":"roundReady"
}
```
| 종류    | 타입   | 설명        | 비고 |
|---------|--------|-------------|------|
| seq     |        |             |      |
| profile | JSON   | 대상 프로필 |      |
| type    | String | 패킷 타입   |      |

## daneo
```json
{  
   "round":1,
   "theme":"90",
   "mission":null,
   "profile":{  },
   "type":"roundReady"
}
```
| 종류    | 타입    | 설명               | 비고         |
|---------|---------|--------------------|--------------|
| round   | Integer | 시작하는 라운드    |              |
| theme   | String  | 시작하는 주제 번호 |              |
| mission | String  | 미션 글자          | 없을 시 null |
| profile | JSON    | 대상 프로필        |              |
| type    | String  | 패킷 타입          |              |

## hunmin
```json

```
| 종류    | 타입    | 설명            | 비고         |
|---------|---------|-----------------|--------------|
| round   | Integer | 시작하는 라운드 |              |
| theme   | String  | 시작하는 주제   |              |
| mission | String  | 미션 글자       | 없을 시 null |
| profile | JSON    | 대상 프로필     |              |
| type    | String  | 패킷 타입       |              |

## jaqwi
```json
{  
   "round":1,
   "theme":"ᄉᄂ",
   "mission":null,
   "profile":{  },
   "type":"roundReady"
}
```
| 종류    | 타입    | 설명            | 비고         |
|---------|---------|-----------------|--------------|
| round   | Integer | 시작하는 라운드 |              |
| theme   | String  | 시작하는 주제   |              |
| profile | JSON    | 대상 프로필     |              |
| type    | String  | 패킷 타입       |              |

## sock
```json
{  
   "round":1,
   "board":"기뜯줄악기바　구리휼방어좌신사소설학조송명음후멸환반전엽갈치제성음출후노확활리지주국수초충행충불휼　가산력　당랑후쉬쟁물량엽바방",
   "profile":{  },
   "type":"roundReady"
}
```
| 종류    | 타입    | 설명            | 비고 |
|---------|---------|-----------------|------|
| round   | Integer | 시작하는 라운드 |      |
| board   |         | 보드 판         |      |
| profile | JSON    | 대상 프로필     |      |
| type    | String  | 패킷 타입       |      |

## typing
```json
{  
   "round":1,
   "list":[  
      "미사키하나",
      "씨레오",
      "깝질무",
      "씨근벌떡",
      "안락사",
      "블루머쉬맘",
      "마틸다",
      "마탐정로키",
      "워해머",
      "맘박쥐",
      "윈드스니커",
      "밴시의장막",
      "섀도어",
      "서동요",
      "베베데빌",
      "워스트",
      "야나프",
      "요한나",
      "미쓰에이",
      "빛의정의",
      "야생의징표",
      "제레온",
      "산화탄소",
      "바닐프티",
      "수호자의눈",
      "사악한일격",
      "자리다툼",
      "비버니",
      "전툴라",
      "벨렌의선택",
      "달샤벳",
      "아트록스",
      "벨제바브",
      "사치코",
      "이즈모",
      "상항",
      "에레키블",
      "오하라마리",
      "아무리",
      "엘풍",
      "앨리셔",
      "바닐프티",
      "귀뚤톡크",
      "서머엔드롤",
      "요르문간드",
      "전력질주",
      "만걸",
      "맘복치",
      "완철포",
      "사이퍼즈",
      "덴카",
      "브툼",
      "미사키하나",
      "안궁",
      "도롱마담",
      "바닐리치",
      "솔리드",
      "수신연무",
      "바랜드",
      "리오르",
      "보르그",
      "마키아",
      "번개폭풍",
      "괴물의아이",
      "무쿠로",
      "블로스터",
      "샤로다",
      "달막화",
      "격노수호병",
      "빅터",
      "샤미드",
      "우뿌",
      "그리프",
      "바미의불씨",
      "뽀스락",
      "샹델라",
      "오하라마리",
      "우뿌",
      "이즈모",
      "블록골렘",
      "타이니팜",
      "바다이야기",
      "브리가론",
      "야느와르몽",
      "선왕",
      "별빛섬광",
      "나룸퍼프",
      "이즈모",
      "정신붕괴",
      "세나리우스",
      "디엔엔젤",
      "거인학살자",
      "슬레이어즈",
      "머쉬맘",
      "시티즌",
      "식령",
      "왕도둑징",
      "열외",
      "배틀메이지",
      "머쉬맘",
      "별빛섬광",
      "섀도어",
      "걸즈브라보",
      "달빛섬광",
      "빨강머리앤",
      "사이퍼즈",
      "마리갈리",
      "암트르",
      "사향소",
      "데몬어벤저",
      "주니어부기",
      "윈드러너",
      "닥터슬럼프",
      "비조도",
      "용의아들",
      "씨레오",
      "안녕로봇",
      "달빛섬광",
      "곡궁",
      "윈드러너",
      "예티",
      "에레키드",
      "오닉시아",
      "서머엔드롤",
      "탐식의망치",
      "얼음송곳니",
      "버키와투투",
      "야나프",
      "절각참",
      "샤크",
      "에레키블",
      "상벌",
      "리티",
      "블랙펄",
      "앤티골",
      "사자에상",
      "시오미슈코",
      "시야석",
      "유우키안쥬",
      "건그레이브",
      "트루티어즈",
      "유유시키",
      "샤미드",
      "스티지",
      "엠페르트",
      "마틴",
      "빅터",
      "야나키",
      "데스마스",
      "블루와이번",
      "아트록스",
      "블랙라군",
      "제이나",
      "윌라드",
      "엘풍",
      "서풍의신령",
      "아만츄",
      "워스트",
      "샬럿",
      "바닐리치",
      "시크릿",
      "세나리우스",
      "용임",
      "서동요",
      "실토",
      "야느와르몽",
      "리티",
      "입회",
      "유우키안쥬",
      "유유시키",
      "윈드러너",
      "씨레오",
      "야느와르몽",
      "블루머쉬맘",
      "염화벤젠",
      "얼음방패",
      "워스트",
      "귀부시리즈",
      "불카모스",
      "괴물의아이",
      "북두의권",
      "수왕성",
      "적룡왕",
      "이블",
      "더블에이",
      "밴시의장막",
      "열정의검",
      "네코아츠메",
      "영웅의일격",
      "아트록스",
      "샤코",
      "마틸다",
      "임연",
      "심판관",
      "킬미베이비",
      "아이바유미",
      "샤크",
      "전툴라",
      "워해머",
      "아비아나"
   ],
   "profile":{  },
   "type":"roundReady"
}
```
| 종류    | 타입    | 설명            | 비고 |
|---------|---------|-----------------|------|
| round   | Integer | 시작하는 라운드 |      |
| list    | Array   | 단어/속담 목록  |      |
| profile | JSON    | 대상 프로필     |      |
| type    | String  | 패킷 타입       |      |
