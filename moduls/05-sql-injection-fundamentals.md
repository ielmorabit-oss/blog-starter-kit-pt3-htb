# 5. SQL Injection Fundamentals

Aquest mòdul cobreix l'ús de bases de dades relacionals (MySQL) i l'explotació de vulnerabilitats d'**injecció SQL (SQLi)**: enumeració d'esquemes i taules, evasió d'autenticació, atacs basats en `UNION`, lectura de fitxers del servidor i execució remota de codi (RCE).

## Resum d'activitats i respostes clau

* **Consultes SQL bàsiques:** Connexió al client MySQL, llistat de bases de dades (`employees`), filtratge per departament (`d005`) i condicions `AND`/`OR` (`Mitchem`, `654` i `663` registres).
* **Authentication Bypass:** Accés com a usuari `tom` (`202a1d1a8b195d5e9a57e434cc16000c`) i com a l'usuari amb `id = 5` (`cdad9ecdf6f14b45ff5c4de32909caec`).
* **UNION SQL Injection:** Extracció de l'usuari de la base de dades (`root@localhost`), obtenció del hash de contrasenya de `newuser` (`9da2c9bcdf39d8610954e0e11ea8f45f`) i del hash Argon2i de `admin`.
* **Lectura de fitxers i RCE:** Lectura de fitxers PHP inclosos (`dB_pAssw0rd_iS_flag!`), obtenció d'una *webshell* (`d2b5b27ae688b6a0f1d21b7d3a0798cd`), identificació de la ruta arrel (`/var/www/chattr-prod`) i lectura de `/flag_XXXXXX.txt` (`061b1aeb94dec6bf5d9c27032b3c1d8d`).

## Evidències i captures de pantalla

![Captura 1 - 5. SQL Injection Fundamentals](../assets/mod5_img01.png)

![Captura 2 - 5. SQL Injection Fundamentals](../assets/mod5_img02.png)

![Captura 3 - 5. SQL Injection Fundamentals](../assets/mod5_img03.png)

![Captura 4 - 5. SQL Injection Fundamentals](../assets/mod5_img04.png)

![Captura 5 - 5. SQL Injection Fundamentals](../assets/mod5_img05.png)

![Captura 6 - 5. SQL Injection Fundamentals](../assets/mod5_img06.png)

![Captura 7 - 5. SQL Injection Fundamentals](../assets/mod5_img07.png)

![Captura 8 - 5. SQL Injection Fundamentals](../assets/mod5_img08.png)

![Captura 9 - 5. SQL Injection Fundamentals](../assets/mod5_img09.png)

![Captura 10 - 5. SQL Injection Fundamentals](../assets/mod5_img10.png)

![Captura 11 - 5. SQL Injection Fundamentals](../assets/mod5_img11.png)

![Captura 12 - 5. SQL Injection Fundamentals](../assets/mod5_img12.png)

![Captura 13 - 5. SQL Injection Fundamentals](../assets/mod5_img13.png)

![Captura 14 - 5. SQL Injection Fundamentals](../assets/mod5_img14.png)

![Captura 15 - 5. SQL Injection Fundamentals](../assets/mod5_img15.png)

![Captura 16 - 5. SQL Injection Fundamentals](../assets/mod5_img16.png)

![Captura 17 - 5. SQL Injection Fundamentals](../assets/mod5_img17.png)

![Captura 18 - 5. SQL Injection Fundamentals](../assets/mod5_img18.png)

![Captura 19 - 5. SQL Injection Fundamentals](../assets/mod5_img19.png)

![Captura 20 - 5. SQL Injection Fundamentals](../assets/mod5_img20.png)

![Captura 21 - 5. SQL Injection Fundamentals](../assets/mod5_img21.png)

![Captura 22 - 5. SQL Injection Fundamentals](../assets/mod5_img22.png)

![Captura 23 - 5. SQL Injection Fundamentals](../assets/mod5_img23.png)

![Captura 24 - 5. SQL Injection Fundamentals](../assets/mod5_img24.png)

![Captura 25 - 5. SQL Injection Fundamentals](../assets/mod5_img25.png)

![Captura 26 - 5. SQL Injection Fundamentals](../assets/mod5_img26.png)

![Captura 27 - 5. SQL Injection Fundamentals](../assets/mod5_img27.png)
