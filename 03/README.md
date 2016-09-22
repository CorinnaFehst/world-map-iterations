## 03 update to es2015, update code style

convert to [ES2015](https://babeljs.io/docs/learn-es2015/) with [lebab](https://github.com/lebab/lebab)

```shell
➜  03 git:(master) ✗ lebab es5.js -o es6.js --transform arrow
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform for-of
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform arg-spread
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform obj-method
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform obj-shorthand
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform multi-var
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform let
➜  03 git:(master) ✗ lebab es6.js -o es6.js --transform template
```
