RCOMP 2019-2020 Project - Sprint 2 - Member 1190769 folder
===========================================

# VLANs Usadas #

| VLANID | Display Nome | Função |
|:----------:|:----------:|:----------:|
|260|VLAN_Backboune|Uma VLAN para a backblone|
|271|VLAN_4_GFOutlets|Uma VLAN para todas os outlets no piso 0|
|272|VLAN_4_F1Outlets|Uma VLAN para todas os outlets no piso 1|
|273|VLAN_4_WiFiNetwork|Uma VLAN para a rede Wi-Fi (para todas as saídas de pontos de acesso dentro do edifício)|
|274|VLAN_4_DMZ|Uma VLAN para a DMZ do edificio (para servidores, estações de trabalho de administração e industriais máquinas para os edifícios 3, 4 e 5)|
|275|VLAN_4_VoIP|Uma VLAN para VoIP (para telefones IP)|


| VLANID | SubNetID | Host Range | Broadcast | Máscaras |
|:----------:|:----------:|:----------:|:----------:|:-----------:|
|260|10.124.250.0|10.124.250.1 -- 10.124.250.126|10.124.250.127|255.255.255.128|
|271|10.124.245.64|10.124.245.65 -- 10.124.245.126|10.124.245.127|255.255.255.192|
|272|10.124.245.128|10.124.245.129 -- 10.124.245.190|10.124.245.191|255.255.255.192|
|273|10.124.245.0|10.124.245.1 -- 10.124.245.62|10.124.245.63|255.255.255.192|
|274|10.124.244.0|10.124.244.1 -- 10.124.244.254|10.124.244.255|255.255.255.0|
|275|10.124.245.192|10.124.245.193 -- 10.124.245.222|10.124.245.223|255.255.255.224|


# Routing Table #

10.124.248.0/26 via 10.124.250.1
10.124.240.0/26 via 10.124.250.2
10.124.242.0/26 via 10.124.250.3
10.124.246.0/26 via 10.124.250.5