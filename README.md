# Mochila-Com-Repeticao
Comparação entre os algoritmos de Força Bruta e Programação Dinâmica para o Problema da Mochila com Repetição. Inclui implementações, medições de tempo de execução, gráficos comparativos e análises assintóticas para ilustrar a eficiência de cada abordagem.

Aqui está um exemplo de README completo para o seu repositório no GitHub:

---

# Knapsack Problem Analysis

Este repositório apresenta uma análise comparativa dos algoritmos de Força Bruta e Programação Dinâmica para resolver o **Problema da Mochila com Repetição**. O objetivo é entender as diferenças de desempenho e eficiência entre as duas abordagens.

## Descrição do Problema

O Problema da Mochila com Repetição consiste em maximizar o valor total de itens que podem ser colocados em uma mochila com uma capacidade máxima, permitindo o uso repetido de cada item. Cada item tem um peso e um valor associados, e o objetivo é maximizar o valor total sem exceder a capacidade da mochila.

## Algoritmos Implementados

1. **Força Bruta**: Explora todas as combinações possíveis de itens para encontrar a solução ótima.
2. **Programação Dinâmica**: Utiliza uma abordagem de dividir para conquistar, resolvendo subproblemas e combinando suas soluções para otimizar o resultado final.

## Estrutura do Repositório

- `brute_force.py`: Implementação do algoritmo de Força Bruta.
- `dynamic_programming.py`: Implementação do algoritmo de Programação Dinâmica.
- `measure_time.py`: Script para medir o tempo de execução dos algoritmos.
- `plot_graph.py`: Script para gerar gráficos comparativos dos tempos de execução.
- `README.md`: Este arquivo de documentação.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/Knapsack-Problem-Analysis.git
   cd Knapsack-Problem-Analysis
   ```
2. Execute os scripts para medir o tempo de execução:
   ```bash
   python measure_time.py
   ```
3. Gere os gráficos comparativos:
   ```bash
   python plot_graph.py
   ```

## Resultados

Os gráficos mostram que o algoritmo de Programação Dinâmica é significativamente mais eficiente em termos de tempo de execução, especialmente para maiores capacidades de mochila, enquanto o algoritmo de Força Bruta rapidamente se torna inviável devido ao seu crescimento exponencial.

## Análise Assintótica

- **Força Bruta**: \(O(2^n \cdot n)\), onde \(n\) é o número de itens.
- **Programação Dinâmica**: \(O(n \cdot C)\), onde \(C\) é a capacidade da mochila.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no código ou na documentação.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

Este README abrange todos os pontos importantes do projeto, desde a descrição do problema até instruções de execução e detalhes dos algoritmos.