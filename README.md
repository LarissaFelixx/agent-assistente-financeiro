# 💰 Agent Assistente Financeiro

Este projeto implementa um **Agente Inteligente** utilizando [LangChain](https://www.langchain.com/) e a API da OpenAI.  
O objetivo é fornecer um **assistente financeiro pessoal**, capaz de responder perguntas em português brasileiro, dando dicas de **finanças pessoais, economia e investimentos**.

---

## ⚙️ Tecnologias utilizadas
- Python 3.10+
- [LangChain](https://python.langchain.com/)
- [LangChain OpenAI](https://pypi.org/project/langchain-openai/)
- [DuckDuckGo Search](https://pypi.org/project/duckduckgo-search/)
- [LangChain Experimental Utilities](https://python.langchain.com/docs/integrations/utilities/python_repl)

---

## 🚀 Funcionalidades
- Responde perguntas financeiras em português.
- Executa cálculos com Python REPL para apoiar as respostas.
- Busca informações atualizadas na internet com DuckDuckGo.
- Usa um agente do tipo **ReAct** para raciocínio passo a passo.

---

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/agent-assistente-financeiro.git
cd agent-assistente-financeiro

---

# 🔑 Configuração da API

export OPENAI_API_KEY="sua_chave_aqui"   # Linux/Mac
setx OPENAI_API_KEY "sua_chave_aqui"     # Windows

## ▶️ Como executar

python main.py

---

## 📝 Exemplo de uso

Minha renda é de R$10000 por mês, o total de minhas despesas é de R$ 8500 mais R$1000 de aluguel.
Quais dicas de investimento você me dá?

---

