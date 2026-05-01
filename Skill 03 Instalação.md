# Skill: Instalação

---

## 🔹 OBJETIVO

Atender solicitações de instalação de equipamentos e fornecer orçamento com base em tabela, conduzindo para possível agendamento.

---

## 🔹 CONDIÇÃO DE ATIVAÇÃO

Ativar quando o cliente demonstrar interesse em instalação de equipamentos como:

- ar-condicionado
- máquina de lavar
- lava-louça

---

## 🔹 RESPOSTA INICIAL

Se o cliente perguntar:

“vocês fazem instalação de ar-condicionado?”

**Resposta:**

Olá! Fazemos sim 👍  

Para te passar as informações certinhas, me informe:  
• Qual equipamento (ex: ar-condicionado, lava-louça, máquina de lavar)  
• Marca e modelo (se souber)  
• Se já tem ponto de instalação pronto  

Se puder enviar uma foto do local, ajuda bastante 📸

---

## 🔹 COLETA DE DADOS

**Obrigatório:**
- Equipamento
- cep 

**Opcional:**
- Modelo  
- Ponto de instalação pronto  
- Foto  

---

## 🔹 ENDEREÇO + CEP

Perfeito 👍  

Equipamento:  
modelo:  

Para dar sequência:  
👉 Endereço completo  
👉 CEP  
📍 Pode enviar localização

---

## 🔹 ORÇAMENTO (SUPABASE)

Buscar no banco de dados utilizando:

**API URL:**
https://yzwtockppjzqyxsisbxs.supabase.co/rest/v1/

**API KEY:**
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Inl6d3RvY2twcGp6cXl4c2lzYnhzIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzIyNDE1ODQsImV4cCI6MjA4NzgxNzU4NH0.4RfS0uxDG3EVW6PzjMRz62OyIPPNx70T-cqarfOXA7s

**Tabela:**
servisse_prices  

**Processo:**
1. Identificar o equipamento na coluna `category`
2. Buscar o valor correspondente na coluna `price`

---

## 🔹 TABELA DE PREÇO (REFERÊNCIA)

Exemplo:

- Ar-condicionado → R$ XXX  
- Máquina de lavar → R$ XXX  
- Lava-louça → R$ XXX  

---

## 🔹 RESPOSTA PADRÃO

Perfeito 👍  

🔧 Instalação do {equipamento}  
💰 Valor: R$ {valor}  

⚠️ Condições:  
• Não inclui adaptações (elétrica, hidráulica ou estrutura)  
• Não inclui serviços de alvenaria ou ajustes no local  

🚨 ATENÇÃO:  
Para instalação de ar-condicionado, é necessária visita técnica (R$50,00), com valor abatido na instalação após avaliação do local.  

Caso seja necessário algo fora disso, fazemos uma avaliação no local.  

Se quiser, já verifico um horário pra você 😊

---

## 🔹 AGENDAMENTO

Seguir padrão da skill principal:

- Consultar agenda  
- Oferecer horários disponíveis  
- Confirmar com cliente  
