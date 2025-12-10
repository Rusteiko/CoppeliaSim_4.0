# 🎥 SCRIPT OFICIAL – AULA 6  
## Sensores no CoppeliaSim  
### Robótica Industrial – Detecção, Percepção e Interação

---

## 🎬 **CENA 1 — ABERTURA**

Para que um robô seja realmente inteligente, não basta se mover.  
Ele precisa **perceber**, **sentir**, **reconhecer** o mundo ao seu redor.  
É aí que entram os sensores — os olhos, ouvidos e tato da robótica.

Na **Aula 6**, exploramos profundamente três categorias fundamentais de sensores usados em simulações industriais dentro do CoppeliaSim:

- Sensores de Proximidade  
- Sensores de Visão  
- Sensores de Força  

Cada um deles representa uma forma única de interação entre robôs e ambiente.

---

## 📡 **CENA 2 — SENSOR DE PROXIMIDADE**

O sensor de proximidade simula tecnologias como:

- ultrassônicos,  
- infravermelho,  
- laser,  
- indutivo  
- e capacitivo.

Ele mede a **distância mínima** até objetos com a propriedade *detectable* ativada.

No CoppeliaSim, existem **6 tipos de volume de detecção**, cada um representando um feixe ou forma geométrica diferente:

- 🔦 Feixe  
- 🔺 Pirâmide  
- 🧱 Cilindro  
- 🟦 Disco  
- 🔻 Cone  
- 🎲 Feixe aleatório  

Essas formas determinam *como* e *onde* o sensor procura por objetos.

---

## 🧩 **CENA 3 — PROPRIEDADES DO SENSOR DE PROXIMIDADE**

Ao configurar esse sensor, o aluno deve ajustar:

- Tipo de sensor simulado  
- Objeto que será detectado  
- Volume de detecção  
- Parâmetros de sensibilidade e alcance  
- Ativação da propriedade **detectable** nos objetos

Se um objeto não estiver marcado como *detectable*, o sensor simplesmente não o enxerga.

---

## 🎥 **CENA 4 — SENSOR DE VISÃO**

O sensor de visão funciona como uma câmera real.  
Ele captura imagens renderizadas diretamente na simulação, podendo operar em dois modos:

- **Ortográfico** (retangular)  
- **Perspectiva** (trapezoidal)

O sensor pode gerar:

- imagens RGB,  
- mapas de profundidade,  
- capturas 3D,  
- e dados visuais para algoritmos.

---

## 🎛️ **CENA 5 — PROPRIEDADES DO SENSOR DE VISÃO**

Entre os ajustes disponíveis estão:

- Tipo de câmera  
- Campo de visão  
- Ângulo de perspectiva  
- Resolução (X e Y)  
- Profundidade  
- Renderização  
- Ajuste de área de detecção  

E um detalhe fundamental:  
Todo objeto que deve aparecer na imagem precisa estar com a propriedade **renderizable** ativada.

---

## 💪 **CENA 6 — SENSOR DE FORÇA**

Diferente dos anteriores, o sensor de força é estrutural.  
Ele mede:

- **torque**,  
- **força**,  
- e tensões** aplicadas entre dois objetos conectados.

Ele funciona como uma articulação sensível, capaz de:

- detectar sobrecargas,  
- registrar forças mecânicas,  
- e até **romper** se um limite configurado for ultrapassado.

É o sensor ideal para robôs manipuladores, testes de carga e sistemas que exigem alta precisão física.

---

## 🧭 **CENA 7 — A IMPORTÂNCIA DAS PROPRIEDADES DOS OBJETOS**

Para que tudo funcione corretamente:

- Objetos observados por sensores de proximidade → **detectable**
- Objetos observados por sensores de visão → **renderizable**
- Objetos que interagem com sensores de força → **dinâmicos ou com vínculos físicos configurados**

A simulação só funciona direito quando cada propriedade está ajustada ao tipo de sensor utilizado.

---

## 🛠️ **CENA 8 — EXEMPLOS DA AULA**

A aula apresenta os arquivos:

```
Aula_06_Sensores_Proximidade.ttt
Aula_06_Sensores_Visao.ttt
Aula_06_Sensores_Forca.ttt
```

Cada um demonstra:

- diferentes volumes de detecção,  
- configurações de visão,  
- respostas físicas a forças aplicadas.

---

## 🎯 **CENA 9 — DESAFIO FINAL**

Ao final, o estudante deve montar **sua própria simulação** usando sensores de proximidade.  
A cena deve demonstrar:

- volumes de detecção diferentes,  
- objetos configurados corretamente,  
- leitura dinâmica dos sensores.

---

## 🧠 **CENA 10 — OBJETIVOS DE APRENDIZAGEM**

Após esta aula, você será capaz de:

- Entender o funcionamento de sensores industriais  
- Configurar sensores no CoppeliaSim  
- Ajustar propriedades dos objetos para detecção  
- Criar simulações completas com detecção visual e física  
- Desenvolver lógica baseada em dados sensoriais

---

## 🏁 **CENA 11 — ENCERRAMENTO**

Sensores são o elo entre o mundo real e o movimento robótico.  
Dominar essas ferramentas abre caminho para simulações complexas, robôs inteligentes e automações avançadas.

**TODOS:**  
```
WE ARE TOGETHER!
```

---

## 👤 **CRÉDITOS**

**Professor:**  
Prof. MSc. Adilson Cunha Rusteiko  
Cinemática e Robótica Industrial – AULA 6


