# 🧩 Modos do Copiloto

Uma guia completa sobre os diferentes modos de interação do GitHub Copilot Chat: **Ask**, **Edit**, **Plan**, **Agent** e **Study**.

---

## 📋 Índice

- [Ask](#-ask-entender) - Tire dúvidas sem alterar código
- [Edit](#️-edit-modificar) - Altere trechos específicos
- [Plan](#-plan-planejar) - Divida tarefas antes de executar
- [Agent](#-agent-automatizar) - Deixe o Copiloto trabalhar sozinho
- [Study](#-study-aprender) - Aprenda enquanto resolve
- [Resumo Rápido](#-resumo-rápido) - Comparação visual

---

## ❓ Ask — Entender

**O que é:** Faça perguntas e compreenda o código sem modificar nada.

**Use quando:**
- Precisa entender um arquivo ou função específica
- Encontra um erro e quer investigar
- Tem dúvidas sobre conceitos gerais
- Quer analisar uma stack trace

**Como funciona:**
O Copiloto lê o contexto do seu projeto (arquivos abertos, seleção, etc.) e responde como um **"mentor técnico"**, explicando o que está acontecendo e por quê.

📄 **Prompt padrão:** `prompts/prompt-ask.md`

---

## ✏️ Edit — Modificar

**O que é:** Altere código existente de forma rápida e direcionada.

**Use quando:**
- Quer fazer um **refactor**
- Precisa ajustar lógica ou performance
- Quer melhorar estilo de código
- Deseja converter entre linguagens
- Quer adicionar logs ou tratamento de erros

**Como funciona:**
Selecione um trecho (ou arquivo inteiro), descreva o que quer mudar, e o Copiloto aplica a modificação diretamente.

💡 **Foco:** "Pegue isso que já existe e transforme"

📄 **Prompt padrão:** `prompts/prompt-edit.md`

---

## 🧭 Plan — Planejar

**O que é:** Para tarefas complexas, o Copiloto planeja os passos antes de executar.

**Use quando:**
- Tem uma mudança grande ou nova feature
- Quer validar a abordagem antes de codificar
- Precisa dividir um problema em etapas

**Como funciona:**
1. O Copiloto divide o problema em etapas
2. Explica a abordagem
3. Só depois executa

💡 **Benefício:** Evita refatorações desnecessárias e decisões precipitadas.

📄 **Prompt padrão:** `prompts/prompt-plan.md`

---

## 🤖 Agent — Automatizar

**O que é:** O modo mais autônomo. O Copiloto pode navegar, criar e modificar múltiplos arquivos.

**Use quando:**
- Tem um objetivo claro (ex.: "implemente login com JWT")
- Quer que o Copiloto tome decisões de arquitetura
- Precisa de mudanças em vários arquivos simultaneamente

**Como funciona:**
Você dá um objetivo e o Copiloto:
- Navega pelo projeto
- Cria/modifica arquivos necessários
- Mantém contexto entre passos
- Funciona como um **dev júnior** trabalhando com você

💡 **Ideal para:** Automação de tarefas repetitivas e features end-to-end.

📄 **Prompt padrão:** `prompts/prompt-agent.md`

---

## 📚 Study — Aprender

**O que é:** Focado em aprendizado ativo, não apenas na resposta final.

**Use quando:**
- Quer entender conceitos por trás do código
- Aprecia um processo educativo
- Tem tempo para aprender progressivamente

**Como funciona:**
Em vez de simplesmente explicar, o Copiloto:
- 🎓 Ensina e guia seu raciocínio
- 🎯 Destaca conceitos e trade-offs
- ❓ Faz perguntas reflexivas
- 📈 Avança com progressão gradual de dificuldade

💡 **Similar a:** Um tutor particular que adapta o ensino ao seu nível.

📄 **Prompt padrão:** `prompts/prompt-study.md`

---

## 🧠 Resumo Rápido

| Modo | Objetivo | Resultado |
|------|----------|-----------|
| **Ask** | ❓ Entender | Explicação sem mudanças |
| **Edit** | ✏️ Modificar | Código alterado |
| **Plan** | 🧭 Planejar | Estratégia definida |
| **Agent** | 🤖 Automatizar | Tarefas executadas |
| **Study** | 📚 Aprender | Conhecimento construído |

---

## 🚀 Como Começar

1. Escolha o modo que melhor se encaixa na sua necessidade
2. Abra o prompt correspondente em `prompts/`
3. Descreva sua tarefa ao Copiloto
4. Acompanhe as sugestões ou automações

---

**Dica:** Combine os modos! Comece com **Ask** para entender, **Plan** para estratégia, **Edit** para ajustes finos, e **Agent** para automação.