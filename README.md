Descrizione Role
=========
Eseguo il passaggio della componente ETL a pentaho 8.0
Contestualmente a questo passaggio, modifica la struttura della reportistica per rimuovere tomcat8 che al momento svolge funzione di BI server

Requisiti
------------

Variabili
--------------
- etl --> Indica il server in cui è presente lo strato applicativo etl di reportistica

Dipendenze
------------

Esempio di chiamata
----------------

ansible-playbook /home/playbook/bugs/6585/main.yml -e etl=<il server in cui è presente lo strato applicativo ETL>

Informazioni Autore
------------------

Martino.Viganò
Martino.Vigano@enghouse.com

![alt text](https://www.105.net/resizer/659/-1/true/1509976718395.jpg--una_balena_impara_il_linguaggio_dei_delfini_per_comunicare_con_loro.jpg?1509976718000)
