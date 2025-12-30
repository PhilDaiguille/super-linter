# Test cases for TwigCS linter

This folder contains test cases to validate the integration of the TwigCS linter in super-linter.

- Files containing `good` in their name must pass TwigCS validation.
- Files containing `bad` in their name must fail TwigCS validation.

## twigcs_good_1.twig
Valid Twig file, compliant with TwigCS rules.

## twigcs_bad_1.twig
Non-compliant Twig file (forbidden space before the pipe).
