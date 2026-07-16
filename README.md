# 🧮 Projeto A3: Análise Combinatória e Segurança Computacional

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Linguagem](https://img.shields.io/badge/Linguagem-Python-blue)
![Disciplina](https://img.shields.io/badge/Disciplina-Matemática_Computacional_Aplicada-orange)

## 📌 Sobre o Projeto

Este repositório contém os arquivos do **Projeto Final (A3)** desenvolvido para a disciplina de Matemática Computacional Aplicada do curso de Ciência da Computação (Universidade São Judas Tadeu).

O trabalho, intitulado **"Princípios de contagem e análise combinatória em problemas de geração de senhas e segurança computacional"**, tem como objetivo demonstrar matematicamente a relação direta entre o cálculo combinatório e a segurança de sistemas digitais contra ataques de força bruta.

A proposta não foi apenas apresentar fórmulas, mas provar, através de um **estudo de caso prático em Python**, a seguinte premissa: *Quanto maior o número de combinações possíveis (Espaço de Busca), maior a segurança de um sistema.*

---

## 📚 Conteúdo do Repositório

Neste repositório, você encontrará todo o material produzido durante a pesquisa e desenvolvimento do projeto:

*   📄 **Projeto Escrito (ABNT):** Documento detalhado abordando a fundamentação teórica (Princípio Fundamental da Contagem, Permutação, Arranjo e Combinação) e suas aplicações em segurança da informação. *(Arquivo: Princípios de contagem e análise combinatória...)*
*   📊 **[Apresentação (Slides)](./Combinatoria_Seguranca_Digital.pptx):** Material visual utilizado na defesa do projeto, resumindo os conceitos de crescimento exponencial e a viabilidade de ataques cibernéticos[cite: 1, 2].
*   💻 **[Código-fonte](./gerador_senhas.py):** Algoritmo desenvolvido como estudo de caso para comprovar a teoria na prática.

---

## ⚙️ O Estudo de Caso (Algoritmo em Python)

Para consolidar a teoria matemática, foi desenvolvido um script em Python que funciona como um gerador e analisador de senhas. 

O algoritmo utiliza a fórmula central do Espaço de Busca ($E = c^n$)[cite: 1] para:
1.  **Gerar senhas aleatórias** com base nos parâmetros escolhidos (tamanho, inclusão de letras, números e símbolos especiais).
2.  **Calcular o Espaço de Busca:** Retorna o número exato de combinações possíveis ($E$) com base no alfabeto ($c$) e no comprimento ($n$) da senha.
3.  **Estimar o tempo de ataque (Força Bruta):** Calcula uma estimativa de quanto tempo um computador padrão levaria para quebrar a senha testando todas as possibilidades.

---

## 🤝 Autores

*   **Gabriel Roque França**
*   **Vinícius Paulo de Almeida**

**Orientação:**
*   Prof. Fernando Mori
*   Prof. Antonio Tavares de Franca Junior

---
*Projeto acadêmico desenvolvido no semestre de 2026 para fins educacionais, unindo a base da matemática discreta aos desafios reais da Cibersegurança.*
