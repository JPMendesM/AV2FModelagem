# Otimização de Corte de Barras (Cutting Stock Problem)

![Python](https://img.shields.io/badge/python-3.13+-blue.svg)
![OR-Tools](https://img.shields.io/badge/Library-OR--Tools-orange.svg)

Este projeto utiliza **Programação Linear Inteira (PLI)** para resolver o problema clássico de corte de barras. O sistema calcula a melhor forma de cortar barras de tamanho padrão para atender a uma demanda específica, focando na eficiência produtiva.

---

## 👥 Autores
* **Ricardo André**
* **João Pedro**
* **Disciplina:** T293-60/61 – Modelagem em Programação Matemática

---

## 🛠️ Tecnologias e Requisitos

Para rodar este projeto, você precisará de:
* **Python 3.13** ou superior.
* Bibliotecas: `ortools`, `pandas`, `numpy`.

### Instalação das Dependências
```bash
pip install ortools pandas numpy
🚀 Como Executar
Clone o repositório:

Bash
git clone [https://github.com/JPMendesM/AV2FModelagem.git](https://github.com/JPMendesM/AV2FModelagem.git)
cd AV2FModelagem
Inicie o Ambiente:
Abra o arquivo principal no Jupyter Notebook ou VS Code:

Bash
jupyter notebook "TRABALHO_AV2_Ricardo_André_e_João_Pedro.ipynb"
Entrada de Dados:
Ao executar as células, o programa solicitará os seguintes parâmetros:

Tamanho da barra original (bruta).

Quantidade de tipos de itens (peças) necessários.

Tamanho e demanda de cada item individual.

📊 Saída de Dados
Ao final da execução, o script gera:

Padrões de Corte: Lista de combinações possíveis que respeitam o limite da barra.

Solução Ótima: Quantidade exata de cada padrão a ser utilizado.

Métricas de Desempenho: Total de barras usadas e porcentagem de desperdício.

📚 Referências
Google OR-Tools Python Documentation

Conceitos de Programação Linear Inteira e Problema de Corte de Barras