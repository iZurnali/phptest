## iŽurnāli PHP programmētāja uzdevums

### Apraksts

Izveidot mini web aplikāciju ar šādu funkcionalitāti:

1. Kā lietotājs varu augšupielādēt un importēt eksel failu ar datiem rēķinu sagatavošanai 
   1. Piemēra fails importam: `imports.xlsx`. 
   2. Importa kolonnu secība ir strikti definēta, potenciāli citos importa failos tā būs nemainīgi tieši tāda pati. 
   3. Kolonnā "Pakalpojumi" ieraksti atdalīti ar semikolu (;). Starp tiem katram pakalpojumam ir ar komatu (,) atdalītas 5 vērtības pēc kārtas - pakalpojums, mērienība, skaits, cena un summa.
   4. Ielasot datus nav jāveic matemātika vai jāpārbauda rēķina summas, dati jāielasa tieši tā kā norādīts failā.
2. Kā lietotājs varu redzēt importētos rēķinus tabulā (kā sarakstu)
   1. Kolonnas: rēķina numurs, rēķina datums, pircēja nosaukums, kopējā summa.
3. Kā lietotājs varu ģenerēt un no tabulas lejuplādēt jebkuru importēto rēķinu PDF formātā.
   1. Spiežot uz "lejuplādēt" pogas importēto rēķinu sarakstā. 
   2. Rēķina piemērs: `rekins.pdf`. Šeit ar dzeltenu atdzīmētas importējamās vērtības: `rekins_marked.pdf`
   3. Ģenerētā rēķina dizainam ir aptuveni jāatbilst piemērā dotajam, bet precīzi font izmēri, pixeļi un citas mazas detaļas nav svarīgas. 

Projekta izstrādes gaita jānorāda git repozitorija vēsturē. 

### Tehnoloģijas un ierobežojumi

- Darbs jāveic izmantojot PHP un OOP principus.
- Drīkst izmantot jebkuru ietvaru (piem. Laravel), bet tas nav obligāti.
- Drīkst izmantot jebkādas publiski pieejamas composer bibliotēkas.
- Drīkst izmantot jebkāda veida datubāzi - mysql, mongoDB, file, sqlite. 

### Vērtēšana

Izvērtējot rezultātu tiks vērtēts: 
- uzdevumā definētās funckionalitātes darbība
- koda atbilstība "labajām praksēm" strādājot ar PHP, kā piemēram, PSR2 standarta un SOLID principu (ar uzsvaru uz SRP) ievērošana.
- risinājuma koda vienkāršība un  lasāmība.

Netiks vērtēts: 
- PHP ietvara izvēle.
- Izmantoto composer biblioteku daudzums.
- Front-end dizains. Svarīgi lai var saprast, kas lapā notiek, bet uzsvars ir uz back-end funckionalitāti.


### Projekta nodošana

Gatavā risinājuma git repozitoriju ievietot **privātā** GitHub repozitorijā un nosūtīt piekļuves lietotājam `https://github.com/ralfsspirga`

