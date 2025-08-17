# APP DAVI — v8.1 (Importar Extrato + Dashboard com Gráficos)

- **Importar Extrato** (CSV/PDF) com mapeamento de colunas, normalização BR, anti-duplicata e integração automática no Livro Caixa.
- Balde **Imprevistos** criado/uso automático quando marcado.
- Datas `DD/MM/YY`, moeda BRL, alertas/toasts, aportes e vitória automática.
- **Dashboard com gráficos**: Barras (Receitas x Despesas mês), Pizza (participação por balde), Linha (Fluxo diário 30 dias).

## Rodar
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python seed.py   # opcional
streamlit run app.py --server.port 8504 --server.headless true
```
