📌 README.md — Stock Screener Automation

🧠 Descrição (até 250 caracteres)
Automação completa para seleção das melhores ações e FIIs da B3 com critérios técnicos, processamento diário de dados, histórico consolidado e exportação para Excel. Ideal para tomada de decisão e monitoramento contínuo de investimentos.

📊 Stock Screener Automation — B3 🇧🇷

Ferramenta automatizada de análise fundamentalista para encontrar as melhores oportunidades em Ações e FIIs, baseada em múltiplos, risco e liquidez.

🛠️ Tecnologias & Dependências








📈 Recursos do Projeto

✅ Coleta automatizada de dados do Fundsexplorer (opcional)
✅ Limpeza e padronização das colunas financeiras
✅ Aplicação de filtros customizáveis (DY, P/VP, PL, Volatilidade etc.)
✅ Seleção das Top 20 oportunidades
✅ Exportação para Excel (snapshot do dia)
✅ Geração e atualização de histórico de resultados
✅ Estrutura pronta para rodar diariamente

🧮 Exemplo de Saída (Top 20 FIIs)
🗂️ Estrutura do Repositório
📦 stock-screener-automation
 ┣ 📂 data
 ┃ ┣ 📂 input/    → entrada manual (opcional)
 ┃ ┣ 📂 output/   → snapshots atuais
 ┃ ┗ 📂 old/      → históricos acumulados
 ┣ 📂 src
 ┃ ┗ 📜 Investimentos_filtros.py
 ┣ 📘 README.md
 ┗ 📜 requirements.txt

▶️ Execução
pip install -r requirements.txt
python src/Investimentos_filtros.py

🚀 Próximos passos

Integrar dados de ações via API / webscraping

Deploy automático semanal (GitHub Actions)

Dashboard Power BI / Streamlit

👤 Autor

Ítalo Petricioni Statonato
📍 São Paulo — Brasil
Analista de Dados | Automação | Analytics para Investimentos

🎯 Automatizar para investir melhor: decisões baseadas em dados, não em achismos.
