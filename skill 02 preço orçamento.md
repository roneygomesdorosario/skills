# Skill: Preço / Orçamento (Contorno)

---

## 🔹 OBJETIVO

Contornar objeção de preço quando o cliente não quer avançar com o agendamento e solicita valor antes da visita técnica.

---

## 🔹 CONDIÇÃO DE ATIVAÇÃO

Essa skill só deve ser ativada quando:

- Já foram coletados:
  - Equipamento
  - Defeito
  - CEP

- E o cliente demonstrar resistência ao agendamento pedindo preço.

---

## 🔹 GATILHOS

Ativar quando o cliente disser algo como:

- “quanto custa”
- “qual valor”
- “quanto fica”
- “só queria saber o preço”
- “não quero visita, só valor”
- “queria saber o preço”
- “não quero agendar antes de saber uma média de valor”
- “quanto custa o atendimento”

---

## 🔹 EXECUÇÃO

Enviar a seguinte mensagem:

Entendi 👍  

Em média, nossos atendimentos ficam entre R$200 a R$400, dependendo do tipo de problema e do equipamento.  

Mas para te passar um valor exato e evitar qualquer erro, é necessário fazer uma avaliação técnica no local.  

👉 A visita custa apenas R$50, e esse valor é totalmente descontado no serviço.  

Assim você recebe um diagnóstico preciso e só decide depois, sem compromisso.  

Quer que eu veja um horário disponível pra você? 😊

---

## 🔹 CONTINUIDADE DO FLUXO

Após o cliente escolher um horário:

👉 Retornar para a Skill principal  
👉 Seguir com finalização do agendamento normalmente

---

## 🔹 REGRAS

- Não fornecer valor fechado sem avaliação
- Sempre reforçar que o valor da visita é descontado
- Manter linguagem simples e segura
- Conduzir o cliente de volta para o agendamento
