# Lokaverkefni í mynstursgreiningu, vor 2020
Eftirfarandi eru kóðabútar og gögn fyrir lokaverkefni í mynstursgreiningu vorið 2020
Verkefnið er eftir __Baldvin Kára Magnússon__ og __Bjarka Bernardsson__. Markmið verkefnisins er 
að nota tauganet til þess að greina og flokka umferðarskilti út frá myndum. 
## Yfirlit
* DataAug - Mappan inniheldur kóða sem notaður var til þess að setja gagnasett á rétt form
ásamt kóða sem notaður var til þess að búa til margar útgáfur af sömu mynd
* myndir - Mappan inniheldur myndir sem notaðar voru við kynningu á módelum þann 20.apríl
* Classifier_train.ipynb - Inniheldur kóða sem notaður var til að þjálfa
módelið sem sá um að flokka skiltin
* demo.ipynb - Kóði sem hægt er að keyra á eigin myndum til þess að prófa,
sjá leiðbeiningar fyrir neðan
* nidurstodur.txt -  Accuracy niðurstöður fyrir hvern flokk í classifier

## Slóð á gagnasett og slóð á módel
Þar sem stærð eftirfarandi skjala er of stór fyrir Github eru hér slóðir til þess að halaða niður
gögnum og demo-möppu sem þarf til þess að keyra demoið

* [data.zip](https://drive.google.com/file/d/1f3to_pi7YVEL1JBbiX31P37aEPMDEb-m/view?usp=sharing)
* [demo.zip](https://drive.google.com/open?id=1WDDotXitXG-G2lLCS8I4zFY2OKpq77cx)

## Leiðbeinginar fyrir demo
Til þess að keyra demo kóðann þarf að hlaða niður demo.zip og demo.ipynb. Bæði þessi skjöl þurfa að vera í sömu möppu
Kóðinn notar Tensorflow útgáfu: 1.13.1.
Í kóðanum þarf að velja:
* slóð á möppu þar sem þær myndir sem á að greina eru geymdar (input)
* slóð á möppu þar sem merktu myndirnar eru vistaðar 
* slóð á möppu þar sem myndir af skilitunum eru vistaðar

Tauganetið getur greint eftirfarandi skilti
* Hámarkshraði (20 km/klst)
* Hámarkshraði (30 km/klst)
* Hámarkshraði (50 km/klst)
* Hámarkshraði (60 km/klst)
* Hámarkshraði (70 km/klst)
* Hámarkshraði (80 km/klst)
* Hámarkshraða lokið (80 km/klst)
* Hámarkshraði (100 km/klst)
* Hámarkshraði (120 km/klst)
* Frammúrakstur bannaður
* Frammúrakstur vörubifreiða bannaður
* Umferð á vegi á forgang
* Aðalbraut
* Biðskylda
* Stöðvunarskylda
* Allur Akstur bannaður
* Akstur vörubifreiða bannaður
* Innakstur bannaður
* Önnur hætta
* Hættuleg beygja til vinstri
* Hættuleg beygja til hægri
* Hættulegar beygjur, fyrst til vinstri
* Ósléttur vegur
* Sleipur vegur
* Vegur mjókkar frá hægri
* Vegavinna
* Umferðarljós
* Gangbraut framundan
* Börn
* Hljóðreiðamenn
* Ísing á vegi
* Hreindýr
* Afnám banna
* Hægri beygja framundan
* Vinstri beygja framundan
* Aktu Áfram
* Áfram eða til hægri
* Áfram eða til vinstri
* Aksturstefna til hægri
* Aksturstefna til vinstri
* Hringakstur
* Banni við framúrakstri lokið
* Banni við framúrakstri vörubifreiða lokið
* Hámarkshraði (90 km/klst)
* Þéttbýli endar
* Bannað að leggja
* Götuskilti
