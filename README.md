# **Obalno in priobalno inženirstvo - OPI**
### **Hidrodinamika plavajočih morskih struktur**

- **Datum:** 15/11/2021
- **Avtor:** Aleksander Sandro GRM (aleksander.grm@fpp.uni-lj.si)

---
## Uvod

Predmet **Obalno in priobalno inženirstvo** se predava na *2.stopnji*, smeri *Pomorstvo* na **[UL-FPP](https://www.fpp.uni-lj.si/studij/2-stopnja/pomorstvo/)**. Pri segmentu **Hidrodinamike plavajočih morskih struktur** se študentje seznanijo z naslednjo vsebino:

 - statističen opis okoljskih sil,
 - zapisa matematičnih modelov dinamike plavajoče morske strukture,
 - numerične simulacije dinamike plavajoče morske strukture.

V delu numeričnih simulacij plavajoče morske strukture, študentje spoznajo in izvedejo:
 
 - osnovne statistične obdelave časovnih meritev valov, vetra 
 - izdelavo časovnega naključnega vala na podlagi spektra valovanja,
 - izračun osnovnih parametrov priveza (statične, kvazi-statične in dinamične)
 - uporaba integracije **[MoorDyn](http://www.matt-hall.ca/moordyn.html)** knjižnjice za izračun priveznih sil,
 - določanje hidrodinamičnih koeficientov s pomočjo **[HAMS](https://github.com/YingyiLiu/HAMS)** knjižnjice,
 - simulirajo gibanje plavajoče strukture pod vplivom zunanjih sil (val in privez),
 - določijo maksimalne privezne sile in izdelajo osnovno študijo vzdržnega priveza.

Celoten program numeričnih obdelav je osnovan na Python programskem okolju, ki se izvaja znotraj Jupyter okolja.
 
Svoje lastno Jupyter okolje, si lahko naredite tudi na svojem računalniku. Najenostavneje to naredite v **Linux operacijskem sistemu**, kjer priporočam uporabo **[Debian Stable](https://www.debian.org)** distribucije. Druga distribucija je **[Ubuntu](https://ubuntu.com/download/desktop)**. V primerjavi z **Debian** distribucijo je za uporabnika mogoče lažja inštalacija, vendar je Debian distribucija, ki je najbolj podprta. Če še niste uporabnik Linux OS, vam zelo priporočam njegovo testiranje in nadaljno uporabo, če se vidite kot bodoči inženir v morskih tehnikah. 

V primeru, da ste zagrizen uporabnik **Windows operacijskega sistema**, je priporočljiva inštalacija **[Anaconda](https://www.anaconda.com/products/individual)** *individualne odprtokodne rešitve*. Poleg tega bi vam priporočal še inštalacijo **[WSL](https://docs.microsoft.com/en-us/windows/wsl/)** sistema, ki omogoča uporabo Linux OS znotraj Windows OS.

---
 
## Struktura programa

Program **Hidrodinamike plavajočih morskih struktur** je razdeljen v štiri faze:

1. Uvod v Python okolje
2. Osnove numeričnih izračunov
3. Napredni numerični izračuni
4. Integracija Python okolja s klicem zunanjih knjižnjic, kot sta *MoorDyn* in *HAMS*

### Uvod v Python

Povezava do vsebin [Uvod v Python](https://github.com/as-grm/python_class)

### Osnove numeričnih izračunov

Povezava do vsebin [Osnove numeričnih izračunov](https://github.com/as-grm/python_class)


### Napredni numerični izračuni

Povezava do vsebin [Napredni numerični izračuni](https://github.com/as-grm/opi_class/tree/main/02_advanced_numerics)


### Integracija Python z zunanjimi knjižnjicami

Povezava do vsebin [Integracija Python z zunanjimi knjižnjicami](https://github.com/as-grm/opi_class/tree/main/03_integration_python_shared-libs)
