RCOMP 2019-2020 Project - Sprint 2 - Member 1190974 folder
===========================================

# VLANs Usadas#

| VLANID | Display Nome | Função |
|:----------:|:----------:|:----------:|
|261|VLAN_2_GFOutlets|Uma VLAN para todas os outlets no piso 0|
|262|VLAN_2_F1Outlets|Uma VLAN para todas os outlets no piso 1|
|263|VLAN_2_WiFiNetwork|Uma VLAN para a rede Wi-Fi (para todas as saídas de pontos de acesso dentro do edifício)|
|264|VLAN_2_DMZ|Uma VLAN para a DMZ do edificio (para servidores, estações de trabalho de administração e industriais máquinas para os edifícios 3, 4 e 5)|
|265|VLAN_2_VoIP|Uma VLAN para VoIP (para telefones IP)|



| VLANID | SubNetID | Host Range | Broadcast|
|:----------:|:----------:|:----------:|:----------:|
|261|10.124.241.0|10.124.241.1 -- 10.124.241.62|10.124.241.63|
|262|10.124.240.128|10.124.240.129 -- 10.124.240.254|10.124.240.255|
|263|10.124.240.0|10.124.240.1 -- 10.124.240.126|10.124.240.127|
|264|10.124.241.128|10.124.241.129 -- 10.124.241.142|10.124.241.143|
|265|10.124.241.64|10.124.241.65 -- 10.124.241.126|10.124.241.127|