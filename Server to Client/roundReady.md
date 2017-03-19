
```json
{  
   "round":3,
   "char":"고",
   "mission":null,
   "profile":{  
      "type":"naver",
      "id":"127680890",
      "name":"anonymous",
      "title":"박예성",
      "image":"https://ssl.pstatic.net/static/pwe/address/img_profile.png"
   },
   "type":"roundReady"
}
```

| 종류    | 타입 | 설명            | 비고                     |
|---------|------|-----------------|--------------------------|
| round   | Integer | 시작하는 라운드 |                          |
| char    | String | 시작하는 글자   |                          |
| mission | String | 미션 글자       | 미션 글자가 없을 시 null |
| profile | JSON | 대상 프로필     |                          |
| type    | String | 패킷 타입       |                          |
