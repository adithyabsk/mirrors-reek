reek mirror
===========

Mirror of reek gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For reek: see https://github.com/troessner/reek


### Using reek with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/adithyabsk/mirrors-reek
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: reek


**Based on**: https://github.com/pre-commit/mirrors-ruby-lint