
# Kubernetes - Comandos e Configurações

Este repositório contém exemplos e comandos para trabalhar com Kubernetes usando o Kind (Kubernetes in Docker).

## 📚 Documentação

Para uma explicação detalhada dos conceitos e comandos, consulte nossa documentação completa:

**[📖 Documentação Completa - Kubernetes](https://www.notion.so/Kubernets-1e4b8ca18b488003a2edc57ed2fc3fba?source=copy_link)**

## 🚀 Comandos Básicos

### Criando um cluster com o kind:

```sh
kind create cluster --name <your-name>
```

### Listando os clusters criados com o kind:

```sh
kind get clusters
```

### Obtendo informação de um cluster:

```sh
kubectl cluster-info <cluster-name>
```

## 📁 Arquivos de Configuração

Este repositório contém exemplos de:
- `deployment.yml` - Configuração de deployment
- `service.yaml` - Configuração de serviço
- `replicaset.yaml` - Configuração de replicaset