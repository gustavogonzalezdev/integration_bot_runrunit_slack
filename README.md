# Slack Runrun.it Integration Bot

## Visão Geral

Este projeto tem como objetivo criar um bot que integra o Runrun.it com o Slack, permitindo que notificações de eventos do Runrun.it sejam enviadas automaticamente para um canal do Slack. Esta integração ajudará equipes a se manterem informadas sobre o progresso de tarefas, atualizações de projetos e outros eventos importantes sem precisar sair do Slack.

## Tecnologias Utilizadas

- **Golang (Go)**: Linguagem de programação utilizada para desenvolver o backend do projeto.
- **Gorilla Mux**: Framework de roteamento HTTP para Go, utilizado para criar endpoints e manipular requisições HTTP.
- **Slack API**: API do Slack para enviar mensagens e notificações para canais do Slack.
- **Runrun.it API**: API do Runrun.it para obter dados de tarefas, projetos e eventos, e configurar webhooks.
- **Serviços de Nuvem**: Como Google Cloud Platform (GCP), Amazon Web Services (AWS) ou Heroku para hospedar o aplicativo.

## Funcionalidades

- **Receber notificações do Runrun.it**: Configurar webhooks no Runrun.it para enviar notificações de eventos (como criação de tarefas, atualizações de status) para o bot.
- **Enviar mensagens para Slack**: Processar as notificações recebidas e enviar mensagens formatadas para um canal específico do Slack.
- **Configuração de Webhooks**: Instruções sobre como configurar webhooks no Runrun.it para integrar com o endpoint criado.

## Configuração e Instalação

### Pré-requisitos

- Conta no Runrun.it com acesso à API.
- Conta no Slack e permissão para criar e configurar aplicativos/bots.
- Token de acesso da API do Slack.

### Passos para Configuração

1. **Clone este repositório:**
   ```sh
   git clone https://github.com/usuario/repositorio.git
   cd repositorio
