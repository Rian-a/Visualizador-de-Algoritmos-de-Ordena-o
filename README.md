# Visualizador de Algoritmos de Ordenação

Projeto acadêmico desenvolvido para a disciplina de Estrutura de Dados.

A aplicação consome dados reais da API pública do Mercado Livre e permite visualizar o funcionamento dos principais algoritmos clássicos de ordenação através de animações interativas, métricas em tempo real e comparações de desempenho.

---

# Objetivo

Demonstrar o funcionamento interno dos algoritmos de ordenação utilizando dados reais obtidos de uma API pública.

O sistema permite:

- Visualizar ordenações em tempo real
- Comparar algoritmos
- Acompanhar comparações e trocas
- Visualizar pseudocódigo
- Entender complexidade computacional
- Executar algoritmos passo a passo
- Comparar desempenho entre algoritmos

---

# API Utilizada

Mercado Livre API

Endpoint utilizado:

```txt
https://api.mercadolibre.com/sites/MLB/search?q=notebook
```

---

# Estrutura dos Dados

Cada produto possui informações como:

```js
{
  id,
  title,
  price,
  sold_quantity,
  available_quantity
}
```

Campos disponíveis para ordenação:

- price
- sold_quantity
- available_quantity

---

# Tecnologias Utilizadas

- React
- JavaScript
- TailwindCSS
- Recharts
- Vite
- Mercado Livre API

---

# Algoritmos Implementados

Todos os algoritmos foram implementados manualmente, sem utilização de `array.sort()`.

## Algoritmos disponíveis

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Heap Sort

---

# Funcionalidades

# Visualização Interativa

- Barras verticais representando os elementos
- Altura proporcional ao valor atual
- Exibição dos valores
- Exibição dos nomes dos produtos
- Destaques visuais durante execução

## Cores utilizadas

- Azul → elemento normal
- Amarelo → comparação
- Vermelho → troca/movimentação
- Verde → elemento ordenado

---

# Controles de Execução

A aplicação possui:

- Executar
- Pause
- Step (passo a passo)
- Reiniciar
- Controle de velocidade da animação

---

# Métricas em Tempo Real

Durante a execução dos algoritmos, o sistema exibe:

- Número de comparações
- Número de trocas
- Tempo de execução
- Quantidade de passos
- Algoritmo atual

---

# Aspecto Didático

Cada algoritmo possui uma área explicativa contendo:

## Explicação simples

Descrição do funcionamento do algoritmo em linguagem acessível.

## Estratégia utilizada

Exemplos:

- Comparação e troca
- Divisão e conquista
- Particionamento por pivô
- Heapificação

## Narração do passo atual

Exemplos:

```txt
Comparando índices 3 e 4
Trocando valores 7 e 2
Particionando em torno do pivô
Heapificando subárvore
```

## Pseudocódigo

O sistema exibe o pseudocódigo do algoritmo em execução.

## Complexidade computacional

Exibição de:

- Melhor caso
- Caso médio
- Pior caso
- Espaço auxiliar

---

# Comparação de Desempenho

Todos os algoritmos podem ser executados sobre o mesmo dataset.

O sistema apresenta:

## Tabela comparativa

- Nome do algoritmo
- Comparações
- Trocas
- Tempo de execução
- Complexidade

## Gráficos

Comparação visual entre:

- Tempo
- Comparações
- Trocas

---

# Estrutura do Projeto

```txt
src/
├── components/
├── algorithms/
├── services/
├── hooks/
├── utils/
├── pages/
└── App.jsx
```

## components/

Responsável pela interface visual da aplicação.

## algorithms/

Implementação manual dos algoritmos de ordenação.

## services/

Responsável pelo consumo da API do Mercado Livre.

## hooks/

Gerenciamento de estados e lógica reutilizável.

## utils/

Funções auxiliares e utilitários do sistema.

---

# Conceitos Aplicados

- Algoritmos de ordenação
- Estruturas de dados
- Arrays
- Heap binário
- Recursão
- Divisão e conquista
- Complexidade assintótica
- Visualização de algoritmos
- Consumo de API REST
- Manipulação dinâmica de dados

---

# Como Executar

Clone o repositório:

```bash
git clone <url-do-repositorio>
```

Entre na pasta do projeto:

```bash
cd nome-do-projeto
```

Instale as dependências:

```bash
npm install
```

Execute o projeto:

```bash
npm run dev
```

---

# Observação

Este projeto foi desenvolvido exclusivamente para fins educativos e acadêmicos, com foco no aprendizado de algoritmos de ordenação, estruturas de dados e análise de complexidade computacional.

---

# Autor

Rian Simão Gomes

Estudante de Análise e Desenvolvimento de Sistemas
