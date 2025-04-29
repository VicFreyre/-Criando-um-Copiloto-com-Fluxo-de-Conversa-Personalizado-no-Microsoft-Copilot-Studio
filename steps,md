# ⚙️ Parte Prática – Criando um Copiloto com Fluxo de Conversa no Microsoft Copilot Studio

## 1. Acessar o Microsoft Copilot Studio
- Acesse: [https://copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)
- Faça login com sua conta Microsoft.

---

## 2. Criar um Novo Copiloto
- Clique em **“Criar” > “Copiloto personalizado”**.
- Dê um nome ao seu bot (ex: `AtendimentoBot`).
- Escolha o idioma e clique em **Criar**.

---

## 3. Criar um Tópico de Conversa
- No menu lateral, clique em **“Tópicos” (Topics)**.
- Clique em **“Novo tópico”**.
- Nomeie o tópico (ex: `Agendamento de Atendimento`).
- Em **Gatilhos (Triggers)**, adicione frases como:
  - “Quero agendar atendimento”
  - “Preciso de ajuda”
  - “Agendar consulta”

---

## 4. Construir o Fluxo de Conversa
Após salvar o tópico, clique em **“Ir para o autor de tópicos”** (Go to authoring canvas). Monte o fluxo com mensagens e perguntas. Exemplo:

```plaintext
🤖 Bot: Olá! Posso te ajudar a agendar um atendimento. Qual o seu nome?
👤 Usuário: [nome] → (armazenar em uma variável)

🤖 Bot: Obrigado, {nome}! Qual dia você prefere?
👤 Usuário: [data] → (armazenar em uma variável)

🤖 Bot: Perfeito! Seu atendimento está agendado para o dia {data}. Deseja mais alguma coisa?
👤 Usuário: [Sim/Não]
