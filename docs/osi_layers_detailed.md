# OSI Layers Explained / Explicação das Camadas do Modelo OSI

| Layer | Name (EN)       | Nome (PT)              | Key Role (Função Principal)                               |
|-------|------------------|-------------------------|------------------------------------------------------------|
| 7     | Application      | Aplicação               | Interface com o usuário e serviços de rede                 |
| 6     | Presentation     | Apresentação            | Formatação, criptografia e compressão dos dados           |
| 5     | Session          | Sessão                  | Estabelecimento, controle e encerramento de sessões       |
| 4     | Transport        | Transporte              | Entrega fim a fim confiável ou rápida                     |
| 3     | Network          | Rede                    | Endereçamento e roteamento de pacotes                     |
| 2     | Data Link        | Enlace de Dados         | Comunicação ponto a ponto com endereços MAC               |
| 1     | Physical         | Física                  | Transmissão de bits no meio físico                        |

---

## Examples of Protocols / Exemplos de Protocolos

### Layer 7 - Application
- HTTP, HTTPS, FTP, SMTP, DNS, DHCP, SIP
- Ex: Navegar na web (HTTP), enviar e-mail (SMTP), VoIP (SIP)

### Layer 6 - Presentation
- SSL/TLS, ASCII, JPEG, MPEG
- Ex: Criptografia HTTPS (TLS), codificação de imagens

### Layer 5 - Session
- NetBIOS, RPC, PPTP
- Ex: Sessão VPN, compartilhamento de arquivos Windows

### Layer 4 - Transport
- TCP, UDP, SCTP
- Ex: TCP (navegação segura), UDP (streaming de vídeo)

### Layer 3 - Network
- IP, ICMP, IPSec, OSPF, RIP
- Ex: IP para endereçamento e roteamento; ICMP para ping

### Layer 2 - Data Link
- Ethernet, VLAN (802.1Q), PPP, ARP
- Ex: Comunicação entre dispositivos via switch (MAC)

### Layer 1 - Physical
- RJ-45, UTP, Fiber, Wi-Fi (físico), DSL
- Ex: Sinais elétricos, ondas de rádio, cabos ópticos
