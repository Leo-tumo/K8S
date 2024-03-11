# K8S

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Installation


```bash
$ kubectl apply -f example.yaml
```

## Usage



```bash
$ kubectl get pods
```

## Configuration



```yaml
apiVersion: v1
kind: Pod
metadata:
  name: example-pod
spec:
  containers:
  - name: nginx
    image: nginx:latest
    ports:
    - containerPort: 80
```

## Documentation


- [Kubernetes Ingress Controllers List](https://docs.google.com/spreadsheets/d/191WWNpjJ2za6-nbG4ZoUMXMpUK8KlCIosvQB0f-oq3k/edit?pli=1#gid=907731238)
- [Kubernetes Ingress Documentation](https://kubernetes.io/docs/concepts/services-networking/ingress/)
- [NGINX Ingress Controller Documentation](https://kubernetes.github.io/ingress-nginx/)
- [Traefik Ingress Controller Documentation](https://doc.traefik.io/traefik/providers/kubernetes-ingress/)
- [HAProxy Ingress Controller Documentation](https://haproxy-ingress.github.io/)

## Contributing


1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request

## License


This project is licensed under the [MIT License](LICENSE).
