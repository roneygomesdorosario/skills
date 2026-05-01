# Skill: Retorno / Garantia

---

## 🔹 OBJETIVO

Atender solicitações de retorno técnico e verificar se o atendimento está dentro do prazo de garantia (90 dias), conduzindo para agendamento de retorno ou novo atendimento.

---

## 🔹 RESPOSTA INICIAL

Olá! 👍  

Entendi, vamos verificar isso pra você.  

Pode me informar o número da ordem de serviço?

---

## 🔹 IDENTIFICAÇÃO DA OS (SUPABASE)

Buscar no banco de dados utilizando:

**API URL:**
https://yzwtockppjzqyxsisbxs.supabase.co/rest/v1/

**API KEY:**
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Inl6d3RvY2twcGp6cXl4c2lzYnhzIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzIyNDE1ODQsImV4cCI6MjA4NzgxNzU4NH0.4RfS0uxDG3EVW6PzjMRz62OyIPPNx70T-cqarfOXA7s

**Tabela:**
service_orders  

**Processo:**
1. Identificar o número da OS na coluna `id`
2. Buscar a data de emissão na coluna `date timestampzt`

---

## 🔹 VERIFICAÇÃO DE GARANTIA

Verificar se a data do atendimento está dentro de 90 dias.

---

### 🔴 CASO: FORA DA GARANTIA

Se estiver fora do prazo:

**Resposta:**

Verifiquei aqui e o atendimento está fora do prazo de garantia.  

Mas podemos agendar uma nova visita técnica para avaliar o equipamento novamente.  

💰 A visita tem o valor de R$50, que é descontado no serviço caso seja aprovado.  

Quer que eu veja um horário disponível pra você? 😊  

👉 Retornar para Skill principal para continuidade do atendimento  

---

### 🟢 CASO: DENTRO DA GARANTIA

Se estiver dentro do prazo:

**Resposta:**

Perfeito 👍  

Seu atendimento está dentro do prazo de garantia.  

Vamos agendar um retorno técnico para verificar o ocorrido.  

---

## 🔹 AGENDAMENTO

Seguir padrão da skill principal:

- Consultar agenda  
- Oferecer horários disponíveis  
- Confirmar com cliente  

---

## 🔹 CONFIRMAÇÃO FINAL

✅ Retorno agendado com sucesso!  

📅 Data: {data}  
⏰ Horário: {hora}  

🔧 Equipamento: {equipamento}  
🔁 Tipo: Retorno em garantia  
📍 Endereço: {endereço}  
📌 CEP: {cep}  

Nossa equipe estará no local no horário marcado 👍
