# default DARK theme for fastapi-simple-auth

This is DARK theme for [fastapi-simple-auth](https://github.com/yaroslaff/fastapi-simple-auth), it's based on [fastapi-simple-auth-basic](https://github.com/yaroslaff/fastapi-simple-auth-basic) (see basic theme to learn how to create new themes).

Differences between basic theme and this repo:
1. This `README.md` file
2. package names in `pyproject.toml`
3. variables at top of [styles.css](fastapi_simple_auth_dark/statics/css/styles.css)
4. `update.py` script in this repository

This theme uses these colors (in `styles.css`):
~~~
:root {
  --background: #000; /* Background color */
  --background-footer: #222; /* Background color */
  --background-content: #222; /* Background color */
  --text-color: #ccc; /* Text color */
}
~~~

`update.py` automatically copies files from locally installed [fastapi-simple-auth-basic](https://github.com/yaroslaff/fastapi-simple-auth-basic) repo and patches `styles.css`.

