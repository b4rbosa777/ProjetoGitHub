# GitFlow Automation Script

Este script automatiza o processo de conexão com o GitHub, aplicando o padrão de branching **GitFlow**. Ele auxilia no fluxo de desenvolvimento de projetos, gerenciando pull requests, push, e a criação de novas branches de features.

## Funcionalidades

- **Conexão com o GitHub**: Automatiza o login e conexão com um repositório remoto.
- **GitFlow**: Implementa o padrão de branching GitFlow para organização de desenvolvimento.
- **Criação de Features**: Automatiza a criação de branches de feature para novos desenvolvimentos.
- **Pull Requests**: Automatiza a sincronização com o repositório remoto (fetch, pull).
- **Push Automático**: Envia mudanças para o repositório remoto, seguindo o padrão GitFlow.

## Pré-requisitos

Antes de usar o script, certifique-se de ter instalado:

- [Git](https://git-scm.com/) 
- [GitHub ](https://github.com/)

## Instalação

1. Clone este repositório:

    ```bash
    git clone https://github.com/b4rbosa777/ProjetoGitHub.git
    cd ProjetoGit
    ```

2. Dê permissão de execução aos scripts:

    ```bash
    chmod +x gitflow_automation.sh
    chmod +x branches_automation.sh
    chmod +x pull.sh
    chmod +x commit_push.sh
    ```

## Uso

Execute o script com o seguinte comando:

```bash
./gitflow_automation.sh
./branches_automation.sh
./pull.sh
./commit_push.sh