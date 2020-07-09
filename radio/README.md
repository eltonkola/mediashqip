#qellimi
Ne failin list.json, kemi listen e radiove dhe webradiove publike shqiptare, qellimi eshte qe ata qe manaxhojne radiot dhe programatoret te kene nje pike takimi ku te verifikojne nje liste te vlefshme te dhenash.
Cdo njeri mund ti beje fork projektit dhe perdore ate, per sa kohe respektohet formati mbi te cilin biem dakord me poshte.

## perdorimi i te dhenave si api
Me pas programatoret mund te perdorin kete burim si api duke thirrur adresen:
```
https://raw.githubusercontent.com/eltonkola/mediashqip/master/radio/list.json
```

# formati

formati i radiove eshte:
```
{
    "emri": "TopAlbaniaRadio",
    "pershkrimi": "Alter your existence",
    "streamingUrl": "http://tar.stream.dev.al:9078",
    "logo": "http://www.topalbaniaradio.com/v7/wp-content/themes/top2016/images/logo9.png",
    "faqejaWeb": "http://www.topalbaniaradio.com",
    "webRadio": false,
    "vendi": "Tirane"
}
```


#fushat

```emri```
eshte nje string, duhet te jete emri i sakte i radios

```pershkrimi```
eshte nje string, mund te jete nje moto apo pershkrim i radios

```streamingUrl```
eshte nje string, kjo ehste pjesa me e rendesishme, duhet url streaming funsional, testojeni me pare me vlc nga pc para se ta publikoni ketu, qellimi kryesor i ketij projekti eshte qe cdo maintainer i radiove ti beje update ketyre te dhenave ne menyre autonome

```logo```
logo eshte nje string, mund te jete nje adrese web, ose nje file lokal nen direktorine 'logo', idealja ehste qe imazhi te jete ne kete projekt

```faqejaWeb```
eshte nje string, adresa e faqes web te radios

```webRadio```
eshte nje boolean, nese kjo radio transmeton me vale am/fm lokalisht, apo vetem nje webradio ne internet
  
```webRadio```
eshte nje string, mund te jete qyteti/shteti nga ku kjo radio funsionon

