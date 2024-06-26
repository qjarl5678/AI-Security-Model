# 선형대수학 기초 한줄정리

### Linearly Independent란?

```markdown
선형 독립이란 벡터들이 서로 선형 관계로 표현될 수 없는 상태를 말합니다.
다시 말해, 벡터들이 선형 독립이라면 어떤 한 벡터를 다른 벡터들의 선형
조합으로 표현할 수 없습니다. 예를 들어, 만약 벡터들이 선형 독립이라면 
그들 각각이 서로 독립적인 방향을 가지고 있어야 합니다. 

만약 한 벡터가 다른 벡터들의 선형 조합으로 표현될 수 있다면,
그들은 선형 종속이라고 합니다.

V1,V2..Vn까지의 벡터의 집합이 있다고 가정하겠습니다.
여기서 선형결함 A1V1 + A2V2 ... AnVn의 값이 0 일때
A1 ~ An의 값이 모두 0인 경우 선형 독립이라고 할 수 잇습니다.
그리고 만약 그렇지 않은 경우는 선형 종속이라고 할 수 있습니다.
```
![alt text](image-1.png)

---

### Basis와 Dimension이란 무엇인가?

```markdown
벡터공간 V의 부분집합 S = {v1,v2,...vn} 에 대해서
S가 일차독립이고  span{S} = V
라는 두 조건을 만족하면 S를 V의 기저라고 부른다.

또 이 벡터공간 V의 한 기저의 개수가 n개일때 V의 차원을
기저의 개수가 차원이 됩니다.
```

---

### Symmetric Matrix란?

```markdown
대칭행렬이란 어떠한 행렬 A와 A transpose의 값이 같은
행렬을 말합니다.

A = AT : A = Symmetric Matrix
```

---

### Possitive-definite란?

```markdown
정치행렬이란 고윳값이 양수인 대칭행렬을 의미합니다.

Possitive definite matrix의 성질
- 주대각선의 우하향 방향으로의 Sub-Determinat들이 모두 양수이다.
- 모든 Pivot이 양수이다.
- 0이 아닌 벡터 X에 대해 Energy-based-Definition이 양수이다.
```

---

### Rank 란 무엇인가?

```makefile
Rank란 행렬이 가지는 independent한 column의 수를 말합니다.
그 말은 다시 말해 column space의 dimmension을 말하며
col-rank와 row-rank는 같다는 성질이 있습니다.

임의의 행렬 A가 있을 때, 이 행렬의 Rank 라는 것은 이 행렬의 
열들로 생성될 수 있는 벡터 공간의 차원을 의미한다
```
