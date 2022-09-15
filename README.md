# Go Template

My simple template for Go (GoLang) projects. This is **not** an official standard!

## Directories

* `/cmd`: Main application/service directory. Should not be used for package/library projects.
* `/bin`: for binaries. Should be included in `.gitignore`. Should not be used for package/library projects.
* `/pkg`: actual packages that can be exported outside of the project. The packages in this folder could be moved into their own projects if they were too big or used by other a lot of other projects.
* `/internal`: like `/pkg`, but for internal use only. Should not be used for package/library projects.
* `/examples`: code with examples to demo a package (library) for example.

### Other options for bigger projects

* `/scripts`: when projects are big to make the `Makefile` small and simple.
* `/deployments`: deployment's configuration
* `/assets`: assets (images, icons, logos, ...)

## Other non-official templates

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout)
* [SchwarzIT/go-template](https://github.com/SchwarzIT/go-template)
