# Changelog

## 1.19.0 (2017-11-17)

* [feature] Remove include restriction for several loader.

> https://github.com/nowa-webpack/nowa-server/pull/20

## 1.18.0 (2017-09-05)

* [feature] Update version of ts-loader.

## 1.17.0 (2017-06-21)

* [feature] Support IE<=10 `static extends` on `loose` mode.

## 1.16.0 (2017-05-18)

* [feature] Inject `webpack` to user defined config.

## 1.15.3 (2017-05-11)

* [fix] Revert to 1.15.0.

## 1.15.1 (2017-05-10)

* [fix] .ts files support jsx.

## 1.15.0 (2017-04-21)

* [feature] Add `--no-sourcemap` option to disable sourcemap.

> https://github.com/nowa-webpack/nowa-server/pull/19

## 1.14.1 (2017-03-20)

* [fix] Update react version to resolve peerDependencies issue.

## 1.14.0 (2017-03-16)

* [feature] Proxy support rewrite path.

> https://github.com/nowa-webpack/nowa/issues/39

## 1.13.0 (2017-03-16)

* [feature] Add transform-decorators plugin.

> https://github.com/nowa-webpack/nowa/issues/38

## 1.12.0 (2017-03-12)

* [feature] Support page filter to add specified pages to entry.

> https://github.com/nowa-webpack/nowa/issues/35

## 1.11.1 (2017-03-09)

* [feature] Add process info.

> https://github.com/nowa-webpack/nowa-server/issues/18

## 1.10.3 (2017-02-09)

* [improve] Add inject point.

> https://github.com/nowa-webpack/nowa-server/pull/16

## 1.10.2 (2017-01-23)

* [improve] Improve injection algorithm.

## 1.10.1 (2017-01-23)

* [feature] Support html injection for css resources.

## 1.10.0 (2017-01-19)

* [feature] Support html injection.
* [feature] Add host option to support custom host.
* [feature] Add TypeScript support.

> https://github.com/nowa-webpack/nowa-server/issues/14

> https://github.com/nowa-webpack/nowa-server/pull/7

> https://github.com/nowa-webpack/nowa-server/pull/15

## 1.9.1 (2017-01-17)

* [fix] Fix loader found error issue.

> https://github.com/nowa-webpack/nowa-server/issues/11

## 1.9.0 (2016-12-26)

* [fix] Fix root dependency mismatch bug.

> https://github.com/nowa-webpack/nowa/issues/30

## 1.8.3 (2016-12-22)

* [fix] Update less version.

## 1.8.2 (2016-12-22)

* [fix] Update stylus-loader version for supporting Nodejs 6+.

## 1.8.1 (2016-12-13)

* [fix] Fix alias bug.

## 1.8.0 (2016-12-11)

* [feature] Add alias option for module path alias defination.

> https://github.com/nowa-webpack/nowa-server/issues/10

## 1.7.0 (2016-11-22)

* [feature] Add jsx extension support.

> https://github.com/nowa-webpack/nowa-server/pull/9

## 1.6.1 (2016-11-17)

* [fix] Add missing babel-runtime for non-lazyload mode.

> https://github.com/nowa-webpack/nowa-server/issues/8

## 1.6.0 (2016-10-23)

* [feature] Support font files(woff,woff2,ttf,otf).

## 1.5.0 (2016-10-14)

* [feature] Use eval mode to build sourcemap.

## 1.4.1 (2016-09-27)

* [fix] babel-runtime do not support old IEs, so use es3ify-loader to transform babel-runtime.

> https://github.com/nowa-webpack/nowa/issues/22

## 1.4.0 (2016-09-27)

* [feature] Update version of babel plugins.
* [feature] Use es2015 internel loose mode.
* [feature] Use babel-runtime to support polyfill.

> https://github.com/nowa-webpack/nowa-build/issues/10

> https://github.com/nowa-webpack/nowa/issues/20

## 1.3.0 (2016-08-23)

* [feature] Add include option to support adding more include path for loader.

> https://github.com/nowa-webpack/nowa-build/issues/9

## 1.2.0 (2016-07-27)

* [feature] Ignore babelrc.
* [improve] Add cache directory for babel to speed up.

## 1.1.2 (2016-07-12)

* [fix] `--loose` argument do not take effect.

> https://github.com/nowa-webpack/nowa-server/issues/4

## 1.1.1 (2016-06-30)

* [fix] Can not find nowa plugin when nowa was locally installed.

> https://github.com/nowa-webpack/nowa/issues/6

## 1.1.0 (2016-06-27)

* [feature] Support varible replacement in historyApiFallback.

> https://github.com/nowa-webpack/nowa-server/issues/3

## 1.0.0 (2016-06-26)

* [feature] Add historyApiFallback.
* [feature] Add mockapi.

> https://github.com/nowa-webpack/nowa-server/issues/1

> https://github.com/nowa-webpack/nowa-server/issues/2
