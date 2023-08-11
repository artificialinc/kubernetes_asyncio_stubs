# publish for artificial

```bash
poetry config repositories.pypi-internal https://<redacted>/repository/pypi-internal/
poetry config http-basic.pypi-internal <redacted> $GH_TOKEN
poetry publish -r pypi-internal
```
