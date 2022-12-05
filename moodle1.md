# Enunciat:

Documenteu la instal·lació de Moodle a la vostra Màquina Virtual.

- Explicar els passos seguits durant la instal·lació de Moodle (4 punts).
  -   Instal·lació APACHE (1p).
  -   Instal·lació BBDD (1p).
  -   Instal·lació PHP (1p).
  -   Instal·lació Moodle (1p).
- Inserir les captures de pantalla dels moments delicats de la instal·lació, explicant què es fa a la captura (4 punts).
  -   Instal·lació APACHE (1p).
  -   Instal·lació BBDD (1p).
  -   Instal·lació PHP (1p).
  -   Instal·lació Moodle (1p).
- Documentar els problemes que hem tingut durant la instal·lació (2 punts).
  -   Com hem sapigut quina versió de PHP instal·lar (1p).
  -   Altres (1p).

## IMPORTANT:

### Versió de PHP:

Heu de vigilar quina versió de PHP instal·leu, tant del mateix PHP com de totes les llibreries que l'implementen.

Així si teniu instal·lat PHP7.3 haureu d'instal·lar sempre aquesta versió:

Per exemple en lloc de:

```
sudo apt install php libapache2-mod-php php-mysql
```

instal·larieu així:

```
sudo apt install php7.3 libapache2-mod-php7.3 php7.3-mysql
```

Si teniu alguna llibreria o versió de PHP que no voleu la desinstal·leu:

```
sudo apt purge php
sudo apt remove php
sudo apt autoremove
```
### IP de Moodle:

Haureu de canviar la IP de moodle cada vegada que reinicieu i canvii la IP del servidor:



![image](https://user-images.githubusercontent.com/110727546/205661377-e93f5920-72a8-4fcf-ba1c-6cf2296d98c6.png)
