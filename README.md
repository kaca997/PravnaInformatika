# Multi-label klasifikacija klauzula iz pravnih ugovora

### Članovi tima:
- Nikolina Batinić R2 14-2020
- Katarina Aleksić R2 12-2020

### Preduslovi:
-	Python 3.7+
- Jupyter lab ili Google Colab)
- Sve biblioteke iz fajla requirements.txt(ukoliko se .ipynb skripta ne pokreće iz Google Colab-a)
- Preuzeti pretrenirani Glove tekstualni fajl sa Kaggle-a sa linka https://www.kaggle.com/danielwillgeorge/glove6b100dtxt

### Pokretanje u Google Colab-u:
- Potrebno je preuzeti repozitorijum sa linka https://github.com/kaca997/PravnaInformatika
- Upload-ovati .ipynb skrptu na Google Colab
- Pokrenuti redom sve ćelije
- U 3. ćeliji označenoj sa "#files for google colab" potrebno je upload-ovati sve .csv fajlove iz foldera individual_contract_clauses i fajl glove.6B.100d.txt, i eventualno ugovore .pdf formatu, ali to je moguće i kasnije 
- Moguće je preskočiti ćelije sa GridSearch-om, već samo pokrenuti funkcije u kojima se pravi i trenira model sa već pronađenim najboljim parametrima
- Moguće je učitati sačuvani i istrenirani model pokretanjem ćelije označene sa  "#load rnn model"
- Svi rezultati vidljivi su u ispisima u .ipynb skripti i bez pokretanja bilo čega

