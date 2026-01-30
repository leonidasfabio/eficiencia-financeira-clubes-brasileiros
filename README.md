# Análise de Eficiência Financeira dos Clubes Brasileiros

Análise estatística da relação entre investimento em futebol profissional e desempenho esportivo no Campeonato Brasileiro.

---

## 📊 Problema de Negócio

**Pergunta Central:**  
Qual a relação entre o investimento financeiro em futebol profissional e o desempenho esportivo no Campeonato Brasileiro? Gastar mais garante proporcionalmente mais pontos?

**Questões Investigadas:**
- Existe correlação entre custo com futebol e pontuação no Brasileirão?
- Clubes com melhor margem líquida têm desempenho mais consistente?
- O endividamento impacta negativamente os resultados esportivos?
- Qual clube apresenta melhor ROI esportivo (retorno por real investido)?

---

## 🎯 Objetivos

1. Analisar a relação entre investimento financeiro e desempenho esportivo
2. Criar indicadores de eficiência (ROI esportivo, margem líquida, endividamento)
3. Identificar quais variáveis financeiras mais impactam o desempenho através de Regressão Linear
4. Comparar a eficiência de gestão entre clubes com perfis financeiros diferentes

---

## 🔍 Metodologia

Aplicação de técnicas de análise exploratória e modelagem estatística:

**1. Coleta e Preparação de Dados**
- Extração de dados dos balanços patrimoniais oficiais (2020-2024)
- Coleta de classificações do Campeonato Brasileiro
- Tratamento de valores ausentes (imputação com mediana)
- Detecção e tratamento de outliers (método IQR)

**2. Feature Engineering**
- Criação de variáveis derivadas:
  - Margem Líquida (%)
  - ROI Esportivo (pontos por R$ 100M investidos)
  - Endividamento (%)

**3. Análise Exploratória**
- Estatísticas descritivas
- Análise de distribuições
- Visualizações comparativas entre clubes

**4. Análise de Correlação**
- Matriz de correlação
- Identificação de multicolinearidade
- Seleção de variáveis (3 filtros)

**5. Modelagem Estatística**
- Regressão Linear Múltipla (OLS)
- Análise de coeficientes e p-valores
- Validação do modelo (R², RMSE)

---

## 📁 Dados

**Clubes Analisados (5 perfis diversos):**
| Clube | Perfil | Justificativa |
|-------|--------|---------------|
| Flamengo | Alta receita, gestão profissionalizada | Maior orçamento do Brasil |
| Palmeiras | Alto investimento, resultados consistentes | Múltiplos títulos recentes |
| Corinthians | Alta dívida, grande torcida | Caso de crise financeira |
| Botafogo | SAF recente (2022) | Recuperação financeira rápida |
| Fortaleza | Baixo custo, eficiência | Modelo de gestão sustentável |

**Período:** 2020-2024 (5 temporadas completas)

**Variáveis Coletadas:**

*Financeiras (balanços patrimoniais):*
- Receita Total (R$ milhões)
- Custo com Futebol Profissional (R$ milhões)
- Dívida Total (R$ milhões)
- Ativo Total (R$ milhões)
- Resultado Líquido (R$ milhões)

*Esportivas (classificação CBF):*
- Pontos no Brasileirão
- Posição final (1-20)

*Variáveis Criadas (Feature Engineering):*
- Margem Líquida = (Resultado Líquido / Receita Total) × 100
- ROI Esportivo = Pontos / (Custo Futebol / 100)
- Endividamento = (Dívida Total / Ativo Total) × 100

**Fontes:**
- Balanços Patrimoniais: Sites oficiais dos clubes
- Classificações: CBF / Wikipedia

---

## 💡 Principais Insights

*[A ser preenchido após conclusão da análise]*

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Operações numéricas
- **Matplotlib / Seaborn** - Visualizações
- **Statsmodels** - Regressão Linear (OLS)
- **Jupyter Notebook** - Ambiente de desenvolvimento

---

## 📂 Estrutura do Projeto

```
eficiencia-financeira-clubes/
│
├── data/
│   └── clubes_brasileirao.csv          # Dataset principal
│
├── notebooks/
│   └── analise_eficiencia_clubes.ipynb # Análise completa
│
├── README.md                            # Este arquivo
└── requirements.txt                     # Dependências Python
```

---

## 🚀 Como Reproduzir

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/eficiencia-financeira-clubes

# Navegue até o diretório
cd eficiencia-financeira-clubes

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook
jupyter notebook notebooks/analise_eficiencia_clubes.ipynb
```

---

## 📫 Contato

Fabio Leonidas - leonidasfabio@gmail.com  
LinkedIn: https://www.linkedin.com/in/fabioleonidas/

---

## 📄 Licença

Este projeto está sob a licença MIT.
