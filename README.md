Kryptohistoria kuvaajaksi-ohjelma

Ohjelmassa on 4 toimintoa:

![image](https://user-images.githubusercontent.com/121788922/215994823-a5e5fdf9-7825-482a-97ae-f2a0c7a9cb81.png)

1) Jos käyttäjällä ei ole mitään tietoa kryptovaluutoista voi hän printata listan 50 suurimmista kryptovaluutasta vaikka testailutarkoitukseen.

![image](https://user-images.githubusercontent.com/121788922/215994542-c20c1c66-5394-43c7-be70-06b425ce8759.png)

2) Ohjelmalta voi myös kysyä tietyn kryptovaluutan vaihtosuhdetta euroina, jolloin ohjelma printtaa:

![image](https://user-images.githubusercontent.com/121788922/215993631-ea1aed6b-c694-45cb-926c-e901237289ed.png)

3,4) Ohjelman varsinaiset piirtotoiminnot. Ohjelma hakee käyttäjän syöttämältä aikaväliltä kysytyn kryptovaluutan hintahistorian ja piirtää siitä joko yksinkertaisen viivakuvaajan tai kynttiläkuvaajan muutamalla indikaattorilla. Yksinkertainen viivakuvaaja piirtää joko yhden tai kaksi kryptovaluutan hintahistoriaa, joko samaan tai eri kuvaajaan käyttäjän syötteistä riippuen. Esimerkiksi tässä Ethereumin ja Bitcoinin kurssit 1.2.2023 kuukausi taaksepäin euroina.

![eth and btc](https://user-images.githubusercontent.com/121788922/215992277-720e9298-36a6-49a4-b857-2414932b221b.png)

Kynttiläkuvaaja piirtää käyttäjän syötteiden mukaan perinteisen kynttiläkuvaajan, johon on myös lisättynä Suhteellisen voimakkuuden indikaattori (RSI) ja Bollingerin nauhat indikaattorit (BB). Tässä sama Bitcoinin kurssi, kuin aiemmassa kuvaajassa.

![newplot](https://user-images.githubusercontent.com/121788922/215992782-48ce7b78-135a-4ecd-8f27-d6759f13922a.png)


Ohjelma käyttää seuraavia moduuleja:

cryptocompare
pandas
datetime
matplotlib
plotly

Asennus:
!pip install cryptocompare
