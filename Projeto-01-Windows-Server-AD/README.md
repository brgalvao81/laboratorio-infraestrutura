# Projeto 01: Windows Server e Active Directory

Laboratório em máquina virtual para praticar o que as vagas de suporte e help desk pedem em ambiente Windows: servidor, Active Directory, usuários, senhas, acessos, protocolos de rede, DNS, DHCP, acesso remoto, backup e segurança.

## Ambiente
- Notebook com Windows 11 e VirtualBox
- Servidor `SRV01`: Windows Server 2025 Standard Evaluation (Desktop Experience)
- Domínio: `empresa.local`

## Partes

| Parte | Tema | Situação |
|---|---|---|
| 1 | Instalação do Windows Server e promoção a controlador de domínio | feito: [parte01](parte01-instalacao-e-promocao.md) |
| 2 | Verificar o domínio e criar OUs, grupos e usuários | em andamento |
| 3 | Gerenciamento de acessos: senhas, bloqueio de conta, permissões e pasta compartilhada | planejado |
| 4 | Política de grupo (GPO) | planejado |
| 5 | Redes e protocolos TCP/IP, DNS e DHCP | planejado |
| 6 | Administração e monitoramento do servidor | planejado |
| 7 | Acesso remoto e suporte remoto (RDP e Assistência Rápida) | planejado |
| 8 | Backup e restauração, e virtualização (snapshots) | planejado |
| 9 | Segurança da informação (firewall, antivírus, senhas e LGPD) | planejado |
| 10 | Troubleshooting: cenários de problemas de usuários e de rede | planejado |

### O que cada parte cobre

**Parte 5: Redes e protocolos TCP/IP, DNS e DHCP**
- TCP/IP: endereço IP, máscara de sub-rede, gateway e DNS.
- Protocolos e portas: ICMP (ping), ARP, DNS (53), DHCP (67 e 68), HTTP (80), HTTPS (443), SSH (22), RDP (3389), SMB (445) e os usados pelo Active Directory (LDAP 389 e Kerberos 88).
- DNS: zonas, registros A, CNAME e PTR, e resolução de nomes com `nslookup`.
- DHCP: escopo, reservas e concessões de endereços.
- Ferramentas de diagnóstico: `ping`, `tracert`, `nslookup`, `ipconfig`, `netstat` e `Test-NetConnection`.

**Parte 6: Administração e monitoramento do servidor**
- Visualizador de Eventos, Gerenciador de Tarefas, Monitor de Desempenho e serviços.
- Comandos do PowerShell para consultar o estado do servidor.

**Parte 7: Acesso remoto e suporte remoto**
- Área de Trabalho Remota (RDP) para o servidor e a Assistência Rápida entre dois equipamentos.

**Parte 8: Backup e virtualização**
- Windows Server Backup: fazer um backup, apagar um arquivo e restaurar.
- Snapshots no VirtualBox como ponto de retorno da máquina virtual.

**Parte 9: Segurança da informação**
- Firewall do Windows, Microsoft Defender, política de senhas e noções de LGPD.

**Parte 10: Troubleshooting**
- Cenários simulados: conta bloqueada, usuário sem acesso a uma pasta, computador sem rede, DNS errado e serviço parado, com o passo a passo da solução.

## Próximos projetos
Os itens que dependem de outras ferramentas ficam em projetos separados, listados no [mapa das vagas](../mapa-das-vagas.md): sistema de chamados e inventário (GLPI), equipamentos de rede e VPN, monitoramento (Zabbix e Grafana), Microsoft 365 e Office, e hardware e manutenção.
