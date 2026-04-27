# 🧬 Game of Life — Simulação Emergente Interativa

Uma simulação avançada de partículas baseada em regras dinâmicas que gera comportamento emergente em tempo real diretamente no navegador.

🔗 **Acesse a simulação online:**
https://yurifreitas.github.io/gameoflife/#91651088029

---

## 🧠 Visão Geral

Este projeto expande o conceito clássico de autômatos celulares, inspirado no trabalho de John Conway, para um sistema contínuo de partículas com interações físicas parametrizadas.

Ao invés de uma grade discreta, o sistema simula:

* Partículas com posição e velocidade
* Forças de atração e repulsão entre elementos
* Regras dinâmicas baseadas em cores
* Formação espontânea de estruturas (clusters)

O resultado é um **universo emergente determinístico**, controlado por uma seed numérica.

---

## 🔗 Estrutura do Link

Formato:

```
https://yurifreitas.github.io/gameoflife/#<seed>
```

Exemplo:

```
https://yurifreitas.github.io/gameoflife/#91651088029
```

---

## 🔑 Seed

A seed define completamente o comportamento da simulação:

* Mesma seed → mesmo universo
* Seeds diferentes → dinâmicas completamente distintas

Isso permite:

* Reprodução exata de padrões
* Compartilhamento de "universos"
* Exploração procedural controlada

---

## ⚙️ Modelo de Simulação

Cada partícula ("átomo") é representada por:

```
[x, y, vx, vy, color]
```

---

## 🔬 Interações

As partículas interagem através de uma matriz de regras:

```
rules[colorA][colorB]
```

A força aplicada segue um modelo contínuo:

```
F = g / sqrt(d)
```

Onde:

* g → intensidade da interação entre cores
* d → distância entre partículas

---

## 🎨 Características Principais

* 🧬 Sistema multi-agente contínuo
* 🎲 Geração determinística via seed
* 🎛️ Controle em tempo real via GUI
* 🌈 Interações baseadas em cores
* 🔁 Regras dinâmicas e mutáveis
* 🧩 Detecção de clusters (agrupamentos)
* 🎥 Exportação de imagem e vídeo
* ⚡ Execução em tempo real no navegador

---

## 🎮 Controles

### 🖱️ Mouse

* Clique → aplica pulso de força local
* Shift + clique → pulso inverso

### ⌨️ Teclado

* `r` → gerar novas regras aleatórias
* `s` → aplicar regras simétricas
* `o` → resetar partículas
* `t` → alternar visualização de clusters

---

## 🧩 Interface (GUI)

O projeto utiliza lil-gui para permitir:

* Ajuste de parâmetros físicos
* Controle de cores e regras
* Manipulação da seed
* Exportação de imagem e vídeo
* Monitoramento de performance (FPS)

---

## 🔬 Parâmetros Importantes

* `atoms.count` → quantidade de partículas por cor
* `time_scale` → velocidade da simulação
* `viscosity` → amortecimento do movimento
* `gravity` → força gravitacional aplicada
* `wallRepel` → repulsão nas bordas
* `numColors` → número de grupos interativos

---

## 🚀 Como Executar Localmente

1. Clone o repositório
2. Abra o arquivo `index.html` no navegador

Não há necessidade de build ou dependências externas além do navegador.

---

## 🧠 Conceito Avançado

Este projeto pode ser interpretado como:

* Um sistema de dinâmica não linear
* Um simulador de matéria artificial
* Um ambiente de comportamento emergente
* Uma base para arte generativa procedural

---

## 📌 Possíveis Expansões

* Renderização via WebGL / GPU
* Exportação de estados como dados estruturados
* Sistema de compartilhamento de seeds
* Integração com áudio reativo
* Aplicações em arte digital e visualização científica

---

## 🤝 Contribuições

Contribuições são bem-vindas. Sinta-se livre para abrir issues ou pull requests com melhorias, otimizações ou novas ideias.
