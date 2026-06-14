# bootcamp-dio-my-first-copilot
Projeto DIO - Usando IA Como Copiloto para Criar Novas Features no Seu Projeto

Este repositório contém os prompts de diretrizes técnicas para configurar seu copiloto (com a personalidade e tom da assistente **Cortana**) em diferentes modos de atuação no dia a dia do desenvolvimento.

---

# ❓ Ask
O modo **Ask** é focado em leitura, ideal para fazer perguntas e entender o ecossistema, **sem alterar seu código**. Você pode perguntar sobre um arquivo específico, debugar um erro, analisar uma stack trace ou tirar dúvidas conceituais gerais.

O Copiloto lê o contexto do projeto e responde como um **mentor técnico**, explicando o que está acontecendo e sugerindo caminhos sem aplicar mudanças automáticas.

📄 **Prompt:** [prompts/prompt-ask.md](prompts/prompt-ask.md)

---

# 🧭 Plan
Para cenários de maior complexidade, o modo **Plan** entra em ação como um arquiteto técnico. Ele **estrutura e descreve todos os passos macro antes de realizar qualquer alteração de código**.

Ele divide o problema em fases lógicas, mapeia riscos de compatibilidade e gera checklists de implementação. Ideal para planejar **grandes refatorações, migrações de sistemas ou novas features complexas**.

📄 **Prompt:** [prompts/prompt-plan.md](prompts/prompt-plan.md)

---

# 🤖 Agent Code
O modo **Agent Code** é o executor puro e autônomo. Sua missão é **transformar requisitos e planos em código real, completo e implementável** (módulos, classes, configurações e testes), tratando edge cases e gerando entregas prontas para o projeto.

Diferente do modo Ask, aqui o foco é a ação: criar novos arquivos, estruturar endpoints e gerar blocos de códigos completos com alta qualidade de engenharia.

📄 **Prompt:** [prompts/prompt-agent.md](prompts/prompt-agent.md)

---

# 📚 Study
O modo **Study** é focado em **aprendizado ativo** e engenharia reversa de conceitos, atuando como uma tutora especializada em programação.

Em vez de apenas entregar a resposta ou o código pronto, ele foca nos fundamentos: explica a intuição por meio de analogias, destrincha conceitos técnicos pelo nome, mapeia trade-offs (vantagens e desvantagens), expõe armadilhas comuns e faz perguntas reflexivas adaptadas ao seu nível de senioridade.

📄 **Prompt:** [prompts/prompt-study.md](prompts/prompt-study.md)
