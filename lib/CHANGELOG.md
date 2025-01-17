# Revision history for falsify

## 0.2 -- unreleased

* Avoid use of `Expr` in `at` (#48)
* Add `oneof` (#54, Simon Kohlmeyer)
* Generalize `Range`, so that it can be used for types like `Char` (#51).
  As a consequence, `Gen.integral` and `Gen.enum` are now deprecated, and
  superseded by `Gen.inRange`.

## 0.1.1 -- 2023-04-07

* Better verbose mode for test failures
* New predicates: `split` and `pairwise`.
* Shrink towards the _second_ half of the range in `withOrigin`

## 0.1.0 -- 2023-04-05

* First release
