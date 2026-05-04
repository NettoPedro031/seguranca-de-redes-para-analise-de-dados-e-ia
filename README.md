# Segurança de Redes para Análise de Dados e IA

Repositório criado como parte do desafio de projeto  
**"Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM"**  
no bootcamp **Accenture - Python para Análise e Automação de Dados (DIO)**.

---

## 1. Contexto e Objetivos

Neste projeto, uso o **NotebookLM (Google)** como ferramenta de 
aprendizagem ativa para estudar **segurança de redes aplicada 
a dados e IA**.

### Tema do caderno temático
**Segurança de Redes para Análise de Dados e IA**

Foco em:
- Pilares CIA (Confidencialidade, Integridade e Disponibilidade);
- Arquiteturas de rede: Modelo OSI e TCP/IP;
- Roteadores, Firewalls e VPNs;
- Criptografia aplicada em redes;
- Segurança em redes sem fio e virtuais;
- Protocolos de segurança: IPsec, HTTPS, SSH, SFTP;
- Governança de dados e aplicações de IA.

### Objetivos de estudo
- Consolidar fundamentos de segurança de redes para provas e mercado;
- Entender como protocolos protegem dados usados em análises e IA;
- Conectar segurança de redes com governança de dados;
- Criar um miniguia de estudo reutilizável.

---

## 2. Curadoria de Fontes

Fontes selecionadas e carregadas no NotebookLM:

1. **Fundamentos de Segurança de Redes de Computadores**
   - Cobre: pilares CIA, ameaças, ataques e mecanismos de proteção.

2. **Roteadores e Configurações de Firewalls**
   - Cobre: dispositivos de borda, filtragem de pacotes, NAT e 
   segmentação de redes.

3. **Criptografia na Segurança de Redes de Computadores**
   - Cobre: criptografia simétrica, assimétrica, chaves e 
   certificados digitais.

4. **Segurança em Redes Sem Fio e Virtuais**
   - Cobre: Wi-Fi, WEP/WPA/WPA2/WPA3 e conceitos de VPN.

5. **Protocolos de Segurança de Redes de Computadores**
   - Cobre: IPsec, HTTPS, SSH, SFTP, camadas de atuação e 
   exemplos práticos.

**Critérios de curadoria:**
- Acesso aberto e gratuito;
- Conteúdo alinhado ao tema do desafio;
- Equilíbrio entre teoria e exemplos práticos;
- Linguagem didática.

---

## 3. Engenharia de Prompts e Cicatrizes

### Prompt 1 – Resumo geral do material
> "Usando apenas os documentos deste caderno, faça um resumo 
> estruturado sobre segurança de redes cobrindo: CIA, OSI/TCP-IP, 
> roteadores/firewalls, criptografia, redes sem fio/virtuais, 
> protocolos (IPsec, HTTPS, SSH, SFTP) e governança de dados. 
> Organize em seções com títulos e destaque o que é mais 
> importante para provas."

**Resultado:** (preencher com o que o NotebookLM gerou)  
**Cicatriz:** (preencher com dificuldades e ajustes feitos)

---

### Prompt 2 – Protocolos de segurança em profundidade
> "A partir dos documentos, explique IPsec, HTTPS, SSH e SFTP. 
> Para cada um: camadas de atuação (OSI/TCP-IP), tipo de proteção 
> oferecida e exemplo de uso corporativo. Use apenas o conteúdo 
> dos documentos. Se algo não estiver claro, diga explicitamente."

**Resultado:** (preencher)  
**Cicatriz:** (preencher)

---

### Prompt 3 – Roteiro de podcast
> "Usando exclusivamente os documentos carregados, escreva um 
> roteiro de podcast didático cobrindo todos os temas principais. 
> Escreva em tom de fala natural, sem depender de imagens, com 
> exemplos práticos e mini-resumos ao final de cada bloco."

**Resultado:** Este prompt foi usado no NotebookLM para gerar o Episódio 1 do podcast (“Tríade CIA e segurança de redes”). O modelo produziu um roteiro em tom de conversa, explicando de forma integrada a tríade CIA, a importância da informação, firewalls, roteadores com ACL, IDS/IPS, criptografia (simétrica, assimétrica, hash), protocolos seguros (HTTPS, SSH, SFTP, IPsec), redes Wi‑Fi e noções de nuvem (SaaS, PaaS, IaaS, pública/privada/híbrida). O texto veio organizado em blocos com exemplos do dia a dia (como o bunker, o banco, o Wi‑Fi da padaria, o home office) e com mini‑resumos ao final de cada parte, o que facilitou transformar o roteiro em um áudio de aproximadamente 17 minutos para revisão dos conteúdos.

**Cicatriz:** Apesar de funcionar bem como visão geral, esse prompt mostrou algumas limitações:

por ser genérico (“todos os temas principais”), o modelo acabou priorizando os tópicos mais amplos e deixou vários detalhes técnicos dos PDFs só citados de passagem, como modos do IPsec (transporte/túnel, AH/ESP), AAA com RADIUS/TACACS+, protocolos de VPN (L2TP, PPTP, L2F, SSL VPN), três estágios da criptografia ponta a ponta e os “sete pecados da nuvem”;
o prompt não pedia divisão clara por temas, então alguns blocos ficaram “misturando assuntos” (por exemplo, Wi‑Fi, VPN e nuvem no mesmo trecho), o que dificultou mapear diretamente cada parte do áudio de volta para um PDF específico.
A partir dessa cicatriz, refinei o Prompt 3 para o Episódio 2, especificando explicitamente os documentos usados e os temas mínimos por bloco (protocolos de transferência segura, IPsec em detalhes, AAA/RADIUS/TACACS+, segurança em Wi‑Fi, VPNs, nuvem e aprendizagem por projetos). Esse ajuste deixou o roteiro seguinte mais profundo, melhor alinhado aos textos técnicos e mais fácil de documentar no README como “revisão avançada” da parte de Segurança de Redes.

---

## 4. Miniguia de Estudo

### 4.1. Resumos estruturados
## 4. Miniguia de Estudo

### 4.1. Resumos estruturados

Nesta seção, organizei os principais conceitos dos PDFs em resumos estruturados para revisão rápida.
Eles estão alinhados com os roteiros dos podcasts (Episódios 1 e 2).

#### 4.1.1. Tríade CIA e papel da Segurança da Informação

- **Confidencialidade**  
  - Garantir que apenas pessoas/autenticações autorizadas acessem a informação.  
  - Ex.: criptografia, controle de acesso, cofres de senha, VPN, WPA2 no Wi‑Fi.  

- **Integridade**  
  - Garantir que o dado não seja alterado indevidamente (por erro ou ataque).  
  - Ex.: funções hash (efeito avalanche), assinaturas digitais, detecção de alteração em arquivos.  

- **Disponibilidade**  
  - Sistemas e dados devem estar acessíveis quando o usuário legítimo precisa.  
  - Ex.: monitoramento 24×7, alta disponibilidade (HA), planos de contingência.  

- **Equilíbrio dos 3 pilares**  
  - Exemplo do “servidor no bunker”: confidencialidade e integridade máximas, mas disponibilidade zero.  
  - Segurança é um **processo contínuo** (não um produto), que envolve revisar senhas padrão, parametrizações de fábrica e vigilância constante.

---

#### 4.1.2. Firewalls, roteadores, IDS/IPS e zonas de segurança

- **Firewall**  
  - Atua como muro entre redes de diferentes níveis de confiança (Internet, DMZ, LAN).  
  - Tipos: filtro de pacotes, stateful, proxy, NGFW (camada de aplicação).  
  - Divide a rede em zonas:  
    - **Internet** (sem confiança),  
    - **DMZ** (zona intermediária, saguão do banco),  
    - **LAN** (rede interna protegida).

- **Roteadores com ACL**  
  - Roteador é quem encaminha pacotes, mas também pode filtrar.  
  - **ACL (Access Control List)**: lista que define quem pode passar (IP/porta/protocolo).  
  - Analogia: segurança na porta de festa VIP com lista de convidados.

- **Netfilter e IPtables (Linux)**  
  - Netfilter atua no kernel, interceptando pacotes antes de chegar às aplicações.  
  - IPtables é a interface para configurar regras: bloquear IPs, NAT, redirecionamento, log de tráfego.

- **IDS x IPS**  
  - **IDS (Intrusion Detection System)**: detecta atividade suspeita e gera alerta (passivo).  
  - **IPS (Intrusion Prevention System)**: detecta e bloqueia ativamente tráfego malicioso (ativo).

---

#### 4.1.3. Criptografia: simétrica, assimétrica, hash e HTTPS

- **Criptografia simétrica**  
  - Mesma chave para cifrar e decifrar.  
  - Muito rápida, boa para grandes volumes de dados.  
  - Problema: distribuição segura da chave.

- **Criptografia assimétrica**  
  - Par de chaves: **pública** (para cifrar) e **privada** (para decifrar).  
  - Mais segura para troca de chaves, mas mais lenta.  
  - Na prática: usada para negociar chaves simétricas em protocolos como SSL/TLS.

- **Funções hash**  
  - Geram uma “impressão digital” fixa a partir de qualquer tamanho de arquivo.  
  - Pequena alteração no arquivo altera completamente o hash (efeito avalanche).  
  - Usadas para garantir **integridade** de arquivos e mensagens.

- **HTTPS / SSL / TLS**  
  - HTTPS = HTTP + SSL/TLS (criptografia entre navegador e servidor).  
  - Garante confidencialidade, integridade e autenticidade na web (ex.: banco, login, e‑commerce).

---

#### 4.1.4. Transferência segura de arquivos (CIA aplicada)

- **Dados em trânsito x dados em repouso**  
  - Em trânsito: enquanto viajam pela rede.  
  - Em repouso: armazenados em disco/servidor.

- **Criptografia em trânsito**  
  - Protocolos: **FTPS, SFTP, HTTPS, WebDAVs**, baseados em:  
    - **SSL/TLS** (FTPS, HTTPS, WebDAVs)  
    - **SSH** (SFTP – roda dentro de um túnel SSH).

- **Criptografia em repouso**  
  - Ex.: **OpenPGP** e criptografia de disco/arquivo.  
  - Protege o arquivo mesmo que alguém acesse o servidor ou o disco.

- **Três estágios da criptografia ponta a ponta**  
  1. Criptografar o arquivo **na origem** (antes de enviar).  
  2. Criptografar **durante a transferência** (túnel seguro SSL/TLS/SSH).  
  3. Criptografar **no destino** (armazenamento seguro).  

- **Integridade e HA**  
  - Integridade: hash e assinaturas digitais para detectar corrupção ou adulteração.  
  - Alta disponibilidade (HA): clusters **ativo‑passivo** ou **ativo‑ativo** para manter o serviço no ar.

---

#### 4.1.5. Wi‑Fi e redes sem fio

- **Classificação**  
  - **WPAN** – curtas distâncias (Bluetooth).  
  - **WLAN** – rede local sem fio (Wi‑Fi).  
  - **WMAN** – rede metropolitana (WiMAX).

- **Segurança Wi‑Fi**  
  - **WEP**: fraco, chaves curtas e estáticas, facilmente quebrado.  
  - **WPA**: transição, usa TKIP para melhorar WEP.  
  - **WPA2**: padrão atual com **AES**, muito mais robusto.  

- **SSID e “segurança por obscuridade”**  
  - Ocultar o SSID não resolve o problema: ferramentas detectam o tráfego mesmo assim.  
  - Segurança real vem de **criptografia forte** (WPA2 + AES).

- **TKIP, AES, 802.1X, EAP, RSN**  
  - **TKIP**: paliativo entre WEP e WPA; hoje considerado obsoleto.  
  - **AES**: criptografia forte usada no WPA2.  
  - **802.1X**: autenticação por porta (exige que o dispositivo se autentique antes de entrar).  
  - **EAP**: framework de métodos de autenticação (senha, certificado, token).  
  - **RSN/RSNA**: arquitetura de segurança robusta para redes Wi‑Fi modernas.

---

#### 4.1.6. VPNs e IPsec

- **VPN (Virtual Private Network)**  
  - Cria um “túnel” lógico seguro sobre uma rede pública.  
  - Permite que home office/filiais funcionem como se estivessem dentro da rede corporativa.

- **IPsec (Internet Protocol Security)**  
  - Extensão de segurança para o IP (camada de rede).  
  - Oferece controle de acesso, confidencialidade, integridade e autenticação.  
  - **Modos de operação**:  
    - **Transporte**: criptografa apenas o payload; cabeçalho IP original visível.  
    - **Túnel**: criptografa todo o pacote IP e encapsula em um novo IP (ideal para VPN entre redes).  
  - **Protocolos**:  
    - **AH (Authentication Header)**: autenticação e integridade.  
    - **ESP (Encapsulating Security Payload)**: confidencialidade (criptografia) + integridade.

- **Protocolos de VPN**  
  - **PPTP**: antigo, inseguro; não recomendado hoje.  
  - **L2TP**: faz tunelamento de camada 2; normalmente combina com IPsec (L2TP/IPsec).  
  - **L2F**: protocolo Cisco para tunelamento; precisa de criptografia adicional.  
  - **VPN SSL/TLS**: usa SSL/TLS via navegador; acesso remoto seguro com baixa barreira de entrada.

---

#### 4.1.7. AAA, RADIUS e TACACS+

- **AAA (Authentication, Authorization, Accounting)**  
  - Autenticação: quem é você?  
  - Autorização: o que você pode fazer?  
  - Accounting/Auditoria: o que você fez (logs, tempo, volume de dados).

- **RADIUS (Remote Authentication Dial‑In User Service)**  
  - Modelo cliente/NAS/servidor.  
  - Usa normalmente portas UDP 1645/1812 (autenticação) e 1646/1813 (accounting).  
  - Centraliza as credenciais para equipamentos de rede (Wi‑Fi corporativo, VPN, switches, roteadores).  
  - Ajuda a garantir **não repúdio** (log detalhado de quem fez o quê e quando).

- **TACACS+**  
  - Protocolo da Cisco, porta 49 (TCP/UDP).  
  - Muito usado para autenticar administradores em dispositivos de rede.  
  - Dá granularidade fina de autorização (comandos permitidos, etc.).

---

#### 4.1.8. Computação em Nuvem, Cloud/Fog/Edge e riscos

- **Modelos de serviço**  
  - **SaaS**: software pronto via web (e‑mail, ferramentas online).  
  - **PaaS**: plataforma para desenvolvimento e hospedagem de aplicações.  
  - **IaaS**: infraestrutura (VMs, storage, rede) “crua” para o cliente configurar.

- **Tipos de nuvem**  
  - **Pública**: infraestrutura compartilhada (AWS, Azure, GCP).  
  - **Privada**: nuvem dedicada a uma empresa.  
  - **Híbrida**: combinação de pública e privada.

- **Hierarquia Cloud/Fog/Edge**  
  - **Edge**: dispositivos de borda (sensores, câmeras, IoT).  
  - **Fog**: nós intermediários que pré‑processam e filtram dados perto da origem.  
  - **Cloud**: datacenters centrais, processamento pesado e armazenamento massivo.

- **Responsabilidade compartilhada**  
  - Provedor cuida da infraestrutura física e da disponibilidade básica.  
  - Cliente é responsável pela configuração de sistemas, senhas, firewall, permissões em storage etc.

- **“Sete pecados da cloud” (Zanutto)**  
  - Perda/vazamento de dados.  
  - Vulnerabilidades em tecnologias compartilhadas.  
  - Funcionário interno mal‑intencionado.  
  - Desvio de contas e serviços.  
  - APIs inseguras.  
  - Uso inapropriado da cloud.  
  - Perfil de risco desconhecido.

- **Categorias da Cloud Security Alliance (CSA)**  
  - Segurança tradicional (ataques, vulnerabilidades, phishing).  
  - Disponibilidade (uptime, pontos únicos de falha).  
  - Controle de dados por terceiros (auditoria, data lock‑in, espionagem).

---

### 4.2. Glossário

| Termo | Definição |
|---|---|
| CIA | Tríade de Confidencialidade, Integridade e Disponibilidade, base da segurança da informação. |
| Confidencialidade | Garantir que apenas usuários autorizados tenham acesso à informação (ex.: criptografia, controle de acesso). |
| Integridade | Garantir que os dados não sejam alterados indevidamente (ex.: hash, assinaturas digitais). |
| Disponibilidade | Garantir que os sistemas e dados estejam acessíveis quando necessário (ex.: HA, redundância). |
| Firewall | Dispositivo ou software que controla o tráfego de rede com base em regras, separando zonas (Internet, DMZ, LAN). |
| DMZ | Zona desmilitarizada: segmento intermediário entre a Internet e a rede interna, onde ficam serviços expostos ao público. |
| IDS | Intrusion Detection System: sistema que detecta tráfego suspeito e gera alertas, sem bloquear automaticamente. |
| IPS | Intrusion Prevention System: sistema que detecta e bloqueia tráfego malicioso em tempo real. |
| ACL | Access Control List: lista de regras em roteadores/firewalls que define quais IPs/portas podem passar. |
| Netfilter/IPtables | Mecanismo de filtragem no kernel Linux (netfilter) e ferramenta de configuração de regras de firewall (IPtables). |
| Criptografia simétrica | Mesma chave para cifrar e decifrar; rápida, usada para grandes volumes de dados. |
| Criptografia assimétrica | Par de chaves pública/privada; usada para troca segura de chaves e autenticação. |
| Hash | Função de mão única que gera uma “impressão digital” dos dados, usada para garantir integridade. |
| HTTPS | HTTP sobre TLS/SSL; protege comunicações web com confidencialidade, integridade e autenticidade. |
| SSL/TLS | Protocolos de segurança usados para criar canais criptografados (base de HTTPS, FTPS, WebDAVs). |
| SSH | Protocolo seguro para acesso remoto a servidores; base para SFTP. |
| SFTP | Protocolo de transferência de arquivos seguro que roda sobre SSH. |
| FTPS | FTP sobre SSL/TLS; adiciona criptografia à transferência de arquivos via FTP. |
| OpenPGP | Padrão de criptografia que protege arquivos/dados em repouso usando chaves assimétricas. |
| IPsec | Conjunto de protocolos de segurança na camada de rede, usado em VPNs, com modos transporte e túnel. |
| AH | Authentication Header; componente do IPsec focado em autenticação e integridade dos pacotes. |
| ESP | Encapsulating Security Payload; componente do IPsec que provê confidencialidade (criptografia) e integridade. |
| VPN | Rede privada virtual que cria túneis criptografados sobre redes públicas (ex.: Internet). |
| PPTP | Protocolo antigo de VPN; possui falhas conhecidas e não é recomendado em ambientes modernos. |
| L2TP | Protocolo de tunelamento de camada 2; geralmente combinado com IPsec para segurança. |
| L2F | Protocolo Cisco de tunelamento de camada 2; requer criptografia adicional para ser seguro. |
| VPN SSL/TLS | VPN baseada em SSL/TLS, acessível via navegador, sem cliente dedicado. |
| WPA/WPA2 | Protocolos de segurança para Wi‑Fi; WPA2 usa AES e é o padrão atual de segurança. |
| AES | Advanced Encryption Standard; algoritmo de criptografia simétrica forte, usado em WPA2 e outros protocolos. |
| TKIP | Temporal Key Integrity Protocol; paliativo entre WEP e WPA, hoje considerado obsoleto. |
| 802.1X | Padrão de autenticação em portas de rede (cabeada e Wi‑Fi), usado com RADIUS. |
| EAP | Extensible Authentication Protocol; framework de métodos de autenticação utilizado com 802.1X. |
| RSN/RSNA | Robust Security Network/Association; arquitetura de segurança robusta para redes Wi‑Fi modernas. |
| AAA | Authentication, Authorization, Accounting; modelo para controle de acesso e auditoria. |
| RADIUS | Protocolo de AAA centralizado, usado em Wi‑Fi corporativo, VPN e equipamentos de rede. |
| TACACS+ | Protocolo de AAA (porta 49) muito usado para autenticar administradores em equipamentos de rede. |
| SaaS | Software as a Service; software pronto consumido via internet (ex.: webmail). |
| PaaS | Platform as a Service; plataforma para desenvolver, testar e hospedar aplicações. |
| IaaS | Infrastructure as a Service; oferta de infraestrutura (VMs, storage, rede) como serviço. |
| Nuvem pública | Infraestrutura de cloud compartilhada entre vários clientes. |
| Nuvem privada | Infraestrutura de cloud dedicada a uma organização. |
| Nuvem híbrida | Combinação de nuvem pública e privada. |
| Edge Computing | Processamento na borda da rede, próximo aos dispositivos/usuários. |
| Fog Computing | Camada intermediária entre edge e cloud, que pré‑processa dados. |
| Cloud Computing | Processamento e armazenamento em datacenters centralizados na nuvem. |
| DLP | Data Loss Prevention; estratégias/tecnologias para evitar perda ou vazamento de dados. |

*(você pode continuar expandindo o glossário conforme estudar mais tópicos)*

---

### 4.3. Prompts reutilizáveis

Aqui estão alguns prompts prontos para reutilizar com o mesmo caderno de documentos
(no NotebookLM ou em outra IA que esteja conectada a esses PDFs):

- **Revisão geral:**
  > "Com base exclusivamente nos documentos deste caderno, faça um resumo em 10 tópicos
  > dos principais conceitos de segurança de redes (CIA, firewalls/IDS/IPS, criptografia, Wi‑Fi/VPN,
  > protocolos de segurança e nuvem), em linguagem simples."

- **Conceito específico:**
  > "Explique o que é **[CONCEITO]** com base apenas nos meus documentos de segurança de redes,
  > em até 8 linhas, com pelo menos um exemplo prático ligado a dados ou IA."

- **Comparação:**
  > "Compare **[CONCEITO A]** e **[CONCEITO B]** em termos de segurança de redes
  > (camada de atuação, impacto na CIA e casos de uso), usando apenas os meus documentos,
  > em até 6 linhas."

- **Checklist de prova:**
  > "Gere um checklist com 15 pontos que eu preciso lembrar sobre **[TEMA]** para a prova,
  > usando exclusivamente o conteúdo dos meus PDFs. Foque em conceitos, siglas importantes
  > e pelo menos 3 exemplos práticos."

- **Questões de múltipla escolha:**
  > "Crie 10 questões de múltipla escolha sobre **[TEMA]** usando apenas os meus documentos.
  > Para cada questão, dê 4 alternativas (A, B, C, D), indique a correta e explique o porquê em
  > 2 a 3 linhas."

- **Mapa mental em texto:**
  > "Monte um mapa mental em formato de lista sobre segurança em nuvem, usando só meus documentos:
  > organize em tópicos SaaS/PaaS/IaaS, pública/privada/híbrida, Cloud/Fog/Edge, sete pecados da cloud
  > e categorias da CSA."

### 4.4. Simulado de Prova (com base nos podcasts)

As questões abaixo foram elaboradas a partir dos roteiros dos episódios:

- Episódio 1 – “Tríade CIA e segurança de redes”
- Episódio 2 – “Blindagem de dados do Wi‑Fi à nuvem”

Cada questão tem 4 alternativas, com gabarito comentado.

---

#### Questão 1 – Tríade CIA

Em um exemplo do Episódio 1, é citado um servidor guardado em um bunker subterrâneo, sem internet e sem portas físicas. Qual é a conclusão sobre a tríade CIA nesse cenário?

A) Confidencialidade baixa, integridade alta e disponibilidade alta.  
B) Confidencialidade alta, integridade alta e disponibilidade praticamente nula.  
C) Confidencialidade baixa, integridade baixa e disponibilidade alta.  
D) Confidencialidade, integridade e disponibilidade todas no máximo.

**Resposta correta:** B  

**Comentário:**  
No exemplo do bunker, ninguém consegue acessar nem alterar os dados (confidencialidade e integridade muito altas), mas o próprio dono não consegue usar o servidor (disponibilidade zero). O episódio usa esse exemplo para mostrar que segurança não é só “trancar” tudo, e sim equilibrar os três pilares.

---

#### Questão 2 – Senhas padrão e parametrizações de fábrica

Por que as senhas padrão (como “admin/admin”) são consideradas tão perigosas, segundo o Episódio 1?

A) Porque reduzem apenas a disponibilidade do sistema.  
B) Porque exigem criptografia mais forte para funcionarem.  
C) Porque equivalem a deixar o cofre com a combinação em “0000”, facilitando a invasão.  
D) Porque impedem o uso de firewalls e IDS na rede.

**Resposta correta:** C  

**Comentário:**  
O episódio compara senhas padrão à combinação “0000” em um cofre caríssimo: o invasor nem precisa quebrar a criptografia, basta “puxar a maçaneta”. Isso mostra uma falha humana básica que quebra o equilíbrio da tríade, especialmente a confidencialidade.

---

#### Questão 3 – Firewall e DMZ

Qual analogia o Episódio 1 usa para explicar o papel da DMZ (zona desmilitarizada) na rede?

A) Um quarto trancado dentro de casa.  
B) Um cofre de banco subterrâneo.  
C) O saguão de um banco, com acesso público limitado.  
D) Um corredor vazio entre dois prédios.

**Resposta correta:** C  

**Comentário:**  
A DMZ é comparada ao saguão de um banco: qualquer pessoa pode entrar, mas há barreiras (como portas com detector de metais) que separam o saguão da área interna, onde ficam os cofres e os gerentes. É ali que ficam serviços públicos (como sites) sem expor diretamente a LAN.

---

#### Questão 4 – Netfilter e IPtables

De acordo com o Episódio 1, qual a relação entre Netfilter e IPtables no Linux?

A) Netfilter é um firewall de aplicação; IPtables é um IDS.  
B) Netfilter roda em user space; IPtables roda no kernel.  
C) Netfilter intercepta pacotes no kernel; IPtables é a interface onde o administrador escreve as regras.  
D) Netfilter é um protocolo de roteamento; IPtables é um protocolo de criptografia.

**Resposta correta:** C  

**Comentário:**  
O episódio explica que o Netfilter atua direto no núcleo (kernel) interceptando os pacotes, enquanto o IPtables é a ferramenta de configuração das regras (o “painel de controle”). Por isso, a filtragem acontece antes dos dados chegarem às aplicações.

---

#### Questão 5 – Criptografia simétrica x assimétrica

Segundo os episódios, por que não usamos criptografia assimétrica para todo o tráfego, apesar dela ser tão segura?

A) Porque a assimétrica não garante confidencialidade.  
B) Porque a assimétrica não funciona em redes públicas.  
C) Porque a assimétrica é mais lenta e consome muito processamento.  
D) Porque a assimétrica não permite uso de chaves públicas.

**Resposta correta:** C  

**Comentário:**  
No Episódio 1, a assimétrica é comparada a uma matemática “super pesada”: muito segura, mas lenta demais para grandes volumes (como vídeo 4K). Por isso, ela é usada só por alguns milissegundos para trocar a chave simétrica; depois, os dados são cifrados com simétrica, que é mais rápida.

---

#### Questão 6 – Hash e integridade

Qual imagem o Episódio 2 usa para explicar o papel de uma função hash?

A) Uma porta blindada de aço.  
B) Um moedor de carne digital que gera uma impressão digital única do arquivo.  
C) Uma caixa de correio pública.  
D) Um túnel escuro sem iluminação.

**Resposta correta:** B  

**Comentário:**  
A função hash é descrita como um “moedor de carne digital”: pega os dados e gera uma “impressão digital” única. Uma pequena alteração no arquivo muda completamente o hash, permitindo que o sistema detecte qualquer modificação e proteja a integridade.

---

#### Questão 7 – IPsec em modo transporte e modo túnel

No Episódio 2, qual analogia é usada para diferenciar o modo transporte do modo túnel no IPsec?

A) Modo transporte é um cofre; modo túnel é um armário aberto.  
B) Modo transporte é um cartão postal cifrado na mensagem; modo túnel é o cartão postal dentro de um envelope novo.  
C) Modo transporte é um livro aberto; modo túnel é um e-book protegido por senha.  
D) Não há diferença relevante entre os modos; ambos criptografam igual.

**Resposta correta:** B  

**Comentário:**  
O modo transporte é comparado a um cartão postal: o conteúdo está cifrado, mas endereços de origem e destino permanecem visíveis. Já o modo túnel coloca esse cartão dentro de um envelope com novo cabeçalho IP, escondendo inclusive quem está falando com quem atrás dos roteadores.

---

#### Questão 8 – AAA e RADIUS

Na analogia da “balada corporativa de luxo”, qual elemento representa a auditoria (Accounting) no modelo AAA?

A) O segurança conferindo RG na porta.  
B) A pulseira que dá acesso ao camarote VIP.  
C) As câmeras de segurança e as comandas registrando tudo que é consumido.  
D) O DJ que controla a música da festa.

**Resposta correta:** C  

**Comentário:**  
O Episódio 2 associa: Autenticação = segurança na porta, Autorização = tipo de pulseira (acesso), Auditoria = câmeras e comandas registrando tempo, consumo, ações. Em redes, é o log detalhado que permite rastrear tudo o que foi feito por cada identidade.

---

#### Questão 9 – Segurança em Wi‑Fi

Por que, segundo o Episódio 2, ocultar o SSID (nome da rede Wi‑Fi) é considerado uma falsa sensação de segurança?

A) Porque impede qualquer dispositivo de se conectar.  
B) Porque as ondas de rádio continuam sendo transmitidas e qualquer ferramenta básica ainda detecta a rede.  
C) Porque o SSID nunca é usado em ataques.  
D) Porque ocultar o SSID desativa o WPA2.

**Resposta correta:** B  

**Comentário:**  
O episódio explica que ocultar o SSID é “segurança por obscuridade”: o nome some da lista, mas o sinal continua no ar. Ferramentas simples detectam o tráfego mesmo sem o nome, então a verdadeira defesa é usar WPA2 com AES e, em ambientes corporativos, 802.1X/EAP com RADIUS.

---

#### Questão 10 – VPNs e serviços gratuitos

Qual é o principal risco apontado no Episódio 2 ao usar uma VPN gratuita sem modelo de negócio claro?

A) O tráfego fica visível apenas para o roteador do aeroporto.  
B) Não há criptografia entre o usuário e o servidor da VPN.  
C) O tráfego é criptografado até o servidor do provedor, mas pode ser analisado ou vendido por ele.  
D) A VPN impede qualquer acesso à internet.

**Resposta correta:** C  

**Comentário:**  
A VPN gratuita apenas desloca o ponto de confiança: o roteador público deixa de ver o conteúdo, mas o servidor da VPN enxerga tudo descriptografado. Como manter essa estrutura custa caro, se não há cobrança, é provável que o “produto” sejam os próprios dados do usuário.

---

#### Questão 11 – Modelos de serviço em nuvem

Qual analogia o Episódio 2 usa para explicar a diferença entre SaaS, PaaS e IaaS?

A) Reserva de hotel, hostel e camping.  
B) Apartamento mobiliado, apartamento sem acabamento e terreno vazio.  
C) Carro novo, carro usado e bicicleta.  
D) Restaurante, delivery e cozinhar em casa.

**Resposta correta:** B  

**Comentário:**  
SaaS é comparado a um apartamento mobiliado pronto para morar (software pronto, como webmail). PaaS é o apartamento com paredes prontas, mas você escolhe móveis e acabamento (plataforma para desenvolver apps). IaaS é o terreno nu, onde você constrói tudo (infraestrutura bruta).

---

#### Questão 12 – Edge, Fog e Cloud

Segundo o Episódio 2, qual é o papel dos nós de Fog (Fog Nodes) em uma arquitetura com Edge e Cloud?

A) Substituir completamente a nuvem, processando tudo localmente.  
B) Apenas armazenar dados, sem processamento.  
C) Servir como servidores intermediários que pré‑processam dados da borda antes de enviar para a nuvem central.  
D) Apenas duplicar dados para backup.

**Resposta correta:** C  

**Comentário:**  
Os nós de Fog recebem dados brutos dos dispositivos de borda (Edge), filtram, agregam e só então enviam um volume reduzido e mais rico para a Cloud. Isso reduz latência e tráfego, mas aumenta a superfície de ataque, como destacado no episódio.

