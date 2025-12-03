# Platform Services

`platform-services` is a centralized repository containing configuration files for all platform-level services that are deployed using [ArgoCD](https://argo-cd.readthedocs.io/)
. This includes Helm values, Kubernetes manifests, and any other configuration definitions required for the applications running on the platform.

> [!NOTE] 
> This repository does not contain ArgoCD "App of Apps" configurations. Those are maintained in a separate repository.

## Getting Started

### Step 1. ⚙️ Prepare Environment for Installation

#### 📦 Install Binaries

The installation requires the following binaries in the local environment:

+ [**kubectl**](https://kubernetes.io/docs/tasks/tools/)
+ [**helm**](https://helm.sh/docs/intro/install/)