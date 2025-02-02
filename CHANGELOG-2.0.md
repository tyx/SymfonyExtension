# CHANGELOG for `2.0.x`

## v2.0.9 (2019-10-10)

- [#77](https://github.com/FriendsOfBehat/SymfonyExtension/issues/77) Fix docs: change 'kernel.file' to 'kernel.path' ([@mkilmanas](https://github.com/mkilmanas))
- [#78](https://github.com/FriendsOfBehat/SymfonyExtension/issues/78) Use right namespace for service definition ([@alanpoulain](https://github.com/alanpoulain))
- [#84](https://github.com/FriendsOfBehat/SymfonyExtension/issues/84) Minor improvements to CI config ([@pamil](https://github.com/pamil))
- [#92](https://github.com/FriendsOfBehat/SymfonyExtension/issues/92) Improve Mink installation docs ([@pamil](https://github.com/pamil))
- [#93](https://github.com/FriendsOfBehat/SymfonyExtension/issues/93) [HotFix] Force object typehint ([@lchrusciel](https://github.com/lchrusciel))
- [#96](https://github.com/FriendsOfBehat/SymfonyExtension/issues/96) Add base_url to docs for configuring Mink ([@liquorvicar](https://github.com/liquorvicar))
- [#97](https://github.com/FriendsOfBehat/SymfonyExtension/issues/97) Do not require base URL set with Mink ([@pamil](https://github.com/pamil))

## v2.0.8 (2019-03-21)

- [#76](https://github.com/FriendsOfBehat/SymfonyExtension/issues/76) Initialize contexts registered as services ([@pamil](https://github.com/pamil))

## v2.0.7 (2019-03-17)

- [#75](https://github.com/FriendsOfBehat/SymfonyExtension/issues/75) Hotfix for weird bug in Sylius ([@pamil](https://github.com/pamil))

## v2.0.6 (2019-03-15)

- [#74](https://github.com/FriendsOfBehat/SymfonyExtension/issues/74) Fix bug preventing changes of Mink default session service ([@pamil](https://github.com/pamil))

## v2.0.5 (2019-03-04)

- [#72](https://github.com/FriendsOfBehat/SymfonyExtension/issues/72) Allow accessing a context in another context ([@pamil](https://github.com/pamil))

## v2.0.4 (2019-02-13)

- [#68](https://github.com/FriendsOfBehat/SymfonyExtension/issues/68) Better compatibility with Behat itself ([@pamil](https://github.com/pamil), [@alanpoulain](https://github.com/alanpoulain))

## v2.0.3 (2019-02-07)

Removed the possibility to autoconfigure `$minkParameters` without a typehint due to an instable implementation in Symfony.

- [#64](https://github.com/FriendsOfBehat/SymfonyExtension/issues/64) Fix typo ([@rogamoore](https://github.com/rogamoore))
- [#66](https://github.com/FriendsOfBehat/SymfonyExtension/issues/66) Revert mink parameters autoconfiguration ([@pamil](https://github.com/pamil))

## v2.0.2 (2019-01-30)

- [#57](https://github.com/FriendsOfBehat/SymfonyExtension/issues/57) Fix support for context initializers ([@pamil](https://github.com/pamil))
- [#58](https://github.com/FriendsOfBehat/SymfonyExtension/issues/58) Add support for PHP 7.3 ([@pamil](https://github.com/pamil))
- [#59](https://github.com/FriendsOfBehat/SymfonyExtension/issues/59) Fix Symfony 4.1 build ([@pamil](https://github.com/pamil))

## v2.0.1 (2019-01-24)

- [#55](https://github.com/FriendsOfBehat/SymfonyExtension/issues/55) Require symfony/dependency-injection ^3.4.10|^4.1 ([@pamil](https://github.com/pamil))
