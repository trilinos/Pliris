# Pliris

This repository is a **deprecated package** from the Trilinos project and is no longer being supported. This package was last supported in the [Trilinos version 16.2.0 release branch](https://github.com/trilinos/Trilinos/tree/trilinos-release-16-2-branch).

Please see: https://github.com/trilinos/Trilinos


## How to add a deprecated package to an unsupported version of Trilinos

Although this package is **unsupported** in Trilinos versions greather than 16.2.0, if you want to use this deprecated package with a newer version of Trilinos, you can do the following:

1. Clone the Trilinos repository

```shell
git clone https://github.com/trilinos/Trilinos.git
```

2. Clone this deprecated package repository to the `packages` directory in Trilinos

```
cd Trilinos
git clone https://github.com/trilinos/Pliris.git packages/pliris
```

3. Proceed to configure, build, and use Trilinos with the deprecated package as previously known.

