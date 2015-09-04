# pre-commit sass-lint mirror

Mirror of `sass-lint` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For sass-lint: see https://github.com/sasstools/sass-lint


### Using sass-lint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/elidupuis/pre-commit-hooks
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: sass-lint