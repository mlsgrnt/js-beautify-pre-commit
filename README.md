# js-beautify mirror

Mirror of js-beautify package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For js-beautify: see https://github.com/jshint/jshint

### js-beautifyshint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/mlsgrnt/js-beautify-pre-commit
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: js-beautify
