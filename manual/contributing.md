## Issues

Report issues and suggest features and improvements on the
[GitHub issue tracker](https://github.com/bbatsov/rubocop/issues). Don't ask
questions on the issue tracker - use the [support channels](support.md) instead.

If you want to file a bug, please provide all the necessary info listed in
our issue reporting template (it's loaded automatically when you create a
new GitHub issue).

## Patches

Patches in any form are always welcome! GitHub pull requests are even better! :-)

Before submitting a patch or a pull request make sure all tests are
passing and that your patch is in line with the [contribution
guidelines](https://github.com/bbatsov/rubocop/blob/master/.github/CONTRIBUTING.md).

See also. [development.md](development.md)

## Documentation

Good documentation is just as important as good code.

Consider improving and extending the
this manual and the
[community wiki](https://github.com/bbatsov/rubocop/wiki).

### Working on the Manual

The manual is generated from the markdown files in the
[doc](https://github.com/bbatsov/rubocop/tree/master/manual) folder of RuboCop's
GitHub repo and is published to [Read the Docs](readthedocs.org). The
[MkDocs](http://www.mkdocs.org/) tool is used to convert the markdown sources to
HTML.

To make changes to the manual you simply have to change the files under
`manual`. The manual will be regenerated automatically when changes to those files
are merged in `master` (or the latest stable branch).

You can install `MkDocs` locally and use the command `mkdocs serve` to see the
result of changes you make to the manual locally:

```
$ cd path/to/rubocop/repo
$ mkdocs serve
```

If you want to make changes to the manual's page structure you'll have to edit
[mkdocs.yml](https://github.com/bbatsov/rubocop/blob/master/mkdocs.yml).

## Donations

You can support the development of RuboCop via
[Salt](https://salt.bountysource.com/teams/rubocop) and
[Gratipay](https://www.gratipay.com/rubocop).

[![Support via Gratipay](https://cdn.rawgit.com/gratipay/gratipay-badge/2.1.3/dist/gratipay.png)](https://gratipay.com/rubocop)
