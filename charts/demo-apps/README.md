# demo-apps

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.0](https://img.shields.io/badge/AppVersion-1.0-informational?style=flat-square)

A Helm chart for Kubernetes

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| golangEcho.image | string | `"flyingsnake12/demo-golang-echo:1.0.1"` |  |
| golangEcho.podAnnotations | object | `{}` |  |
| golangEcho.replicas | int | `1` |  |
| ingress.annotations | object | `{}` |  |
| ingress.className | string | `"nginx"` |  |
| ingress.enabled | bool | `true` |  |
| ingress.hosts | string | `"demo.example.com"` |  |
| ingress.tls | list | `[]` |  |
| javaSb.image | string | `"flyingsnake12/demo-java-springboot:1.0.1"` |  |
| javaSb.podAnnotations | object | `{}` |  |
| javaSb.replicas | int | `1` |  |
| mysql.env.MYSQL_DATABASE | string | `"test"` |  |
| mysql.env.MYSQL_ROOT_PASSWORD | string | `"root"` |  |
| mysql.image | string | `"flyingsnake12/demo-mysql:1.0.0"` |  |
| nodejsExpress.image | string | `"flyingsnake12/demo-nodejs-express:1.0.1"` |  |
| nodejsExpress.podAnnotations | object | `{}` |  |
| nodejsExpress.replicas | int | `1` |  |
| phpFlight.image | string | `"flyingsnake12/demo-php-flight:1.0.1"` |  |
| phpFlight.podAnnotations | object | `{}` |  |
| phpFlight.replicas | int | `1` |  |

