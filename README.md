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

Lint rules used by Surf. 

<details><summary>Const rules</summary><br/>
    <ul>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_const_constructors.html">prefer_const_constructors</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_const_constructors_in_immutables.html">prefer_const_constructors_in_immutables</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_const_declarations.html">prefer_const_declarations</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_const_literals_to_create_immutables.html">prefer_const_literals_to_create_immutables</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_const.html">unnecessary_const</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_late.html">unnecessary_late</a> </li>
    </ul>
</details>

<details><summary>Dart code metrics rules</summary><br/>
  <ul>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/flutter/always-remove-listener">always-remove-listener</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/flutter/avoid-returning-widgets">avoid-returning-widgets</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/flutter/avoid-unnecessary-setstate">avoid-unnecessary-setstate</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/binary-expression-operand-order">binary-expression-operand-order</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/no-equal-then-else">no-equal-then-else</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/prefer-trailing-comma">prefer-trailing-comma</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/avoid-passing-async-when-sync-expected">avoid-passing-async-when-sync-expected</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/prefer-moving-to-variable">prefer-moving-to-variable</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/format-comment">format-comment</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/prefer-async-await">prefer-async-await</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/avoid-missing-enum-constant-in-map">avoid-missing-enum-constant-in-map</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/prefer-match-file-name">prefer-match-file-name</a> </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/avoid-throw-in-catch-block">avoid-throw-in-catch-block</a>  </li>
    <li> <a href="https://dartcodemetrics.dev/docs/rules/common/avoid-unused-parameters">avoid-unused-parameters</a> </li>
  </ul>
</details>

<details><summary>Error rules</summary><br/>
    <ul>
      <li> <a href="https://dart-lang.github.io/linter/lints/always_use_package_imports.html">always_use_package_imports</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_dynamic_calls.html">avoid_dynamic_calls</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_empty_else.html">avoid_empty_else</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_print.html">avoid_print</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_relative_lib_imports.html">avoid_relative_lib_imports</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_returning_null_for_future.html">avoid_returning_null_for_future</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_slow_async_io.html">avoid_slow_async_io</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_type_to_string.html">avoid_type_to_string</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_types_as_parameter_names.html">avoid_types_as_parameter_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_web_libraries_in_flutter.html">avoid_web_libraries_in_flutter</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/cancel_subscriptions.html">cancel_subscriptions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/close_sinks.html">close_sinks</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/comment_references.html">comment_references</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/control_flow_in_finally.html">control_flow_in_finally</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/empty_statements.html">empty_statements</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/hash_and_equals.html">hash_and_equals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/iterable_contains_unrelated_type.html">iterable_contains_unrelated_type</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/list_remove_unrelated_type.html">list_remove_unrelated_type</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/literal_only_boolean_expressions.html">literal_only_boolean_expressions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_adjacent_strings_in_list.html">no_adjacent_strings_in_list</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_duplicate_case_values.html">no_duplicate_case_values</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_logic_in_create_state.html">no_logic_in_create_state</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_void_to_null.html">prefer_void_to_null</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/test_types_in_equals.html">test_types_in_equals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/throw_in_finally.html">throw_in_finally</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_statements.html">unnecessary_statements</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unrelated_type_equality_checks.html">unrelated_type_equality_checks</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unsafe_html.html">unsafe_html</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_build_context_synchronously.html">use_build_context_synchronously</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_key_in_widget_constructors.html">use_key_in_widget_constructors</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/valid_regexps.html">valid_regexps</a>  </li>
    </ul>
</details>


<details><summary>Style rules</summary><br/>
    <ul>
      <li> <a href="https://dart-lang.github.io/linter/lints/always_declare_return_types.html">always_declare_return_types</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/always_put_required_named_parameters_first.html">always_put_required_named_parameters_first</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/always_require_non_null_named_parameters.html">always_require_non_null_named_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/annotate_overrides.html">annotate_overrides</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_annotating_with_dynamic.html">avoid_annotating_with_dynamic</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_bool_literals_in_conditional_expressions.html">avoid_bool_literals_in_conditional_expressions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_catches_without_on_clauses.html">avoid_catches_without_on_clauses</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_catching_errors.html">avoid_catching_errors</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_equals_and_hash_code_on_mutable_classes.html">avoid_equals_and_hash_code_on_mutable_classes </a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_escaping_inner_quotes.html">avoid_escaping_inner_quotes</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_field_initializers_in_const_classes.html">avoid_field_initializers_in_const_classes</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_function_literals_in_foreach_calls.html">avoid_function_literals_in_foreach_calls</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_implementing_value_types.html">avoid_implementing_value_types</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_init_to_null.html">avoid_init_to_null</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_js_rounded_ints.html">avoid_js_rounded_ints</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_multiple_declarations_per_line.html">avoid_multiple_declarations_per_line</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_null_checks_in_equality_operators.html">avoid_null_checks_in_equality_operators</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_positional_boolean_parameters.html">avoid_positional_boolean_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_private_typedef_functions.html">avoid_private_typedef_functions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_redundant_argument_values.html">avoid_redundant_argument_values</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_renaming_method_parameters.html">avoid_renaming_method_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_return_types_on_setters.html">avoid_return_types_on_setters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_returning_null.html">avoid_returning_null</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_returning_null_for_void.html">avoid_returning_null_for_void</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_returning_this.html">avoid_returning_this</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_setters_without_getters.html">avoid_setters_without_getters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_shadowing_type_parameters.html">avoid_shadowing_type_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_single_cascade_in_expression_statements.html">avoid_single_cascade_in_expression_statements</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_types_on_closure_parameters.html">avoid_types_on_closure_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_unnecessary_containers.html">avoid_unnecessary_containers</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_unused_constructor_parameters.html">avoid_unused_constructor_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_void_async.html">avoid_void_async</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/await_only_futures">await_only_futures</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/camel_case_extensions">camel_case_extensions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/camel_case_types">camel_case_types</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/cascade_invocations">cascade_invocations</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/constant_identifier_names">constant_identifier_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/curly_braces_in_flow_control_structures">curly_braces_in_flow_control_structures</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/deprecated_consistency">deprecated_consistency</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/directives_ordering">directives_ordering</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/do_not_use_environment">do_not_use_environment</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/empty_catches">empty_catches</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/empty_constructor_bodies">empty_constructor_bodies</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/exhaustive_cases">exhaustive_cases</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/file_names">file_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/implementation_imports">implementation_imports</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/leading_newlines_in_multiline_strings">leading_newlines_in_multiline_strings</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/library_names">library_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/library_prefixes">library_prefixes</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/missing_whitespace_between_adjacent_strings">missing_whitespace_between_adjacent_strings</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_runtimeType_toString">no_runtimeType_toString</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/non_constant_identifier_names">non_constant_identifier_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/null_closures">null_closures</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/omit_local_variable_types">omit_local_variable_types</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/one_member_abstracts">one_member_abstracts</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/only_throw_errors">only_throw_errors</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/overridden_fields">overridden_fields</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/package_api_docs">package_api_docs</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/parameter_assignments">parameter_assignments</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_adjacent_string_concatenation">prefer_adjacent_string_concatenation</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_asserts_in_initializer_lists">prefer_asserts_in_initializer_lists</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_collection_literals">prefer_collection_literals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_conditional_assignment">prefer_conditional_assignment</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_constructors_over_static_methods">prefer_constructors_over_static_methods</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_contains">prefer_contains</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_equal_for_default_values">prefer_equal_for_default_values</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_final_fields">prefer_final_fields</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_final_in_for_each">prefer_final_in_for_each</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_final_locals">prefer_final_locals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_for_elements_to_map_fromIterable">prefer_for_elements_to_map_fromIterable</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_function_declarations_over_variables">prefer_function_declarations_over_variables</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_generic_function_type_aliases">prefer_generic_function_type_aliases</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_if_elements_to_conditional_expressions">prefer_if_elements_to_conditional_expressions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_if_null_operators">prefer_if_null_operators</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_initializing_formals">prefer_initializing_formals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_inlined_adds">prefer_inlined_adds</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_interpolation_to_compose_strings">prefer_interpolation_to_compose_strings</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_is_empty">prefer_is_empty</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_is_not_empty">prefer_is_not_empty</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_is_not_operator">prefer_is_not_operator</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_iterable_whereType">prefer_iterable_whereType</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_mixin">prefer_mixin</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_null_aware_operators">prefer_null_aware_operators</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_single_quotes">prefer_single_quotes</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_spread_collections">prefer_spread_collections</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_typing_uninitialized_variables">prefer_typing_uninitialized_variables</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/provide_deprecation_message">provide_deprecation_message</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/public_member_api_docs">public_member_api_docs</a> (set to false) </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/recursive_getters">recursive_getters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/sized_box_for_whitespace">sized_box_for_whitespace</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/slash_for_doc_comments </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/sort_child_properties_last">sort_child_properties_last</a> (set to false)</li>
      <li> <a href="https://dart-lang.github.io/linter/lints/sort_constructors_first">sort_constructors_first</a> (set to false) </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/sort_unnamed_constructors_first">sort_unnamed_constructors_first</a> (set to false) </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/type_annotate_public_apis">type_annotate_public_apis</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/type_init_formals">type_init_formals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unawaited_futures">unawaited_futures</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_await_in_return">unnecessary_await_in_return</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_brace_in_string_interps">unnecessary_brace_in_string_interps</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_getters_setters">unnecessary_getters_setters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_lambdas">unnecessary_lambdas</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_new">unnecessary_new</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_null_aware_assignments">unnecessary_null_aware_assignments</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_null_checks">unnecessary_null_checks</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_null_in_if_null_operators">unnecessary_null_in_if_null_operators</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_nullable_for_final_variable_declarations">unnecessary_nullable_for_final_variable_declarations</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_overrides">unnecessary_overrides</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_parenthesis">unnecessary_parenthesis</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_raw_strings">unnecessary_raw_strings</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_string_escapes">unnecessary_string_escapes</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_string_interpolations">unnecessary_string_interpolations</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_this">unnecessary_this</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_full_hex_values_for_flutter_colors">use_full_hex_values_for_flutter_colors</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_function_type_syntax_for_parameters">use_function_type_syntax_for_parameters</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_if_null_to_convert_nulls_to_bools">use_if_null_to_convert_nulls_to_bools</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_is_even_rather_than_modulo">use_is_even_rather_than_modulo</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_late_for_private_fields_and_variables">use_late_for_private_fields_and_variables</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_named_constants">use_named_constants</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_raw_strings">use_raw_strings</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_rethrow_when_possible">use_rethrow_when_possible</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_setters_to_change_properties">use_setters_to_change_properties</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_string_buffers">use_string_buffers</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_to_and_as_if_applicable">use_to_and_as_if_applicable</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/void_checks">void_checks</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/lines_longer_than_80_chars">lines_longer_than_80_chars</a>  (set to false)</li>
      <li> <a href="https://dart-lang.github.io/linter/lints/flutter_style_todos">flutter_style_todos</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/conditional_uri_does_not_exist">conditional_uri_does_not_exist</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_leading_underscores_for_library_prefixes">no_leading_underscores_for_library_prefixes</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_leading_underscores_for_local_identifiers">no_leading_underscores_for_local_identifiers</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/secure_pubspec_urls">secure_pubspec_urls</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/sized_box_shrink_expand">sized_box_shrink_expand</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_decorated_box">use_decorated_box</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_colored_box">use_colored_box</a> </li>
      </ul>
</details>

<details><summary>Pub rules</summary><br/>
    <ul>
      <li> <a href="https://dart-lang.github.io/linter/lints/package_names.html">package_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/sort_pub_dependencies.html">sort_pub_dependencies</a> </li>
    </ul>
</details>

<details><summary>Analyzer. Errors</summary><br/>
    <ul>
      <li> <a href="https://dart-lang.github.io/linter/lints/always_use_package_imports">always_use_package_imports</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_dynamic_calls">avoid_dynamic_calls</a>  </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_empty_else">avoid_empty_else</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_print">avoid_print</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_relative_lib_imports">avoid_relative_lib_imports</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_returning_null_for_future">avoid_returning_null_for_future</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_slow_async_io">avoid_slow_async_io</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_type_to_string">avoid_type_to_string</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_types_as_parameter_names">avoid_types_as_parameter_names</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/avoid_web_libraries_in_flutter">avoid_web_libraries_in_flutter</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/cancel_subscriptions">cancel_subscriptions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/close_sinks">close_sinks</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/comment_references">comment_references</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/control_flow_in_finally">control_flow_in_finally</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/empty_statements">empty_statements</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/hash_and_equals">hash_and_equals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/iterable_contains_unrelated_type">iterable_contains_unrelated_type</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/list_remove_unrelated_type">list_remove_unrelated_type</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/literal_only_boolean_expressions">literal_only_boolean_expressions</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_adjacent_strings_in_list">no_adjacent_strings_in_list</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_duplicate_case_values">no_duplicate_case_values</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/no_logic_in_create_state">no_logic_in_create_state</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/prefer_void_to_null">prefer_void_to_null</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/test_types_in_equals">test_types_in_equals</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/throw_in_finally">throw_in_finally</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unnecessary_statements">unnecessary_statements</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unrelated_type_equality_checks">unrelated_type_equality_checks</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/unsafe_html">unsafe_html</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_build_context_synchronously">use_build_context_synchronously</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/use_key_in_widget_constructors">use_key_in_widget_constructors</a> </li>
      <li> <a href="https://dart-lang.github.io/linter/lints/valid_regexps">valid_regexps</a> </li>
    </ul>
</details>

<details><summary>Member ordering</summary><br/>
    <ul>
      <li>public-static-const-fields</li>
      <li>private-static-const-fields</li>
      <li>public-static-final-fields</li>
      <li>private-static-final-fields</li>
      <li>public-static-fields</li>
      <li>private-static-fields</li>
      <li>public-final-fields</li>
      <li>private-final-fields</li>
      <li>public-fields</li>
      <li>public-getters-setters</li>
      <li>private-fields</li>
      <li>private-getters-setters</li>
      <li>constructors</li>
      <li>named-constructors</li>
      <li>factory-constructors</li>
      <li>overridden-methods</li>
      <li>public-static-methods</li>
      <li>public-methods</li>
      <li>protected-methods</li>
      <li>private-static-methods</li>
      <li>private-methods</li>
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
