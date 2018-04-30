C, C++로 구현한 간단한 콘솔 게임
================================
제작자 :  [Kim Minsu](https://github.com/alstn2468)
--------------------------------
## Game 1 : 미로 찾기

### 스크린샷
- - -
![Maze Game](images/1.png)

### 조작법
- - -
위(↑) : `w` <br/>
아래(↓) : `s` <br/>
왼쪽(←) : `a` <br/>
오른쪽(→) : `d` <br/>
폭탄 설치(♨) : `t` <br/>
폭탄 터뜨리기 : `u` <br/>
벽 밀기 ON/OFF : `i` <br/>


시작 지점 : `★` <br/>
출구 : `◎` <br/>
플레이어 : `☆` <br/>
폭탄 : `♨` <br/>
길 : `□` <br/>
벽 : `■` <br/>
폭탄 파워 아이템 : `ⓟ` <br/>
벽 밀기 아이템 : `⇔` <br/>
투명화 아이템 : `▷` <br/>


시작지점(`★`)에서 플레이어(`☆`)를 출구(`◎`)까지 보내면 된다.<br/>
폭탄(`♨`) 사용 시 위, 아래, 왼쪽, 오른쪽 한 칸씩 길(`□`)로 만들어 준다.<br/>
단, 폭탄(`♨`)은 최대 한번에 `5`개 까지 설치할 수 있다.<br/>
폭탄 파워 아이템(`ⓟ`)을 먹으면 폭탄의 범위가 증가한다.<br/>
벽 밀기 아이템(`⇔`)을 먹으면 벽을 밀 수 있다.<br/>
투명화 아이템(`▷`)을 먹으면 벽을 통과 할 수 있다. <br/>

### LICENSE
- - -
[(MIT LICENSE)](LICENSE)
