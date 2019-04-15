# ModelDB: A system to manage ML models

### Prerequisites

- Kubernetes version 1.8+
- kubectl
- Helm

### Deploying ModelDB on Kubernetes

```
git clone https://github.com/VertaAI/modeldb.git
helm install modeldb
```

### What next?

Now that you have modelDB up and running on your K8s cluster, please visit [our user guide and documentation](https://verta.readthedocs.io/en/docs/index.html) to get started.

### Contributing

To build and deploy each of the services running as a part of modelDB, please follow the instructions in the corresponding service's repository to build the docker image for that service. Once the image is pushed to a container registry, update the corresponding property to point to the newly developed image in the [values.yaml](https://github.com/VertaAI/modeldb/values.yaml) file.
