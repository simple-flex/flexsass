# flex.sass
###### simpler flex syntax
###### simple-flex implementation mixins

### [simple-flex]() implementation in sass style (`@include flex(sass)`)

```sh
npm i flexsass # -- save
```
```sass
@import '../node_modules/flexsass/flex'

body
  @include flex(sass)
  // display: flex;
  
  @include flex(line)
  // display: inline-flex;
  
  @include flex(center)
  /*
    align-items: center;
    align-content: center;
    justify-content: center;
  */

  @include flex(wrap)
  // flex-wrap: wrap;

  @include flex(column)
  // flex-direction: column;

  @include justify(end)
  // justify-content: flex-end;

  @include justify(around)
  // justify-content: space-around;

  @include align(start)
  // align-items: flex-start;

  @include self(auto)
  // align-self: auto;

  @include flex(grow)
  // flex-grow: 1;
```
