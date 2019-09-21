# mobx-basic

[![Greenkeeper badge](https://badges.greenkeeper.io/seongjoojin/mobx-basic.svg)](https://greenkeeper.io/)

벨로퍼트님 벨로그 따라하기

## Mobx 주요 개념

1. Observable State (관찰 받고 있는 상태)

   - Mobx를 사용하고 있는 앱의 상태를 Observable라고 함. (관찰 받고 있는 상태라고 이해하면 조금 더 쉬울 수 있음)
   - 앱에서 사용하는 상태는 변할 수 있으며 만약에 특정 부분이 변경되면 Mobx에서는 정확히 어떤 부분이 바뀌었는지 알 수 있습니다.

2. Computed Value (연산된 값)

   - 연산된 값은 기존의 상태값과 다른 연산된 값에 기반하여 만들어질 수 있는 값임.
   - 주로 성능 최적화를 위하여 많이 사용됨.
   - 어떤 값을 연산해야 할 때, 연산에 기반되는 값이 바뀔때만 새로 연산하게 되고, 바뀌지 않았다면 그냥 기존의 값을 사용 할 수 있게 해줌.

3. Reactions (반응)

   - Reactions는 Computed Value와 비슷함.
   - 값이 바뀜에 따라 해야 할 일을 정하는 것을 의미함.

4. Actions (액션:행동)

   - 상태에 변화를 일으키는 것을
