# Jogo de Xadrez em Java Puro

<p>Este projeto é uma implementação de um jogo de xadrez utilizando apenas Java puro, sem frameworks adicionais. Ele oferece uma interface simples para jogar xadrez, suportando todas as regras tradicionais do jogo.</p>

## Funcionalidades Principais:

<ul>
  <li><strong>Tabuleiro de Xadrez:</strong> Representação do tabuleiro de xadrez com 8x8 casas.</li>
  <li><strong>Movimentação das Peças:</strong> Implementação completa das regras de movimentação para todas as peças (rei, rainha, bispo, cavalo, torre e peões).</li>
  <li><strong>Detecção de Xeque e Xeque-mate:</strong> Verificação de situações de xeque e xeque-mate durante o jogo.</li>
  <li><strong>Promoção de Peão:</strong> Implementação da regra de promoção de peão quando ele atinge a última fileira.</li>
  <li><strong>Roque:</strong> Implementação das regras de roque, tanto o pequeno quanto o grande.</li>
  <li><strong>En Passant:</strong> Suporte à captura especial En Passant.</li>
  <li><strong>Interface de Console:</strong> Interface simples baseada em console para interação com o jogo.</li>
</ul>

## Como Usar:

<ol>
  <li><strong>Clone o Repositório:</strong> Clone este repositório para o seu ambiente local.</li>
  <li><strong>Compile o Código:</strong> Compile o código Java utilizando o seguinte comando:
    <pre><code>javac -d bin src/*.java</code></pre></li>
  <li><strong>Execute o Jogo:</strong> Execute o jogo utilizando o comando:
    <pre><code>java -cp bin Main</code></pre></li>
  <li><strong>Interaja com o Jogo:</strong> Siga as instruções no console para mover as peças e jogar o jogo.</li>
</ol>

## Exemplo de Uso:

- **Mover uma Peça:**
  <pre><code>
  De: e2
  Para: e4
  </code></pre>

- **Realizar um Roque:**
  <pre><code>
  De: e1
  Para: g1
  </code></pre>
