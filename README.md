# Lokaverkefni í mynstursgreiningu, vor 2020
Eftirfarandi eru kóðabútar og gögn fyrir lokaverkefni í mynstursgreiningu vorið 2020
Verkefnið er eftir __Baldvin Kára Magnússon__ og __Bjarka Bernardsson__. Markmið verkefnisins er 
að nota tauganet til þess að greina og flokka umferðarskilti út frá myndum. 
## Yfirlit

* demo.ipynb - Kóði sem hægt er að keyra á eigin myndum til þess að prófa,
sjá leiðbeiningar fyrir neðan
* Classifier_train.ipynb - Inniheldur kóða sem notaður var til að þjálfa
módelið sem sá um að flokka skiltin
* DataAug - Mappan inniheldur kóða sem notaður var til þess að setja gagnasett á rétt form
ásamt kóða sem notaður var til þess að búa til margar útgáfur af sömu mynd
* myndir - Mappan inniheldur myndir sem notaðar voru við kynningu á módelum þann 20.apríl
* nidurstodur.txt -  Accuracy niðurstöður fyrir hvern flokk í classifier

## Slóð á gagnasett og slóð á módel
Þar sem stærð skjalana er of stór fyrir Github eru hér slóðir til þess að halaða niður
gögnum og möppu sem þarf til þess að keyra demoið

* [Gagnasett](https://drive.google.com/file/d/1f3to_pi7YVEL1JBbiX31P37aEPMDEb-m/view?usp=sharing)
* [demo.zip](https://drive.google.com/open?id=1WDDotXitXG-G2lLCS8I4zFY2OKpq77cx)

## Leiðbeinginar fyrir demo
Til þess að keyra demo kóðann þarf að hlaða niður demo.zip og demo.ipynb.
Kóðinn notar Tensorflow útgáfu: 1.13.1.
Í kóðanum þarf að velja slóð á möppu þar sem upprunalegu myndirnar eru geymdar (input)
ásamt því að velja slóð þar sem merktu myndirnar eru vistaðar sem og myndirnar af skiltunum sem 
forritið býr til 
