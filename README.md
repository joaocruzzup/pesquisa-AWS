<h1 align="center">
☁️<br>Pesquisa AWS
</h1>
Repositório referente a pesquisa que envolve AWS do programa catalisa

---

## Sumário
1. [O que é um sistema distríbuido?](#o-que-é-um-sistema-distribuído)
   1. [Requisitos de um sistema distribuído](#requisitos-de-um-sistema-distribuído)
   2. [Modelo Cliente/Servidor](#modelo-clienteservidor)
   3. [Modelo P2P](#modelo-p2p)
2. [O que é Iaas, Paas, Saas?](#o-que-é-iaas-paas-saas)
3. [O que é World Wide Web?](#o-que-é-world-wide-web)
4. [O que é Cloud?](#o-que-é-cloud)
5. [O que é HTML?](#o-que-é-html)
6. [O que é URL?](#o-que-é-url)
7. [O que é o protocolo HTTP?](#o-que-é-o-protocolo-http)
8. [O que é uma API REST?](#o-que-é-uma-api-rest)
9. [Fontes](#fontes)

## 💻 O que é um sistema distribuído?

Um sistema distribuído é um conjunto de computadores conectados que trabalham juntos para realizar uma tarefa ou conjunto de tarefas. 
Nele, as máquinas individuais são chamadas de nós, e cada nó tem sua própria memória e processador. Os sistemas distribuídos visam remover gargalos ou pontos centrais de falha de um sistema.

### 📄 Requisitos de um sistema distribuído
1. Disponibilidade:  O sistema deve conseguir continuar funcionando corretamente mesmo se um ou mais nós falharem.
2. Confiabilidade: O sistema deve informar dados sempre corretos, apesar de corrupções que podem ocorrer no caminho, nesse caso ele deve tratar as corrupções para gerar os melhores dados.
3. Transparência: Os usuários devem conseguir interagir com o sistema distribuído como se fosse um único sistema centralizado, sem se preocupar com os detalhes de sua implementação distribuída.
4. Tolerância a falhas: O sistema deve conseguir lidar com falhas nos nós, na rede ou em outros componentes, garantindo que a operação continue mesmo nessas condições.
5. Escalabilidade: O sistema deve conseguir lidar com um aumento no número de nós ou de demanda sem degradação significativa do desempenho.
6. Segurança: O sistema deve proteger os dados e recursos contra acesso não autorizado e garantir a autenticidade e integridade das informações.

### 👩‍💻🖥️ Modelo Cliente/Servidor
Nesse modelo, o sistema é dividido em duas partes principais: o cliente e o servidor.

O cliente é a parte do sistema que inicia a comunicação por meio de solicitações de serviços ou recursos.

Já o servidor é a parte do sistema que recebe as solicitações do cliente, processa essas solicitações e fornece as respostas apropriadas. Ele está sempre em execução, aguardando solicitações dos clientes.

A comunicação entre o cliente e o servidor é baseada em um protocolo específico, como HTTP, TCP/IP, ou outros protocolos de rede.

### 👩‍💻👨‍💻 Modelo P2P
São sistemas distribuídos nos quais os membros da rede são equivalentes em funcionalidade  Permitem que os pares compartilhem recursos diretamente, sem envolver intermediários

No modelo P2P, cada par pode atuar tanto como cliente quanto como servidor, colaborando de forma direta e descentralizada para compartilhar recursos e executar tarefas. Essa abordagem oferece maior autonomia e escalabilidade, tornando-se útil em diversas aplicações distribuídas.

Aplicações comuns do modelo P2P incluem redes de compartilhamento de arquivos, como BitTorrent, sistemas de mensagens instantâneas descentralizadas, jogos multiplayer distribuídos e criptomoedas, como o Bitcoin, que utilizam uma rede P2P para validar transações.

OBS.: P2P é mais adequado quando há uma necessidade de compartilhar recursos entre os pares

## 📲 O que é Iaas, Paas, Saas?
R: São modelos de serviços em nuvem que permitem armazenar e acessar dados pela internet, sem precisar de servidores locais.

- IaaS (Infrastructure as a Service) - Infraestrutura como Serviço:
Com o IaaS, as empresas podem alugar a capacidade de espaço de armazenamento, poder de processamento e memória, entre outros,, de acordo com suas necessidades com empresas que oferecem esse tipo de serviço. Exemplo: AWS
<br> <br>
- PaaS (Platform as a Service) - Plataforma como Serviço:
Além de oferecer todos os itens básicos da IaaS, o PaaS fornece uma plataforma para desenvolvimento de aplicações oferecidas na nuvem proporcionando todo um sistema de infraestrutura, armazenamento e comunicação. Exemplos: Servidores que hospedam sites
  <br> <br>
- SaaS (Software as a Service) - Software como Serviço:
A empresa que oferece o serviço é responsável por hospedar e disponibilizar  o aplicativo aos usuários finais. Em vez de vender o aplicativo para outra empresa hospedar, ela mesma mantém o software em seus próprios servidores e fornece acesso aos usuários por meio da internet. Exemplos: Whatsapp, LinkedIn e Facebook.

## 🌐 O que é World Wide Web?
R:World wide web ou WWW como conhecemos, significa literalmente uma teia de aranha mundial , normalmente chamamos de Web, é um sistema de documentos públicos colocados e disponibilizados na internet, em um formato de hipertexto acessível através de um programa de computador chamado, browser ou navegador, a Web desde então tem se tornado mais moderna e interativa, onde podemos fazer várias coisas, entre acessar mídias sociais, fazer uma compra etc.

## ☁️ O que é Cloud?
R: Cloud ou serviço em nuvem é uma rede de servidores Interligados com uma capacidade grande de armazenamento e processamento de dados onde nos permite uma maior elasticidade ou seja,por exemplo antigamente as empresas utilizavam servidores físicos, e para disponibilizar para o seus usuários era um custo muito alto,quando o cloud surgiu, ficou mais acessível disponibilizar os recursos de uma empresa através da internet, você não sabe o local físico do recurso disponibilizado, mas sempre que o usuário precisar ele vai estar lá guardado na nuvem um exemplo disso são os jogos,antigamente para ter acesso a um jogo a gente tinha que acessar mídias físicas como cartucho ou cd, hoje em dia se você quiser jogar um jogo, basta no seu console escolher o jogo que você quer e baixar.

## 📑 O que é HTML?
R: O HTML é o componente básico da web , seu acrônimo significa HiperText Markup Language, traduzindo ao português: Linguagem de Marcação de Hipertexto. A criação de qualquer página depende do HTML , porém ele não se enquadra como linguagem de programação, ele é considerado uma linguagem de marcação o qual  permite inserir o conteúdo e estabelecer a estrutura básica de um website, como dividir as seções do site, inserir hiperlinks, estruturar parágrafos, pular linhas no texto, ordenar listas, enfim, uma infinidade de comandos que são úteis na construção de um site, geralmente por um par de marcadores conhecidos como tags.

![Capturar.PNG](img/Capturar.PNG)

Um exemplo de uma página HTML que exibe a mensagem “Olá, mundo!” em um parágrafo.
Fonte da imagem: Tecnoblog

## ➡️ O que é URL?
R: URL é o endereço de qualquer site na internet

A estrutura do  URL geralmente é composta por:
- Protocolo: é o esquema de comunicação usado para acessar o recurso, como HTTP (Hypertext Transfer Protocol) ou HTTPS (HTTP Secure) para páginas web, FTP (File Transfer Protocol) para transferência de arquivos, entre outros.
- Domínio: é o nome do servidor onde o recurso está hospedado. Por exemplo, em "www.exemplo.com", o domínio é "exemplo.com".
- Caminho: é o local específico onde o recurso está localizado no servidor. Por exemplo, em "www.exemplo.com/pagina", "/pagina" é o caminho.
- Parâmetros: são informações adicionais fornecidas na URL que podem influenciar o comportamento ou a exibição do recurso. Por exemplo, em "www.exemplo.com/pagina?parametro1=valor1&parametro2=valor2", os parâmetros são "parametro1=valor1" e "parametro2=valor2".
- Fragmento: é uma parte opcional da URL que se refere a um local específico dentro do recurso. Geralmente é indicado por um sinal de jogo da velha (#) seguido de um identificador. Por exemplo, em "www.exemplo.com/pagina#secao", "#secao" é o fragmento.

![protocolo.PNG](img/protocolo.PNG)
Exemplo de estrutura URL.Fonte: Hostinger Tutoriais.

## O que é o protocolo TCP/IP?
R: O protocolo TCP/IP é um conjunto de regras usado em redes de computadores para troca de dados. O IP cuida do  endereçamento e roteamento  dos pacotes de dados, enquanto o TCP garante a  entrega correta e confiável dos dados. É essencial para a comunicação na Internet.

 	Exemplo: ao acessar um site, o TCP/IP estabelece a conexão,  divide os dados em segmentos, roteia-os pela Internet e os  reorganiza no destino. Garante que a página seja exibida corretamente no navegador. Simplificando, o TCP/IP permite a troca de informações entre dispositivos em redes, tornando possível a navegação e a comunicação online.

## 🆔 O que é DNS? - Márlen

R:O DNS é um sistema que  traduz nomes de domínio em endereços IP. Ele permite que você acesse sites usando  nomes amigáveis , em vez de números de IP.

Exemplo: quando você digita um nome de domínio, como www.exemplo.com, o DNS localiza o endereço IP correspondente, como 203.0.113.1. Isso permite que seu dispositivo se conecte ao servidor correto e exiba o site solicitado.

O DNS é essencial para a navegação na web, pois simplifica o acesso aos sites sem a necessidade de memorizar números de IP. Ele atua tornando a experiência online mais  conveniente e acessível.


## 🔐 O que é o protocolo HTTP?
R: O HTTP é um protocolo usado na Internet que permite aos navegadores solicitar informações de servidores e receber respostas.
Ele é usado para acessar páginas da web e outros recursos online. O HTTP segue o modelo  cliente-servidor , onde o navegador envia solicitações e o servidor processa e envia respostas.
O protocolo é stateless, tratando cada solicitação independentemente.

## 📟 O que é uma API REST?
R: Uma API (Interface de Programação de Aplicativos) é como um canal de comunicação que permite que diferentes aplicativos ou sistemas interajam entre si. Ela define regras e formatos para essa interação.
Uma API REST é um tipo específico de API que segue certas diretrizes para facilitar a comunicação entre aplicativos. Ela usa a internet como base e utiliza URLs (endereços) e métodos HTTP (como GET e POST) para solicitar e enviar informações.
Em termos mais simples.

---
## 📃 Fontes
 - https://tecnoblog.net/responde/o-que-e-html-guia-para-iniciantes/
 - https://www.buscape.com.br/pc-computador/conteudo/o-que-e-html
 - https://www.hostinger.com.br/tutoriais/url
