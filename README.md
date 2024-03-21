# A simple Go dev container

A sandbox dev container for Go development. Go is a cross-platform, statically typed and compiled proramming language. A dev container (development container) is a self-contained dev environment with a Docker container allowing portability and instant creation of a dev environment without manual installation.

## dev container

I'm using a dev container so I don't have to install Go on my Mac. All I need a is a Docker daemon, which in my case is `colima` and VS Code with the dev container extension.

## Known Issues

This dev container does not appear to start Flask as a `CMD` at the end of the Dockerfile, but as `postCreateCommand` in the `devcontainer.json` works.

## Resources

[Coder cloud development environment repo](https://github.com/coder/coder)

[Go](https://go.dev/)

[Dev Container specification](https://containers.dev/implementors/spec/)