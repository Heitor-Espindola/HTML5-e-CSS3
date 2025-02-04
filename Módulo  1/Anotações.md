# CURSO DE HTML5 e CSS3 - CURSO EM VIDEO - PROFESSOR GUSTAVO GUANABARA

# Capítulo 0 - Assunto do Módulo 1 de 5

## 1. Primeiros Passos
## 2. Preparação do ambiente
## 3. Semântica do HTML5
## 4. Textos
## 5. Títulos
## 6. ligações
## 7. Multimídia
## 8. Estilos

# Capítulo 1 - Primeiros Passos
## Capítulo 1.3 - Bibliografia Recomendada

### REFERÊNCIAS ON-LINE

MDN	- Mozilla Developer Network
W3C Standards - World Wide Web Consortium 
WHATWG Living Standard - Web Hypertext Aplication Technology Working Group
W3Schools - Refsnes Data

### Amazon(Kindle)

Autor  Livros
---  ---
OSTRanning  (Flexbox)(CSS Grid)

### LIVROS

Autor  Livro
---  ---
O'Reilly (Série)
Alta Books (Série)
NOVATEC	 (Série)
GG  (design gráfico)(A psicologia das cores)(Pensar com tipos)
Senac  (desiar)
Bookman  (HTML5)(CSS)

## Capítulo 1.4 - Como a internet chega na minha casa

A Internet surgiu durante a Guerra Fria

### Em 1969
 A União Soviética Lançou o Sputnik
 O EUA Fundou um orgãoagencia, chamada de DARPA, e servia para estudos de tecnologias para a guerra. 

Para que a US não destruíssem todos os dados ao destruir uma base militar, eles criaram então, a ARPANET que fazia a comunicação entre os computadores

 SDS Sigma 7 na Univrsidade da Califórnia
 SDS 90 na Universidade de Stanford
 IBM 37075 no Centro de Matemática de Los Angeles
 DEC PDP-10 na base Militar de Utah

Porém, como esses computadores eram diferentes, e não poderiam se comunicar entre si, então a UCLA (Universidade da Califórnia) criou um protocolo, chamado NCP (Network Control Protocol ou Protocolo de Controle de Rede).

Como o NCP era um protocolo primordial, só uma conexão poderia acontecer por vez, e quando a rede cresceu, em 1972, o NCP já estava impraticável, então dois pesquisadores criaram dois protocolos que depois foram unidos.

Bob Kahn criou o TPC, que eliminava o problema do NCP de só poder fazer uma conexão por vez, porém tinha problema em reconhecer os pontos (computadores).

Já Vint Cerf criou um protocolo solução, o IP (Internetwork Protocol), que servia para identificar as máquinas

Juntando o trabalho de cada um, criou-se o Protocolo TCP IP

Mas como tinha muitas universidades e alguns comercios estavam utilizando a rede, a ARPANET foi dividida em MILNET (Militar), NSFNET (National Science Fundation) e redes Comercial, e como as redes queriam se comunicar entre si, foi fundada o termo Interconnect Networking, que foi simplificado para Internetworking, e depois para Internet.

### E hoje em dia?

#### Em 1993, Genebra

Tim Breners-Lee criou o protocolo HTTP (HyperText Transfer Protocol) que foi incluido no TCP IP, e também criou o HTML (HyperText Markup Language, ou Linguagem de Marcação de HiperTexto), e também criou o www (World Wide Web). Para o funcionamento do www, é preciso de um navegador, e Marc Andreessen criou o primeiro navegador, o chamado Mozaik.

#### Internet e WWW

 Internet É mais ampla, é a rede das redes, e dentro dela, existe servidores especializados, como o FTP, que servia para trasferência de arquivos; o GOPHER, que servia para trasferência de hipertexto simples, o SMTP, o POP3, e o IMAP, que serviam para trasferência de Email; e os servidores especializados em HTTP.
 WWW É uma sub-rede da rede Internet, que é especializado em HTTP.

# Capítulo 2 - Preparação do ambiente
## Capítulo 2.1 - Como a Internet funciona

### Representação de Dados

Digitos Binários ou Ondas Quadradas - 0 e 1 - Bit

8 bits = 1 byte

Exemplo:
01000001 = A (UTF-8)

Quantidade de | É eqivalente a
--- | ---
8 bits | 1 byte
1024 bytes | KiloByte ou KB
1024 KB | 1 Megabyte ou MB
1024 MB | 1 Gigabbyte ou GB
1024 GB | 1 Terabyte ou TB
1024 TB | 1 PetaByte ou PB
1024 PB | 1 Exabyte ou EB
1024 EB | 1 Zettabyte ou ZB
1024 ZB | 1 Yottabyte ou YB


MB != Mb -> Megabytes != MEGABITS
MB -> Armazenamento (Pendrive ou SSD por exemplo)
Mb -> Trasmissão (Rede por exemplo)

### Como nos conectamos?

Computador/Celular/etc (Seu dispositivo) -> Cliente (Entende Ondas Quadradas)
Aparelho de Telecomunicações(Entende Ondas Senoidais)
Internet

#### Como faz agora?

Um aparelho faz a mediação entre os dois

Ele trasforma:
* OQ em OS -> **mo**dulação (Enviando)
* OS em OQ -> **dem**odulação (Recebendo)

O nome desse aparelho é **modem** (Gateway na verdade, mas nós chamamos de modem)

### Como Acessar um Servidor

Todo site fica **hospedado** (guardado/salvo) em um servidor.

E para acessar um site, o modem utiliza um DNS (Domain Name Sistem - Sistema de Domínio de Nomes) para pesquisar qual o IP do servidor, e então envia para o* modem novamente, e agora o modem sabe qual o IP do servidor desejado, ele acessa o servidor

## Capítulo 2.2 - O que é domínio e hospedagem?

### URL, Domínio, TLD, Caminho e Hospedagem

www.**github *.com***/gustavoguanabara -> O conjunto completo é uma URL (Uniform Resource Locator)

www.github.com -> Domínio

www -> Sub-domínio

.com -> TLD

gustavoguanabara -> Caminho

#### Domínio

* É o que indentifica o site 
* Pago anualmente
* Único
* Vários **TLD**s

##### TLD

GTLD (Generic Top Level Domain)

* .com -> comercial
* .net -> serviço de rede
* .io -> Input/Output (entrada/saída)
* .gov -> governamental
* .edu -> educacional
* .store -> lojas

CCTLD (Country Code Top Level Domain)

* .br -> Brasil
* .us -> United States
* .uk -> United Kingdom
* .tv -> Tuvalu

#### Hospedagem

* Espaço para armazenar arquivos
* Pago mensalmente (geralmente)
* Espaço, memória e recursos

### Exemplo Prático

**gustavoguanabara.github.io**

* O total é uma URL
* github.io -> Domínio
* .io -> TLD
* gustavoguanabara -> Sub-domínio (particularmente, eu achei que esse seria o caminho, mas essa URL não tem caminho)