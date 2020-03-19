![Logo](images/OL_BANNER.png)

# Baló de ventilació de baix cost

- Aquest projecte fou impulsat per la pandèmia global COVID-19 a partir de les conversacions entre la comunitat d'usuaris del grup de Facebook `Open Source COVID19 and OpenSourceVentilator`. És per això que vaig crear un projecte GitLab per a un producte nou basat en programari lliure: l'OpenLung.
- Més concretament, en una conversa sobre respiradors d'emergència basats en balons de ventilació de baix cost (`BVM` o `Ambu bag`), per als quals s'havien desenvolupat solucions prèvies. [La primera d'un grup de recerca del MIT](https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf) integrat per Abdul Mohsen Al Husseini, Heon Ju Lee, Justin Negrete, Stephen Powelson, Amelia Servi, Alexander Slocum i Jussi Saukkonen. [El segon dispositiu d'un grup d'estudiants d'Enginyeria Mecànica de la Universitat de Rice](http://oedk.rice.edu/Sys/PublicProfile/47585242/1063096), format per Madison Nasteff, Carolina De Santiago, Aravind Sundaramraj, Natalie Dickman, Tim Nonet i Karen Vasquez Ruiz.
- Aquest projecte pretén combinar i millorar els esforços d'aquests dos projectes en un dispositiu més simple i fiable que consta majoritàriament de peces impreses en 3D.

*AVÍS D'EXEMPCIÓ DE RESPONSABILITAT: Sempre que sigui possible, sol·liciteu assistència mèdica professional amb equipament operat per operadors amb la formació mèdica i tècnica adequades. No és recomanable utilitzar informació aleatòria d'Internet. Els membres d'aquest projecte no som professionals mèdics, sinó voluntaris que col·laboren a Internet.*

## Motius per utilitzar un Ambu-Bag

- Producció en massa
- Components certificats
- Requeriments mecànics simples
- Investigacions i proves prèvies en aquest àmbit
- Adaptat tant a mascaretes invasives com a tubs

## Requeriments del projecte

Els requeriments del projecte es mostren [aquí](Requirements.md).

## Estat del projecte

![Concepte mecànic](CONCEPT_6_MECH.png)
*Actualment s'està desenvolupant la versió 5 del concepte de disseny, la qual té encara problemes coneguts per resoldre.*

## PER FER (on ens cal ajuda)

*Si podeu ajudar en qualsevol d'aquestes tasques, cloneu o bifurqueu aquest projecte i creeu una sol·licitud de combinació amb els fitxers nous o modificats.*

- Organització de l'estructura del repository del projecte
- ~~Dissenyar un mecanisme d'actuació imprès en 3D més integral~~
- ~~Especificació d'un motor adequat~~
- Especificació de la interfície d'usuari (LCD i botons)
- Especificació dels sensors de retroalimentació PEEP, esdeveniments de baixa tensió, alta i baixa pressió.
- Diagrama visual de la interfície d'usuari

## EN PROGRÉS (en què estem treballant avui, 17 de març del 2020)

- Organització de l'estructura del repositori
- Model CAD actualitzat amb Ambu-Bag
- Esquema d'interactivitat
- Comunicació i col·laboració amb el projecte de ventilador de codi obert irlandès
- Avaluació dels mètodes de comunicació i delegació per al projecte

## FET (què s'ha completat)

- Requeriments de disseny

## Millores iteratives següents

- ~~Connexió perpendicular del motor / eix de transmissió per problemes de càrrega axial~~
- ~~Simplificar l'estructura de transmissió~~
- ~~Compactació addicional de la construcció general~~
