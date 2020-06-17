<h1>CARACTERIZAÇÃO DE SISTEMAS DISTRIBUÍDOS</h1>
<ol type="I">
  <h2><li>INTRODUÇÃO</li></h2>
  <ul style="list-style-type:circle;">
    <h3><li>DEFINIÇÃO</li></h3>
    <p>Componentes de hardware ou software, localizados e computadores interligados em rede, se comunicam e coordenam suas ações apenas enviando mensagens entre si.</p>
    <h3><li>CONSEQUÊNCIAS IMPORTANTES</li></h3>
    <p><b>Concorrência:</b> execução concorrente de programas.</p>
    <p><b>Inexistência de relógio global:</b> não existe uma noção global única do tempo correto.</p>
    <p><b>Falhas independentes:</b> cada componente do sistema pode falhar independentemente, deixando os outros ainda em funcionamento.</p>
  </ul>
  <h2><li>EXEMPLOS DE SISTEMAS DISTRIBUÍDOS</li></h2>
  <ul style="list-style-type:circle;">
    <h3><li>INTERNET</li></h3>
    <p>Conjunto de redes de computadores, de muitos tipos diferentes, interligadas.</p>
    <p>Permite que os usuários, onde quer que estejam, façam uso do serviço como a World Wide Web, e-mail e transferência de arquivo.</p>
    <h3><li>INTRANETS</li></h3>
    <p>Parte da Internet administrada separadamente, cujo limite pode ser configurado para impor planos de segurança locais.</p>
    <p>É conectada à internet por intermédio de um roteador, o qual permite aos usuários de dentro dessa intranet utilizarem serviços que são providos em outro lugar, como acesso a servidores web ou de correios eletrônico.</p>
    <p></p>
    <h3><li>COMPUTAÇÃO MÓVEL E UBÍQUA</li></h3>
    <p><b>Móvel:</b> Execução de tarefas de computação enquanto o usuário está se deslocando de um lugar para o outro. Ex.: notebooks, telefones moveis e assistentes digitais pessoais.</p>
    <p><b>Ubíqua:</b> Utilização de vários de vários dispositivos de computacionais presentes nos ambientes físicos dos usuários. Ex.: Dispositivos incorporados em aparelhos, como maquinas de lavar e geladeiras.</p>
  </ul>
  <h2><li>COMPARTILHAMENTO DE RECURSOS E A WEB</li></h2>
  <ul style="list-style-type:circle;">
    <h3><li>WORLD WIDE WEB</li></h3>
    <p>Sistema para a publicação e acesso a recursos e serviços pela Internet.</p>
    <p><b>HTML:</b> linguagem para especificar o conteúdo e o layout de páginas.</p>
    <p><b>URLs:</b> identificam documentos e outros recursos armazenados como parte da web.</p>
    <p><b>HTTP:</b> meio pelo qual os navegadores e outros clientes buscam documentos e outros recursos dos servidores web.</p>
  </ul>
  <h2><li>DESAFIOS</li></h2>
  <ul style="list-style-type:circle;">
    <h3><li>HETEROGENEIDADE</li></h3>
    <p>Construídos a partir de uma variedade de redes, sistemas operacionais, hardware e linguagens de programação.</p>
    <p>Protocolos de internet mascaram a diferença existente nas redes e o middleware cuida das outras diferenças.</p>
    <p></p>
    <h3><li>SISTEMAS ABERTOS</li></h3>
    <p>Sistema computacional pode ser estendido e reimplementado de várias maneiras.</p>
    <p>Especificações e documentação das interfaces do e software disponíveis para desenvolvedores.</p>
    <h3><li>SEGURANÇA</li></h3>
    <p>Criptografia pode ser usada para proporcionar proteção adequada para os recursos compartilhados.</p>
    <p>Deve-se manter informações sigilosas em segredo, em especial, quando são transmitidas em mensagens por uma rede.</p>
    <h3><li>ESCALABILIDADE</li></h3>
    <p>Eficiente quando há um aumento significativo no número de recursos e no número de usuários.</p>
    <ul>
      <li>Controlar o custo dos recursos físicos;</li>
      <li>Controlar a perda de desempenho;</li>
      <li>Impedir que os recursos de software se esgotem;</li>
      <li>Evitar gargalos de desempenho;</li>
      <li>Dados acessados frequentemente devem ser replicados;</li>
    </ul>
    <h3><li>TRATAMENTO DE FALHAS</li></h3>
    <p>Cada componente precisa conhecer as maneiras possíveis pelas quais os componentes de que depende podem falhar e ser projetado de forma a tratar de cada umas dessas falhas apropriadamente.</p>
    <ul>
      <h4>TÉCNICAS PARA TRATAMENTO DE FALHAS:</h4>
      <li>Detecção de falhas;</li>
      <li>Mascaramento de falhas;</li>
      <li>Tolerância a falhas;</li>
      <li>Recuperação de falhas;</li>
      <li>Redundância;</li>
    </ul>
    <h3><li>CONCORRÊNCIA</li></h3>
    <p>Possibilidade de vários clientes acessarem um recurso compartilhado ao mesmo tempo.</p>
    <p>Cada recurso deve ser projetado para manter a consistência nos estados dos seus dados.</p>
    <h3><li>TRANSPARÊNCIA</li></h3>
    <p>Tornar certos aspectos invisíveis para um usuário final ou para um programador.</p>
    <ul>
      <h4>FORMAS DE TRANSPARÊNCIA:</h4>
      <li>Acesso;</li>
      <li>Localização;</li>
      <li>Concorrência;</li>
      <li>Replicação;</li>
      <li>Falha;</li>
      <li>Mobilidade;</li>
      <li>Desempenho;</li>
      <li>Escalabilidade;</li>
    </ul>
  </ul>
</ol>
<br>
<p>COULOURIS, George. Caracterização de sistemas distribuídos. In: SISTEMAS DISTRIBUÍDOS: Conceitos e projetos. 4. ed. São Paulo: ARTMED, 2007. cap. 1, p. 15-36.</p>
