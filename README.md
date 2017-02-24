# jasmin-theme-django

Django app providing Django base templates for JASMIN websites.

The static files from the [JASMIN theme package](https://github.com/cedadev/jasmin-theme)
are included as a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules),
for local development, but production installs should use a static content server.

## Installation

`jasmin-theme-django` can be installed directly from Github using pip:

```
$ pip install git+https://github.com/cedadev/jasmin-theme-django.git
```

## Developing

When developing `jasmin-theme-django`, you must ensure that you include the
`--recursive` flag when cloning to ensure that the `jasmin-theme` submodule is
properly initialised:

```
$ git clone --recursive git@github.com:cedadev/jasmin-theme-django.git
```
