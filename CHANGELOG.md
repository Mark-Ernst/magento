# Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.7.0](https://github.com/myparcelnl/magento/compare/v4.6.1...v4.7.0) (2022-10-05)


### :sparkles: New Features

* allow exporting digital stamp ([#716](https://github.com/myparcelnl/magento/issues/716)) ([793e78c](https://github.com/myparcelnl/magento/commit/793e78cc8d4cc12e0d453a0e7b8828ed29237784))
* show only relevant delivery options ([#711](https://github.com/myparcelnl/magento/issues/711)) ([1806558](https://github.com/myparcelnl/magento/commit/1806558ea9db450fc98c7e5df0e15fbae8e5a80f))


### :bug: Bug Fixes

* fix delivery options loading forever ([#713](https://github.com/myparcelnl/magento/issues/713)) ([6dc37e2](https://github.com/myparcelnl/magento/commit/6dc37e2a8a6c1159647a976c2f99694ba52577aa))
* fix mailbox amount ([#714](https://github.com/myparcelnl/magento/issues/714)) ([c9970f5](https://github.com/myparcelnl/magento/commit/c9970f56043accdecef7a9485131076297e0e7d3))
* translate instabox strings ([#718](https://github.com/myparcelnl/magento/issues/718)) ([a15b595](https://github.com/myparcelnl/magento/commit/a15b595dd032f9f95fea54e6638af45c65a42731))

## [4.6.1](https://github.com/myparcelnl/magento/compare/v4.6.0...v4.6.1) (2022-09-15)


### :bug: Bug Fixes

* display correct version to end user ([#706](https://github.com/myparcelnl/magento/issues/706)) ([a821359](https://github.com/myparcelnl/magento/commit/a82135985f96656c7d83781e1cdc8b0c29b7e1b7))
* fix wrong parameter type ([#707](https://github.com/myparcelnl/magento/issues/707)) ([57d79fa](https://github.com/myparcelnl/magento/commit/57d79facc56d33f7049d05441c2c955ae9da943d))
* have cronjob update shipment status ([#708](https://github.com/myparcelnl/magento/issues/708)) ([a615f6e](https://github.com/myparcelnl/magento/commit/a615f6e566848b8d20493dcb7664870d8e68bfaf))

## [4.6.0](https://github.com/myparcelnl/magento/compare/v4.5.0...v4.6.0) (2022-07-28)


### :sparkles: New Features

* allow custom amount of items in mailbox package ([#695](https://github.com/myparcelnl/magento/issues/695)) ([557f355](https://github.com/myparcelnl/magento/commit/557f355e9663882764c05e39623b57233d45881e))


### :bug: Bug Fixes

* compatibility with php 8.1 ([#690](https://github.com/myparcelnl/magento/issues/690)) ([027ee90](https://github.com/myparcelnl/magento/commit/027ee90d8105bbb6fca2ca18fe87a757cd1ecd63))
* error invalid element tooltip ([#698](https://github.com/myparcelnl/magento/issues/698)) ([6e0ea60](https://github.com/myparcelnl/magento/commit/6e0ea60fd0e2d1b090e3316d5d348fa44583c4ae))
* export order from order details ([#693](https://github.com/myparcelnl/magento/issues/693)) ([5d04892](https://github.com/myparcelnl/magento/commit/5d0489224464878bb5f4c58cbc76166dbe91d66f))
* **om:** show enable setting ([#691](https://github.com/myparcelnl/magento/issues/691)) ([0a72278](https://github.com/myparcelnl/magento/commit/0a722781044ab7975022c23a509614c30ddc8368))
* only get available options for carriers ([#703](https://github.com/myparcelnl/magento/issues/703)) ([f6317f7](https://github.com/myparcelnl/magento/commit/f6317f7b3bd0312220cff3c334f88e2d80410121)), closes [#701](https://github.com/myparcelnl/magento/issues/701)
* prevent loop while exporting shipment ([#700](https://github.com/myparcelnl/magento/issues/700)) ([ae83b0a](https://github.com/myparcelnl/magento/commit/ae83b0add4cb14dd037df495670190346aeebe1f))
* prevent upgrade from failing on new install ([#702](https://github.com/myparcelnl/magento/issues/702)) ([df24444](https://github.com/myparcelnl/magento/commit/df2444414e2d024fd1e08ed3a0e50367313e556e))

## [4.5.0](https://github.com/myparcelnl/magento/compare/v4.4.0...v4.5.0) (2022-06-14)


### :sparkles: New Features

* add custom insurance option ([#674](https://github.com/myparcelnl/magento/issues/674)) ([caaee09](https://github.com/myparcelnl/magento/commit/caaee09ee09740c0d24e2bcdff138e9024a9bd24))
* add instabox ([#662](https://github.com/myparcelnl/magento/issues/662)) ([d322919](https://github.com/myparcelnl/magento/commit/d3229192fc76a8a0e927254a68d0b9c558649cb0))
* update shipping status orderbeheer ([#677](https://github.com/myparcelnl/magento/issues/677)) ([2cbb2be](https://github.com/myparcelnl/magento/commit/2cbb2bee1a5dae4883b1ab5384a12da73682e1a3))


### :bug: Bug Fixes

* don't render delivery options when already visible ([#680](https://github.com/myparcelnl/magento/issues/680)) ([d5c084a](https://github.com/myparcelnl/magento/commit/d5c084ab138c322c1a973a9443c3761015086f5c))
* **om:** order grid shipment column options ([#681](https://github.com/myparcelnl/magento/issues/681)) ([cb7d2c0](https://github.com/myparcelnl/magento/commit/cb7d2c0d23377156ce65df2a104117dade981503))
* **regression:** mailbox price is baseprice by itself ([#686](https://github.com/myparcelnl/magento/issues/686)) ([c7d07ac](https://github.com/myparcelnl/magento/commit/c7d07ac48a1d9ca15b40aa13611e608184f904b6))
* **regression:** remove instabox pickup options ([#685](https://github.com/myparcelnl/magento/issues/685)) ([88f2020](https://github.com/myparcelnl/magento/commit/88f202069a0ac7ff702db7570f386afe76db1b01))
* set default carrier for row shipments ([#679](https://github.com/myparcelnl/magento/issues/679)) ([5f5437b](https://github.com/myparcelnl/magento/commit/5f5437baeadfa635a686565624a98a89b8c37892))
* set filterable and searchable attributes to false ([#668](https://github.com/myparcelnl/magento/issues/668)) ([7961df1](https://github.com/myparcelnl/magento/commit/7961df125bb5e1fffa37fd79d5ff8dbcb453a107))
