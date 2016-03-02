[![Build Status](https://travis-ci.org/ciao-lang/test-ci.svg?branch=master)](https://travis-ci.org/ciao-lang/test-ci)
[![Build Status](https://ci.appveyor.com/api/projects/status/nmgot3y6p57qgdvf?svg=true)](https://ci.appveyor.com/project/jfmc/test-ci)

# test-ci
Ciao build and tests based on public CI services.

## Keys for deployment to BinTray

Keys are encrypted using:

 - Travis-CI: Install
   [Travis CI CLI](https://github.com/travis-ci/travis.rb) and use
   ``travis encrypt BINTRAY_KEY=<YOUR_BINTRAY_KEY>`. The output is
   added to `env.global` at the `.travis.yml` file.

 - AppVeyor: https://ci.appveyor.com/tools/encrypt (pass
   `<YOUR_BINTRAY_KEY>`)
