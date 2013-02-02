hello-gyp-ninja
===============

hello gyp ninja

## build

to build project using gyp ninja
type following commands:

  gyp build.gyp --depth=. -f ninja
  ninja -v -C out/Default -f build.ninja

### test

  $ ./out/Default/hello
  hello gyp ninja
