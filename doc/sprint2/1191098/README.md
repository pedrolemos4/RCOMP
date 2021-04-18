RCOMP 2020-2021 Project - Sprint 2 - Member 1191098 folder
===========================================

# VLANs Usadas #

| VLANID | Display Nome | Função |
|:----------:|:----------:|:----------:|
|260|VLAN_Backbone|Uma VLAN para a backbone|
|266|Vlan_GroundFloor_Outlets|Uma VLAN para todas os outlets no piso 0|
|267|Vlan_FloorOne_Outlets|Uma VLAN para todas os outlets no piso 1|
|268|Vlan_WiFi_Network|Uma VLAN para a rede Wi-Fi (para todas as saídas de pontos de acesso dentro do edifício)|
|269|Vlan_DMZ|Uma VLAN para a DMZ do edificio (para servidores, estações de trabalho de administração e industriais máquinas para os edifícios 3, 4 e 5)|
|270|Vlan_VoIP|Uma VLAN para VoIP (para telefones IP)|

| VLANID | SubNetID | Host Range | Broadcast | Mask |
|:----------:|:----------:|:----------:|:----------:|:----------:|
|266|10.124.243.0|10.124.243.1 -- 10.124.243.62|10.124.243.63|255.255.255.192|
|267|10.124.243.64|10.124.243.65 -- 10.124.243.126|10.124.243.127|255.255.255.192|
|268|10.124.243.128|10.124.243.129 -- 10.124.243.190|10.124.243.191|255.255.255.192|
|269|10.124.242.0|10.124.242.1 -- 10.124.242.254|10.124.242.255|255.255.255.0|
|270|10.124.243.192|10.124.243.1 -- 10.124.243.254|10.124.243.255|255.255.255.192|
|260|10.124.250.0|10.124.250.1 -- 10.124.250.126|10.124.250.127|255.255.255.128|


# Routing Table #

10.124.248.0/23 via 10.124.250.1

10.124.240.0/23 via 10.124.250.2

10.124.244.0/23 via 10.124.250.4

10.124.246.0/23 via 10.124.250.5