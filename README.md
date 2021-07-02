# nginx-substitution

## Setup

* Update absolute path for `root` in [nginx.conf](https://github.com/searchingforlife/nginx-substitution/blob/main/nginx.conf#L12) to point to this repo.
* Now, we can run

```sh
# Use same absolute path as in "root" above.
nginx -c /absolute-path-to/nginx-substitution/nginx.conf
```

* Open [http://localhost:8080/](http://localhost:8080/)

Inspecting browser console output as well as the actual HTML output in dev tools, we can see that only the first script gets added/injected.
