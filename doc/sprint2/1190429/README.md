RCOMP 2019-2020 Project - Sprint 2 - Member 1190429 folder
===========================================

# VLANs Usadas #

| VLANID | Display Nome | Função |
|:----------:|:----------:|:----------:|
|255|VLAN_1_GFOutlets|Uma VLAN para todas os outlets no piso 0|
|256|VLAN_1_F1Outlets|Uma VLAN para todas os outlets no piso 1|
|257|VLAN_1_WiFiNetwork|Uma VLAN para a rede Wi-Fi (para todas as saídas de pontos de acesso dentro do edifício)|
|258|VLAN_1_DMZ|Uma VLAN para a DMZ do edificio (para servidores, estações de trabalho de administração e industriais máquinas para os edifícios 3, 4 e 5)|
|259|VLAN_1_VoIP|Uma VLAN para VoIP (para telefones IP)|


| VLANID | SubNetID | Host Range | Broadcast|
|:----------:|:----------:|:----------:|:----------:|
|255|10.124.248.128|10.124.248.129 -- 10.124.248.190|10.124.248.191|
|256|10.124.248.192|10.124.248.193 -- 10.124.248.254|10.124.248.255|
|257|10.124.249.0|10.124.249.1 -- 10.124.249.30|10.124.249.31|
|258|10.124.248.0|10.124.248.1 -- 10.124.248.126|10.124.248.127|
|259|10.124.249.32|10.124.249.33 -- 10.124.249.62|10.124.249.63|


# Routing Table #

10.124.240.0/23 via 10.124.250.2
10.124.242.0/23 via 10.124.250.3
10.124.244.0/23 via 10.124.250.4
10.124.246.0/23 via 10.124.250.5