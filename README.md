# three.ar.js-dragon-raid
만들면 재밌을거 같아서 만들어보자! three.ar.js를 이용한 몬스터 레이드 게임

## 구현 목표

* 안정적인 구동
* 용과 유저가 서로 투사체를 쏜다.
* 용의 남은 피에 따른 phase 별 공격패턴
* 한정 된 모션에서 용의 모션이 자연스럽다.
* 첫 시작에 땅과의 거리를 재서 용의 위치를 명확히 설정한다.

*** 서버사이드 렌더 ***
## truoble shooting

  * 자동변환 된 gltf파일에서 문제가 발생(black model)
    - 이번에는 uv를 추가하여 해결 했지만, 사이즈조절이나 black model해결이 안되는 경우도 있음 
    - three.ar.js에서 제공하는 obj mlt파일을 이용한는것이 안정적

