# Change log

## 0.2.0

- Renamed from `mdg:method` to `mdg:validated-method` and `Method` to `ValidatedMethod`
- Removed `schema` option, the way to use SimpleSchema now is by passing `SimpleSchema#validator()` into the `validate` option
- Added a special meaning to `validate: null` to allow people to intentionally skip validation if they need to, for example when a method has no arguments

## 0.1.0

Initial version
