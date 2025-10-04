# Spero Estimate App

Aplicação Flask que lê uma planilha Excel de itens e custos e permite buscar por descrição (ex: "drywall").

## Rodar Localmente

```bash
pip install -r requirements.txt
python app.py
```

Acesse em: http://localhost:5000

## Estrutura

- app.py → Código principal Flask
- estimate.xlsx → Planilha de dados
- static/ → Arquivos estáticos (logo, CSS, JS)
- templates/ → HTML do app
