---

# Testado e homologado no GNU/Linux Ubuntu Server 24.04.x LTS

## Links de Referência e Releases
* **Release Ubuntu Server 24.04:** [Acessar Link](https://fridge.ubuntu.com/2024/04/25/ubuntu-24-04-lts-noble-numbat-released/)
* **Release Notes 24.04.3:** [Acessar Link](https://fridge.ubuntu.com/2025/08/08/ubuntu-24-04-3-lts-released/)
* **Release Notes 24.04.2:** [Acessar Link](https://fridge.ubuntu.com/2025/02/20/ubuntu-24-04-2-lts-released/)
* **Release Notes 24.04.1:** [Acessar Link](https://lists.ubuntu.com/archives/ubuntu-announce/2024-August/000304.html)
* **Release Notes 24.04.x:** [Acessar Link](https://canonical.com/blog/canonical-releases-ubuntu-24-04-noble-numbat)
* **Ubuntu Advantage for Infrastructure:** [Acessar Link](https://ubuntu.com/advantage)
* **Ciclo de Lançamento:** [Acessar Link](https://ubuntu.com/about/release-cycle)
* **Releases All Ubuntu Server:** [Acessar Link](https://wiki.ubuntu.com/Releases)

---

## Conteúdo estudado nessa instalação
1. Download da ISO do Ubuntu Server 24.04.x LTS
2. Criação da Máquina Virtual no Oracle VirtualBOX
3. Configurações da Máquina Virtual DockerUbuntu
4. Iniciando a Instalação do Ubuntu Server 24.04.x LTS (localizar a ISO)
5. Instalação e Configuração do Ubuntu Server 24.04.x LTS
6. Acessando o Ubuntu Server pela primeira vez

---

## Sites de IA (Inteligência Artificial) indicados para os Desafios
* **OpenAI ChatGPT:** [https://chatgpt.com](https://chatgpt.com)
* **Microsoft Copilot:** [https://copilot.microsoft.com](https://copilot.microsoft.com)
* **Google Gemini:** [https://gemini.google.com](https://gemini.google.com)
* **DeepSeek:** [https://chat.deepseek.com/](https://chat.deepseek.com/)
* **x.AI Grok:** [https://grok.com/](https://grok.com/)

---

## Perguntas para a IA

**Prompt-01:**
> qual sistema operacional que mais se destacada em serviços para Container Local (on-premises) e Cloud (nuvem) no Brasil e no Mundo, por que ele é o mais usado?

**Prompt-02:**
> qual distribuição GNU/Linux lidera o mercado de servidores locais (on-premises) e nuvem (cloud) no Brasil e no mundo? por que essas distribuições são as mais usadas?

**Prompt-03:**
> quais as principais Big Techs no Brasil e no mundo que utiliza o GNU/Linux?

**Prompt-04:**
> quais as principais Big Techs no Brasil e no mundo utiliza Container? 

---

## Glossário de Conceitos

* **O QUE É E PARA QUE SERVE O ON-PREMISES:** O "on-premises" se refere a uma infraestrutura de TI que está localizada fisicamente nas instalações da empresa. Isso significa que os servidores, bancos de dados, aplicações e demais recursos de TI são hospedados, gerenciados e mantidos internamente pela equipe da empresa, em vez de serem executados em uma nuvem pública como AWS, Azure ou Google Cloud.
* **O QUE É E PARA QUE SERVE O CLOUD:** O Cloud Computing (Computação em Nuvem) é um modelo de TI que permite o acesso remoto a servidores, armazenamento, bancos de dados, redes e softwares por meio da internet. Em vez de manter servidores e infraestrutura física dentro da empresa (on-premises), tudo é hospedado em datacenters de provedores de nuvem, como AWS, Microsoft Azure, Google Cloud, entre outros.
* **O QUE É E PARA QUE SERVE A CANONICAL:** A Canonical Ltd. é uma empresa de tecnologia britânica fundada por Mark Shuttleworth em 2004. Ela é conhecida principalmente como a desenvolvedora do sistema operacional Ubuntu, uma das distribuições Linux mais populares do mundo.
* **O QUE É E PARA QUE SERVE O UBUNTU SERVER:** O Ubuntu Server é uma versão do sistema operacional Ubuntu desenvolvida especificamente para servidores. Ele é baseado no Debian e é uma das distribuições Linux mais populares para servidores devido à sua estabilidade, segurança e facilidade de uso.
* **O QUE É E PARA QUE SERVE O LTS:** LTS significa Long-Term Support (Suporte de Longo Prazo). Ele é um tipo de versão de software que recebe atualizações e suporte por um período estendido, geralmente de 3 a 5 anos ou mais, dependendo do projeto.
* **O QUE É E PARA QUE SERVE O UBUNTU SERVER MINIMAL:** O Ubuntu Server Minimal é uma versão enxuta do Ubuntu Server, projetada para oferecer uma instalação mais leve e essencial, sem pacotes e serviços adicionais que podem não ser necessários para todos os usuários. Ele é ideal para quem deseja uma base limpa e personalizada, instalando apenas os componentes essenciais para o funcionamento do servidor.

**Vídeo Aula:** [Assista no YouTube](https://www.youtube.com/watch?v=p4f6a_-yM_8)

---

## 01. Download da ISO do Ubuntu Server 24.04.x LTS
**Link oficial:** [https://releases.ubuntu.com/24.04/](https://releases.ubuntu.com/24.04/)

1. **Versão:** `ubuntu-24.04.3-live-server-amd64.iso` (Atualizado em 06/10/2025)
2. **Arquitetura:** AMD64 (64-bit)
3. **Tipo:** DVD Image (ISO) Installer

---

## 02. Criação da Máquina Virtual no Oracle VirtualBOX
* **Download VirtualBOX:** [Clique aqui](https://www.virtualbox.org/wiki/Downloads)
* **Instalação no Linux Mint:** [Vídeo](https://www.youtube.com/watch?v=yTihvAaaxpU)
* **Atualização no Linux Mint:** [Vídeo](https://www.youtube.com/watch?v=DU47PLFSxpA)

**OBSERVAÇÃO:** Utilizar o Oracle VirtualBOX Gerenciador (versão 7.x ou superior).

1.  **Ferramentas > Novo**
2.  **Nome e SO:**
    * **Nome:** DockerUbuntu
    * **Pasta:** #PATH_PADRÃO\DockerUbuntu
    * **Imagem ISO:** \<não selecionar\>
    * **Tipo:** Linux
    * **Versão:** Ubuntu (64-bit)
3.  **Hardware:**
    * **Memória Base:** 4096MB (mínimo 2048MB)
    * **Processadores:** 02 CPU (mínimo 2 CPU)
    * **Habilitar EFI:** OFF
4.  **Disco Rígido Virtual:**
    * **Criar um novo disco agora:** ON
    * **Tamanho:** 50,00GB (mínimo 50GB)
    * **Pré-alocar Tamanho Total:** OFF

---

## 03. Configurações da Máquina Virtual DockerUbuntu

1.  **Selecionar VM: DockerUbuntu > Configurações**
2.  **Sistema:**
    * **Placa-Mãe:** Relógio retorno hora UTC: OFF
    * **Processador:** Habilitar PAE/NX e Habilitar VT-x/AMD-v Aninhado: ON
3.  **Monitor:**
    * **Memória de Vídeo:** 128MB
    * **Aceleração 3D:** ON
4.  **Áudio:**
    * **Habilitar Áudio:** OFF
5.  **Rede:**
    * **Adaptador 1 (LAN):** Habilitar Placa de Rede: ON
    * **Conectado a:** Placa em modo Bridge
    * **Nome:** Selecionar sua placa ativa (Preferencialmente cabeada).

---

## 04. Iniciando a Instalação (Localizar ISO)

1.  **Selecionar VM > Iniciar**
2.  **VirtualBOX VM:**
    * **DVD:** \<Outro\>
    * Selecionar a ISO baixada.
3.  **Montar e Tentar Novo Boot**

---

## 05. Instalação e Configuração do Ubuntu Server 24.04.x LTS
**Documentação oficial:** [Ubuntu Server Docs](https://ubuntu.com/server/docs/installation)

> **DICA:** Para parar o Boot Inicial, pressione `<Seta para Baixo>`.

| Opção de Boot | Descrição |
| :--- | :--- |
| **Try or Install Ubuntu Server** | Instalador padrão. Recomendado. |
| **Ubuntu Server with the HWE kernel** | Suporte a hardwares mais recentes. |
| **Test memory** | Executa Memtest86+ para diagnóstico de RAM. |

### Passo a Passo:
1.  **Try or Install Ubuntu Server**
2.  **Language:** English
3.  **Keyboard:** Portuguese (Brazil) / Variant: Portuguese (Brazil)
4.  **Type of install:** Ubuntu Server (minimized)
5.  **Network:** Verificar DHCPv4 (enp0s3)
6.  **Proxy:** Default (vazio)
7.  **Mirror:** `http://archive.ubuntu.com/ubuntu`
8.  **Storage:** Use an entire disk / Set up as LVM group
9.  **Storage Config:** Editar `ubuntu-lv` para ocupar o tamanho máximo (47.996G) e Salvar.
10. **Profile setup:** Definir Nome, Nome do Servidor (ctnseunome), Usuário e Senha.
11. **Ubuntu Pro:** Skip for now.
12. **SSH Setup:** [X] Install OpenSSH server.
13. **Featured Server Snaps:** Done.
14. **Install complete!** > Reboot Now.
15. **Remove medium:** Pressione Enter.

---

## 06. Acessando pela primeira vez via Terminal

**OBSERVAÇÃO:** Aguarde a geração das chaves SSH antes de pressionar Enter na tela de login.

1.  **Login:** seu_usuário
2.  **Password:** sua_senha
3.  **Resultado esperado:** `seu_usuário@ctnseunome:~$`
