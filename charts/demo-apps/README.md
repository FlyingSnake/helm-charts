# demo-apps

![Version: 0.1.1](https://img.shields.io/badge/Version-0.1.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.0](https://img.shields.io/badge/AppVersion-1.0-informational?style=flat-square)

A Helm chart for Kubernetes

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| dotnetCarter.enabled | bool | `true` |  |
| dotnetCarter.image | string | `"flyingsnake12/demo-dotnet-carter:1.0.0"` |  |
| dotnetCarter.podAnnotations | object | `{}` |  |
| dotnetCarter.replicas | int | `1` |  |
| frontWeb.enabled | bool | `true` |  |
| frontWeb.image | string | `"flyingsnake12/demo-react:nginx-otel-stable"` |  |
| frontWeb.ingress.annotations | object | `{}` |  |
| frontWeb.ingress.className | string | `"nginx"` |  |
| frontWeb.ingress.enabled | bool | `true` |  |
| frontWeb.ingress.hosts | string | `"demo-web.example.com"` |  |
| frontWeb.ingress.tls | list | `[]` |  |
| frontWeb.podAnnotations | object | `{}` |  |
| frontWeb.replicas | int | `1` |  |
| golangEcho.enabled | bool | `true` |  |
| golangEcho.image | string | `"flyingsnake12/demo-golang-echo:1.0.2"` |  |
| golangEcho.podAnnotations | object | `{}` |  |
| golangEcho.replicas | int | `1` |  |
| ingress.annotations | object | `{}` |  |
| ingress.className | string | `"nginx"` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts | string | `"demo.example.com"` |  |
| ingress.tls | list | `[]` |  |
| javaSb.enabled | bool | `true` |  |
| javaSb.image | string | `"flyingsnake12/demo-java-springboot:1.0.2"` |  |
| javaSb.podAnnotations | object | `{}` |  |
| javaSb.replicas | int | `1` |  |
| mysql.env.MYSQL_ROOT_PASSWORD | string | `"root"` |  |
| mysql.image | string | `"flyingsnake12/demo-mysql:1.0.0"` |  |
| nodejsExpress.enabled | bool | `true` |  |
| nodejsExpress.image | string | `"flyingsnake12/demo-nodejs-express:1.0.2"` |  |
| nodejsExpress.podAnnotations | object | `{}` |  |
| nodejsExpress.replicas | int | `1` |  |
| phpFlight.enabled | bool | `true` |  |
| phpFlight.image | string | `"flyingsnake12/demo-php-flight:1.0.2"` |  |
| phpFlight.podAnnotations | object | `{}` |  |
| phpFlight.replicas | int | `1` |  |
| pythonFlask.enabled | bool | `true` |  |
| pythonFlask.image | string | `"flyingsnake12/demo-python-flask:1.0.0"` |  |
| pythonFlask.podAnnotations | object | `{}` |  |
| pythonFlask.replicas | int | `1` |  |

