# Grafo e Algoritmos de Busca

Este é um exemplo de implementação de algoritmos de busca em largura (BFS) e busca em profundidade (DFS) em um grafo usando Python. O código também permite encontrar componentes conexas no grafo.

## Como Usar

1. Certifique-se de ter o Python instalado em seu sistema.

2. Clone este repositório ou copie o código em um arquivo Python.

3. Execute o código Python:

    python nome_do_arquivo.py
   
##  Detalhes da Implementação
A classe Grafo é usada para criar e manipular o grafo.
O método adicionar_aresta(u, v) permite adicionar arestas ao grafo entre os vértices u e v.
Os métodos busca_em_largura(vertice, componente) e busca_em_profundidade(vertice, componente) implementam os algoritmos BFS e DFS, respectivamente.
O método encontrar_componentes_conexas() encontra todas as componentes conexas do grafo.

##  Exemplo de Uso
g = Grafo()
g.adicionar_aresta(0, 1)
g.adicionar_aresta(0, 2)
g.adicionar_aresta(1, 3)
g.adicionar_aresta(4, 5)

componentes_conexas = g.encontrar_componentes_conexas()
print("Componentes Conexas:")
for i, (bfs, dfs) in enumerate(componentes_conexas):
    print(f"Componente {i + 1} (BFS): {bfs}")
    print(f"Componente {i + 1} (DFS): {dfs}")
    
 ##  Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar solicitações de pull (pull requests) com melhorias ou correções.

Lembre-se de substituir `nome_do_arquivo.py` pelo nome real do arquivo que contém seu código. Este é um exemplo básico de README.md, e você pode personalizá-lo
e adicionar mais informações relevantes conforme necessário.

  
