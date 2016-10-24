# Dataset for training and evaluating Named Entity Recognition systems on medical texts in Swedish.

Data comes from Swedish Wikipedia, Läkartidningen, and 1177.se.


## Authors

* Simon Almgren, simonwalmgren@gmail.com
* Sean Pavlov, sean.pavlov@gmail.com
* Olof Mogren, olof@mogren.one

Chalmers University of Techbology

## Citing this work

If you are using this work, please cite the following:

@inproceedings{almgrenpavlovmogren2016bioner,
 title="Named Entity Recognition in Swedish Medical Journals with Deep Bidirectional Character-Based LSTMs",
 author="Simon Almgren, Sean Pavlov, Olof Mogren",
 booktitle="Proceedings of the Fifth Workshop on Building and Evaluating Resources for Biomedical Text Mining (BioTxtM 2016)",
 pages="1",
 year="2016"  
}


### License

This work is shared under the Attribution-ShareAlike 4.0 International
license. See http://creativecommons.org/licenses/by-sa/4.0/ for details.


## Swedish Wikipedia

  Pages were downloaded and then automatically annotated by finding
  words in a dictionary and extracting 60 character long context windows
  randomly positioned around the main word.

    * Infektionssjukdom
    * Cancer
    * Patogen
    * Sjukdomar i blodet och blodbildande organ
    * Endokrina sjukdomar
    * Autoimmunitet
    * Reumatism
    * Medicinsk diagnostik
    * Förkylning
    * Depression
    * Sjukdomar i nervsystemet
    * Hjärntumör
    * Allergi
    * Astma
    * Smitta
    * Stress
    * Människans anatomi
    * Kroppsdel
    * Muskel
    * Anatomi
    * Anatomisk variation
    * Nervsystemet
    * Skelett
    * Perifera nervsystemet
    * Ansikte
    * Magsäck
    * Ryggrad
    * Tarm
    * Hormon
    * Läkemedel
    * Antibiotikum
    * Medicinalväxt
    * Kirurgi
    * Selektiva serontinåterupptagshämmare
    * Ibuprofen
    * Enzym
    * Aminosyror
    * Vitamin
    * Näringsämne
    * Fettvävnad
    * Vaccination
    * Farmakokinetik
    * Insulin
    * Pencillin

## Läkartidningen
  Pages were downloaded and then automatically annotated by finding
  words in a dictionary and extracting 60 character long context windows
  randomly positioned around the main word.

## 1177.se
  Pages were downloaded in May 2016 and manually annotated.
  The file contains one sentence per line, and the lines
  were shuffled.
  
  Articles included:

    * Demens - Alzheimers sjukdom
    * Bedövning och smärtlindring vid tandvård
    * Receptfria läkemedel vid tillfällig smärta
    * Så åldras kroppen
    * Läkemedel vid pollenallergi
    * Vaccinationsprogram för barn
    * Stroke – slaganfall
    * Behöver jag testa mig för zikaviruset?
    * Denguefeber
    * KOL – kroniskt obstruktiv lungsjukdom
    * Knöl i bröstet
    * Läkemedel som tas upp genom huden
    * Drick sundare
    * Myggbett och knottbett
    * Ibumetin

# Data format

Tags are as follows:

* Prenthesis, (): Disorder and Finding
* Brackets, []: Pharmaceutical Drug
* Curly brackets, {}: Body Structure


