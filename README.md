# ML Project Template

Estrutura padrão para projetos de Machine Learning.

## Setup

```bash
=========================
📌 TEMPLATE PASSO A PASSO – PROJETO ML
=========================

1️⃣ CRIAR NOVO REPOSITÓRIO A PARTIR DO TEMPLATE
-------------------------------------------------
1. Abra seu Template Repository no GitHub (ml-project-template)
2. Clique no botão verde: "Use this template"
3. Dê um nome ao projeto novo (ex: fraud-api)
4. Escolha Public ou Private
5. Clique "Create repository"
✅ Projeto criado no GitHub

2️⃣ CLONAR PROJETO NO VSCode
-------------------------------------------------
1. Abra o VSCode
2. Abra o terminal (Terminal → New Terminal)
3. Clone o repositório:

   git clone https://github.com/SEU_USUARIO/fraud-api.git
   cd fraud-api
   code .

✅ Projeto aberto no VSCode

3️⃣ CRIAR E ATIVAR AMBIENTE CONDA
-------------------------------------------------
1. Criar ambiente do projeto:

   conda env create -f environment.yml

2. Ativar ambiente:

   conda activate ml-project-template

3. (Opcional) Instalar/atualizar pacotes pip:

   pip install -r requirements.txt

✅ Ambiente pronto para uso

4️⃣ TESTAR AMBIENTE
-------------------------------------------------
1. Crie arquivo teste.py com:

   import sys, pandas, numpy, sklearn
   print("Ambiente OK:", sys.executable)

2. Rode → deve mostrar o Python do seu ambiente Conda

✅ Ambiente funcionando

5️⃣ COMEÇAR A TRABALHAR
-------------------------------------------------
- Analise de dados → notebooks/
- Limpeza e funções → src/preprocess.py
- Treino → src/train.py
- Predição → src/predict.py
- Salvar modelos → models/
- Interface / app → app/app.py (Streamlit ou FastAPI)
