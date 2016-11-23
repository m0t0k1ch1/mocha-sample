# mocha-sample

a sample test code for [mocha](https://github.com/mochajs/mocha)

## install mocha

``` sh
$ npm install -g mocha
```

## run

``` sh
$ mocha node_modules/app/hiyoco_test.js


  Hiyoco
    feed
      ✓ weight: 0 -> 1
      ✓ weight: 2 -> 5 -> 10
    canFly
      ✓ can - weight: 3
      ✓ can not - weight: 4


  4 passing (13ms)

```
