# Vending-Machine
Java Vending Machine

Programul scris isi doreste implementarea unui distribuitor automat(vending machine) care le permite utilizatorilor sa cumpere diferite produse Avira.
In acest sens, am folosit Java, respective JavaFX pentru interfata grafica.
	Interfata intai intreaba utilizatorul despre limba dorita, apoi ii permite acestuia sa efectueze diferite operatii in cadrul aplicatiei.
  Spre exemplu, in cazul in care dorim sa ne autentificam cu un cont de Admin, putem face acest lucru cu contul (user: root ; pass:12345).
  In noul meniu putem vedea diferite statistici despre produsele vandute, avand, de asemenea optiunea de a crea alt cont Admin.
	Revenind la pagina cu produse, avem posibilitatea de a selecta mai multe produse si de a le cumpara, folosind diferite metode de plata.
  Pagina urmatoare ne ofera diferite metode de plata (ex. paysafecard – cod de 16 cifre, cash – monede si banknote, totalul acestora fiind actualizat constant, pe ecran).
	Se poate trece la metoda de payment doar daca a fost ales un produs. Se poate cumpara doar cate un produs pe rand.
  In pagina de prezentare se pot selecta din lista produse. In pane-ul de admin putem seta stock-ul/adauga un nou admin/download stats.
  De asemenea ne arata diferite statistici de la momentul pornirii.
	Aplicatia a fost construita pentru a rula pe ecrane mici de pe vending machines.
  Presupunem ca avem o tastatura virtuala/fizica atasata la tonomat, iar majoritatea schimbarilor logice au loc datorita touch screen-ului.
	Majoritatea file-urilor se gasesc in src\vending\machine.
