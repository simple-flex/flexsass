# flex.sass
###### simpler flex syntax
###### simple-flex implementation mixins
```sh
npm i flexsass # -- save
```
```sass
@import 'node_modules/flexsass/flex'

body
  @include flex(sass)
  @include flex(center)
  /*
    display: flex;
    align-items: center;
    justify-content: center;
  */
```
