# Proiect_integrare_cunostinte

Proiect de Practică: Integrarea Cunoștințelor în CCNA, Python și Linux Essentials
Acest proiect a fost dezvoltat în cadrul stagiului de practică la Centrul de Instruire Savnet și demonstrează integrarea cunoștințelor practice și teoretice din trei domenii principale: 

CCNA, Python în Telecom și Linux Essentials.

Obiectivele  Proiectului
Proiectul urmărește rezolvarea a trei sarcini distincte, fiecare corespunzând unei părți din curriculum:


Partea I - CCNA: Configurarea, subrețelarea (subnetting) și rutarea unei topologii de rețea complexe folosind RIPv2, rutare statică și alte protocoale de rețea.





Partea II - Python în Telecom: Crearea unei aplicații Python pentru automatizarea extragerii și aplicării configurațiilor de rețea (backup și restaurare).



Partea III - Linux Essentials: Administrarea unui sistem de operare Linux, incluzând crearea de utilizatori și grupuri, managementul fișierelor și arhivarea, precum și automatizarea sarcinilor cu scripturi bash.


Partea I: CCNA
Această secțiune se concentrează pe implementarea unei rețele fizice și virtuale.

Cerințe de rețea:

Adresare IP și Subnetare: Calcularea și aplicarea adreselor IP și a subneturilor, inclusiv calcularea măștii optime x pentru Site A și Site B.



VLAN-uri: Configurarea VLAN-urilor 10, 20, 30, 40 și 99 pentru a segrega traficul în cadrul Site A și Site B.



Rutare: Implementarea protocolului de rutare dinamică RIPv2 și a rutelor statice pentru a asigura conectivitatea deplină între toate rețelele. De asemenea, a fost configurată o rută implicită (default) către ISP.




Servicii: Configurarea DHCP pe router-ul R3 pentru a aloca automat adrese IP dispozitivelor din Site A.


Securitate: Configurarea accesului securizat pe echipamente, utilizând SSH și Telnet.

Topologie
Aici poți insera o imagine cu topologia rețelei tale, dacă ai una.

Partea II: Python în Telecom
Această secțiune detaliază aplicația Python creată pentru a automatiza sarcinile de rețea.

Funcționalități:

Extragere Configurație: Aplicația se conectează la echipamentele de rețea și extrage automat configurația curentă.


Aplicare Configurație: Permite aplicarea unei configurații predefinite dintr-un fișier pe echipamentele selectate.


Backup: Salvează configurațiile extrase în fișiere text (ex: hostname.txt) pentru a păstra istoricul modificărilor.


Verificare: Include funcționalități pentru a testa conectivitatea (ping) între dispozitive.

Dacă ai un fișier cu codul sursă Python, menționează-l aici și explică cum se rulează.

Partea III: Linux Essentials
Această secțiune acoperă sarcinile de administrare de sistem realizate pe un VM Linux.

Sarcini îndeplinite:

Ziua 0: Crearea unei structuri complexe de directoare și fișiere în directorul home al utilizatorului, conform cerințelor specifice.

Ziua 1: Managementul utilizatorilor și grupurilor. S-au creat grupuri și utilizatori pentru departamentele de Inginerie, Vânzări și IS, cu permisiunile corespunzătoare.

Ziua 2: Automatizarea administrării de utilizatori cu un script bash. Scriptul verifică duplicările, creează utilizatori și grupuri, setează parole și permisiuni, asigurând un proces fluid și eficient.



Ziua 3: Arhivarea fișierelor de log din directorul /var/log într-un fișier log.tar, stocat în ~/archive, și copierea lor într-un director de backup, ~/backup.


Ziua 4: Extragerea și filtrarea serviciilor recunoscute din fișierul /etc/services, salvând rezultatul într-un fișier uniqueservices.txt și numărând liniile acestuia.


Cum să Rulați Proiectul


Python: Pașii necesari pentru a rula scriptul Python, inclusiv instalarea dependențelor.

Linux: Pași pentru a rula scripturile bash și pentru a recrea mediul de lucru.
