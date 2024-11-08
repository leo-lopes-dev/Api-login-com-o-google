# Configuração da API de Login do Google

> Guia rápido para configurar a autenticação de login com Google em seu projeto.

## Pré-requisitos

- Conta no [Google Cloud Platform](https://console.cloud.google.com/).

## 📋 Passo a Passo

### 1. Criar Conta no Google Cloud Platform
- Acesse o [Google Cloud Platform](https://console.cloud.google.com/) e faça login com sua conta Google, caso ainda não tenha uma.

### 2. Criar o Projeto
1. No console do Google Cloud, selecione **Create Project** para criar um novo projeto.
2. Navegue para **APIs & Services > Credentials**.
3. Selecione **Configurar Consentimento** e escolha o tipo de usuário **Externo**.
4. Configure o registro do aplicativo conforme necessário e retorne para a seção **Credentials**.
5. Clique em **Criar Credenciais** e escolha **OAuth Client ID**.
6. Gere o **OAuth Client ID** de acordo com as especificações do seu projeto.

### 3. Alterações no HTML
1. No seu arquivo HTML, substitua `client_id` pelo OAuth Client ID gerado no passo anterior.
2. Adicione um botão para permitir o login via Google. Ao clicar no botão, o usuário poderá autenticar-se e receber as informações do perfil.
https://developers.google.com/identity/gsi/web/guides/personalized-button?hl=pt-br


Exemplo de funcionamento no video:

https://github.com/user-attachments/assets/8b6cce29-162a-4040-a78a-e8450889a5b2

