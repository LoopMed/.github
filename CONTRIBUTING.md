# Guia de Contribuição — LoopMed

Obrigado pelo interesse em contribuir com os projetos da LoopMed! Este guia descreve como você pode participar do desenvolvimento das nossas soluções de saúde.

## 📋 Pré-requisitos

Antes de começar, por favor:

1. Leia o nosso [Código de Conduta](CODE_OF_CONDUCT.md) e concorde com seus termos.
2. Verifique se já existe uma *issue* ou *pull request* aberta para o que você deseja fazer.
3. Para mudanças maiores, abra uma *issue* primeiro para discutir a proposta antes de começar a codificar.

## 🐛 Reportando Bugs

Use o template de [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md) e inclua:

- Uma descrição clara e concisa do problema
- Passos para reproduzir o comportamento
- Comportamento esperado vs. comportamento atual
- Screenshots ou logs relevantes
- Ambiente (SO, versão do browser, versão do app, etc.)

## 💡 Sugerindo Melhorias

Use o template de [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md) e inclua:

- Uma descrição clara da melhoria proposta
- A motivação e o contexto do problema que ela resolve
- Exemplos de uso

## 🔀 Enviando Pull Requests

1. **Fork** o repositório e crie uma branch a partir de `main`:
   ```bash
   git checkout -b feature/minha-feature
   ```

2. **Faça suas alterações**, seguindo os padrões de código do projeto.

3. **Escreva ou atualize testes** relevantes para as mudanças realizadas.

4. **Garanta que todos os testes passem**:
   ```bash
   # Veja o README de cada repositório para os comandos específicos
   npm test   # ou yarn test, pytest, etc.
   ```

5. **Faça o commit** seguindo o padrão [Conventional Commits](https://www.conventionalcommits.org/):
   ```
   feat: adiciona suporte a autenticação via SSO
   fix: corrige cálculo de dosagem em mg/kg
   docs: atualiza guia de instalação
   ```

6. **Abra o Pull Request** preenchendo o [template](.github/PULL_REQUEST_TEMPLATE.md) disponível.

## 🔒 Vulnerabilidades de Segurança

**Não abra issues públicas para vulnerabilidades de segurança.** Consulte nossa [Política de Segurança](SECURITY.md) para o processo de divulgação responsável.

## 📐 Padrões de Código

- Siga as convenções de estilo já definidas em cada repositório (`.editorconfig`, linters, formatters).
- Escreva código legível com nomes descritivos.
- Documente funções públicas e APIs.
- Mantenha os commits atômicos e bem descritos.

## 🌍 Idioma

- Issues e Pull Requests podem ser escritos em **português (BR)** ou **inglês**.
- Comentários no código preferencialmente em **inglês**.

## ❓ Dúvidas

Tem alguma dúvida? Entre em contato pelo e-mail **dev@loopmed.com.br** ou abra uma *Discussion* no repositório correspondente.

---

Agradecemos sua contribuição para tornar a saúde mais acessível e eficiente! 💙
