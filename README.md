# Go Template

My simple template for Go (GoLang) projects. This is **not** an official standard

## Directories

* `/cmd`: Main application/service directory. Should not be used for packages (libraries).
* `/bin`: for binaries. Should be included in `.gitignore`. Should be deleted for packages (libraries).
* `/pkg`: actual packages that can be exported outside of the project. You could remove it from the project if it's used by a lot of other projects or its getting big.
* `/internal`: like `/pkg`, but for internal use only. Should not be used for packages (libraries).
* `/examples`: code with examples to demo a package (library) for example.

### Other options for bigger projects

* `/scripts`: when projects are big to make the `Makefile` small and simple.
* `/deployments`: deployment's configuration
* `/assets`: assets (images, icons, logos, ...)

## Other non-official templates

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout)
* [SchwarzIT/go-template](https://github.com/SchwarzIT/go-template)
