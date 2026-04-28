# 📊 Calculadora de Média FIAP

Este projeto foi desenvolvido como um trabalho solicitado em aula, com o objetivo de aplicar conceitos básicos de programação em Python, incluindo entrada de dados, estruturas condicionais, listas e cálculos de média ponderada.

## 🧠 Descrição

O sistema calcula a média final de um aluno com base nos seguintes critérios:

* **CPs (Checkpoints)**

  * São inseridas várias notas
  * As **duas maiores notas** são consideradas
  * Peso total: **20%**

* **Sprints**

  * Média entre duas notas
  * Peso total: **20%**

* **Global Solution**

  * Nota única
  * Peso total: **60%**

O cálculo é realizado para dois semestres:

* **1º semestre:** peso de 40%
* **2º semestre:** peso de 60%

A média final é a combinação dos dois semestres.

---

## ⚙️ Funcionalidades

* Entrada dinâmica de notas de CPs
* Seleção automática das melhores notas
* Cálculo de médias ponderadas
* Verificação de status do aluno:

  * ✅ Aprovado (média ≥ 6)
  * ⚠️ Exame (média entre 4 e 6)
  * ❌ Reprovado (média < 4)
* Cálculo adicional com nota de exame (quando necessário)

---

## 🧮 Lógica do Sistema

1. Calcula média das CPs (top 2)
2. Calcula média das Sprints
3. Soma parcial e verifica desempenho
4. Adiciona nota da Global Solution
5. Calcula média do semestre
6. Repete o processo para os dois semestres
7. Aplica pesos e define resultado final

---

## ▶️ Como Executar

1. Certifique-se de ter o Python instalado
2. Execute o arquivo `.py`
3. Insira as notas conforme solicitado no terminal

---

## ⚠️ Observações

* É necessário inserir **no mínimo 3 CPs**
* O programa é interativo e depende de entrada manual
* Não há tratamento de erro para entradas inválidas

---

## 🏁 Resultado

Ao final, o sistema informa:

* Média final do aluno
* Situação acadêmica (Aprovado, Exame ou Reprovado)
* Possibilidade de aprovação após exame

---

## 📌 Objetivo Educacional

Este projeto tem como foco reforçar:

* Manipulação de listas
* Estruturas condicionais (`if`, `elif`, `else`)
* Funções em Python
* Cálculo de médias ponderadas
* Interação com o usuário via terminal

---

## 👨‍💻 Autor

Desenvolvido como atividade acadêmica.
