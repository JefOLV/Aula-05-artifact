# aula-05-artifact
Este repositório demonstra um servidor simples escrito em Go e um pipeline de integração contínua (CI/CD) configurado no GitHub Actions. O fluxo de trabalho faz a construção de artefatos para sistemas Linux e Windows e executa um script que envia requisições para o servidor.

Estrutura do Projeto
hello-server.go: Código Go que implementa um servidor básico.
run.sh: Script em shell que faz requisições ao servidor e exibe as respostas.
.github/workflows/go-example.yml: Arquivo que define o pipeline de CI/CD no GitHub Actions, responsável por compilar o servidor e executar os jobs automatizados.
