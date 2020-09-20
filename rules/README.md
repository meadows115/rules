Rule

Rules are patterns and anti-patterns for your software stack. All Rules are grouped in Bundles.

Rule Bundles are groups of related rules that can usefully be applied to new projects, or serve as exemplars for the CodeLingo community.

Bundles using a single language are in that language's directory, cross domain bundles have their own directories.

## Writing a bundle

Bundles have a README to explain their purpose with an ideas section for rules yet to be implemented. Each rule should have an associated src file (or other example of queried domain) and an expected output at `./testdata/<rule_name>.<language_extension>` and `./testdata/<rule_name>.json` respectively.
<!-- TODO: build simple  `lingo test-rule <dir>` command -->
