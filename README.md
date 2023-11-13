# pp02
Practice Project #2 : GitOps using Flux in monorepo pattern

As we choose monorepo pattern for our project, we need to use a single git repository for all the components of our project including infra and application code. 

infra code lies in the "infra/" folder and application code lies in the "app/" folder. 

clusters folder contains different cluster definitions in different folders. Here there are two folders for two clusters i.e. staging and prod.

## Prerequisites
We need the following installations on our local machine to run this projecct locally:
    * Docker Desktop
    * kubectl (Kubernetes CLI)
    * flux (GitOps tool)
    * helm (Package manager for Kubernetes)

We can install all the above tools using the Chocolatey package manager on Windows.

Follow the following links to install the above tools using Chocolatey:

    - [Chocolatey](https://chocolatey.org/install)
    - [Docker Desktop](https://chocolatey.org/packages/docker-desktop)
    - [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/#install-kubectl-binary-using-chocolatey-on-windows)
    - [flux](https://community.chocolatey.org/packages/flux)
    - [helm](https://community.chocolatey.org/packages/helm)



