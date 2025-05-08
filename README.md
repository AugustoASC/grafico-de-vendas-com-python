# 🐍 Gráfico de Vendas com Python e ECharts

**Dashboard interativo usando Apache ECharts adaptado de JavaScript para Python com Streamlit**

---

## 📘 Descrição

Este projeto apresenta a criação de gráficos interativos com a biblioteca [Apache ECharts](https://echarts.apache.org/en/index.html), originalmente baseada em JavaScript, mas aqui adaptada com **Python** via **Streamlit** e **streamlit-echarts**.

O dashboard permite alternar dinamicamente entre diferentes tipos de visualização:

* Gráfico de Linhas
* Gráfico de Barras
* Gráfico de Pizza (Rosca)
* Gráfico Misto (linha + barra)

---

## ⚖️ Tecnologias Utilizadas

* [Streamlit](https://streamlit.io/): Para criação da interface web.
* [streamlit-echarts](https://pypi.org/project/streamlit-echarts/): Wrapper para integrar Apache ECharts com Streamlit.
* Python 3.9+

---

## ⚙️ Como Executar Localmente

1. **Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/grafico-de-vendas-com-python.git
cd grafico-de-vendas-com-python
```

2. **Crie um ambiente virtual (opcional, mas recomendado):**

```bash
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
```

3. **Instale as dependências:**

```bash
pip install streamlit streamlit-echarts
```

4. **Execute a aplicação:**

```bash
streamlit run app.py
```

---

## 🔢 Exemplo de Uso

Ao iniciar o app, o usuário pode selecionar o tipo de gráfico desejado através de um menu lateral. O gráfico muda dinamicamente de acordo com a seleção, exibindo:

* **Total de vendas por dia da semana** (Gráfico de Linhas)
* **Receita mensal** (Gráfico de Barras)
* **Distribuição de acessos por canal** (Gráfico de Pizza)
* **Comparativo entre dados de linha e barra** (Gráfico Misto)

---

## 🌐 Visual do Projeto

Abra [app.py](./app.py) no navegador com o comando acima e veja os gráficos se atualizando em tempo real conforme a interação do usuário.

---

## 🚀 Objetivo

Demonstrar como é possível aproveitar os exemplos e a lógica do Apache ECharts (feito originalmente em JavaScript) para criar visualizações poderosas e responsivas com Python.

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
