RCOMP 2020-2021 Project - Sprint 1 - Member 1191098 folder
===========================================

# Piso 0 #
![Piso0](Piso0.PNG)

#### Medidas ####

| Sala | Comprimento (cm) | Largura (cm) | Comprimento Real (m) | Largura Real (m) | Área (m²) | Outlets |
|----------|----------|----------|---------|---------|---------|----------|
| 30.1 | 1,40 | 1,10 | 7,778 | 6,111 | 47,531 | 10 |
| 30.2 | 1,40 | 1,20 | 7,778 | 6,667 | 51,856 | 12 |
| 30.3 | 1,40 | 1,20 | 7,778 | 6,667 | 51,856 | 12 |
| 30.4 | 1,40 | 1,40 | 7,778 | 7,778 | 60,497 | 12 |
| 30.5 | 1,40 | 1,10 | 7,778 | 6,111 | 47,531 | 10 |
| Open Area | 10,10 | 5 | 56,111 | 27,778 | 1558,483 | 312 |

Todas as medições tiveram em conta a escala representada na figura. Considerei que 10 metros correspondem a 3,3 centímetros. De forma a calcular o número de outlets em cada sala, foi seguida a regra que refere que têm de existir 2 outlets a cada 10 m² em todas as salas deste piso.

Como a sala 30.1 tem 47,531 m² de área, são necessários 10 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância. 
Cada um destes 10 outlets está ligado a um CP instalado na sala 30.3.

Como a sala 30.2 tem 51,856 m² de área, são necessários 12 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Cada um destes 12 outlets está ligado a um CP instalado na sala 30.3.

Como a sala 30.3 tem 51,856 m² de área, são necessários 12 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Foram colocados neste espaço um CP, devido ao número elevado de outlets existentes nesta zona (salas 30.1, 30.2, 30.3), um patch panel de 48 portas, com 2U de tamanho, e um switch de 48 portas, de 2U tamanho. Será portanto utilizado um gabinete de 12U.

A sala 30.4 é a sala de telecomunicações do edifício, uma vez que é nessa sala que entrarão os cabos de fibra de ótica monomodo provenientes do exterior e é a partir dessa sala que os cabos passarão para o andar de cima. Assim, nesta sala foi colocado o IC do piso, assim como um dos HC's, para cobrir a área do lado esquerdo do edifício.
Como esta sala tem 60,497 m² de área, são necessários 12 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância. 
Nesta sala foi ainda colocado um patch panel, para os cabos de fibra ótica monomodo, de 8 portas, sendo que 2 portas são utilizadas para o IC, 1 para um CP da sala 30.5 e 1 para o HC da área do lado direito do edifício. Para a ligação aos outlets foi colocado um patch panel de 24 portas, com 1U de tamanho, e um switch de 24 portas, como 1U de tamanho. Será portanto utilizado um gabinete de 6U.

Como a sala 30.5 tem 47,531 m² de área, são necessários 10 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Nesta sala foi colocado um CP, um patch panel de 24 portas, com 1U de tamanho, e um switch de 24 portas, com 1U de tamanho. Será portanto utilizado um gabinete de 6U.

Em relação à área do lado direito, esta zona tem 1558,483 m² de área. Assim, são necessários 312 outlets para cobrir esta área. Foi colocado um HC no limite inferior esquerdo desta sala e 4 CP, cada um responsável por um quarto da sala. Assim conseguiu-se cumprir a regra de que um cabo de cobre não pode ter mais de 90 metros de comprimento. 
No HC foi colocado um patch panel de 24 portas e um switch de 24 portas, para a ligação aos CP. Apesar de apenas serem utilizadas 10 portas (2 para cada CP), esta escolha permite a utilização de mais portas, se assim for pretendido no futuro. Em cada CP foi colocado um patch panel de 144 portas, com 6U de tamanho, e um switch de 144 portas, com 6U de tamanho. Será portanto utilizado um gabinete de 24U. 

Para além dos outlets, como podemos observar na imagem acima representada foram instalados 2 AP, de 50 metros diâmetro, de forma a que exista cobertura WiFi em toda a área do piso. Cada um dos AP's está sintonizado num canal diferente de forma a evitar conflitos entre ambos.

#### Inventário ####
* 1 IC
    * 1 Patch Panel de 8 portas
    * 1 Switch de 8 portas
* 2 HC
    * 2 Patch Panel de 24 portas
    * 2 Switchs de 24 portas
* 6 CP
    * 1 Patch Panel de 24 portas
    * 1 Switch
    * 1 Patch Panel de 48 portas
    * 1 Switch de 48 portas
    * 4 Patch Panels de 144 portas
    * 4 Switchs de 144 portas
* 2 AP
* 368 Outlets
* 368 cabos de cobre CAT6A
* 7004,26 metros de cabo de cobre CAT6A
* 10 cabos de fibra
* 393,94 metros de cabos de fibra
* 368 Patch Cords (ISO8877 connectors (RJ45)) de 3 metros

# Piso 1 #
![Piso1](Piso1.PNG)

#### Medidas ####

| Sala | Comprimento (cm) | Largura (cm) | Comprimento Real (m) | Largura Real (m) | Área (m²) | Outlets |
|----------|----------|----------|---------|---------|---------|----------|
| 31.1 | 1,40 | 1,10 | 7,778 | 6,111 | 47,531 | 10 |
| 31.2 | 1,40 | 1,20 | 7,778 | 6,667 | 51,856 | 12 |
| 31.3 | 2,00 | 1,20 | 11,111 | 6,667 | 74,078 | 16 |
| 31.4 | 1,40 | 1,40 | 7,778 | 7,778 | 60,497 | 12 |
| 31.5 | 1,40 | 1,10 | 7,778 | 6,111 | 47,531 | 10 |
| 31.6 | 1,20 | 0,90 | 6,667 | 5,000 | 33,335 | 8 |
| Open Area | 10,10 | 5 | 56,111 | 27,778 | 1558,483 |-----|

Todas as medições tiveram em conta a escala representada na figura. Considerei que 10 metros correspondem a 3 centímetros. De forma a calcular o número de outlets em cada sala, foi seguida a regra que refere que têm de existir 2 outlets a cada 10 m² em todas as salas deste piso.

Como a sala 31.1 tem 47,531 m² de área, são necessários 10 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Cada um destes 10 outlets está ligado a um CP instalado na sala 31.2.

Como a sala 31.2 tem 51,856 m² de área, são necessários 12 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Nesta sala foi ainda colocado um CP, para garantir a ligação aos outlets das salas 31.1 e 31.2. Para além do CP foi colocado um patch panel de 48 portas, que ocupa 2U de tamanho, e um switch de 48 portas, que ocupa 2U de tamanho. Será portanto um gabinete de 12U de tamanho.

Como a sala 31.3 tem 74,078 m² de área, são necessários 16 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Cada um destes 16 outlets está ligado a um CP, colocado na sala 34.6.

Como a sala 31.4 tem 60,497 m² de área, são necessários 12 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Cada um destes 12 outlets está ligado a um HC que foi colocado nesta sala, que é onde chega a fibra ótica monomodo proveniente do andar de baixo. Foi também instalado um patch panel de 48 portas, de 2U tamanho, e um switch de 48 portas, de 2U de tamanho. Será portanto um gabinete de 12U de tamanho.

Como a sala 31.5 tem 47,531 m² de área, são necessários 10 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Cada um destes 10 outlets está ligado ao HC instalado na sala 31.4.

Como a sala 31.6 tem 33,335 m² de área, são necessários 8 outlets que foram distribuídos neste espaço tendo em conta que tem que existir sempre um outlet a menos de três metros de distância.
Nesta sala foi ainda colocado um CP, para estabelecer ligação com os outlets das salas 31.3 e 31.6. Foi também colocado um patch panel de 48 portas, com 2U de tamanho, e um switch de 48 portas, com 2U de tamanho. Será portanto utilizado um gabinete de 12U.

Para além dos outlets, como podemos observar na imagem acima representada foram instalados 2 AP, de 50 metros diâmetro, de forma a que exista cobertura WiFi em toda a área do piso. Cada um dos AP's está sintonizado num canal diferente de forma a evitar conflitos entre ambos.

#### Inventário ####
* 1 HC
    * 1 Patch Panel de 48 portas
    * 1 Switch de 48 portas
* 2 CP
    * 2 Patch Panels de 48 portas
    * 2 Switchs de 48 portas
* 2 AP
* 68 outlets
* 68 cabos de cobre CAT6A
* 566,65 metros de cabo de cobre CAT6A
* 5 cabos de fibra
* 94 metros de fibra
* 68 Patch Cords (ISO8877 connectors (RJ45)) de 3 metros


# Inventário Total #
* 1 IC
    * 1 Patch Panel de 8 portas
    * 1 Switch de 8 portas
* 3 HC
    * 2 Patch Panel de 24 portas
    * 2 Switchs de 24 portas
    * 1 Patch Panel de 48 portas
    * 1 Switch de 48 portas
* 8 CP
    * 1 Patch Panel de 24 portas
    * 1 Switch
    * 3 Patch Panel de 48 portas
    * 3 Switch de 48 portas
    * 4 Patch Panels de 144 portas
    * 4 Switchs de 144 portas
* 4 AP
* 436 Outlets
* 436 cabos de cobre CAT6A
* 7570,91 metros de cabo de cobre CAT6A
* 15 cabos de fibra
* 487,94 metros de cabos de fibra
* 436 Patch Cords (ISO8877 connectors (RJ45)) de 3 metros
