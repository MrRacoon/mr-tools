# mr-tools

Tools for maintaining javascript mono-repos

**Current invariants for mr-tools mono-repo packages**

* All subpackages will get published with the same version of common dependencies

* All subpackages will inherit some properties of the root `package.json`

* Versioning isn't smart yet, and will likely only work for typescript/flow projects.
