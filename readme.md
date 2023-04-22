  <body>
    <h1>Jogo dos 8</h1>
    <p>Este é um programa em Python que implementa o jogo dos 8. O objetivo do jogo é mover as peças numeradas em um tabuleiro 3x3, deixando-as em ordem crescente. O espaço vazio pode ser usado para mover as peças.</p>
    <h2>Requisitos</h2>
    <ul>
      <li>Python 3.x</li>
    </ul>
    <h2>Instruções</h2>
    <ol>
      <li>Baixe o arquivo <code>jogoDosOito.py</code>.</li>
      <li>Abra o terminal e navegue até o diretório onde o arquivo <code>jogoDosOito.py</code> foi salvo.</li>
      <li>Execute o seguinte comando: <code>python jogoDosOito.py</code>.</li>
      <li>Siga as instruções exibidas na tela para jogar o jogo.</li>
    </ol>
    <h2>Funcionamento</h2>
    <p>O programa utiliza uma classe <code>JogoDosOito</code> para representar o tabuleiro do jogo. O tabuleiro é representado por uma lista de listas, onde cada sublista representa uma linha do tabuleiro. O número 0 representa o espaço vazio.</p>
    <p>O programa utiliza o algoritmo A* para encontrar a solução mais curta para o tabuleiro atual. O algoritmo A* é um algoritmo de busca em grafos que utiliza uma heurística para estimar o custo para chegar do estado atual ao estado objetivo.</p>
    <h2>Limitações</h2>
    <p>O programa não possui interface gráfica e é executado apenas no terminal. Além disso, o programa não possui validação para garantir que o usuário não insira valores inválidos durante o jogo.</p>
    <h2>Contribuindo</h2>
    <p>Contribuições são bem-vindas. Abra uma issue para discutir as mudanças que você gostaria de fazer ou envie um pull request com as mudanças propostas.</p>
    <h2>Licença</h2>
    <p>Este programa é licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.</p>
