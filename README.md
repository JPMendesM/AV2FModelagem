# Trabalho AV2 – Modelagem em Programação Matemática

**Autores:** Ricardo André e João Pedro  
**Disciplina:** T293-60/61 – Modelagem em Programação Matemática  
**Tipo de Projeto:** Otimização de Corte de Barras

---

## Tecnologias e Requisitos

- Python 3.13 ou superior
- Bibliotecas Python:
  - OR-Tools
  - Pandas
  - NumPy

Instalação rápida:

```bash
pip install ortools pandas numpy
Descrição

Este projeto resolve o problema de corte de barras usando Programação Linear Inteira (PLI).
O objetivo é:

Atender à demanda de peças de diferentes tamanhos;
Minimizar o número de barras utilizadas;
Reduzir o desperdício de material.

O programa gera padrões de corte possíveis e utiliza o solver SCIP do OR-Tools para encontrar a solução ótima.

Execução
Clone o repositório:
git clone https://github.com/JPMendesM/AV2FModelagem.git
cd AV2FModelagem
Execute o notebook no Jupyter:
jupyter notebook TRABALHO_AV2_Ricardo_André_e_João_Pedro.ipynb
Siga as instruções no notebook para informar:
Tamanho da barra original;
Quantidade de tipos de itens;
Tamanho e demanda de cada item.

O programa exibirá os padrões de corte gerados e a solução ótima com minimização de barras utilizadas e desperdício.

Referências
OR-Tools Python Documentation
Conceitos de Programação Linear Inteira e Problema de Corte de Barras