# Estratégia de Comunicação com Cliente SORRIMED

> Documento interno (não enviar). Define **canal, prazo, formato esperado e fluxo de trabalho** para recolher os dados que faltam na landing page.

---

## 🎯 Contexto

- **Cliente:** Clínica Dentária SORRIMED, Lisboa
- **Estado atual:** Landing page publicada em `https://danielrodrigues83.github.io/sorrimed/` com dados placeholder
- **Objetivo:** Recolher dados reais do cliente para finalizar a landing com conteúdo personalizado (morada, horários, equipa, testemunhos, etc.)
- **Material enviado ao cliente:** QUESTIONARIO-CLIENTE.md

---

## 📡 Canais disponíveis — análise

| Canal | Conforto para cliente (PT) | Conforto para nós | Recomendação |
|---|---|---|---|
| **Email** | ⭐⭐⭐⭐ — profissional, deixa tempo para pensar | ⭐⭐⭐⭐ — registo, anexos, fácil de organizar | ✅ **Principal** |
| **WhatsApp** | ⭐⭐⭐⭐⭐ — mais usado em PT para conversas rápidas | ⭐⭐⭐ — funciona, mas mistura tudo num chat | ✅ **Suporte** (cliente diz preferir, usar) |
| **Telegram** | ⭐⭐ — raro em Portugal para clientes B2B | ⭐⭐⭐ — bom para nós, mas cliente não está familiarizado | ❌ Não recomendado para 1º contacto |
| **Chamada telefónica** | ⭐⭐⭐⭐⭐ — muito natural para clientes PT | ⭐⭐ — difícil registar tudo; tom só serve para follow-up | ✅ **Follow-up** se cliente não responder |
| **Reunião presencial** | ⭐⭐⭐⭐⭐ — ideal para dúvidas | ⭐⭐⭐⭐⭐ — clarifica dúvidas complexas | ⌛ Considerar se cliente pedir |

### Conclusão

**Canal principal: Email** (formal, rastreável, profissional — alinhado com o tom de uma clínica dentária).
**Canal de suporte: WhatsApp** (mais rápido para follow-ups curtos).
**Eskalada: chamada telefónica** (se o cliente não responder em 5 dias úteis).

> ⚠️ **Decisão-chave:** o cliente **não tem WhatsApp** confirmado nesta fase. Por isso o email é o canal mais seguro para o primeiro contacto. Depois da primeira resposta, perguntar se preferem continuar por email ou mudar para WhatsApp para combinar mais rapidamente.

---

## ⏰ Prazo e fluxo temporal

### Cronograma recomendado

| Dia | Ação |
|---|---|
| **Dia 0** (hoje) | Envio do email + questionário em anexo |
| **Dia +2** | Mensagem curta de follow-up se não houver resposta ("Recebeu bem?") |
| **Dia +5** | Follow-up mais detalhado: "Estamos a aguardar a vossa resposta para darmos continuidade" |
| **Dia +7** | Última tentativa — chamada direta se não houver resposta |
| **Dia +8 em diante** | Considerar estender prazo ou reagendar — **não bloquear o projeto à espera** |

### Prazo pedido

**5–7 dias úteis** (= 1 semana + 1 dia) — prazo realista, dá ao cliente tempo para:
- Rever o questionário
- Recolher informação que não tem de memória (fotos, números de seguro, etc.)
- Pedir informação a outros membros da equipa

---

## 📥 Formato esperado das respostas

Aceitar **qualquer** dos seguintes formatos — o cliente não precisa de seguir nenhum template rígido:

### ✅ Formatos aceitáveis (por ordem de preferência)

1. **Questionário preenchido em ficheiro** (Word / Google Docs / PDF anotado) — melhor para nós, mais fácil de extrair dados
2. **Respostas em texto corrido no email** — natural, basta copiar/colar para o questionário internamente
3. **Áudio / mensagem de voz** — preferível via WhatsApp; nós transcrevemos e estruturamos
4. **Fotografias de papéis / cartões / folhetos** — útil para dados que o cliente já tem noutros suportes (ex.: cartão da clínica, lista de preços)
5. **Respostas parciais** — se não conseguir responder a tudo, que responda ao essencial (ver checklist no final do questionário)

### ❌ O que **não** pedimos

- Respostas detalhadas com redação cuidada
- Cumprimento literal da estrutura do questionário
- Logos ou materiais gráficos profissionais (telemóvel basta)
- Que respondam tudo de uma vez — podem enviar em várias mensagens

---

## 🤝 Como lidar com respostas parciais

Cenário: cliente responde só a 3 secções das 7.

**A nossa abordagem:**
1. Agradecer a resposta
2. Fazer **2–3 perguntas curtas de follow-up** sobre o que falta — não despejar tudo de novo
3. Marcar mentalmente o que vai ficar em branco por agora (e perguntar informalmente mais tarde)

---

## 🔄 Workflow interno depois de receber respostas

```
1. Receber respostas
   ↓
2. Consolidar tudo num documento único (notes/sorrimed-dados.md)
   ↓
3. Atualizar /opt/data/projects/sorrimed/index.html com os dados reais
   ↓
4. Substituir imagens-placeholder por fotos reais (se enviadas)
   ↓
5. Testar localmente → publicar nova versão
   ↓
6. Enviar email de confirmação ao cliente com resultado pronto
   ↓
7. Solicitar aprovação antes de qualquer publicação definitiva
```

---

## ✉️ Mensagens modelo (prontas a copiar)

### Follow-up Dia +2 (leve)

> Assunto: `Re: SORRIMED · Questionário para finalizar a landing page`
>
> Olá `gr[Nome]`, espero que esteja bem.
> Só um toque rápido para confirmar que recebeu o questionário que enviei há 2 dias. Se tiver alguma dúvida ou preferir responder por outro formato (WhatsApp, chamada, áudio), diga-me — quero é facilitar o processo.
>
> Obrigado!

### Follow-up Dia +5 (mais firme)

> Assunto: `Re: SORRIMED · Próximos passos`
>
> Olá `gr[Nome]`,
> Estou a fazer o ponto da situação dos projetos em curso. Sobre o questionário da SORRIMED: como ficou? Quer agendar uma chamada rápida de 10 min para eu puxar pela informação diretamente consigo?
>
> Sem pressa, mas gostaríamos de fechar esta fase até final da próxima semana.

### Resposta a primeira receção de dados (Dia 0 de retorno)

> Assunto: `Re: SORRIMED · Recebido, obrigado!`
>
> Olá `gr[Nome]`,
> Recebi tudo e está ótimo. Muito obrigado pela colaboração rápida — vou começar a atualizar o site com base nas vossas respostas.
> Previsão: `gr[X dias úteis]` para vos enviar a versão personalizada para aprovação.
> Se me recordar a esclarecer mais alguma coisa, envio um email rápido.
>
> Obrigado!

---

## 📋 Checklist antes de enviar o email inicial

- [ ] Substituir todos os `[colchetes]` em EMAIL-CLIENTE.md pelos dados reais
- [ ] Confirmar que QUESTIONARIO-CLIENTE.md está em formato anexável (recomendo converter para PDF: mais profissional, abre em qualquer dispositivo)
- [ ] Escolher tom de saudação adequado ao nível de formalidade já estabelecido com a SORRIMED
- [ ] Verificar que o link da landing publicada está correto e acessível
- [ ] Confirmar que temos o **email correto** do destinatário
- [ ] Definir lembrete no calendário para follow-up Dia +2

---

## 💡 Notas finais

- **Paciência:** clínicas dentárias são negócios ocupados — atrasos são normais, não sinal de desinteresse
- **Tom:** sempre cordial e profissional — é uma clínica médica, o cliente valoriza sobriedade
- **Não bloquear:** se o cliente demorar mais de 7 dias, não insistir agressivamente; seguir com o que temos e completar depois
- **Reciprocidade:** facilitar a vida do cliente (aceitar áudio, fotos, etc.) gera mais e melhores respostas do que exigir formato rígido