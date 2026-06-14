# bootcamp-dio-my-first-copilot
Projeto DIO  - Usando IA Como Copiloto para Criar Novas Features no Seu Projeto

# ❓ Ask
O modo **Ask** é para fazer perguntas e entender coisas, **sem alterar seu código**. Você pode perguntar sobre um arquivo específico, um erro, uma função, uma stack trace ou até conceitos gerais.

O Copiloto lê o contexto do projeto (arquivos abertos, seleção, etc.) e responde como um **“mentor técnico”**, explicando o que está acontecendo e por quê. **Ele não modifica nada** — só analisa e explica.

📄 **Prompt:** [prompts/prompt-ask.md](prompts/prompt-ask.md)

# ✏️ Edit
O modo **Edit** serve para **alterar código existente**. Você seleciona um trecho (ou um arquivo inteiro), descreve o que quer mudar, e o Copiloto aplica a modificação diretamente.

Ideal para:
- refactors
- ajustes de lógica
- melhoria de performance
- mudança de estilo
- conversão de linguagem
- adicionar logs
- tratar erros

Aqui o foco é: **“pegue isso que já existe e transforme”**.

📄 **Prompt:** [prompts/prompt-edit.md](prompts/prompt-edit.md)


# 🧭 Plan
Quando você pede algo mais complexo, o Copiloto pode entrar em um modo de **planejamento**, onde ele **pensa e descreve os passos antes de sair codando**.

Ele:
- divide o problema em etapas
- explica o que vai fazer
- só depois executa

Isso é muito útil para **mudanças grandes**, **novas features** ou quando você quer **validar a abordagem** antes de mexer no código.

📄 **Prompt:** [prompts/prompt-plan.md](prompts/prompt-plan.md)

---
# 🤖 Agent
O **Agent** é o modo mais “autônomo”. Ele pode **navegar pelo projeto**, **criar arquivos**, **modificar múltiplos pontos** e **manter contexto entre passos**, como se fosse um dev júnior trabalhando com você.

Você dá um objetivo (ex.: “implemente login com JWT”) e ele decide o que precisa ser feito em vários arquivos para chegar lá.

📄 **Prompt:** [prompts/prompt-agent.md](prompts/prompt-agent.md)

---

# 📚 Study
O modo **Study** é focado em **aprendizado ativo**, não só em chegar à resposta ou ao código final.

Em vez de simplesmente explicar ou executar, ele:
- ensina e guia o raciocínio
- destaca conceitos e trade-offs
- faz perguntas reflexivas
- avança em progressão gradual de dificuldade

Funciona quase como um **tutor particular**.

📄 **Prompt:** [prompts/prompt-study.md](prompts/prompt-study.md)

---

