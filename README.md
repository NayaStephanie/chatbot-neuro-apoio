# 🤖 Chatbot de Dúvidas sobre Autismo

Bem-vindo(a) ao **Chatbot Neuro Apoio**! Este projeto é um chatbot que responde perguntas relacionadas ao autismo, facilitando o acesso a informações de forma simples e rápida.

## 🚀 Funcionalidades

- 💬 **Respostas automatizadas**: O chatbot responde a perguntas comuns sobre autismo.
- 🔗 **Integração com Dialogflow**: Utilizamos o poder do Dialogflow para processar linguagem natural e responder de maneira adequada.
- 🌐 **Interface Web**: O chatbot roda diretamente no navegador, com uma interface acessível e fácil de usar.

## 🛠️ Tecnologias Utilizadas

- **HTML**: Para estruturar a interface do usuário.
- **CSS**: Para estilizar e tornar a experiência mais visual e agradável.
- **Dialogflow Messenger**: widget embutido que permite a integração direta do chatbot na página.

## ⚙️ Configuração

### Pré-requisitos

- Um navegador atualizado (Google Chrome ou Mozilla Firefox são recomendados).
- Uma conta no [Google Cloud](https://cloud.google.com/) com **Dialogflow** habilitado.

### Configuração do Dialogflow

1. Acesse o [Dialogflow Console](https://dialogflow.cloud.google.com/).
2. Crie um novo agente ou use um existente para o projeto.
3. Configure as intenções e respostas relacionadas ao autismo.
4. No seu agente, vá até a aba Integrations.
5. Habilite o Dialogflow Messenger.
6. Copie o código de integração fornecido e cole no arquivo index.html, logo antes do fechamento da tag <body>.
  Exemplo de código:
   <!-- Dialogflow Messenger code -->
<script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
<df-messenger
  intent="WELCOME"
  chat-title="Autismo Chatbot"
  agent-id="your-agent-id"
  language-code="pt-br"
></df-messenger>

## 💡 Contribuindo
Se você quiser contribuir com este projeto, sinta-se à vontade para abrir uma issue com sugestões ou enviar um pull request. Vamos adorar ter sua ajuda! 😊

## 📜 Licença
Este projeto é licenciado sob a MIT License. Confira o arquivo LICENSE para mais detalhes.



