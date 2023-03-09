# Surf Lint Rules

[![Build Status](https://shields.io/github/workflow/status/surfstudio/flutter-surf-lint-rules/Analysis?logo=github&logoColor=white)](https://github.com/surfstudio/flutter-surf-lint-rules)
[![Pub Version](https://img.shields.io/pub/v/surf_lint_rules?logo=dart&logoColor=white)](https://pub.dev/packages/surf_lint_rules)
[![Pub Likes](https://badgen.net/pub/likes/surf_lint_rules)](https://pub.dev/packages/surf_lint_rules)
[![Pub popularity](https://badgen.net/pub/popularity/surf_lint_rules)](https://pub.dev/packages/surf_lint_rules/score)
![Dart Platform](https://badgen.net/pub/dart-platform/surf_lint_rules)
![Flutter Platform](https://badgen.net/pub/flutter-platform/surf_lint_rules)

This package is part of the [SurfGear](https://github.com/surfstudio/SurfGear) toolkit made by [Surf](https://surf.ru).

[![Surf Lint Rules](https://i.ibb.co/D7ymVLp/Surf-Lint-Rules.png)](https://github.com/surfstudio/SurfGear)

## Description

Lint rules used by "Surf". 

### Const rules
- prefer_const_constructors
- prefer_const_constructors_in_immutables
- prefer_const_declarations
- prefer_const_literals_to_create_immutables
- unnecessary_const
- unnecessary_late 

### Error rules
- always_use_package_imports
- avoid_dynamic_calls
- avoid_empty_else
- avoid_print
- avoid_relative_lib_imports
- avoid_returning_null_for_future
- avoid_slow_async_io
- avoid_type_to_string
- avoid_types_as_parameter_names
- avoid_web_libraries_in_flutter
- cancel_subscriptions
- close_sinks
- comment_references
- control_flow_in_finally
- empty_statements
- hash_and_equals
- iterable_contains_unrelated_type
- list_remove_unrelated_type
- literal_only_boolean_expressions
- no_adjacent_strings_in_list
- no_duplicate_case_values
- no_logic_in_create_state
- prefer_void_to_null
- test_types_in_equals
- throw_in_finally
- unnecessary_statements
- unrelated_type_equality_checks
- unsafe_html
- use_build_context_synchronously
- use_key_in_widget_constructors
- valid_regexps 

### Style rules
- always_declare_return_types
- always_put_required_named_parameters_first
- always_require_non_null_named_parameters
- annotate_overrides
- avoid_annotating_with_dynamic
- avoid_bool_literals_in_conditional_expressions
- avoid_catches_without_on_clauses
- avoid_catching_errors
- avoid_equals_and_hash_code_on_mutable_classes
- avoid_escaping_inner_quotes
- avoid_field_initializers_in_const_classes
- avoid_function_literals_in_foreach_calls
- avoid_implementing_value_types
- avoid_init_to_null
- avoid_js_rounded_ints
- avoid_multiple_declarations_per_line
- avoid_null_checks_in_equality_operators
- avoid_positional_boolean_parameters
- avoid_private_typedef_functions
- avoid_redundant_argument_values
- avoid_renaming_method_parameters
- avoid_return_types_on_setters
- avoid_returning_null
- avoid_returning_null_for_void
- avoid_returning_this
- avoid_setters_without_getters
- avoid_shadowing_type_parameters
- avoid_single_cascade_in_expression_statements
- avoid_types_on_closure_parameters
- avoid_unnecessary_containers
- avoid_unused_constructor_parameters
- avoid_void_async
- await_only_futures
- camel_case_extensions
- camel_case_types
- cascade_invocations
- constant_identifier_names
- curly_braces_in_flow_control_structures
- deprecated_consistency
- directives_ordering
- do_not_use_environment
- empty_catches:
- empty_constructor_bodies
- exhaustive_cases
- file_names
- implementation_imports
- leading_newlines_in_multiline_strings
- library_names
- library_prefixes
- missing_whitespace_between_adjacent_strings
- no_runtimeType_toString
- non_constant_identifier_names
- null_closures
- omit_local_variable_types
- one_member_abstracts
- only_throw_errors
- overridden_fields
- package_api_docs
- parameter_assignments
- prefer_adjacent_string_concatenation
- prefer_asserts_in_initializer_lists
- prefer_collection_literals
- prefer_conditional_assignment
- prefer_constructors_over_static_methods
- prefer_contains
- prefer_equal_for_default_values
- prefer_final_fields
- prefer_final_in_for_each
- prefer_final_locals
- prefer_for_elements_to_map_fromIterable
- prefer_function_declarations_over_variables
- prefer_generic_function_type_aliases
- prefer_if_elements_to_conditional_expressions
- prefer_if_null_operators
- prefer_initializing_formals
- prefer_inlined_adds
- prefer_interpolation_to_compose_strings
- prefer_is_empty
- prefer_is_not_empty
- prefer_is_not_operator
- prefer_iterable_whereType
- prefer_mixin
- prefer_null_aware_operators
- prefer_single_quotes
- prefer_spread_collections
- prefer_typing_uninitialized_variables
- provide_deprecation_message
- public_member_api_docs (set to false)
- recursive_getters
- sized_box_for_whitespace
- slash_for_doc_comments
- sort_child_properties_last (set to false)
- sort_constructors_first (set to false)
- sort_unnamed_constructors_first (set to false)
- type_annotate_public_apis
- type_init_formals
- unawaited_futures
- unnecessary_await_in_return
- unnecessary_brace_in_string_interps
- unnecessary_getters_setters
- unnecessary_lambdas
- unnecessary_new
- unnecessary_null_aware_assignments
- unnecessary_null_checks
- unnecessary_null_in_if_null_operators
- unnecessary_nullable_for_final_variable_declarations
- unnecessary_overrides
- unnecessary_parenthesis
- unnecessary_raw_strings
- unnecessary_string_escapes
- unnecessary_string_interpolations
- unnecessary_this
- use_full_hex_values_for_flutter_colors
- use_function_type_syntax_for_parameters
- use_if_null_to_convert_nulls_to_bools
- use_is_even_rather_than_modulo
- use_late_for_private_fields_and_variables
- use_named_constants
- use_raw_strings
- use_rethrow_when_possible
- use_setters_to_change_properties
- use_string_buffers
- use_to_and_as_if_applicable
- void_checks
- lines_longer_than_80_chars (set to false)
- flutter_style_todos
- conditional_uri_does_not_exist
- no_leading_underscores_for_library_prefixes
- no_leading_underscores_for_local_identifiers
- secure_pubspec_urls
- sized_box_shrink_expand
- use_decorated_box
- use_colored_box

### Pub rules
- package_names
- sort_pub_dependencies

### Analyzer. Errors
- always_use_package_imports
- avoid_dynamic_calls
- avoid_empty_else
- avoid_print
- avoid_relative_lib_imports
- avoid_returning_null_for_future
- avoid_slow_async_io
- avoid_type_to_string
- avoid_types_as_parameter_names
- avoid_web_libraries_in_flutter
- cancel_subscriptions
- close_sinks
- comment_references
- control_flow_in_finally
- empty_statements
- hash_and_equals
- iterable_contains_unrelated_type
- list_remove_unrelated_type
- literal_only_boolean_expressions
- no_adjacent_strings_in_list
- no_duplicate_case_values
- no_logic_in_create_state
- prefer_void_to_null
- test_types_in_equals
- throw_in_finally
- unnecessary_statements
- unrelated_type_equality_checks
- unsafe_html
- use_build_context_synchronously
- use_key_in_widget_constructors
- valid_regexps

### Member ordering
- public-static-const-fields
- private-static-const-fields
- public-static-final-fields
- private-static-final-fields
- public-static-fields
- private-static-fields
- public-final-fields
- private-final-fields
- public-fields
- public-getters-setters
- private-fields
- private-getters-setters
- constructors
- named-constructors
- factory-constructors
- overridden-methods
- public-static-methods
- public-methods
- protected-methods
- private-static-methods
- private-methods


## Installation

Add `surf_lint_rules` as dependency to your `pubspec.yaml`

```yaml
dependencies:
  surf_lint_rules: $currentVersion$
```

<p>At this moment, the current version of <code>surf_lint_rules</code> is <a href="https://pub.dev/packages/surf_lint_rules"><img style="vertical-align:middle;" src="https://img.shields.io/pub/v/surf_lint_rules.svg" alt="surf_lint_rules version"></a>.</p>

## Example

You can use both `stable` and `dev` versions of the package listed above in the badges bar.

Create `analysis_options.yaml` file

```yaml
include: package:surf_lint_rules/analysis_options.yaml
```

See the `dartanalyzer` executing the lint checks in you favorite editor.

## Changelog

All notable changes to this project will be documented in [this file](./CHANGELOG.md).

## Issues

To report your issues, file directly in the Issues section.

## Contribute

If you would like to contribute to the package (e.g. by improving the documentation, fixing a bug or adding a cool new feature), please read our [contribution guide](./CONTRIBUTING.md) first and send us your pull request.

Your PRs are always welcome.

## How to reach us

Please feel free to ask any questions about this package. Join our community chat on Telegram. We speak English and Russian.

[![Telegram](https://img.shields.io/badge/chat-on%20Telegram-blue.svg)](https://t.me/SurfGear)

## License

[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
