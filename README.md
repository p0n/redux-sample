# redux-sample

[Reduxの実装とReactとの連携を超シンプルなサンプルを使って解説](https://mae.chab.in/archives/2885)

## ProtoTypes migration
- React.PropTypes has moved into a different package since React v15.5.
- Use the prop-types library instead.
  ```
  yarn add prop-types --dev
  ```
- Use PropTypes instead of React.PropTypes
  ```
  import PropTypes from 'prop-types';
  ```
