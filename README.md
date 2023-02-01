Kryptohistoria kuvaajaksi-ohjelma

Ohjelma hakee käyttäjän syöttämältä aikaväliltä kysytyn kryptovaluutan hintahistorian ja piirtää siitä joko yksinkertaisen viivakuvaajan tai kynttiläkuvaajan muutamalla indikaattorilla. Yksinkertainen viivakuvaaja piirtää joko yhden tai kaksi kryptovaluutan hintahistoriaa, joko samaan tai eri kuvaajaan käyttäjän syötteistä riippuen. Esimerkiksi tässä Ethereumin ja Bitcoinin kurssit 1.2.2023 kuukausi taaksepäin euroina

![eth and btc](https://user-images.githubusercontent.com/121788922/215992277-720e9298-36a6-49a4-b857-2414932b221b.png)

Kynttiläkuvaajassa on myös lisättynä RSI- ja Bollingerin nauhat indikaattorit. Tässä sama Bitcoinin kurssi, kuin aiemmassa kuvaajassa.

![newplot](https://user-images.githubusercontent.com/121788922/215992782-48ce7b78-135a-4ecd-8f27-d6759f13922a.png)

Ohjelmalta voi myös kysyä tietyn kryptovaluutan vaihtosuhdetta euroina, jolloin ohjelma printtaa:

![image](https://user-images.githubusercontent.com/121788922/215993631-ea1aed6b-c694-45cb-926c-e901237289ed.png)

Ohjelma käyttää seuraavia moduuleja:

cryptocompare
pandas
datetime
matplotlib
plotly

Asennus:
!pip install cryptocompare
