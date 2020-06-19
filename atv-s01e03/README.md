<h1>TIPOS DE SISTEMAS DISTRIBUÍDOS E MIDDLEWARE</h1>
<ol type="I">
  <h2><li>SISTEMAS DE COMPUTAÇÃO DISTRIBUÍDOS</li></h2>
  <p>Utilizados para tarefas de computação de alto desempenho.</p>
  <ul>
    <h3><li>SISTEMAS DE COMPUTAÇÃO DE CLUSTER</li></h3>
    <p>Série de computadores simples conectados a uma rede de alta velocidade.</p>
    <p>Um único programa é executado em paralelo em várias maquinas.</p>
    <p>Homogeneidade: mesmo sistema operacional e conectados à mesma rede.</p>
    <h4>ALGUNS TIPOS DE CLUSTERS:</h4>
    <ul>
      <li>High Performance Computing Cluster;</li>
      <li>High Availability Computing Cluster;</li>
      <li>Load Balancing;</li>
    </ul>
    <h3><li>SISTEMAS DE COMPUTAÇÃO EM GRADE</li></h3>
    <p>Alto grau de heterogeneidade.</p>
    <p>Recursos de diferentes organizações são reunidos para permitir a colaboração de um grupo de pessoas ou instituições.</p>
    <p>Acesso a diferentes domínios administrativos para usuários que pertençam a uma organização virtual especifica.</p>
    <h4>CAMADAS:</h4>
    <ul>
      <li>Camada-base: provê interfaces para recursos locais.</li>
      <li>Conectividade: protocolos de comunicação.</li>
      <li>Recursos: gerenciamento de um único recurso.</li>
      <li>Coletiva: manipula o acesso a múltiplos recursos.</li>
      <li>Aplicação: aplicações que atuam na organização virtual.</li>
    </ul>
  </ul>
  <h2><li>SISTEMAS DE INFORMAÇÕES DISTRIBUÍDOS</li></h2>
  <p>Construídos a partir de uma variedade de redes, sistemas operacionais, hardwares e linguagens de programação variadas.</p>
  <p>Transparência: oculta do usuário detalhes do funcionamento do sistema distribuído.</p>
  <ul>
    <h3><li>SISTEMAS DE PROCESSAMENTO DE TRANSAÇÕES</li></h3>
    <p>Operações em um banco de dados costumam ser realizadas sob a forma de transações.</p>
    <p>Requer primitivas especiais fornecidas pelo sistema distribuído subjacente ou sistema de linguagem em tempo de execução.</p>
    <h4>CARACTERÍSTICAS:</h4>
    <ul>
      <li>Atômicas: acontece como se fosse indivisível.</li>
      <li>Consistentes: não viola invariantes de sistema.</li>
      <li>Isoladas: transações concorrentes não interferem entre si.</li>
      <li>Duráveis: após o termino de uma transação, as alterações são permanentes.</li>
    </ul>
    <h3><li>INTEGRAÇÃO DE APLICAÇÕES EMPRESARIAIS</li></h3>
    <p>Assegurar a troca de informações entre diferentes aplicações que integram o sistema de informações da empresa.</p>
    <h4>TIPOS DE MIDDLEWARE DE COMUNICAÇÃO:</h4>
    <ul>
      <li>Remote Procedure Calls</li>
      <li>Remote Method Invocatins</li>
    </ul>
  </ul>
  <h2><li>SISTEMAS DISTRIBUIDOS PERVASIVOS</li></h2>
  <p>Equipamentos caracterizados por seu tamanho pequenos, alimentação por bateria, mobilidade e por uma única conexão sem fio.</p>
  <ul>
    <h4>REQUISITOS:</h4>
    <ul>
      <li>Mudança contextual: sistema ciente que seu ambiente pode se transformar.</li>
      <li>Composição ad hoc: configuração do conjunto de aplicações deve ser simples.</li>
      <li>Compartilhamento com padrão: dispositivos se associam ao sistema para acessar e fornecer informações.</li>
    </ul>
  </ul>
  <ul>
    <h3><li>SISTEMAS DOMÉSTICOS</li></h3>
    <p>Compostos por um ou mais computadores pessoais.</p>
    <p>Integram eletrônicos como: smart TVs, home theaters, videogames e smartphones.</p>
    <h3><li>SISTEMAS ELETRÔNICOS PARA TRATAMENTO DE SAÚDE</li></h3>
    <p>Dispositivos monitoram o bem-estar de indivíduos e entram em contato com profissionais da saúde quando necessário.</p>
    <p>Equipamento com vários sensores conectados a uma rede sem fio.</p>
    <h3><li>REDES DE SENSORES</li></h3>
    <p>Consistem em dezenas a centenas de milhares de nós relativamente pequenos, cada equipamento com um dispositivo de sensoriamento.</p>
    <p>Geralmente utilizam comunicação sem fio e são alimentados por bateria.</p>
  </ul>
  <h2><li>MIDDLEWARE</li></h2>
  <p>Camada de software que fornece uma abstração de programação e mascaramento da heterogeneidade de redes, hardware, sistemas operacionais e linguagens de programação subjacentes.</p>
  <p>Fornece um modelo computacional uniforme para ser usados pelos programadores de serviços de aplicativos distribuídos.</p>
  <br>
  <h3 align="center">LISTA DE MIDDLEWARES</h3>
  <table>
    <tr>
      <td>NOME</td>
      <td>APLICAÇÃO</td>
      <td>LINGUAGEM</td>
    </tr>
    <tr>
      <td>CORBA</td>
      <td>Permite que clientes escritos em uma linguagem invoquem métodos em objetos que estão em programas servidores escritos em outra linguagem.</td>
      <td>C++</td>
    </tr>
    <tr>
      <td>RMI</td>
      <td>Permite que objetos invoquem métodos em objetos remotos usando a mesma sintaxe das invocações locais.</td>
      <td>Java</td>
    </tr>
    <tr>
      <td>DCOM</td>
      <td>Permitir a comunicação de objetos em computadores diferentes através de uma rede.</td>
      <td>C</td>
    </tr>
  </table>
</ol>
