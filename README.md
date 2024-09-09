# aula-05-artifact
Aula 05 - CI/CD com GitHub Actions: Hello Server
Este repositório contém um exemplo de um servidor em Go e um fluxo de trabalho (workflow) CI/CD no GitHub Actions. O workflow inclui a construção de um artefato para Linux e Windows, além de executar um script que realiza chamadas para o servidor.

Estrutura do Projeto
hello-server.go: Arquivo Go que define um servidor simples.
run.sh: Script de shell que realiza chamadas para o servidor e verifica as respostas.
.github/workflows/go-example.yml: Workflow do GitHub Actions que compila o servidor e executa os jobs CI/CD.
