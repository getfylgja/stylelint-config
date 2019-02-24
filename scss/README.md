# Fylgja stylelint-config (SCSS)

Extra rules for when you use SCSS.

## Usage

Same as for the main stylelint config.
But now add scss to the end to also load theses rules.

```json
{
  "extends": "@fylgja/stylelint-config/scss"
}
```

## List of Rules

For information on what each rule does.
[Checkout the SCSS Stylelint plugin DOC](https://github.com/kristerkari/stylelint-scss/blob/master/src/rules).

### @else

- `at-else-closing-brace-newline-after`: always-last-in-chain
- `at-else-closing-brace-space-after`: always-intermediate
- `at-else-empty-line-before`: never
- `at-else-if-parentheses-space-before`: always

### @extend

- `at-extend-no-missing-placeholder` true

### @function

- `at-function-parentheses-space-before`: never

### @if

- `at-if-closing-brace-newline-after`: always-last-in-chain
- `at-if-closing-brace-space-after`: always-intermediate

### @import

- `at-import-no-partial-leading-underscore`: true

### @mixin

- `at-mixin-argumentless-call-parentheses`: never
- `at-mixin-parentheses-space-before`: never

### At-rule

- `at-rule-no-unknown`: true
  - _Unsets core rule `at-rule-no-unknown`_

### $variable

- `dollar-variable-colon-newline-after`: null
  - _should be always-multi-line but it has a bug with maps_
- `dollar-variable-colon-space-after`: always-single-line
- `dollar-variable-colon-space-before`: never
- `dollar-variable-no-missing-interpolation`: true

### Comments

- `double-slash-comment-whitespace-inside`: always

### Media feature

- `media-feature-value-dollar-variable`: true

### Operator

- `operator-no-newline-after`: true
- `operator-no-newline-before`: true
- `operator-no-unspaced`: true

### Selector

- `selector-no-redundant-nesting-selector`: true