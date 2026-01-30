# Análise de Eficiência Financeira dos Clubes Brasileiros

Análise quantitativa da relação custo-benefício entre investimento em futebol profissional e desempenho esportivo no Campeonato Brasileiro.

---

## 📊 Problema de Negócio

**Pergunta Central:**  
Qual clube brasileiro apresenta a melhor relação custo-benefício entre investimento em futebol profissional e desempenho esportivo no Campeonato Brasileiro?

**Questões Investigadas:**
- Gastar mais em futebol garante proporcionalmente mais pontos?
- Existe um ponto ótimo de investimento (lei dos rendimentos decrescentes)?
- Clubes com boa gestão financeira (margem positiva) têm desempenho mais consistente?
- Endividamento elevado impacta negativamente a performance esportiva?

---

## 🎯 Objetivos

1. Identificar padrões na relação entre investimento financeiro e resultados esportivos
2. Calcular métricas de eficiência financeira (ROI esportivo, margem líquida)
3. Desenvolver modelo preditivo de desempenho baseado em variáveis financeiras
4. Ranquear clubes por eficiência de gestão (custo vs resultado)

---

## 🔍 Metodologia

Aplicação do framework CRISP-DM adaptado para análise esportiva:

1. **Coleta de Dados:** Balanços patrimoniais oficiais (2020-2024) + classificações do Brasileirão
2. **Preparação:** Tratamento de outliers, imputação, feature engineering
3. **Análise Exploratória:** Estatísticas descritivas, visualizações, correlações
4. **Modelagem:** Regressão Linear Múltipla (OLS) para identificação de drivers de performance
5. **Validação:** Análise de coeficientes, p-valores, R², RMSE

---

## 📁 Dados

**Clubes Analisados:**
- Flamengo (alta receita, gestão profissional)
- Palmeiras (alto investimento, resultados consistentes)
- Corinthians (alta dívida, grande torcida)
- Botafogo (SAF recente, recuperação rápida)
- Fortaleza (baixo custo, alta eficiência)

**Período:** 2020-2024 (5 temporadas)

**Variáveis Coletadas:**
- **Financeiras:** Receita total, Custo com futebol, Dívida total, Ativo total, Resultado líquido
- **Esportivas:** Pontos no Brasileirão, Posição final
- **Engineered:** Margem líquida (%), ROI esportivo, Endividamento (%)

**Fontes:**
- Balanços Patrimoniais: Sites oficiais dos clubes
- Classificações: CBF / Wikipedia

---

## 💡 Principais Insights

*[A ser preenchido após análise]*

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação de dados
- **NumPy** - Operações numéricas
- **Matplotlib / Seaborn** - Visualizações
- **Statsmodels** - Modelagem estatística (OLS)
- **Jupyter Notebook** - Ambiente de desenvolvimento

---

## 🚀 Como Reproduzir
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/eficiencia-financeira-clubes

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook
jupyter notebook analise_eficiencia_clubes.ipynb
```

---

## 📫 Contato

Fabio Leonidas - leonidasfabio@gmail.com  
LinkedIn: https://www.linkedin.com/in/fabioleonidas/

---

## 📄 Licença

Este projeto está sob a licença MIT.
