[![Build Status](https://travis-ci.org/ciao-lang/test-ci.svg?branch=master)](https://travis-ci.org/ciao-lang/test-ci)
[![Build Status](https://ci.appveyor.com/api/projects/status/nmgot3y6p57qgdvf?svg=true)](https://ci.appveyor.com/project/jfmc/test-ci)

Repository that builds and generates distributions for:
 - [Ciao](https://github.com/ciao-lang/ciao) (master branch)
 - Linux, Mac, Windows
 - i686, x86_64

It uses resources provided by public CI and CD services (see
`.appveyor.yml` and `.travis.yml`). Files are uploaded
[here](https://bintray.com/ciao-lang/builds/ciao#files).

## Keys for uploading

Keys for uploading to BinTray are encrypted using:

 - Travis-CI: Install
   [Travis CI CLI](https://github.com/travis-ci/travis.rb) and use
   `travis encrypt BINTRAY_KEY=<YOUR_BINTRAY_KEY>`. The output is
   added to `env.global` at the `.travis.yml` file.

 - AppVeyor: use https://ci.appveyor.com/tools/encrypt (pass
   `<YOUR_BINTRAY_KEY>`)
