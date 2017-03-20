* 본 패킷 타입은 게임 타입에 따라 JSON 내용이 달라집니다.

## classic
```json

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

```
| 종류    | 타입   | 설명        | 비고 |
|---------|--------|-------------|------|
| seq     |        |             |      |
| profile | JSON   | 대상 프로필 |      |
| type    | String | 패킷 타입   |      |

## daneo
```json

```
| 종류    | 타입    | 설명            | 비고         |
|---------|---------|-----------------|--------------|
| round   | Integer | 시작하는 라운드 |              |
| theme   | String  | 시작하는 주제   |              |
| mission | String  | 미션 글자       | 없을 시 null |
| profile | JSON    | 대상 프로필     |              |
| type    | String  | 패킷 타입       |              |

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

```
| 종류    | 타입    | 설명            | 비고         |
|---------|---------|-----------------|--------------|
| round   | Integer | 시작하는 라운드 |              |
| theme   | String  | 시작하는 주제   |              |
| profile | JSON    | 대상 프로필     |              |
| type    | String  | 패킷 타입       |              |

## sock
```json

```
| 종류    | 타입    | 설명            | 비고 |
|---------|---------|-----------------|------|
| round   | Integer | 시작하는 라운드 |      |
| board   |         | 보드 판         |      |
| profile | JSON    | 대상 프로필     |      |
| type    | String  | 패킷 타입       |      |

## typing
```json

```
| 종류    | 타입    | 설명            | 비고 |
|---------|---------|-----------------|------|
| round   | Integer | 시작하는 라운드 |      |
| list    |         | 단어/속담 목록  |      |
| profile | JSON    | 대상 프로필     |      |
| type    | String  | 패킷 타입       |      |
