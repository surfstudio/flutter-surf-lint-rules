# Changelog

## 4.0.0

* Updated version of `flutter_lints` to `5.0.0`
* Updated minSdk version to 3.5.0

### Removed 

* prefer_const_constructors
* prefer_const_declarations
* prefer_const_literals_to_create_immutables

https://github.com/dart-lang/core/issues/833

### Added 

* avoid_null_checks_in_equality_operators 

## 3.1.0

### Removed

* one_member_abstracts 
* use_setters_to_change_properties

## 3.0.0

* [BREAKING CHANGE] Removed dart_code_metrics
* Added new lint rules for dart 3
* Updated README.md

## 2.1.0

* added new DCM rules
* added lint rules description links
* updated README.md

## 2.0.0

* upgraded flutter_lints to 2.0.1
* upgraded dart_code_metrics to 5.5.1
* remove deprecated rule: invariant_booleans

## 1.5.0

### Added

* conditional_uri_does_not_exist rule;
* no_leading_underscores_for_library_prefixes rule;
* no_leading_underscores_for_local_identifiers rule;
* secure_pubspec_urls rule;
* sized_box_shrink_expand rule;
* use_decorated_box rule;
* use_colored_box rule;
* unnecessary_late rule;

## 1.4.1

* internal improvements

## 1.4.0

* Stable release

## 1.4.0-dev.1

* Remove pedantic dependency

## 1.3.0

* Stable release

## 1.2.1-dev.2

* Add some rules: [always-remove-listener](https://github.com/dart-code-checker/dart-code-metrics/blob/master/doc/rules/always-remove-listener.md), [avoid-unnecessary-setstate](https://github.com/dart-code-checker/dart-code-metrics/blob/master/doc/rules/avoid-unnecessary-setstate.md).

## 1.2.1-dev.1

* Switch on `dart_code_metrics` 4.0.0-dev.1

## 1.2.0

* Stable release

## 1.1.1-dev.4

* Add new rule: [member-ordering-extended](https://github.com/dart-code-checker/dart-code-metrics/blob/master/doc/rules/member-ordering-extended.md)

## 1.1.1-dev.3

* Tune metrics settings

## 1.1.1-dev.2

* Set min SDK version to `2.13.0`.
* Tune `avoid-returning-widgets`.

## 1.1.1-dev.1

* Add some rules: `avoid_multiple_declarations_per_line`, `deprecated_consistency`, `prefer_if_elements_to_conditional_expressions`, `unnecessary_null_checks`, `unnecessary_nullable_for_final_variable_declarations`, `use_if_null_to_convert_nulls_to_bools`, `use_late_for_private_fields_and_variables`, `use_named_constants`, `missing_whitespace_between_adjacent_strings`, `avoid_type_to_string`, `use_build_context_synchronously`.
* Disable rules: `sort_child_properties_last`, `sort_constructors_first`, `sort_unnamed_constructors_first`.

## 1.1.0

* Bump pedantic version.
* Add [dart-code-metrics](https://pub.dev/packages/dart_code_metrics) dependency.

## 1.0.0

* Migrated to null safety, min SDK is `2.12.0`.

## 0.0.2-dev.6

* Add new error-rule : no_runtimeType_toString.
* Lint level changed from warning to error for : type_annotate_public_apis, await_only_futures, always_declare_return_types rules.
* Add new rule : flutter_style_todos

## 0.0.2-dev.2

* Disabled lines_longer_than_80_chars to increase line length without warnings

## 0.0.1-dev.0

* Initial release
