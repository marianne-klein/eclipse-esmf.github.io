# ESMF documentation site

This repository contains the setup for the documentation of the [Eclipse Semantic Modeling Framework](https://projects.eclipse.org/projects/dt.esmf)
(ESMF) that is available at [https://eclipse-esmf.github.io/](https://eclipse-esmf.github.io/). Please note that there are no Github releases as such, the released artifact is the website itself.

The documentation is built using [https://antora.org/](Antora). Refer to site.yml to see which
documentation sources are included.

## Building locally

To build the documentation locally, you will need to have Java installed. To build, run:

```sh
./mvnw generate-resources -Pantora
```

After that, the documentation is available at `build/site/index.html`.
