# 6. Exercici extra: Màquina Meow (Starting Point)

Resolució completa de la màquina **Meow** (nivell *Very Easy*, sistema operatiu *Linux*) dins de la plataforma **Hack The Box Starting Point**.

## Connexió i qüestionari inicial (Tasks 1 - 7)

Abans d'obtenir la *flag* final, es responen les preguntes teòriques i de reconeixement de la màquina:

| Task | Pregunta | Resposta |
| :--- | :--- | :--- |
| **Task 1** | What does VM stand for? | `Virtual Machine` |
| **Task 2** | What tool do we use to interact with the operating system via command line? | `terminal` |
| **Task 3** | What service do we use to form our VPN connection into HTB labs? | `openvpn` |
| **Task 4** | What tool do we use to test our connection to the target with an ICMP echo request? | `ping` |
| **Task 5** | What is the name of the most common tool for finding open ports on a target? | `nmap` |
| **Task 6** | What service do we identify on port 23/tcp during our scans? | `telnet` |
| **Task 7** | What username is able to log into the target over telnet with a blank password? | `root` |

## Procediment d'explotació pas a pas

![Captura 1 - Meow](../assets/mod6_img01.png)

![Captura 2 - Meow](../assets/mod6_img02.png)

![Captura 3 - Meow](../assets/mod6_img03.png)

![Captura 4 - Meow](../assets/mod6_img04.png)

![Captura 5 - Meow](../assets/mod6_img05.png)

![Captura 6 - Meow](../assets/mod6_img06.png)

![Captura 7 - Meow](../assets/mod6_img07.png)

![Captura 8 - Meow](../assets/mod6_img08.png)

![Captura 9 - Meow](../assets/mod6_img09.png)

![Captura 10 - Meow](../assets/mod6_img10.png)

![Captura 11 - Meow](../assets/mod6_img11.png)

![Captura 12 - Meow](../assets/mod6_img12.png)

![Captura 13 - Meow](../assets/mod6_img13.png)

![Captura 14 - Meow](../assets/mod6_img14.png)

![Captura 15 - Meow](../assets/mod6_img15.png)

![Captura 16 - Meow](../assets/mod6_img16.png)

Obrim la màquina amb un terminal:

![Captura 17 - Meow](../assets/mod6_img17.png)

![Captura 18 - Meow](../assets/mod6_img18.png)

i escrivim la comanda per connectar-nos per telnet:

![Captura 19 - Meow](../assets/mod6_img19.png)

![Captura 20 - Meow](../assets/mod6_img20.png)

una vegada dins la maquina victima a través de telnet, ens loguejem amb root:

![Captura 21 - Meow](../assets/mod6_img21.png)

I automàticament ens otorga accès. Ara llistem els directoris en busca de l’arxiu “flags”:

![Captura 22 - Meow](../assets/mod6_img22.png)

Amb la comanda cat el podrem llegir:

![Captura 23 - Meow](../assets/mod6_img23.png)

Copiem el text i el peguem al HTB:

![Captura 24 - Meow](../assets/mod6_img24.png)

![Captura 25 - Meow](../assets/mod6_img25.png)

![Captura 26 - Meow](../assets/mod6_img26.png)

![Captura 27 - Meow](../assets/mod6_img27.png)

## Resultat final

* **Flag obtinguda:** `b40abdfe23665f766f9c61ecba8a4c19`
* **Estat:** Màquina completada (*Meow Pwned*) i perfil actualitzat a [Hack The Box](https://profile.hackthebox.com/profile/01a20f02-f682-7086-a4be-b0f8c4ed27cf?utm_medium=copy_url).
