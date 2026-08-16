# 🌐 Laboratório: Rede Hierárquica — Mulher Digital

Atividade prática de laboratório desenvolvida no **Cisco Packet Tracer** para compreender a organização de uma rede corporativa utilizando o modelo hierárquico em três camadas: **Acesso, Distribuição e Núcleo (Core)**.

## Topologia:

A rede foi composta por:

* 1 Roteador Cisco 4331 — **Core**
* 1 Switch Cisco 3650 — **Distribuição**
* 2 Switches Cisco 2960 — **Acesso**
* 4 PCs

A estrutura foi organizada da seguinte forma:

```text
PCs + Switches de Acesso → Switch de Distribuição → Roteador Core
```

## O que foi realizado:

* Montagem da topologia hierárquica no Cisco Packet Tracer;
* Conexão dos dispositivos utilizando cabos Straight-Through;
* Configuração de endereçamento IP static nos PCs;
* Configuração da interface do roteador via CLI;
* Ativação da interface com `no shutdown`;
* Testes de conectividade utilizando `ping`;
* Simulação de pacotes **ICMP** para visualizar o caminho da comunicação.

## O que aprendi:

Com esta atividade, aprendi na prática como funciona a estrutura de redes hierárquicas, entendendo a separação entre as camadas de acesso, distribuição e núcleo. Também pratiquei o endereçamento IPV4 e a configuração básica de roteadores Cisco utilizando a CLI, além de realizar testes de conectividade com o comando ping. Durante a simulação, foi possível observar o funcionamento do protocolo ICMP e compreender melhor como os dados percorrem as diferentes camadas da rede até chegar ao destino.



