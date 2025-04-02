# ELK Stack Deployment on Kubernetes

## Objective
Deploy Elasticsearch, Kibana and Filebeat on a Kubernetes cluster using YAML files only. Filebeat collects logs from a basic Hello World application and sends them to Elasticsearch. The logs are then visualized in Kibana.

## Stack Components
- Elasticsearch (StatefulSet)
- Kibana (Deployment)
- Filebeat (DaemonSet)
- Hello World application (Deployment)
- All configured using raw Kubernetes YAML files

## Files
- `elasticsearch.yaml`
- `kibana.yaml`
- `filebeat.yaml`
- `ConfigMap.yaml`
- `helloDeployment.yaml`

## Deployment Instructions

Start your local Kubernetes cluster (Minikube) and Docker:

```bash
minikube start
