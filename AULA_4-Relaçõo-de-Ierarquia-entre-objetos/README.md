# ========================================
# Script: gerar_readme.py
# Objetivo: Gerar automaticamente o arquivo README.md
# Conteúdo baseado nas Aulas 4 e 4.1: Hierarquia no CoppeliaSim
# ========================================

readme = """
# 🤖 Aula 4 e 4.1 – Relação de Hierarquia entre Objetos no CoppeliaSim

Este repositório apresenta o conteúdo das Aulas **4** e **4.1** da disciplina **Robótica Industrial**, ministrada pelo **Prof. MSc. Adilson Cunha Rusteiko**.  
O tema central das aulas é **hierarquia entre objetos**, fundamental para manipulação, organização e comportamento de sistemas robóticos no **CoppeliaSim**.

---

## 🎯 Objetivos das Aulas

### Aula 4 — Fundamentos da Hierarquia
- Compreender as **vantagens** da hierarquia entre objetos.  
- Entender hierarquias usadas em **cadeias cinemáticas abertas** (braços robóticos).  
- Compreender hierarquia usada em **robôs móveis com rodas**.  
- Diferenciar objetos **puros** e **não puros** dentro da hierarquia.  

### Aula 4.1 — Atividade Prática
- Criar uma simulação representando a hierarquia entre objetos.  
- Montar um **carrinho com 4 ou 5 eixos**, usando objetos simples.  
- Aplicar hierarquia entre corpo, eixos e rodas.

---

## 🧭 O que é Hierarquia entre Objetos?

Hierarquia é a estrutura que define quem é **pai** e quem é **filho** no ambiente do CoppeliaSim.

### 📌 Características essenciais
- O **objeto pai** afeta automaticamente todos os seus **filhos**.  
- Scripts e funções do pai podem acessar propriedades dos filhos.  
- Cálculos de cinemática (como cinemática inversa) dependem da existência de hierarquia.  
- Cadeias cinemáticas robóticas (joints + links) só funcionam corretamente quando estruturadas hierarquicamente.

---

## 🔍 Objetos Puros e Não Puros

### Objetos **Puros**
- Devem ser **dinâmicos**  
- Devem ser **respondable**  
- Ideais para simulações físicas  

### Objetos **Não Puros**
- Recomendados como **estáticos**  
- Geralmente **não respondable**  
- Usados para elementos visuais ou de suporte  

Demonstração: *Aula_04_00_Hierarquia_Puros_e_NPuros*

---

## 🦾 Hierarquia em Cadeias Cinemáticas (Braços Robóticos)

Uma cadeia cinemática típica inclui:

- Base  
- Juntas (Joints)  
- Elos (Links)  
- Ferramenta / Efetor Final  

Essa hierarquia permite:
- Cálculo da **cinemática direta**  
- Cálculo da **cinemática inversa**  
- Propagação correta dos movimentos  

Demonstração: *Aula_04_01_Hierarquia_dos_Braços_Roboticos*

---

## 🚗 Hierarquia em Robôs com Rodas

Estrutura típica:

- Corpo do robô (pai)
  - Suporte das rodas
    - Roda esquerda
    - Roda direita
    - Rodas auxiliares (caster)

Usado para:
- Navegação diferencial  
- Controle de rodas e tração  
- Simulação de robôs móveis  

Demonstração: *Aula_04_02_Hierarquia_Robo_com_Rodas*

---

## 🏗️ Montando Hierarquias no CoppeliaSim

As aulas demonstram como:

- Criar objetos na Scene Tree  
- Definir e alterar relação pai-filho  
- Verificar propagação de movimentos  
- Configurar propriedades físicas conforme o tipo de objeto  
- Testar a diferença entre movimentação **com** e **sem** hierarquia  

---

## 🛠️ Atividade Prática — Aula 4.1

Monte uma simulação contendo:

- Um carrinho com **4 ou 5 eixos**  
- Objetos simples (cubos, cilindros, esferas…)  
- Hierarquia estruturada corretamente  
- Movimentações aplicadas para comprovar propagação hierárquica  

Objetivo: demostrar entendimento pleno da hierarquia no CoppeliaSim.

---

## 👥 Trabalho Prático

O exercício pode ser feito individualmente ou em grupo (conforme orientação do professor).

Mensagem oficial do material:  
**WE ARE TOGETHER!**

---

## 📄 Direitos Autorais

Material original produzido pelo professor:  
**MSc Prof. Adilson Cunha Rusteiko**  

"""


