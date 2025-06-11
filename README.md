# 🌟 Vagalume
Vagalume é um agente inteligente que automatiza a busca e candidatura em vagas de emprego, iluminando novas oportunidades de forma rápida e eficiente.


> **vaga** + **lume** → clareza para quem busca recolocação no mercado ✨

## 🧠 Visão Geral
O Vagalume foi desenvolvido para facilitar a vida de quem está procurando emprego. Ele automatiza etapas essenciais do processo, economizando tempo e esforço para o usuário. O agente é capaz de:

- 🔍 Raspar dados do LinkedIn do usuário para obter informações profissionais.
- 🧭 Pesquisar vagas de emprego na internet de acordo com o cargo informado.
- 📝 Preencher automaticamente formulários de candidatura usando Selenium com os dados extraídos do LinkedIn.

## 🎨 Identidade Visual

O nome Vagalume surgiu da junção das palavras:

- Vaga (de emprego)
- Lume (luz, claridade)

Assim como o vagalume, o agente traz clareza e visibilidade para novas oportunidades no mercado de trabalho.

## 🚀 Como usar

Clone este repositório:
```
git clone https://github.com/SarahBatagioti/bertoti-vagalume
```
```
cd bertoti-vagalume
```
Instale as dependências:
```
pip install -r requirements.txt
```
Instale o Ollama:
https://ollama.com/download 

Abra o cmd e baixe o modelo que iremos usar:
```
ollama pull llama3.2:3b
```

Depois rode o modelo:
```
ollama run llama3.2:3b
```
Após isso, crie uma conta em https://smith.langchain.com/o/fc513002-0bca-4fc5-989e-c1f7cc3a8080/ e gere uma api key, para configurar o nosso .env. Repita o mesmo em https://app.tavily.com

Após pegar as api keys, preencher seu .env com essas informações, além do seu email e senha para login no linkedin:
```
LANGCHAIN_API_KEY=""
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
LANGCHAIN_PROJECT="ollama-langchain"
TAVILY_API_KEY=""
EMAIL = ""
PASSWORD = ""
```
