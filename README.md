
# install-pinned/mypy
<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->
<!-- ⚠️auto-generated from init.py, do not edit manually ⚠️-->
<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->

![](https://shields.io/badge/python-%3E=3.8-blue)
![](https://shields.io/badge/runner%20os-Windows%20%7C%20Linux%20%7C%20macOS-blue)

Securely install the latest [mypy](https://pypi.org/project/mypy/) release from PyPI.

This action installs a pinned version of **mypy** and all its dependencies,         making sure that file hashes match. Pinning your dependencies:

 1. Stops software supply chain attacks.
 2. Makes sure your CI does not break unexpectedly.

## Usage

In your GitHub Actions workflow, use this action like so:

```yaml
      - name: Install mypy from PyPI
        uses: install-pinned/mypy@afa6e92d97a7d0525672d2e53c76cd6a31a99100  # 1.10.0
```

You can [set up Dependabot](https://docs.github.com/en/code-security/dependabot/working-with-dependabot/keeping-your-actions-up-to-date-with-dependabot#example-dependabotyml-file-for-github-actions)
so that your pins are updated regularly.

## Alternatives

This action is a relatively simple wrapper around [poetry](https://python-poetry.org/)         and is most useful if there is no existing `requirements.txt`/`poetry.lock`/... infrastructure in place.         If you already pin all your dependencies in a single place, you don't need it!

## More Details

See the [@install-pinned README](https://github.com/install-pinned) for details.
