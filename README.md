# nginx-substitution

## Setup

* Update absolute path for `root` in [nginx.conf](https://github.com/searchingforlife/nginx-substitution/blob/main/nginx.conf#L12)
* Now, we can run

```sh
# Use same absolute path as in "root" above.
nginx -c /absolute-path-to/nginx-substitution/nginx.conf
```
