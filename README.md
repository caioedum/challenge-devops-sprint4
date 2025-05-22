# Projeto: Web API .NET com CI/CD no Azure DevOps

Este repositório contém uma Web API desenvolvida em .NET, com automação completa de build, testes e deploy contínuo (CI/CD) utilizando Azure DevOps e publicação automática em um Azure Web App.

---

## 📦 Sobre o Projeto

- **Tecnologia:** .NET (Web API)
- **Repositório:** Azure Repos
- **CI/CD:** Azure Pipelines (Classic)
- **Deploy:** Azure App Service (Web App)

---

## 🚀 Pipeline CI/CD

O projeto utiliza pipelines clássicos do Azure DevOps para garantir integração e entrega contínua:

- **Build:** Restaura dependências, compila o projeto e executa testes automatizados.
- **Testes:** Executa testes unitários e pode publicar resultados de cobertura de código.
- **Publicação:** Gera artefatos (ZIP) prontos para deploy.
- **Release:** Realiza o deploy automático dos artefatos para um Azure Web App.

Link da organização: https://dev.azure.com/MR554025/challenge-devops-sprint4

O pipeline é disparado automaticamente a cada commit na branch principal, garantindo que toda alteração passe por build, testes e deploy sem intervenção manual.

---

## 🛠️ Como funciona o fluxo

1. **Commit no repositório:** Toda alteração no código dispara automaticamente o pipeline de build (CI).
2. **Build e Testes:** O Azure DevOps compila o projeto, executa os testes e publica os artefatos.
3. **Release:** O pipeline de release pega os artefatos gerados e faz o deploy no Azure Web App.
4. **Deploy contínuo:** O deploy é feito automaticamente, garantindo que a versão mais recente esteja sempre disponível no ambiente configurado.

---

## 👥 Integrantes do Grupo

- **Caio Eduardo Nascimento Martins - RM554025**
- **Julia Mariano Barsotti Ferreira - RM552713**
- **Leonardo Gaspar Saheb - RM553383**

## 📝 Licença

🚀 Desenvolvido para o curso de Análise e Desenvolvimento de Sistemas - FIAP.
