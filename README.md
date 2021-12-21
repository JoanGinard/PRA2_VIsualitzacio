# PRA2_Visualitzacio

Segona part de la pràctica de Visualització de dades del Màster de ciència de dades de la UOC

## Descripció del repositori:

### **Data**

Carpeta amb les dades.

1. *student-mat.csv* - dades dels alumnes de matemàtiques
2. *student-por.csv* - dades dels alumnes de portuguès

Font de les dades:

P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.
[Web Link](http://www3.dsi.uminho.pt/pcortez/student.pdf)
<br/>
### **Sortida**

Carpeta amb l'excel que genera l'arxiu de R.

1. *dadesNetes.xlsx*

S'ha triat l'excel com a format de sortida perquè a la visualització s'ha fet servir Flourish i les dades s'han de preparar diferent segons el tipus de gràfic i excel permetia fer-ho tot en un arxiu i no era necessari generar diferents CSVs
<br/>
### **Arxiu de R**

*PRA2-Visualitzacio-Neteja.Rmd*

He triat el format *.Rmd* perquè trobo que els comentaris es visualitzen millor.

L'arxiu:
1. Canvia els noms dels factors que a l'original venen en format numèric.
2. "Tradueix" noms de l'anglès al català.
3. Categoritza les notes, i.e: a partir de les notes numèriques crea una variable on es divideixen les notes en suspès-aprovat i una altra en suspès-aprovat-notable/excel·lent.
4. Junta les dades dels alumnes de portugués i matemàtiques ja que alguns alumnes són els mateixos.
5. Calcula la nota mitjana de les dues matèries i creem les variables del punt 3 per la nota mitjana.
6. Prepara les diferents taules de dades per flourish.
7. Grava l'arxiu .xlsx







