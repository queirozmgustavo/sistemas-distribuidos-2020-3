<h1>CLASSIFICAÇÃO DE HARDWARE COM VÁRIAS CPUs</h1>
<ol type="I">
  <h2><li>MULTIPROCESSADORES</li></h2>
  <ul>
    <li>Processadores independentes, cada processador possui sua própria unidade de controle.</li>
    <li>Multiple Instruction Multiple Data.</li>
    <li>Compartilham a memória por meio de um barramento comum.</li>
    <li>Número maior de processadores aumenta a probabilidade de conflito no acesso de dados, resultando em um menor desempenho.</li>
    <li>Processadores podem dispor de memória local, de uso exclusivo, para o armazenamento de dados, a fim de reduzir conflitos.</li>
  </ul>
  <br>
  <p align="center"><img src="https://1.bp.blogspot.com/-dH0T5jnJaUo/T-HdZA4SsAI/AAAAAAAAAEw/7iRFSSeAPx4/s400/Multiprocessador.jpg" alt=""></p>
  <h2><li>MULTICOMPUTADORES</li></h2>
  <ul>
    <li>Processadores independentes, cada processador possui sua própria unidade de controle.</li>
    <li>Não compartilham memória.</li>
    <li>Construção simples, em relação aos multiprocessadores.</li>
    <li>Programação complexa, em relação aos multiprocessadores.</li>
    <li>Formado por numerosos nós.</li>
    <h4>Divididos em dois grandes grupos:</h4>
    <ul style="list-style-type:disc">
      <li>Processadores Fortemente Paralelos (MMPs)</li>
      <li>Agrupamentos de Estações de Trabalho (COWs)</li>
    </ul>
  </ul>
  <br>
  <p align="center"><img src="https://1.bp.blogspot.com/-dH0T5jnJaUo/T-HdZA4SsAI/AAAAAAAAAEw/7iRFSSeAPx4/s400/Multiprocessador.jpg" alt=""></p>
  <h2><li>TAXONOMIA DE FLYNN</li></h2>
  <ul>
    <li><b>SISD (Single Instruction Single Data):</b> único fluxo de instrução, único fluxo de dados.</li>
    <br>
    <p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/SISD.svg/800px-SISD.svg.png" width="250" height="250"></p>
    <li><b>SIMD (Single Instruction Multiple Data):</b> único fluxo de instrução, múltiplo fluxo de dados.</li>
    <br>
    <p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/MISD.svg/800px-MISD.svg.png" width="250" height="250"></p>
    <li><b>MISD (Multiple Instruction Single Data):</b> múltiplo fluxo de instruções, único fluxo de dados.</li>
    <br>
    <p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/SIMD.svg/800px-SIMD.svg.png"width="250" height="250"></p>
    <li><b>MIMD (Multiple Instruction Multiple Data):</b> múltiplo fluxo de instruções, múltiplo fluxo de dados.</li>
    <br>
    <p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/MIMD.svg/800px-MIMD.svg.png"width="250" height="250"></p>
  </ul>
</ol>
<br>
<p>TANENBAUM, Andrew S. Organização Estruturada de Computadores. 5. ed. São Paulo: Pearson, 2006.</p>
