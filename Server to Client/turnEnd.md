### ※ 게임 타입에 따라 JSON 내용이 달라, 수정 필요

```json
{  
   "ok":true,
   "value":"max",
   "mean":"＂1＂ street names for gamma hydroxybutyrate  ",
   "theme":"e06",
   "wc":"n",
   "score":22,
   "bonus":0,
   "profile":{  
      "type":"naver",
      "id":"64193144",
      "name":"anonymous",
      "title":"horyu****",
      "image":"https://phinf.pstatic.net/contactthumb/20161217_254/14819290210033lfO9_JPEG/%B3%C9%B3%C9%C0%CC22.jpg?type=s80"
   },
   "type":"turnEnd"
}
```

| 종류    | 타입    | 설명          | 비고                       |
|---------|---------|---------------|----------------------------|
| ok      | Boolean | 성공 여부     |                            |
| value   | String  | 입력한 내용   |                            |
| mean    | String  | 단어 뜻       |                            |
| theme   | String  | 단어 테마     |                            |
| wc      | String  |               |                            |
| score   | Integer | 스코어        | 성공시에는 +, 실패시에는 - |
| bonus   | Integer | 보너스 스코어 | 예) 미션 단어 포함시       |
| profile | JSON    | 대상 프로필   | 봇일 경우 표시되지 않음    |
| type    | String  | 패킷 타입     |                            |
