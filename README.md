

```markdown
# Mochila-Com-Repeticao

Este projeto realiza a análise e comparação entre dois algoritmos para o **Problema da Mochila com Repetição**. Os algoritmos implementados são:
1. **Força Bruta**: Algoritmo que explora todas as combinações possíveis de itens para encontrar a solução ótima.
2. **Programação Dinâmica**: Algoritmo que utiliza uma abordagem de otimização, resolvendo subproblemas e combinando suas soluções para otimizar o resultado final.

Através de experimentos, o projeto compara o tempo de execução de ambos os algoritmos, gerando gráficos que ilustram a eficiência de cada abordagem.

## Descrição do Problema

O **Problema da Mochila com Repetição** consiste em maximizar o valor total de itens que podem ser colocados em uma mochila com uma capacidade máxima, permitindo o uso repetido de cada item. Cada item tem um peso e um valor associados, e o objetivo é maximizar o valor total sem exceder a capacidade da mochila.

## Algoritmos Implementados

1. **Força Bruta**: Tenta todas as combinações possíveis de itens até encontrar a solução ótima.
2. **Programação Dinâmica**: Utiliza a técnica de dividir para conquistar, resolvendo subproblemas e combinando as soluções para otimizar o resultado final.

## Estrutura do Repositório

- **main.ipynb**: Notebook principal com a implementação e execução dos algoritmos.
- **test.ipynb, test2.ipynb, test3.ipynb**: Notebooks de teste, com variações de implementação e experimentos.
- **test4.ipynb, test5.ipynb**: Notebooks de teste adicionais para experimentações e resultados.
- **.venv**: Ambiente virtual Python utilizado para isolar as dependências do projeto.
- **.gitignore**: Arquivo que garante que arquivos temporários ou desnecessários não sejam rastreados pelo Git.
- **README.md**: Este arquivo de documentação.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/alyssonwolfpoet/Mochila-Com-Repeticao.git
   cd Mochila-Com-Repeticao
   ```

2. Se você não tiver o ambiente virtual configurado, crie-o:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Para Linux/Mac
   .venv\Scripts\activate  # Para Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o notebook principal (`main.ipynb`) para ver a implementação e resultados:
   ```bash
   jupyter notebook main.ipynb
   ```

## Resultados

Os gráficos gerados mostram a comparação entre os tempos de execução dos algoritmos de **Força Bruta** e **Programação Dinâmica**. O algoritmo de Programação Dinâmica se mostrou significativamente mais eficiente, especialmente para maiores capacidades de mochila. Já o algoritmo de Força Bruta rapidamente se torna inviável devido ao seu crescimento exponencial com o aumento do número de itens.

## Análise Assintótica

- **Força Bruta**: \(O(2^n \cdot n)\), onde \(n\) é o número de itens.
- **Programação Dinâmica**: \(O(n \cdot C)\), onde \(C\) é a capacidade da mochila.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
```