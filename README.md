# 설계를 하기 위해 적용한 원칙

- 책임
- 역할
- 협력

## 협력

협력을 구하는 행위 -> 메세지 전송(Message Sending)

객체를 먼저 결정하는 것이 아님. 메세지를 정하고 그 다음 객체를 결정함.  

```text
ex) run이라는 메시지(메소드)를 만든 후, 이 메시지를 담당할 객체 Kiosk를 결정함.
```

# 설계 사이클

1. 메세지 정의
2. 메세지 받을 객체 선정(없으면 만듬)
3. 세부 코드 채우기