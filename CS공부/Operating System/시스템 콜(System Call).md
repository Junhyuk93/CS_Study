# System Call

fork(), exec(), wait()와 같은 것들은 Process 생성과 제어를 위한 System call

- fork, exec는 새로운 Process 생성과 관련이 되어 있다.
- wait는 Process(Parent)가 만든 다른 Process(child)가 끝날 때까지 기다리는 명령어다.

### Fork

    새로운 Process를 생성할때 사용.
    그러나, 이상한 방식