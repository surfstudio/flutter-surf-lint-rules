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

<details><summary>Const rules</summary><br/>
    <ul>
      <li> prefer_const_constructors </li>
      <li> prefer_const_constructors_in_immutables </li>
      <li> prefer_const_declarations </li>
      <li> prefer_const_literals_to_create_immutables </li>
      <li> unnecessary_const </li>
      <li> unnecessary_late </li>
    </ul>
</details>

<details><summary>Dart code metrics rules</summary><br/>
  <ul>
    <li> always-remove-listener </li>
    <li> avoid-returning-widgets </li>
    <li> avoid-unnecessary-setstate </li>
    <li> binary-expression-operand-order </li>
    <li> no-equal-then-else </li>
    <li> prefer-trailing-comma </li>
    <li> avoid-passing-async-when-sync-expected </li>
    <li> prefer-moving-to-variable </li>
    <li> format-comment </li>
    <li> prefer-async-await </li>
    <li> avoid-missing-enum-constant-in-map </li>
    <li> prefer-match-file-name </li>
    <li> avoid-throw-in-catch-block  </li>
    <li> avoid-unused-parameters </li>
  </ul>
</details>

<details><summary>Error rules</summary><br/>
    <ul>
      <li> always_use_package_imports </li>
      <li> avoid_dynamic_calls </li>
      <li> avoid_empty_else </li>
      <li> avoid_print </li>
      <li> avoid_relative_lib_imports </li>
      <li> avoid_returning_null_for_future </li>
      <li> avoid_slow_async_io </li>
      <li> avoid_type_to_string </li>
      <li> avoid_types_as_parameter_names </li>
      <li> avoid_web_libraries_in_flutter </li>
      <li> cancel_subscriptions </li>
      <li> close_sinks </li>
      <li> comment_references </li>
      <li> control_flow_in_finally </li>
      <li> empty_statements </li>
      <li> hash_and_equals </li>
      <li> iterable_contains_unrelated_type </li>
      <li> list_remove_unrelated_type </li>
      <li> literal_only_boolean_expressions </li>
      <li> no_adjacent_strings_in_list </li>
      <li> no_duplicate_case_values </li>
      <li> no_logic_in_create_state </li>
      <li> prefer_void_to_null </li>
      <li> test_types_in_equals </li>
      <li> throw_in_finally </li>
      <li> unnecessary_statements </li>
      <li> unrelated_type_equality_checks </li>
      <li> unsafe_html </li>
      <li> use_build_context_synchronously </li>
      <li> use_key_in_widget_constructors </li>
      <li> valid_regexps  </li>
    </ul>
</details>


<details><summary>Style rules</summary><br/>
    <ul>
      <li> always_declare_return_types </li>
      <li> always_put_required_named_parameters_first </li>
      <li> always_require_non_null_named_parameters </li>
      <li> annotate_overrides </li>
      <li> avoid_annotating_with_dynamic </li>
      <li> avoid_bool_literals_in_conditional_expressions </li>
      <li> avoid_catches_without_on_clauses </li>
      <li> avoid_catching_errors </li>
      <li> avoid_equals_and_hash_code_on_mutable_classes </li>
      <li> avoid_escaping_inner_quotes </li>
      <li> avoid_field_initializers_in_const_classes </li>
      <li> avoid_function_literals_in_foreach_calls </li>
      <li> avoid_implementing_value_types </li>
      <li> avoid_init_to_null </li>
      <li> avoid_js_rounded_ints </li>
      <li> avoid_multiple_declarations_per_line </li>
      <li> avoid_null_checks_in_equality_operators </li>
      <li> avoid_positional_boolean_parameters </li>
      <li> avoid_private_typedef_functions </li>
      <li> avoid_redundant_argument_values </li>
      <li> avoid_renaming_method_parameters </li>
      <li> avoid_return_types_on_setters </li>
      <li> avoid_returning_null </li>
      <li> avoid_returning_null_for_void </li>
      <li> avoid_returning_this </li>
      <li> avoid_setters_without_getters </li>
      <li> avoid_shadowing_type_parameters </li>
      <li> avoid_single_cascade_in_expression_statements </li>
      <li> avoid_types_on_closure_parameters </li>
      <li> avoid_unnecessary_containers </li>
      <li> avoid_unused_constructor_parameters </li>
      <li> avoid_void_async </li>
      <li> await_only_futures </li>
      <li> camel_case_extensions </li>
      <li> camel_case_types </li>
      <li> cascade_invocations </li>
      <li> constant_identifier_names </li>
      <li> curly_braces_in_flow_control_structures </li>
      <li> deprecated_consistency </li>
      <li> directives_ordering </li>
      <li> do_not_use_environment </li>
      <li> empty_catches </li>
      <li> empty_constructor_bodies </li>
      <li> exhaustive_cases </li>
      <li> file_names </li>
      <li> implementation_imports </li>
      <li> leading_newlines_in_multiline_strings </li>
      <li> library_names </li>
      <li> library_prefixes </li>
      <li> missing_whitespace_between_adjacent_strings </li>
      <li> no_runtimeType_toString </li>
      <li> non_constant_identifier_names </li>
      <li> null_closures </li>
      <li> omit_local_variable_types </li>
      <li> one_member_abstracts </li>
      <li> only_throw_errors </li>
      <li> overridden_fields </li>
      <li> package_api_docs </li>
      <li> parameter_assignments </li>
      <li> prefer_adjacent_string_concatenation </li>
      <li> prefer_asserts_in_initializer_lists </li>
      <li> prefer_collection_literals </li>
      <li> prefer_conditional_assignment </li>
      <li> prefer_constructors_over_static_methods </li>
      <li> prefer_contains </li>
      <li> prefer_equal_for_default_values </li>
      <li> prefer_final_fields </li>
      <li> prefer_final_in_for_each </li>
      <li> prefer_final_locals </li>
      <li> prefer_for_elements_to_map_fromIterable </li>
      <li> prefer_function_declarations_over_variables </li>
      <li> prefer_generic_function_type_aliases </li>
      <li> prefer_if_elements_to_conditional_expressions </li>
      <li> prefer_if_null_operators </li>
      <li> prefer_initializing_formals </li>
      <li> prefer_inlined_adds </li>
      <li> prefer_interpolation_to_compose_strings </li>
      <li> prefer_is_empty </li>
      <li> prefer_is_not_empty </li>
      <li> prefer_is_not_operator </li>
      <li> prefer_iterable_whereType </li>
      <li> prefer_mixin </li>
      <li> prefer_null_aware_operators </li>
      <li> prefer_single_quotes </li>
      <li> prefer_spread_collections </li>
      <li> prefer_typing_uninitialized_variables </li>
      <li> provide_deprecation_message </li>
      <li> public_member_api_docs (set to false) </li>
      <li> recursive_getters </li>
      <li> sized_box_for_whitespace </li>
      <li> slash_for_doc_comments </li>
      <li> sort_child_properties_last (set to false) </li>
      <li> sort_constructors_first (set to false) </li>
      <li> sort_unnamed_constructors_first (set to false) </li>
      <li> type_annotate_public_apis </li>
      <li> type_init_formals </li>
      <li> unawaited_futures </li>
      <li> unnecessary_await_in_return </li>
      <li> unnecessary_brace_in_string_interps </li>
      <li> unnecessary_getters_setters </li>
      <li> unnecessary_lambdas </li>
      <li> unnecessary_new </li>
      <li> unnecessary_null_aware_assignments </li>
      <li> unnecessary_null_checks </li>
      <li> unnecessary_null_in_if_null_operators </li>
      <li> unnecessary_nullable_for_final_variable_declarations </li>
      <li> unnecessary_overrides </li>
      <li> unnecessary_parenthesis </li>
      <li> unnecessary_raw_strings </li>
      <li> unnecessary_string_escapes </li>
      <li> unnecessary_string_interpolations </li>
      <li> unnecessary_this </li>
      <li> use_full_hex_values_for_flutter_colors </li>
      <li> use_function_type_syntax_for_parameters </li>
      <li> use_if_null_to_convert_nulls_to_bools </li>
      <li> use_is_even_rather_than_modulo </li>
      <li> use_late_for_private_fields_and_variables </li>
      <li> use_named_constants </li>
      <li> use_raw_strings </li>
      <li> use_rethrow_when_possible </li>
      <li> use_setters_to_change_properties </li>
      <li> use_string_buffers </li>
      <li> use_to_and_as_if_applicable </li>
      <li> void_checks </li>
      <li> lines_longer_than_80_chars (set to false) </li>
      <li> flutter_style_todos </li>
      <li> conditional_uri_does_not_exist </li>
      <li> no_leading_underscores_for_library_prefixes </li>
      <li> no_leading_underscores_for_local_identifiers </li>
      <li> secure_pubspec_urls </li>
      <li> sized_box_shrink_expand </li>
      <li> use_decorated_box </li>
      <li> use_colored_box </li>
      </ul>
</details>

<details><summary>Pub rules</summary><br/>
    <ul>
      <li> package_names </li>
      <li> sort_pub_dependencies </li>
    </ul>
</details>

<details><summary>Analyzer. Errors</summary><br/>
    <ul>
      <li> always_use_package_imports </li>
      <li> avoid_dynamic_calls  </li>
      <li> avoid_empty_else </li>
      <li> avoid_print </li>
      <li> avoid_relative_lib_imports </li>
      <li> avoid_returning_null_for_future </li>
      <li> avoid_slow_async_io </li>
      <li> avoid_type_to_string </li>
      <li> avoid_types_as_parameter_names </li>
      <li> avoid_web_libraries_in_flutter </li>
      <li> cancel_subscriptions </li>
      <li> close_sinks </li>
      <li> comment_references </li>
      <li> control_flow_in_finally </li>
      <li> empty_statements </li>
      <li> hash_and_equals </li>
      <li> iterable_contains_unrelated_type </li>
      <li> list_remove_unrelated_type </li>
      <li> literal_only_boolean_expressions </li>
      <li> no_adjacent_strings_in_list </li>
      <li> no_duplicate_case_values </li>
      <li> no_logic_in_create_state </li>
      <li> prefer_void_to_null </li>
      <li> test_types_in_equals </li>
      <li> throw_in_finally </li>
      <li> unnecessary_statements </li>
      <li> unrelated_type_equality_checks </li>
      <li> unsafe_html </li>
      <li> use_build_context_synchronously </li>
      <li> use_key_in_widget_constructors </li>
      <li> valid_regexps </li>
    </ul>
</details>

<details><summary>Member ordering</summary><br/>
    <ul>
      <li> public-static-const-fields </li>
      <li> private-static-const-fields </li>
      <li> public-static-final-fields </li>
      <li> private-static-final-fields </li>
      <li> public-static-fields </li>
      <li> private-static-fields </li>
      <li> public-final-fields </li>
      <li> private-final-fields </li>
      <li> public-fields </li>
      <li> public-getters-setters </li>
      <li> private-fields </li>
      <li> private-getters-setters </li>
      <li> constructors </li>
      <li> named-constructors </li>
      <li> factory-constructors </li>
      <li> overridden-methods </li>
      <li> public-static-methods </li>
      <li> public-methods </li>
      <li> protected-methods </li>
      <li> private-static-methods </li>
      <li> private-methods </li>
    </ul>
</details>


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
