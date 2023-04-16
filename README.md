# project-template

This is a template repository that you can use as a starting point for your own projects. It includes a `.devcontainer` directory that provides a configuration for Visual Studio Code's [Remote - Containers](https://code.visualstudio.com/docs/devcontainers/containers) extension.

The `devcontainer` is a preconfigured development environment that can be used to develop, test, and build the project.

To use the devcontainer, simply open the repository in Visual Studio Code and select the "Reopen in Container" option when prompted. This will start the development container and open a new Visual Studio Code window with the devcontainer environment. You can then use the environment to develop and build the project.

## Usage
To use this template, simply run the following command in your terminal:

```sh
git clone https://github.com/buo/project-template project-template \
  && pushd project-template \
  && cat FILES | xargs -I{} cp -rf {} .. \
  && popd \
  && rm -rf project-template
```

## Contributing

If you find any issues with this template or have any suggestions for improvement, please feel free to open an issue or submit a pull request.