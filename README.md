# ATIVIDADE FINAL | Raciocinio Logico Algoritmico

# Sistema de Cálculo de Médias em JavaScript

Este projeto foi desenvolvido para a disciplina de **Raciocínio Lógico Algorítmico** do curso de **Análise e Desenvolvimento de Sistemas (ADS)**.

## 📚 Objetivo da Atividade

Desenvolver um programa em JavaScript capaz de:

- Ler as notas de duas avaliações de vários alunos;
- Calcular a média simples de cada aluno;
- Armazenar as médias em vetores;
- Ordenar as médias em ordem crescente utilizando o método bolha;
- Informar a quantidade de alunos aprovados e reprovados;
- Exibir todos os resultados utilizando `document.write`.

---

## 🛠️ Tecnologias Utilizadas

- JavaScript
- HTML (para executar o script no navegador)

---

## 📌 Conceitos Aplicados

O projeto utiliza os seguintes conceitos aprendidos em aula:

- Variáveis
- Entrada e saída de dados
- Vetores
- Estruturas condicionais (`if/else`)
- Estruturas de repetição (`for`)
- Ordenação de vetores
- Média simples

---

## 📂 Estrutura do Projeto

```bash
📁 projeto-media-alunos
 ├── trabalho_raciocinio_logico.html
 └── README.md
```

---

## ▶️ Como Executar

1. Baixe os arquivos do projeto;
2. Abra o arquivo `trabalho_raciocinio_logico.html` no navegador;
3. Informe:
   - quantidade de alunos;
   - notas da AV1;
   - notas da AV2;
4. O sistema exibirá:
   - médias ordenadas;
   - quantidade de aprovados;
   - quantidade de reprovados.

---

## 🧮 Exemplo de Funcionamento

### Entrada:

```text
Quantidade de alunos: 2

Aluno 1:
AV1 = 5
AV2 = 5

Aluno 2:
AV1 = 8
AV2 = 6
```

### Saída:

```text
Médias em ordem crescente:

Aluno 1: 5.00
Aluno 2: 7.00

Quantidade de aprovados: 1
Quantidade de reprovados: 1
```

---

## 📖 Explicação da Lógica

O programa:

1. Cria vetores para armazenar as notas;
2. Utiliza um `for` para receber os dados dos alunos;
3. Calcula a média simples:

```javascript
(av1 + av2) / 2
```

4. Verifica aprovação:
   - média maior que 5 → aprovado;
   - média menor ou igual a 5 → reprovado;
5. Ordena as médias utilizando o método bolha;
6. Exibe todas as informações com `document.write`.

---

## 👨‍💻 Integrantes

- Jhonatthan Filho de Sousa Lacerda
- Gisela de Sousa Cavalcante
- João Vitor Lima Quintela
- Josué Lira de Andrade
- Luis Otávio Oliveira da Cunha
- Raimundo Oscar de Araújo Neto

---

## 📄 Licença

Projeto acadêmico desenvolvido apenas para fins educacionais.
