# vscode-k8s-pack

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/kdcllc/vscode-k8s-pack/CI?label=CI&logo=github)
[![GitHub license](https://img.shields.io/github/license/kdcllc/vscode-k8s-pack)](https://github.com/kdcllc/vscode-k8s-pack/blob/main/LICENSE)

`vscode-k8s-pack` is a Visual Studio Code extension that simplifies Kubernetes (K8s) development by providing a curated set of tools and features for working with Kubernetes clusters. Whether you are a seasoned Kubernetes user or just getting started, this extension aims to enhance your development workflow and productivity.

## Features

- **Kubernetes Cluster Management**: Easily manage multiple Kubernetes clusters and switch between them.
- **Interactive Pod Exploration**: Explore and interact with pods, containers, and logs directly within the editor.
- **Kubernetes Resource Navigation**: Quickly navigate Kubernetes resources, such as Services, ConfigMaps, and Deployments.
- **Auto-Completion and IntelliSense**: Get intelligent code suggestions and autocompletions for Kubernetes manifest files.
- **Kubectl Integration**: Use your existing `kubectl` configuration and commands within VS Code.
- **Kubernetes YAML Validation**: Validate your Kubernetes manifest files in real-time.
- **Extension Settings**: Customize the extension's behavior to suit your needs.

## Hire me

Please send [email](mailto:kingdavidconsulting@gmail.com) if you consider to **hire me**.

[![buymeacoffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/vyve0og)

## Installation

1. Install Visual Studio Code (VS Code) if you haven't already.
2. Open VS Code and go to the Extensions view by clicking the square icon on the sidebar or pressing `Ctrl+Shift+X`.
3. Search for "vscode-k8s-pack" and click the "Install" button.

## Usage

1. After installing the extension, open a Kubernetes manifest file (e.g., `.yaml`, `.yml`) or switch to a Kubernetes-related context in your project.
2. Explore the provided features by using the context menu or keyboard shortcuts.

## Local development

```bash
    npm install
    
    #build extension
    npx vsce package --no-dependencies
```
## Contributing

Contributions to `vscode-k8s-pack` are welcome! If you'd like to contribute, please follow the [contribution guidelines](./.github/CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Maintainers

- [kdcllc](https://github.com/kdcllc) - Project Lead

## Contact

For any inquiries or feedback, please contact us at [info@kingdavidconsulting.com](mailto:info@kingdavidconsulting.com).

