# Curso de GNU/Linux Ubuntu Server 24.04.x LTS (Noble Numbat) Essentials (Docker-CE e Portainer.io)

## **🖥️ Configurações BÁSICAS do Ubuntu Server 24.04.x LTS (Noble Numbat) Essentials ANTES DE CONTINUAR**

As configurações básicas do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX antes de continuar, nessa aula você vai aprender todos os procedimentos básicos para deixar o nosso servidor configurado de forma correta antes de iniciar a implementação do Docker e Portainer.

Seguir as proximas aulas de:<br>
01 - Atualização do Ubuntu Server<br>
02 - Configuração do Hostname, Hosts e Placa de Rede<br>
03 - Configuração do Locale, Timezone e NTP<br>
04 - Desligar e Reiniciar o Servidor<br>
05 - Habilitando o Ubuntu Pro<br>
06 - Configuração do OpenSSH Server<br>

Link da vídeo aula: https://www.youtube.com/watch?v=dQJhDoCQgNI

## **Atualização do Ubuntu Server 24.04.x LTS**

Atualização do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para manter o seu servidor Ubuntu sempre atualizado antes de começar a instalar e configurar os principais serviços de rede.

Conteúdo estudado nessa atualização:<br>
#01_ Atualizando as Listas sources.list do Apt ou Apt-Get no Ubuntu Server<br>
#02_ Verificando todos os pacotes a serem utilizados no Ubuntu Server<br>
#03_ Atualizando todos os software no Ubuntu Server<br>
#04_ Forçando uma atualização completa de todos os software e dependências no Ubuntu Server<br>
#05_ Forçando uma atualização e remoção de software desnecessários no Ubuntu Server<br>
#06_ Removendo pacotes desnecessários no Ubuntu Server<br>
#07_ Fazendo a limpeza dos repositórios locais e pacotes desnecessários no Ubuntu Server<br>
#08_ Limpando o cache local do sources.list no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: O VÍDEO DAS ATUALIZAÇÕES DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, O PROCEDIMENTO DE ATUALIZAR É O MESMO NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSE CURSO ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

Link da vídeo aula: https://www.youtube.com/watch?v=B3FzV2bxjtw

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/01-AtualizacaoDoServidorUbuntuServer.md

## **Configurando a Placa de Rede do Ubuntu Server 24.04.x LTS **

Configuração da Placa de Rede do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para configurar o Hostname (Novo do Servidor), FQDN (Nome Totalmente Qualificado), tabela de Hosts (Computadores) e configurar a Placa de Rede de modo Estático no Servidor Ubuntu Server e fazer todos os testes de rede antes de iniciar a instalação dos serviços.

Conteúdo estudado nessa configuração:<br>
#01_ Alterando o nome FQDN (Fully Qualified Domain Name) do Ubuntu Server<br>
#02_ Alterando as entradas no arquivo Hosts do Ubuntu Server<br>
#03_ Instalando os principais software de rede no Ubuntu Server<br>
#04_ Verificando informações do Hardware de Rede no Ubuntu Server<br>
#05_ Verificando as informações de Endereços IPv4 no Ubuntu Server<br>
#06_ Alterando as configurações da Placa de Rede do Ubuntu Server<br>
#07_ Aplicando as configurações do Netplan e verificando as informações de Rede do Ubuntu Server<br>
#08_ Acessando a máquina virtual do Ubuntu Server remotamente via SSH<br>

**OBSERVAÇÃO IMPORTANTE: CONFIGURAÇÕES DA PLACA DE REDE DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSA AULA ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

Link da vídeo aula: https://www.youtube.com/watch?v=sKn5fTy1OHI

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/02-ConfiguracaoHostnameHostsNetplan.md

## **Configurando a Data e Hora do Ubuntu Server 24.04.x LTS**

Configuração da Data e Hora do Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para configurar a localidade (Locale), Zona de Horário (Timezone), Sincronismo de Data Hora com o Protocolo NTP (Network Time Protocol) e configurações manuais de Data, Hora e sincronismo com o Hardware.

Conteúdo estudado nessa configuração:<br>
#01_ Verificando as informações do Locale (Localidade) do Sistema Operacional Ubuntu Server<br>
#02_ Configurando o Locale (Localidade) do Brasil no Sistema Operacional Ubuntu Server<br>
#03_ Verificando as informações do Timezone (Fuso Horário) do Sistema Operacional Ubuntu Server<br>
#04_ Configurando o Timezone (Fuso Horário) de São Paulo no Sistema Operacional Ubuntu Server<br>
#05_ Configurando o Sincronismo de Data e Hora com o Protocolo NTP no Ubuntu Server<br>
#06_ Reinicializar o serviço do Systemd Timesyncd (Sincronismo de Data e Hora) no Ubuntu Server<br>
#07_ Configuração de Data e Hora Manual no Sistema Operacional Ubuntu Server<br>
#08_ Sincronizando Data e Hora do Sistema Operacional com o Hardware (BIOS) no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: CONFIGURAÇÕES DO LOCALE E TIMEZONE DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSA AULA ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

Link da vídeo aula: https://www.youtube.com/watch?v=Szt6egOsKxE

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/03-ConfiguracaoDoLocaleTimezone.md

## ** Desligando e Reiniciando o Ubuntu Server 24.04.x LTS **

Desligar e reiniciar o Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nessa aula você vai aprender todos os procedimentos para desligar ou reiniciar o servidor de forma correta, vai aprender a agendar um agendamento de desligamento ou reinicialização do sistema.

Conteúdo estudado nesse procedimento:<br>
#01_ Desligando e reinicializando o servidor com halt no Ubuntu Server<br>
#02_ Desligando e reinicializando o servidor com poweroff no Ubuntu Server<br>
#03_ Desligando e reinicializando o servidor com init no Ubuntu Server<br>
#04_ Desligando e reinicializando o servidor com reboot no Ubuntu Server<br>
#05_ Desligando e reinicializando o servidor com shutdown no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: DESLIGAR E REINICIAR DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS FORMAS DE DESLIGAR E REINICIAR É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSA AULA ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

Link da vídeo aula: https://www.youtube.com/watch?v=NbA-k5-iLWA

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/04-DesligarReiniciarServidor.md

## **Habilitando a Licença Ubuntu Pro Free no Ubuntu Server 24.04.x LTS**

Configuração da Licença do Ubuntu Pro Free no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para habilitar o suporte ao Ubuntu Pro Free no Ubuntu Server, esse recurso permiti manter o nosso servidor sempre atualizado com os novos patch's de segurança e garante o suporte até 10 anos de uso da plataforma para Canonical.

Conteúdo estudado nessa configuração:<br>
#01_ Verificando as Informações do Sistema Operacional Ubuntu Server<br>
#02_ Atualizando o Sistema Operacional Ubuntu Server<br>
#03_ Criando sua conta no Ubuntu One para registrar o Ubuntu Pro no Ubuntu Server<br>
#04_ Criando uma Assinatura do Ubuntu Pro Free para uso Pessoal<br>
#05_ Verificando a versão do Ubuntu Advantage Tools no Ubuntu Server<br>
#06_ Ativando a sua Assinatura do Ubuntu Pro no Ubuntu Server<br>
#07_ Verificando os repositórios de origem das atualizações no Ubuntu Server<br>
#08_ Habilitando outros Serviços do Ubuntu Pro de Atualização<br>
#09_ Atualizando sistema com o suporte do Ubuntu Pro no Ubuntu Server<br>

**OBSERVAÇÃO IMPORTANTE: HABILITAR O UBUNTU PRO NO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSA AULA ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

Link da vídeo aula: https://www.youtube.com/watch?v=SW9JzwjGdkM

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/05-HabilitandoUbuntuPro.md

## **Configuração do OpenSSH Server no Ubuntu Server 24.04.x LTS**

Configuração do OpenSSH Server no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para configurar o acesso remoto no nosso servidor de forma segura e customizada.

Conteúdo estudado nessa configuração:<br>
#01_ Instalado o OpenSSH no Ubuntu Server;<br>
#02_ Verificando os Status do Serviço do OpenSSH;<br>
#03_ Verificando a Versão do OpenSSH Server e Client;<br>
#04_ Verificando a Porta de Conexão do OpenSSH Server;<br>
#05_ Diretórios e Arquivos de Configuração do OpenSSH;<br>
#06_ Segurança do Arquivo Hosts.Deny do TCPWrappers;<br>
#07_ Segurança do Arquivo Hosts.Allow do TCPWrappers;<br>
#08_ Configuração do Arquivo sshd_config do OpenSSH;<br>
#09_ Configuração do Arquivo issue.net (Banner Login);<br>
#10_ Acessando Remoto via Powershell, PuTTY e Terminal.

**OBSERVAÇÃO IMPORTANTE: DAS CONFIGURAÇÕES DO OPENSSH SERVER DO UBUNTU SERVER ESTÁ NA VERSÃO 22.04.x LTS, AS CONFIGURAÇÕES É A MESMA NA VERSÃO 24.04.x LTS, LEVANDO EM CONSIDERAÇÃO APENAS AS DEPENDÊNCIAS DE APLICATIVOS QUE TEM NESSA DOCUMENTAÇÃO, ESSA AULA ESTÁ USANDO A INSTALAÇÃO MINIMIZADA (MINIMIZED) DO UBUNTU SERVER.**

Link da vídeo aula: https://www.youtube.com/watch?v=-cforvm_oV0

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/06-ConfiguracaoOpenSSH.md

**OBSERVAÇÃO IMPORTANTE: CASO VOCÊ QUEIRA APLICAR A SEGURANÇA AVANÇADA NO SERVIÇO DO OPENSSH SERVER, VEJA O VÍDEO DE CONFIGURAÇÃO FEITA NO CURSO DO CA-CERTIFICATE, NESSE VÍDEO É HABILITADO OS RECURSOS DE CHAVE PRIVADA/PÚBLICA E CONFIGURADO OS LOGS DETALHADO DE CONEXÃO REMOTA.**

Link da vídeo aula: https://www.youtube.com/watch?v=Ri-_KMM361o

Link da documentação: https://github.com/vaamonde/ca-certificates/blob/main/01-ca/01-openssh.md

## **🖥️ Desabilitando o SNAPd e Cloud-Init no Ubuntu Server 24.04.x LTS **

Desabilitar e remover o SNAPd e Cloud-Init no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para remover o bloquear a instalação acidental do SNAPd e do Cloud-Init, recursos esses que não será utilizado nesse curso e que consome recursos desnecessário do servidor.

Snap foi criado pela Canonical, o formato de empacotamento de arquivos Snap vem instalado no Ubuntu desde a versão 18.04. Ele isola aplicativos do restante do sistema, uma vantagem em segurança, e tem alguns programas exclusivos, mas vários outros sistemas não são nativamente compatíveis, demandando passos extra para isso.

Snapcraft é uma ferramenta de linha de comando poderosa e fácil de usar para criar snaps. Ele ajuda você a: construir e publicar seus snaps na loja Snap. use canais, trilhas e ramificações para controlar com precisão atualizações e lançamentos.

Cloud-init é o método de multidistribuição padrão da indústria para inicialização de instância de nuvem multiplataforma. Ele é suportado por todos os principais provedores de nuvem pública, sistemas de provisionamento para infraestrutura de nuvem privada e instalações bare-metal.

Conteúdo estudado nessa configuração:<br>
#01_ Listando os aplicativos rodando no SNAPd no Ubuntu Server<br>
#02_ Removendo os aplicativos rodando no SNAPd no Ubuntu Server<br>
#03_ Parando e desabilitando o serviço do SNAPd no Ubuntu Server<br>
#04_ Prevenção contra instalação e inicialização do SNAPd no Ubuntu Server<br>
#05_ Parando e desabilitando o serviço do Cloud-Init no Ubuntu Server<br>
#06_ Prevenção contra instalação e inicialização do Cloud-Init no Ubuntu Server<br>
#07_ Verificando os Status de Serviços Rodando no Ubuntu Server<br>
#08_ Reiniciando o Ubuntu Server para Aplicar as mudanças<br>

Link da vídeo aula: https://www.youtube.com/watch?v=dWoiPeTGFFE

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/07-DesabilitandoSnapdCloud-Init.md

## **🖥️ Monitoramento do Desempenho de Hardware do Ubuntu Server 24.04.x LTS **

Monitoramento do desempenho no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos para monitorar o desempenho de Processador CPU, Memória RAM, Hard Disk HD e Rede Network utilizando comandos simples sem a necessidade de instalação de sistemas de monitoramento complexo.

O Kernel é o núcleo central de um sistema operacional. Ele atua como uma ponte entre o hardware do computador e o software, gerenciando os recursos do sistema e permitindo que os programas de software interajam com o hardware de forma eficiente e segura.

A CPU (Central Processing Unit), também conhecida como processador, é o componente principal de um computador responsável por executar instruções e processar dados. É frequentemente descrita como o "cérebro" do computador, pois é onde a maioria das operações de cálculo e lógica são realizadas.

A RAM (Random Access Memory), ou Memória de Acesso Aleatório, é um tipo de memória volátil usada em computadores e outros dispositivos eletrônicos para armazenar dados temporariamente enquanto estão sendo processados. Diferente do armazenamento permanente, como discos rígidos ou SSDs, a RAM é muito mais rápida, mas só mantém os dados enquanto o dispositivo está ligado.

HD, sigla para "Hard Disk" ou "Hard Disk Drive" (Disco Rígido em português), é um dispositivo de armazenamento de dados usado em computadores e outros dispositivos eletrônicos. Ele armazena permanentemente os dados, mesmo quando o computador está desligado. O HD é um dos métodos mais tradicionais de armazenamento, sendo usado para guardar sistemas operacionais, aplicativos, documentos, fotos, vídeos, e qualquer outro tipo de dado digital.

Uma Interface de Rede é um componente de hardware ou software que conecta um dispositivo, como um computador, servidor, ou roteador, a uma rede, permitindo que ele se comunique e troque dados com outros dispositivos na mesma rede ou em redes externas. A interface de rede é essencial para o funcionamento de redes de computadores, permitindo a transferência de dados entre dispositivos conectados.

Conteúdo estudado nessa configuração:<br>
#01_ Instalando os aplicativos de monitoramento no Ubuntu Server<br>
#02_ Verificando a versão do Ubuntu Server<br>
#03_ Verificando a versão do Kernel e Uptime no Ubuntu Server<br>
#04_ Verificando o Desempenho do Processador CPU (Central Processing Unit) Ubuntu Server<br>
#05_ Verificando o Desempenho da Memória RAM (Random-Access Memory) Ubuntu Server<br>
#06_ Verificando o Desempenho Disco HD (Hard-Disk) Ubuntu Server<br>
#07_ Verificando o Desempenho Rede (Network) Ubuntu Server<br>
#08_ Estressando o Servidor Ubuntu Server para verificar as mudanças no Gráfico<br>

Link da vídeo aula: https://www.youtube.com/watch?v=fstVt6vOrYc

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/08-MonitoramentoHardware.md

## **🖥️ Habilitando a Segurança do Ubuntu Server 24.04.x LTS **

Segurança no Ubuntu Server 24.04.x LTS no Oracle VirtualBOX, nesse vídeo você vai aprender todos os procedimentos habilitar e configurar o sistema de firewall UFW (Uncomplicated Firewall) em nosso servidor, criar as regras básicas de liberação de conexão externos e permitir somente de forma limitada e logada todo o acesso remoto via protocolo SSH em nosso servidor.

Uncomplicated Firewall é uma firewall desenhado para ser de fácil utilização. Utiliza uma interface de linha de comandos simple e de fácil entendimento, e usa o iptables como base para a sua configuração. 

O iptables é um programa escrito em C, utilizado como ferramenta para configurar as regras do protocolo de internet IPv4 na tabela de filtragem de pacotes, utilizando vários módulos e o framework do kernel Linux (versão 2.3.15 ou posteiro).

O netfilter é um módulo que fornece ao sistema operacional Linux as funções de firewall, NAT e log dos dados que trafegam na rede de computadores. iptables é o nome da ferramenta do espaço do usuário que permite a criação de regras de firewall e NATs.

O nftables é um subsistema do kernel Linux que fornece filtragem e classificação de pacotes de rede /datagramas/quadros. Ele está disponível desde o kernel Linux 3.13 lançado em 19 de janeiro de 2014. nftables substitui as partes legadas do iptables do Netfilter.

O rsyslog é uma ferramenta de software de código aberto amplamente utilizada em sistemas Unix e similares para o gerenciamento e a transferência de mensagens de log. Ele é uma implementação avançada do protocolo syslog original, oferecendo funcionalidades aprimoradas que atendem às necessidades modernas de monitoramento e análise de logs em ambientes de TI complexos.

TCP Wrapper é um sistema de rede ACL baseado em host, usado para filtrar acesso à rede a servidores de protocolo de Internet em sistemas operacionais do tipo Unix, como Linux ou BSD.

Conteúdo estudado nessa implementação:<br>
#01_ Verificando a Versão e Status do Firewall UFW no Ubuntu Server<br>
#02_ Habilitando (ENABLE) o Firewall UFW no Ubuntu Server<br>
#03_ Verificando o Serviço do UFW no Ubuntu Server<br>
#04_ Configurando as Regras (RULES) de Bloqueio (DENY) padrão (DEFAULT) de Entrada (INCOMING) e Saída (OUTGOING) do UFW no Ubuntu Server<br>
#05_ Configurando o Nível de Log (LOGGING) do UFW no Ubuntu Server<br>
#06_ Liberando (ALLOW) a Entrada (INCOMING) e Saída (OUTGOING) da Interface de Loopback do UFW no Ubuntu Server<br>
#07_ Liberando (ALLOW) as Saídas (OUTGOING) dos Protocolos Básicos no UFW do Ubuntu Server<br>
#08_ Liberando (ALLOW) a Saída (OUTGOING) do Protocolo ICMP do UFW no Ubuntu Server<br>
#09_ Limitando (LIMIT) e Logando Tudo (LOG-ALL) a Conexão de Entrada (INCOMING) do Protocolo SSH do UFW no Ubuntu Server<br>
#10_ Melhorando a Segurança e Logs Detalhados do TCPWrappers no Ubuntu Server<br>
#11_ Testando novamente a conexão com o OpenSSH e Certificado no Ubuntu Server<br>

Link da vídeo aula: https://www.youtube.com/watch?v=130Xdztvm0I

Link da documentação: https://github.com/vaamonde/ubuntu-2404/blob/main/02-settings/09-Seguranca-UFW.md

Link da vídeo aula: https://www.youtube.com/watch?v=PuahiojOEGA
