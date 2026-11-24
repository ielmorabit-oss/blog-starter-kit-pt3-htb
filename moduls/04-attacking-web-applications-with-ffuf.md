# 4. Attacking Web Applications with Ffuf

Aquest mòdul aprofundeix en les tècniques de *fuzzing* web automatitzat amb l'eina **ffuf** (*Fuzz Faster U Fool*) per descobrir recursos ocults, directoris, extensions de fitxer, subdominis, *Virtual Hosts* (VHosts) i paràmetres GET/POST.

## Resum d'activitats i respostes clau

* **Fuzzing de directoris i pàgines:** Identificació dels directoris `/blog` i `/forum`, i enumeració de pàgines internes (`HTB{bru73_f0r_c0mm0n_p455w0rd5}` i `HTB{fuzz1n6_7h3_w3b!}`).
* **Fuzzing de subdominis i VHosts:** Descoberta de `customer.inlanefreight.com` i dels subdominis/VHosts `test`, `archive` i `faculty` sobre `*.academy.htb`.
* **Fuzzing d'extensions i paràmetres:** Detecció de les extensions `.php`, `.php7` i `.phps`, localització de `http://faculty.academy.htb:PORT/courses/linux-security.php7`, identificació dels paràmetres `user` i `username`, i obtenció de les flags mitjançant peticions GET i POST (`HTB{p4r4m373r_fuzz1n6_15_k3y!}` i `HTB{w3b_fuzz1n6_m4573r}`).

## Evidències i captures de pantalla

![Captura 1 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img01.png)

![Captura 2 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img02.png)

![Captura 3 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img03.png)

![Captura 4 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img04.png)

![Captura 5 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img05.png)

![Captura 6 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img06.png)

![Captura 7 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img07.png)

![Captura 8 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img08.png)

![Captura 9 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img09.png)

![Captura 10 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img10.png)

![Captura 11 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img11.png)

![Captura 12 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img12.png)

![Captura 13 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img13.png)

![Captura 14 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img14.png)

![Captura 15 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img15.png)

![Captura 16 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img16.png)

![Captura 17 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img17.png)

![Captura 18 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img18.png)

![Captura 19 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img19.png)

![Captura 20 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img20.png)

![Captura 21 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img21.png)

![Captura 22 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img22.png)

![Captura 23 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img23.png)

![Captura 24 - 4. Attacking Web Applications with Ffuf](../assets/mod4_img24.png)
