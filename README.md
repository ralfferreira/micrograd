# micrograd

> ⚠️ Este projeto ainda está em desenvolvimento. / This project is still under development.


Implementação pessoal baseada no repositório [micrograd](https://github.com/karpathy/micrograd) do [Andrej Karpathy](https://karpathy.ai/).

---

## 🇧🇷 Português

**micrograd** é um motor de diferenciação automática (autograd) minimalista. Ele implementa *backpropagation* (diferenciação reversa) sobre um grafo acíclico dirigido (DAG) construído dinamicamente, operando sobre valores escalares.

O objetivo é **educacional**: entender como funciona o cálculo de gradientes por trás de frameworks como PyTorch, construindo tudo do zero — neurônio por neurônio, operação por operação.

### O que tem aqui

- **`Value`** — classe base que representa um escalar no grafo computacional, com suporte a operações aritméticas e cálculo automático de gradientes.
- **Visualização do grafo** — usando `graphviz` para visualizar o DAG com dados e gradientes de cada nó.

### Como rodar

```bash
pip install graphviz
```

Abra o notebook [main.ipynb](cci:7://file:///c:/Users/USER/Documents/Code/micrograd/main.ipynb:0:0-0:0) e execute as células.

---

## 🇺🇸 English

**micrograd** is a minimalist autograd engine. It implements backpropagation (reverse-mode autodiff) over a dynamically built DAG, operating on scalar values.

The goal is **educational**: understanding how gradient computation works under the hood of frameworks like PyTorch, by building everything from scratch — neuron by neuron, operation by operation.

### What's here

- **`Value`** — base class representing a scalar in the computational graph, supporting arithmetic operations and automatic gradient calculation.
- **Graph visualization** — using `graphviz` to visualize the DAG with data and gradients at each node.

### How to run

```bash
pip install graphviz
```

Open the [main.ipynb](cci:7://file:///c:/Users/USER/Documents/Code/micrograd/main.ipynb:0:0-0:0) notebook and run the cells.

---

## Referência / Reference

- [Andrej Karpathy](https://karpathy.ai/)
- [karpathy/micrograd](https://github.com/karpathy/micrograd)

## Licença / License

MIT