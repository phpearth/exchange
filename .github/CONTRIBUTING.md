# Contributing guidelines for the PHP earth exchange repository.

Contributing to this repository is as simple as possible. You can open an
[issue](https://github.com/phpearth/exchange/issues) or open a pull request.
Typos and grammatical corrections are perfectly fine as well!

## Contributing procedure

* Fork the repository over GitHub

* Set up your local repository and set a remote branch for future updates

  ```bash
  git add remote upstream git://github.com/phpearth/exchange.git
  git config branch.master.remote upstream
  ```

  That way you can update your repository (when the `upstream` gets updated) and
  automatically pull `upstream` commits:

  ```bash
  git pull
  ```

* Create a new Git branch (for instance, `patch-1`):

  ```bash
  git checkout -b patch-1
  ```

  This ensures that your repository will not need rebasing when the `upstream`
  gets updated.

* Make changes to the `patch-1` branch

* Commit and push to your GitHub repository

  ```bash
  git add .
  git commit -m "my new changes"
  git push origin
  ```

* Send a pull request
