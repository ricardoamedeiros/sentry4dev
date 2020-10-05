# Sentry 4Dev

# Agenda

* [ ] O que é?
* [ ] Criar projeto básico Spring Boot
* [ ] Configuração básica do Sentry no projeto
  * [ ] Criar o projeto no Sentry
  * [ ] Configurar o SENTRY_DSN no projeto. ref.: [documentação oficial](https://docs.sentry.io/platforms/java/configuration/)
  * [ ] Configurar a biblioteca de integração do Sentry. ref.: [documentação oficial](https://docs.sentry.io/platforms/java/guides/spring-boot/)
  * [ ] Realizar deploy na AWS ECS (v1 do .gitlab-ci.yml). [documentação oficial](https://docs.gitlab.com/ee/ci/cloud_deployment/)
* [ ] Simular um erro
* [ ] Analisar o erro no Sentry
* [ ] Configurar integração com Gitlab (v2 do .gitlab-ci.yml). ref.: [documentação oficial](https://docs.sentry.io/product/releases/)
 
**Variáveis do gitlab para deploy na AWS e integração com Sentry

- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- SENTRY_AUTH_TOKEN
- SENTRY_LOG_LEVEL
- SENTRY_ORG
