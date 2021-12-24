# 20911 신이선

## 1장. 리엑트 입문
### 1. 리엑트는 어쩌다가 만들어졌을까?

기본적인 자바스크립트로 DOM을 바꾸려면 작은 프로젝트일때는 괜찮지만 프로젝트가 커질수록 이벤트 규칙이 복잡해진다.<br>

이것을 해결하기 위해 Angular JS같은 프레임워크가 만들어졌는데 이 프레임워크들은 자바스크립트의 값이 바뀌면 DOM이 바뀌도록 연결을 해준다.<br>

리엑트는 작동방식이 다른데 바뀌면 다 날려버리고 새로 만들어버린다.<br>
리엑트에서는 Virtual DOM이라는 것을 사용해서 해서 이를 가능하게 했는데 가상으로 존재하는 DOM을 통해서 업데이트가 필요한 부분은 날려버리고 새로만든 DOM을 업데이트 하는 방식이다.