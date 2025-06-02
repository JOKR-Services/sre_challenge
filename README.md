# Desafio Técnico - Site Reliability Engineer Senior

# **Cenário**

Você foi contratado(a) como SRE Senior em uma startup de e-commerce que está enfrentando problemas de escalabilidade. A empresa possui uma aplicação monolítica que está sendo migrada para microsserviços na AWS, e você precisa projetar e implementar uma solução robusta de infraestrutura.

# **Contexto Atual**

- **Aplicação:** E-commerce com ~50k usuários ativos/dia
- **Arquitetura atual:** Monólito rodando em EC2 com RDS Postgres
- **Problemas identificados:** 
    - Lentidão nos horários de pico (Black Friday chegando!)
    - Falta de observabilidade adequada
    - Deploys manuais e demorados
    - Ausência de disaster recovery

# **Desafio**

Você tem **3 dias** para entregar uma proposta técnica completa que demonstre como você solucionaria esses problemas. O desafio está dividido em partes teóricas e práticas.

# **Instruções de Entrega**

### O que entregar:

1. Funcionalidades descritas no **README.md** de cada etapa
2. Anotações no **README.md** principal do repositório, com instruções de estrutura construida e como executar
3. Anotações específicas de cada parte no **README.md** de cada diretório
4. **Documento de arquitetura** (PDF ou Markdown)
    - Fique a vontade para usar elementos gráficos
5. **Código Terraform** funcional em estrutura modular
6. **GitHub Actions workflows** com steps indicados para entrega de uma aplicação na estrutura provisionada anteriormente
7. **Aplicação exemplo** em qualquer linguagem (opcional, mas valorizado)

### Como entregar:

- Faça um fork do repositório [**sre_challenge**](https://github.com/JOKR-Services/sre_challenge/fork) em um repositório público do github
- O repositório possui os seguintes diretórios:
    - **parte_1_arquitetura** (Contendo markdown ou PDF com solução proposta)
    - **parte_2_terraform** (Com código terraform funcional da estrutura de IAC)
    - **parte_3_workflow** (Com arquivos relacionados a construção de workflow CI/CD para deploy de aplicação na estrutura provisionada)
- Mantenha o commit history organizado, conventional commits é um diferencial.
- Cada parte possui um **README.md** explicando o que é esperado em cada uma delas, além de conter um espaço para anotações onde deve ser preenchido com:
    - Explicação do que foi feito para atingir o resultado entregue
    - Explicação das decisões tomadas envolvendo a solução proposta
    - Tempo gasto em cada parte (aproximadamente(não encana com isso não, só se conseguir um aproximado :D)
    - Qualquer consideração que achar importante
- Após a conclusão, a URL do repositório deve ser enviada para os emails **carlos.santana@soudaki.com** e **renata.azeredo@soudaki.com** com o assunto no formato:
    - NOME_DO_CANDIDATO - Teste prático - SRE Senior

# **Dicas Importantes**

- **Não se preocupe em implementar tudo:** Foque na qualidade sobre quantidade
- **Documente suas decisões:** Explique o "porquê" das escolhas
- **Pense em produção:** Soluções devem ser production-ready
- **Seja pragmático:** Balanço entre ideal e praticável

# **Recursos Úteis**

- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [Terraform AWS Provider Docs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
- [EKS Best Practices](https://docs.aws.amazon.com/eks/latest/best-practices/introduction.html)
- [Github Actions Overview](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

**Contato para dúvidas:** carlos.santana@soudaki.com

Boa sorte! 🚀

# Anotações gerais
// Adicione aqui suas anotações gerais sobre a estrutura utilizada e instruções de como executá-la