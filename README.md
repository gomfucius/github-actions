# github-actions

Testing GitHub Actions

For context, please view: https://stackoverflow.com/questions/61238849/github-actions-if-contains-function-not-working-with-env-variable

The fix is to use `if: contains(env.VARIABLE)`.
