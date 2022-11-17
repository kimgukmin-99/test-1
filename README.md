# test-1
깃허브 사용법에 대해 연습 중인 저장소

뀨뀨 꼬꼬?

# 가로줄 넣기
---
국민국민
***
국민국민

1. 원격저장소 만들기
2. ORIGIN 연결하기
3. PUSH
4. FETCH와 PULL
5. 협업하기

# 깃허브
- 원격저장소 만들기
- ORIGIN 연결하기
- PUSH
- FETCH와 PULL
- 협업하기

# 깃허브
- 원격저장소 만들기

  - ORIGIN 연결
  
  - PUSH
  
- FETCH와 PULL

  - FETCH

# 코드넣기
한줄짜리 소스코드는 `function add(x, y) { return x + y;}`

```pytion
ls = list(input())
sum = [[0 for _ in range(len(ls))]for _ in range(26)]
n = int(input())


for i in range(0, 26):
    cnt = 0
    for j in range(len(ls)):
        if chr(i+97) == ls[j]:
            cnt += 1
        sum[i][j] = cnt
```
