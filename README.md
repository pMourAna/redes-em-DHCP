
# Lab — Rede com DHCP

## Sobre o Laboratório

Neste projeto montei uma pequena rede no Cisco Packet Tracer
para entender na prática como funciona o DHCP.

A ideia foi configurar um servidor para distribuir
automaticamente os endereços IP para os computadores da rede,
sem precisar configurar cada PC manualmente.

## Topologia

A rede foi montada com:

- 1 servidor
- 1 switch
- 2 PCs

[imagem da topologia]

## Configuração

O servidor foi configurado com um endereço IP fixo e o serviço
DHCP foi ativado.

Depois configurei os PCs para obter suas configurações de rede
automaticamente através do DHCP.

## Testes

Depois que os PCs receberam seus endereços IP, fiz um teste
de conectividade usando o comando:

`ping`

O teste foi realizado entre os computadores e houve resposta
dos pacotes enviados.

## DHCP na prática

Também utilizei o Simulation Mode do Packet Tracer para
acompanhar a solicitação DHCP acontecendo na rede.

Foi possível observar o processo:

**DHCP Discover → DHCP Offer → DHCP Request → DHCP ACK**

Esse processo mostrou na prática como o computador solicita
um endereço e como o servidor DHCP responde e confirma a
configuração.

## O que eu aprendi

- Como configurar um servidor DHCP no Packet Tracer
- Como configurar um computador para obter IP automaticamente
- Como funciona o processo DORA
- Como verificar as configurações de IP
- Como testar a comunicação entre dispositivos usando ping
- Como observar o funcionamento do DHCP através do Simulation Mode

## Evidências

As imagens e a gravação da simulação estão na pasta
`evidencias/`.

## Ferramentas utilizadas

- Cisco Packet Tracer
- DHCP
- IPv4
- ICMP / Ping
