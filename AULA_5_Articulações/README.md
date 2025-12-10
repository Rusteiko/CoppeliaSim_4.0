# 🎥 SCRIPT OFICIAL – AULA 5  
## Articulações no CoppeliaSim  
### Robótica Industrial – Cinética e Controle de Movimento

---

## 🎬 **CENA 1 — ABERTURA**

**NARRADOR:**  
Antes que um robô consiga andar, agarrar objetos ou seguir trajetórias precisas, existe um elemento fundamental que define toda sua movimentação: **as articulações**.  
Elas são o elo invisível entre o mundo físico e o mundo matemático que governa a robótica industrial.

**NARRADOR:**  
A **Aula 5** mergulha totalmente nesse universo, explorando o comportamento, a configuração e os modos de controle das articulações dentro do **CoppeliaSim**.

---

## ⚙️ **CENA 2 — TIPOS DE ARTICULAÇÕES**

**NARRADOR:**  
Existem três tipos principais de articulações no CoppeliaSim:

- 🔄 **Revolução (Revolute Joint)**  
- 📏 **Prismática (Prismatic Joint)**  
- 🔘 **Esférica (Spherical Joint)**  

**NARRADOR:**  
As articulações *revolução* e *prismática* possuem **1 grau de liberdade**,  
enquanto a articulação *esférica* possui **3 graus de liberdade**, permitindo movimentos mais complexos.

---

## 🧩 **CENA 3 — ARTICULAÇÕES E HIERARQUIA**

**NARRADOR:**  
Uma articulação define o movimento entre um **objeto pai** e um **objeto filho**.  
Quando há hierarquia, o objeto filho reage diretamente à posição e comportamento da articulação.

**NARRADOR:**  
As articulações podem ter **limites físicos**, como as de um braço robótico,  
ou não ter limites, como o movimento contínuo das rodas.

---

## 🔧 **CENA 4 — MODOS DE CONTROLE**

**NARRADOR:**  
No CoppeliaSim, uma articulação pode operar em diversos modos. A seguir, o roteiro detalhado:

---

### 🎯 **4.1 — Modo Passivo**

**NARRADOR:**  
No modo passivo, a articulação **não é controlada pelo motor**.  
Ela pode ser manipulada por programação ou por forças externas.

Ideal para simulações:

- sem controle direto,  
- com comportamentos físicos livres,  
- ou que dependam de lógica externa.

---

### ⚡ **4.2 — Modo Par/Força (Torque/Force)**

**NARRADOR:**  
Neste modo, a articulação opera de forma **dinâmica**, usando o motor físico do simulador.  
Aqui o motor pode:

- trabalhar ligado ou desligado,  
- usar controle de par,  
- ou operar sem controle, como um eixo livre.

Este modo também permite:

- controle PID,  
- amortecimento,  
- comportamento elástico (mola).

---

### ⚙️ **4.3 — Modo Impedância**

**NARRADOR:**  
O motor é habilitado e configurado como um sistema **mola–amortecedor**.  
Isso permite simular:

- articulações flexíveis,  
- comportamentos biomecânicos,  
- interações mais “suaves”.

---

### 🧮 **4.4 — Modo Cinemática Inversa (IK)**

**NARRADOR:**  
Nesse modo, a articulação se torna **passiva**, porém sua posição é determinada pelo **módulo de Cinemática Inversa**.  
Perfeito para:

- braços robóticos,  
- posicionamento preciso,  
- movimentos coordenados de múltiplos elos.

---

### 🔗 **4.5 — Modo Dependente**

**NARRADOR:**  
A posição de uma articulação depende da posição de outra.  
É possível sincronizar movimentos ou criar cadeias de articulações que seguem comportamentos específicos.

---

## 🧱 **CENA 5 — VISUALIZAÇÃO E DINÂMICA**

**NARRADOR:**  
Um detalhe crucial:  
As articulações devem operar em **modo híbrido** ou **par/força** quando o **objeto filho é dinâmico**.  

Se o objeto filho for **estático**, esses modos não podem ser usados.  
Isso garante que o simulador aplique corretamente as leis físicas.

**NARRADOR:**  
Sempre examine os elementos dinâmicos da simulação antes de escolher o modo de articulação.

---

## 🔍 **CENA 6 — EXEMPLOS DA AULA**

**NARRADOR:**  
A aula apresenta arquivos de demonstração:

```
Aula_05_00_ConfiguraçãoArticulações.ttt
```

Mostrando:

- Modos de motor desativado/ativado  
- Controle PID  
- Configurações de torque  
- Comportamento de impedância  
- Parâmetros estáticos vs dinâmicos

---

## 🧠 **CENA 7 — O PROPÓSITO DA AULA**

**NARRADOR:**  
Ao final desta aula, o estudante deverá ser capaz de:

- identificar cada tipo de articulação,  
- entender seu grau de liberdade,  
- configurar corretamente seus modos,  
- escolher o tipo adequado para cada situação,  
- e interpretar a dinâmica em simulações mais complexas.

Este conhecimento é essencial para:

- braços robóticos,  
- manipuladores industriais,  
- robôs móveis,  
- projetos de cinemática,  
- e qualquer simulação avançada no CoppeliaSim.

---

## 🏁 **CENA 8 — ENCERRAMENTO**

**NARRADOR:**  
Articulações são o coração do movimento robótico.  
Dominar seus modos e configurações significa dominar a base da simulação industrial.

**TODOS:**  
```
WE ARE TOGETHER!
```

---

## 👤 **CRÉDITOS**

**Professor:**  
Prof. MSc. Adilson Cunha Rusteiko  
Cinemática e Robótica Industrial – AULA 5


