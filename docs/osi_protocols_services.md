# Protocols and Services in the OSI Model / Protocolos e Serviços no Modelo OSI

## Real-World Examples / Exemplos Reais

### 1. HTTP (Web Browsing - Navegação Web)
- Camada 7: HTTP/HTTPS
- Camada 6: TLS (se HTTPS)
- Camada 5: Sessão persistente entre cliente e servidor
- Camada 4: TCP (porta 80 ou 443)
- Camada 3: IP (endereçamento e roteamento)
- Camada 2: Ethernet (comunicação local)
- Camada 1: Cabo ou Wi-Fi

---

### 2. Email (Envio via SMTP)
- Camada 7: SMTP (envio), IMAP/POP3 (recebimento)
- Camada 4: TCP (porta 25, 587, 993)
- Camada 3: IP
- Camada 2 e 1: Ethernet/Física

---

### 3. VoIP (SIP + RTP)
- Camada 7: SIP (sinalização)
- Camada 6: SDP, codecs (G.711, G.729)
- Camada 5: Sessão VoIP
- Camada 4: UDP (rapidez sem verificação)
- Camada 3: IP (com QoS em redes empresariais)
- Camada 2: VLANs para VoIP (802.1Q)
- Camada 1: Switch + cabo UTP

---

### 4. DNS Query (Resolução de Nomes)
- Camada 7: DNS
- Camada 4: UDP (porta 53)
- Camada 3: IP
- Camada 2 e 1: Rede local

---

## Summary Table (Tabela Resumo de Serviços)

| Serviço         | Aplicação | Transporte | Rede | Enlace | Física |
|----------------|-----------|------------|------|--------|--------|
| HTTP/HTTPS     | HTTP/TLS  | TCP        | IP   | Ethernet | UTP    |
| VoIP           | SIP/RTP   | UDP        | IP   | VLAN     | UTP    |
| Email          | SMTP/IMAP | TCP        | IP   | Ethernet | UTP    |
| DNS            | DNS       | UDP        | IP   | Ethernet | UTP    |
