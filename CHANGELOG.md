# CHANGELOG

## 2.0.0 (2016-04-23)

#### Breaking Changes:
+ Remove parameter options from [`#flatten()`](https://github.com/nwoltman/pro-array#Array+flatten) ([28dac11](https://github.com/nwoltman/pro-array/commit/28dac11fd9b45a4505c7704974163cf5695275d1))
  + This means if you want to flatten a nested array more than one level, you'll need to use [`#flattenDeep()`](https://github.com/nwoltman/pro-array#Array+flattenDeep) instead
+ Update `string-natural-compare` to v2 ([ab3491a](https://github.com/nwoltman/pro-array/commit/ab3491a1c556bb46f97e76fa7879c62d66348148))
  + See the `string-natural-compare` [documentation](https://github.com/nwoltman/string-natural-compare#usage) if you were using a custom alphabet, otherwise no action is needed when upgrading to v2

#### Other Changes:
+ Update license year ([515c30c](https://github.com/nwoltman/pro-array/commit/515c30c3e609c97eeb1860304d743664b66bcd03))
+ Update Node versions to test ([9820fa0](https://github.com/nwoltman/pro-array/commit/9820fa02a78bbbc019b995c0dec9c96aba6bcfa8))
+ Improve documentation

## 1.2.0 (2015-10-18)
+ Use a faster version of [`.flattenDeep()`](https://github.com/nwoltman/pro-array#Array+flattenDeep) by default ([048f9fe](https://github.com/nwoltman/pro-array/commit/048f9fe123803c181f36d0a66b52e37c3365b279))
+ Implement [`.rnatsort()`](https://github.com/nwoltman/pro-array#Array+rnatsort) ([0aca5bf](https://github.com/nwoltman/pro-array/commit/0aca5bf4fb376bf0f6ce53fe394da0ac0cd58ed9))
+ Test with iojs and Node v4 ([6aacf9f](https://github.com/nwoltman/pro-array/commit/6aacf9f17b0cb1e5c476ee7573cdcf72028850fc))
+ Implement [`.flatten()`](https://github.com/nwoltman/pro-array#Array+flatten) and [`.flattenDeep()`](https://github.com/nwoltman/pro-array#Array+flattenDeep) ([a05b01a](https://github.com/nwoltman/pro-array/commit/a05b01afcc006e71ffac194535fc2c5bd404234f))

## 1.1.0 (2015-05-09)
+ Implement [`.bsearch()`](https://github.com/nwoltman/pro-array#Array+bsearch) ([5e30c60](https://github.com/nwoltman/pro-array/commit/5e30c6027038b4baaef9c9614576a93f0eb71d63))
+ Switch from using natural-compare-lite to string-natural-compare ([41f1202](https://github.com/nwoltman/pro-array/commit/41f120283b99ac48ef2265f4e5af71b83c6b720d))
+ Rename the [`.rem()`](https://github.com/nwoltman/pro-array#Array+rem) alias to [`.pull()`](https://github.com/nwoltman/pro-array#Array+pull) ([330045f](https://github.com/nwoltman/pro-array/commit/330045fd0fd03a49fede1029b013b14303b77770))
+ Make [`.clear()`](https://github.com/nwoltman/pro-array#Array+clear) return the array ([b38b9be](https://github.com/nwoltman/pro-array/commit/b38b9bee57f5569e518bdd6417c3fdb51afe0368))
+ Optimize [`.chunk()`](https://github.com/nwoltman/pro-array#Array+chunk) ([cfc17a4](https://github.com/nwoltman/pro-array/commit/cfc17a41fce05b336d97c5a9fd7f7868bc8d7151))
+ Fix bug in [`.intersect()`](https://github.com/nwoltman/pro-array#Array+intersect) ([af00b28](https://github.com/nwoltman/pro-array/commit/af00b28a9de90d628a618a5b5aec5ba2e370eea9))
+ Add new [`.xor()`](https://github.com/nwoltman/pro-array#Array+xor) method ([ac43453](https://github.com/nwoltman/pro-array/commit/ac4345387c8e716244e0259a492ad4726556fe8d))
