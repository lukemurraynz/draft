<div id="top"></div>

<br />
<div align="center">
  <h1 align="center">Draft</h1>
  <p align="center">
    A tool to help developers hit the ground running with Kubernetes.
    <br />
    <a href="https://github.com/Azure/draft"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Azure/draft/issues">Report Bug</a>
    ·
    <a href="https://github.com/Azure/draft/issues">Request Feature</a>
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

Draft makes it easier for developers to get started building apps that run on Kubernetes by taking a non-containerized application and generating the Dockerfiles, Kubernetes manifests, Helm charts, Kustomize configuration, and other artifacts associated with a containerized application. Draft can also generate a GitHub Action workflow file to quickly build and deploy applications onto any Kubernetes cluster.   

* `draft create` adds the minimum required files for your deployment to the project directory.
* `draft setup-gh` automates the Github OIDC setup process for your project.
* `draft generate-workflow` generates a Github workflow for automatic build and deploy to AKS.
* `draft update` automatically updates your application to be internet accessible.

Draft requires Go version 1.18.x.
* Go
  ```sh
  go version
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Azure/draft.git
   ```
2. Build the binary
   ```sh
   make
   ```
3. Add the binary to your path
   ```sh
   mv draft $GOPATH/bin/
   ```

## License

Distributed under the MIT License. See [LISENCE](https://github.com/Azure/draft/blob/main/LICENSE) for more information.

## Trademark Notice
Trademarks This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow Microsoft’s Trademark & Brand Guidelines. Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party’s policies.

