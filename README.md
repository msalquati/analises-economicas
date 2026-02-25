# Análises Econômicas

Repositório de análises econômicas e financeiras aplicadas ao mercado brasileiro, desenvolvidas com Python.

As análises buscam combinar rigor metodológico com aplicabilidade prática, utilizando dados públicos de fontes como Banco Central do Brasil, B3 e Yahoo Finance.

---

## Estrutura

### `macro/`
Análises de conjuntura macroeconômica e impacto de eventos sobre variáveis financeiras.

| Notebook | Descrição |
|----------|-----------|
| `haddad_controle_sintetico.ipynb` | Estimação do impacto da fala do Ministro Haddad (nov/2024) sobre o BRL via metodologia de Controle Sintético |

### `dca/` *(em construção)*
Simulações de Dollar Cost Averaging (aportes recorrentes) aplicadas a diferentes ativos e períodos.

### `portfolio/` *(em construção)*
Análise e otimização de carteiras de investimento.

### `derivativos/` *(em construção)*
Simulações e estratégias com derivativos negociados na B3.

---

## Metodologias utilizadas

- Controle Sintético
- Regressão linear e otimização quadrática
- Backtesting de estratégias
- Otimização de portfólio (Markowitz, Ledoit-Wolf)
- Análise de fatores (factor investing)

---

## Ferramentas

- Python 3 via Google Colab
- Principais bibliotecas: `pandas`, `numpy`, `matplotlib`, `cvxpy`, `scikit-learn`, `scipy`, `yfinance`, `python-bcb`

---

## Aviso

As análises disponibilizadas neste repositório têm fins exclusivamente educativos e de pesquisa. Não constituem recomendação de investimento.
