# Changelog

This project does NOT follow semantic versioning. The version increases as
follows:

1. Major version updates are breaking updates to the build infrastructure.
   These should be very rare.
2. Minor version updates are made for every major Buildroot release. This
   may also include Erlang/OTP and Linux kernel updates. These are made four
   times a year shortly after the Buildroot releases.
3. Patch version updates are made for Buildroot minor releases, Erlang/OTP
   releases, and Linux kernel updates. They're also made to fix bugs and add
   features to the build infrastructure.

## v0.0.7

* Change Target Name to m5stack_core_mp135
* Publication on hex.pm

## v0.0.6

* set default serial number "0000" by @masahiro-999 in https://github.com/masahiro-999/core_mp135/pull/12

## v0.0.5

* add kernel patch for core mp135 by @masahiro-999 in https://github.com/masahiro-999/core_mp135/pull/9
* Add LT8618SX driver to enable HDMI output by @masahiro-999 in https://github.com/masahiro-999/core_mp135/pull/11

## v0.0.4

* Disable the firmware validation process. by @masahiro-999 in https://github.com/masahiro-999/core_mp135/pull/3
* BR2_GLOBAL_PATCH_DIRの指定を適切にする by @masahiro-999 in https://github.com/masahiro-999/core_mp135/pull/4
* add CONFIG_F2FS_FS=y by @masahiro-999 in https://github.com/masahiro-999/core_mp135/pull/6

## v0.0.2

Change Target Name to core_mp135.

## v0.0.1

* Initial release
  * Port from osd32mp1 v0.19.1
  * [nerves_system_br v1.28.3](https://github.com/nerves-project/nerves_system_br/releases/tag/v1.28.3)
  * [Buildroot 2024.05.2](https://lore.kernel.org/buildroot/87zfpfh147.fsf@dell.be.48ers.dk/T/)
  * [Erlang/OTP 27.0.1](https://erlang.org/download/OTP-27.0.1.README)
