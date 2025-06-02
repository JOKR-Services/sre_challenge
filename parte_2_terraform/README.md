# **Parte 2: Infrastructure as Code**

### Entregável: Código Terraform

Implemente um repositório de código **Terraform modular** que provisione os recursos considerados na arquitetura anteriormente desenvolvida (Parte 1)

**Atenção:**

- Se atente aos IAM Roles necessários
- Só iremos avaliar a coerência com o **plan** não com o **apply** evitando confusões com problemas de versões de api do cloud provider, por exemplo.
- Leve em consideração os recursos de monitoria/observabilidade, pode usar a stack que for mais confortável (Datadog, CloudWatch, ELK, Grafana, Prometheus, etc...), porém ela deve condizer com a proposta entregue na parte 1
- Provisione todos os recursos que foram levantados na arquitetura proposta por você, a não ser que sejam recursos não disponibilizados pelo provider
- Lembre-se que a estrutura do terraform deve ser modular

**Diferenciais:**
- Uso de remote state com S3 + DynamoDB
- Implementação de diferentes environments
- Security groups bem estruturados
- Tags organizadas

# Anotações da parte 2

// Adicione aqui suas considerações e anotações relacionados a Parte 2