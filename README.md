# Redes-iniciante
Curso de redes para iniciantes do cisco academy ' Conceitos Básicos de Redes'

<h1>Módulo 1: Comunicação em um Mundo conectado</h1>
<h2>1.1 Tipos de Rede</h2>
As redes instaladas em pequenos escritórios ou em residências e escritórios domésticos são conhecidas como redes SOHO.

A internet é considerada "rede de redes" pois é formada por milhares de pequenas redes locais conectadas entre si.

<h2>1.2 Transmissão de dados</h2>
Tipos de dados
<ul>
  <li>Dados voluntários: São dados que nós mesmos fornecemos, são dados em que acordamos em compartilhar</li>
  <li>Dados inferidos: São dados gerados pelas nossas atividades. Por exemplo o cartão de crédito</li>
  <li>Dados observados: Um exemplo é o celular que mantêm rastreando sua movimentação.</li>
</ul>

Os computadores e redes só trabalham com dígitos binários (0 e 1). O termo bit é uma abreviação de 'dígito binário' 

Um bit é armazenado e transmitido como um entre dois estados distintos possíveis. Isso pode incluir duas direções de magnetização, dois níveis diferentes de corrente ou voltagem, dois  níveis diferentes de intensidade de luz ou qualquer outro sistema físico com dois estados distintos.

Cada dispositivo de entrada converte a interação humana em código binário para a CPU processar e armazenar. Cada dispositivo de saída converte os dados binários de volta a um formato reconhecido pelos seres humanos.

Cada grupo de oito bits corresponde a um byte.

<h4>1.2.3 Métodos comuns de transmissão de dados</h4>
Depois que os dados são transformados em uma série de bits, eles devem ser convertidos em sinais que possam ser enviados através da mídia de rede para o destino. Mídia significa o meio físico em que os sinais são transmitidos. Alguns exemplos de mídia são os fios de cobre, cabo de fibra óptica e ondas eletromagnéticas pelo ar. Um sinal consiste em padrões ópticos ou elétricos que são transmitidos de um dispositivo conectado para outro. Esses padrões representam os bits digitais(ou seja, dados) e trafegam através da mídia desde a origem até o destino como uma série de pulsos de eletricidade, pulsos de luz ou ondas de rádio.

Os sinais podem ser convertidos muitas vezes antes de alcançar o destino, à medida que a mídia corresponde muda entre a origem e o destino.

Métodos comuns de transmissão de sinal usado em redes:
<ul>
  <li>Sinais elétricos- A transmissão é obtida pela representação dos dados como pulsos elétricos em fios de cobre.</li>
  <li>Sináis ópticos- A transmissão é obtida pela conversão de sinais elétricos em pulsos de luz.</li>
  <li>Sinais sem fio- A transmissão é obtida pelo uso de infravermelho, micro-ondes ou ondas de rádio pelo ar</li>
</ul>

<h3>1.3 Largura de banda e taxa de transferência</h3>
<h4>1.3.1 Largura de banda</h4>

A transferência de dados normalmente é referenciada em termos de largura de banda e taxa de transferência.

Largura de banda é a capacidade de um meio de transportar dados. A largura de banda digital mede a quantidade de dados que podem fluir de um lugar para outro durante um determinado tempo. A largura de banda constuma ser medida pelo número de bits que (teoricamente) podem ser enviados através da mídia em um segundo. Estas são as medidas comuns de largura de banda:
<ul>
  <li>Milhares de bits por segundo (Kbps)</li>
  <li>Milhões de bits por segundo (Mbps)</li>
  <li>Bilhões de bits por segundo (Gbps)</li>
</ul>

<h4>1.3.2 Taxa de transferência</h4>
Taxa de transferência é a medida da transferência de bits através do meio físico durante um determinado período. A taxa de transferência não corresponde à largura de banda especificada. Diversos fatores influenciam a taxa transferência:
<ul>
  <li>A quantidade de dados enviados e recebidos pela conexão.</li>
  <li>Os tipos de dados transmitidos </li>
  <li>A latência criada pelo número de dispositivos de rede encontrados entre a origem e o destino</li>
</ul>

O termo latência se refere ao tempo necessário para os dados viajarem demim ponto a outro, incluindo atrasos.

As medidas de taxa de transferência não levam em consideração a validade ou a utilidade dos bits transmitidos e recebidos.

Em uma rede com vários segmentos, a taxa de transferência não pode ser mais rápida do que o link mais lento do caminho entre o dispositivo emissor e o dispositivo receptor.
Mesmo que todos os segmentos  tenham largura de banda alta, basta um seh=gmento no caminho com largura de banda mais baixa para provocar lentidão no rendimento da rede inteira.

Largura de Banda → Potencial máximo da rede.

Taxa de Transferência → Velocidade real da transmissão de dados.
