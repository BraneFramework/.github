## The Brane Framework
Regardless of the context and rationale, running distributed applications on geographically dispersed IT resources often comes with various technical and organizational challenges. If not addressed appropriately, these challenges may impede development, and in turn, scientific and business innovation. We have designed and developed Brane to support implementers in addressing these challenges. Brane makes use of containerization to encapsulate functionalities as portable building blocks. Through programmability, application orchestration can be expressed using intuitive domain-specific languages. As a result, end-users with limited or no programming experience are empowered to compose applications by themselves, without having to deal with the underlying technical details.

See the [documentation](https://wiki.enablingpersonalizedinterventions.nl) for more information.


## Contributing
If you're interrested in contributing, please read the [code of conduct](.github/CODE_OF_CONDUCT.md) and [contributing](.github/CONTRIBUTING.md) guide.

Bug reports and feature requests can be created in the [issue tracker](https://github.com/epi-project/brane/issues).


### Development
If you are intending to develop on the framework, then you should [setup your machine for framework compilation](https://wiki.enablingpersonalizedinterventions.nl/user-guide/system-admins/installation/dependencies.html#compilation-dependencies) (install both the dependencies for runtime and compilation).

Then, you can clone this repository (`git clone https://github.com/epi-project/brane.git`) to some folder of choice, and start working on the source code. You can check the [specification](https://wiki.enablingpersonalizedinterventions.nl/specification/) to learn more about the inner workings of the framework, and remember: `make.py` is your biggest friend when compiling the framework, and `branectl` when running or testing it.

Consult the [code documentation](https://braneframework.github.io/brane) for more information about the codebase itself. Note, however, that this is generated for the latest release; to consult it for a non-release, navigate to the root of the repository and run:
```bash
cargo doc --release --no-deps --open
```
