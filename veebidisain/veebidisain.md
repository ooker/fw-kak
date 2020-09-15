| chapter: Sissejuhatus
| section: Avaleht
| cols: 1fr 2fr
| rows: 10vh auto
| 1 1
| 2 2
| 3 4

-


<h1 style="--base:1.5vw;">&lt;veebi&shy;disain/&gt;</h1>

##### väike sissejuhatus teemasse: pisut tööprotsessist, prototüüpimisest, töövahenditest jne

&nbsp;

-

&nbsp;

<f-next-button title="Hakkame siis pihta"  />

-

~PS: Vahel on jätkamiseks tehtud kenasti nupp nagu siin, aga teinekord pole seda viitsitud panna. Erinevate teemade vahel saab liikuda veel vasakul menüüst või lihtsalt klaviatuuri nooleklahvide <kbd>vasak</kbd> / <kbd>parem</kbd> abil. Sama rolli täidavad ka üleval paremas nurgas olevad <f-leftarrow-icon /> <f-rightarrow-icon /> noolekesed. Proovi järgi, mine järgmisele lehele, siin pole enam midagi passida.~
    




---










| section: Mis?
| rows: 15vh auto
| 1 2
    
## Mis värk on?

Meie teema nimi tunniplaanis on <var>veebidisain</var>, aga see on võib-olla pisut eksitav. Kindlasti ei peaks me siin ainult veebi või veebilehti silmas pidama, ehkki ka need on kindlasti täna kõige tavalisemad või tihedamini ette tulevad <var>kasutajaliidesed</var>. 

### Kasutajaliides *(user interface)*

Kui pisut üldistada, siis võiksimegi me rääkida **kasutajaliideste disainist**. Kasutajaliides on siis ühenduslüli mingi seadme või teenuse ja selle kasutaja vahel. Kasutajaliides ei pea olema tingimata ekraanil. Võib olla ka <f-link to="https://www.carui.info/about/">**auto armatuurlaud**</f-link> või **vetsupoti juhtimiskeskus** nagu me näeme juuresoleval pildil. 

Meie keskendume siin peamiselt siiski **digitaalsete kasutajaliideste** tegemisele - olgu see siis mõni **mobiilirakendus**, **veebileht**, **mäng** või midagi muud taolist.

-

<f-image src="https://upload.wikimedia.org/wikipedia/commons/8/83/Wireless_toilet_control_panel_w._open_lid.jpg" style="height:80vh" />

<small>Jaapani WC-poti kasutajaliides. Kas julgeksid seda punast nuppu potil istudes vajutada?</small>

---









| chapter: Planeerimine ja kavandamine
| section: Miks?

## Planeerimine ja kavandamine

Enne kui disainiprogrammist puhast ilu voolama või lausa koodiveskid jahvatama hakkavad, tuleks korra maha istuda ja pireke aru pidada. 

### Aga miks?

Sest targad mehed ja naised on öelnud umbes nii, et 

<blockquote style="margin:5vh 0">

#### 📌 *Mida <u>varem me tehtud vea avastame</u>, seda lihtsam hiljem selle parandamine on.*

</blockquote>

Väga lihtne mõte. Siin kõrval on foto ühest kenast noorest mehest kes tegi oma elu jooksul päris hullu pahandust. Kui see "viga" oleks varakult avastatud, oleks suure osa maailma ajalugu hoopis teistsugune. Kas sa tead, kes see tore poiss on?

<details>

<summary>Kliki siia, leiad vastuse</summary>
  
Kui 1922. aastal oleks keegi Stalini maha võtnud, ei teaks me täna temast suurt midagi. Stalin oli üsna tähtsusetu tegelane süsteemis. Aga katsu tast näiteks kümme aastat hiljem, 1932. aastal, jagu saada - no kus sa enam, hea kui ise puhta nahaga pääsed. 

</details>

Vigadega disainis ja arenduses on täpselt samamoodi - mõni on lihtne parandada ja midagi ei juhtu, teine võib istuda nii sügaval süsteemis sees, et välja juurimine paneb kõik muu ümberringi ka võnkuma. Mida varem me ta kätte saame, seda parem. Ja odavam.  

### Mida siis teha?

Nagu öeldud, tuleks korra maha istuda ja pireke aru pidada, et pahandust ei tuleks. Järgnevalt vaatamegi, mida ette võtta.

-

<f-image src="https://media.snl.no/media/37666/standard_Stalin.jpg" style="min-height: 70vh; height: 85vh; position:sticky; top:15vh;" />

---










| section: Kuidas alustada?
| cols: 3fr 2fr
| 1 1
| 2 2
| 3 4
| 5 6
| 7 8
| 9 10
| 11 12

## Millest võiks pihta hakata?

&nbsp;

-

**Esimese asjana paneme kõik kirja, mida me asjast teame:** olgu see siis kliendilt tulnud ülesandepüstituse ehk <var>briifi</var> põhjal või meie endi välja mõeldud rakendus, paneme lihtsalt kirja kõik, mis seal toimuma peaks. 

Käisime tunnis näitena läbi lillepoe rakenduse, kus esmane briif oli väga napp: **kasutajal on võimalus saata sõbrapäevaks kallimale lilled koos sõnumiga**.

&nbsp;

Loomulikult ei ole see üks lause piisav info, et tööga pihta hakata. Seega esimene oluline soovitus olekski:

-

#### 1. Täpsusta vajadusel lähteülesannet

Klient võib olla kas liiga väheste või hoopis liiga suurte kogemustega - tema jaoks võivad olla mingid asjad nii iseenesest mõistetavad, et tal ei tule pähegi meile seda edasi öelda. Seega peaksime meie asju üle küsima. Enne põhjalikult ülesandest aru saamist ei saa projekti vastu võttagi - me ei tea, kas üldse oskame seda lahendada, mis ajakulu võiks olla jne, seega tõenäoliselt ei oska me veel isegi adekvaatset hinnapakkumist teha.

-


<blockquote>

### 🙋‍♀️<sup><sup>💬</sup></sup>

##### ~*Kõige rumalam küsimus on see, mis küsimata jääb.*~
<small>*O. Maaker, 2020*</small>

~<small>Koolis on su "kliendiks" tihti õpetaja, töökohal võib olla selleks näiteks projektijuht või kogenum kolleeg. Ka õpetaja või kolleegide käest tuleb küsida küsimusi, seni kuni on selge, mida su käest tahetakse saada.</small>~

</blockquote>

-

#### 2. Pane kõik kirja

Tavaline list või nimekiri on alustuseks täiesti ok. Jah, see sama, et kirjutad kõik olulised märksõnad lihtsalt eraldi välja koos kommentaaride ja küsimustega. Tuletame meelde oma lillepoe rakendust. Millest seal juttu oligi? **Proovi esmalt meelde tuletada**, siis vaata järgi. 

<details>

<summary>Ok, kliki teemad lahti</summary>

Peamised nn "suured teemad" või märksõnad olid:

- Lilled
- Sõbrapäev
- Sõnumi lisamine
- Saatmine

</details>


Need on sellised esmased märksõnad või tegelikult meie rakenduse peamised <var>funktsionaalsused</var>, mis **tulenesid otseselt** sellest esimesest lausest. Samas on tihti **varjatud küsimusi või funktsioone**, mis tuleks samuti kaardistada. Püüame seda esimest lühikest nimekirja pisut lahata ja vaadata, mis on täpsemalt iga märksõna taga. 

<f-inline>

### ✍&nbsp;&nbsp;
    
Proovi paberile panna **täiustatud variant esimesest nimekirjast** koos endapoolsete tekkinud küsimuste ja kommetaaridega. Need võivad olla nii sisulised kui tehnilised jne. Kui võimalik, siis juba natuke struktureeritult - et on peateemad ja selle all alamteemad või -küsimused. Lase pilk teemadest üle. Mida veel küsima peaks? Valesid küsimusi ei ole. 

</f-inline>

<details>

<summary>Siin on peidus üks näidis. Aga proovi enne ise ka.</summary>

&nbsp;

- **Lilled**
    - mis lillesordid (kas on valik)? No ilmselt peaks?
    - kas saab lihtsalt valida erinevaid lilli või ise kokku panna kimpe?
        - kimpude kokku panemisega tekiks arenduses palju uusi küsimusi, võimalusel jätta tulevikku
    - mitu tükki (kas kasutaja saab valida hulka)?
        - ilmselt peab olema kindlasti sees - kasvõi teenuse hind oleneb ju sellest
        - palju üldse poes lilli tagavaraks on? Kas kasutaja peaks nägema, kui palju on max lillede arv, mida ta saata saab? ilmselt vist peaks? 
        - kuidas uuendada saatmise hetkel? 
            - mis siis kui keegi tellib vahepeal 300 roosi ja kõik roosid saavad otsa kuni ma hoolikalt 4 tundi oma armsamale armastussõnumit koostan?
            - kas ma alguses valin lillede hulga ja nagu broneerin endale sellega need lilled? 
                - Kui kaua see broneering peaks kehtima? Äkki broneeritakse 100 õit, aga kunagi ära ei saadeta? Samas süsteemi jaoks oleksid need lilled "kinni". Kui kaua? Kuidas lahendada? Lilled närtsivad.
- **<s>Sõbrapäev</s>** ?
    - äkki pole üldse vahet, mis tähtpäevaks? Rakendust muuta üldisemaks - lihtsalt sõnumiga annab igaüks edasi, mis sündmuseks see kimp mõeldud on? Äkki võib sõbrapäeva listist üldse maha võtta? Vajab kliendiga täpsustamist? Samas tihti ongi hea alustada ühest väga konkreetsest asjast ja siis täiendada.
- **Saatmine**
    - **Kellele saadetakse**
        - Nimi 
        - Aadress
            - Kuidas lahendada? Mingi väline API või teenus, mis aitab aadressi leida, kui tänavat vms vormi kirjutama hakkad? Mingi kaardilahendus? Tuleb uurida tehnilisi võimalusi.
        - **Sõnumi lisamine:** Saatja saab lisada lilledele sõnumi (kaardikese?)
            - oletame et esialgu ei saa valida kaarti, fonti, kujundust vms
                - kujundusvalikud v 2.0 
            - Ainult tekst?
            - Kui pikk maksimum?
            - Midagi veel?
        - Email või telefon?
            - Mis lillede saaja andmed on kohustuslikud? Mis on miinimum hulk andmeid, millega teenust osutatakse?
        - Kas saatja teab saaja andmeid? 
        (Näide:  Onu Roobertile meeldib kena proua raamatukogust ja tahaks talle lilli saata. Ta teab, kus proua töötab, aga ei tea nime, telefoni, meili, mitte midagi. Kas sellest piisab? Kuidas tagada, et lilled kohale jõuavad? Töökoha aadress on olemas, muud mitte. Mis peaks olema miinimumandmed?) (PERSONAD)
    - **Kes saadab**
        - mis on miinimumandmed et teenust osutada? 
            - Nimi? 
            - e-mail
            - telefon
        - Kui palju infot me saame maksmisel nagunii kätte? Mis näiteks pangalingi kaudu meile edastatakse?
            - järgi uurida 
- **Maksmine**
    - Konkreetsed makselahendused olenevad kliendi vajadustest ja võimalustest, seega on siin raske variantide üle fantaseerida. St teema vajaks veel edasist täpsustamist. 
    - Peaksime olema valmis pakkuma välja mingeid lahendusi: 
        - pangalink 
        - mis muud teenused?

</details>

Esmapilgul lihtne ülesandepüstitus võib tekitada väga palju lisaküsimusi.


-

<f-image src="./img/list.gif" style="--image-height:85vh; position:sticky; top:5vh;" />

-

&nbsp;

#### 3. <var>Mõttekaart</var> e. <var>mind map</var> 

Eelmist pikka nimekirja on tegelikult üsna tülikas hallata - raske on juppe vahelt ära võtta, lisada või ringi tõsta. Kui me kirjutaks iga teema eraldi paberile, oleks juba palju lihtsam. Tere tulemast, Post-it lipikud, magnetid ja knopkad! 

Sellist grupeeritud ja struktureeritud mõtete pilve nimetatakse **mõttekaardiks** ehk *mind mapiks* - väga paljudele on see vast nagunii juba tuttav tööriist.

Nüüd on meil palju lihtsam asju omavahel ringi mängida.

Taolisi info struktureerimise ja kaardistamise meetodeid ja töövahendeid on muidugi veel, aga lihtsuse mõttes piirdume siin praegu mõttekaardiga. Ja tihti sellest ka piisab.

-

<f-image src="./img/mindmap.gif" style="--image-height:70vh" />


-

#### 4. Mis vaated meil tekivad?

Kõik need peamised funktsionaalsused vajavad mingit **kasutaliidese vaadet**: näiteks lillede saaja andmete jaoks peab olema vaade või vorm väljadega, mida saaks infoga täita (nimi, aadress, telefon jne).

Järgmine samm olekski eelneva nimekirja põhjal välja mõelda, mis vaated meil on ja millest nad peaks koosnema, et kõik punktid nimekirjast oleksid täidetud.

Ikka lihtsalt paberi ja pliiatsiga.

<blockquote>

#### 📱 Mobile first!
    
Kuna mobiiltelefonidel on vaateväli väiksem ja seega ei saa sealsed vaated olla väga keerulised, alustatakse tänapäeval enamasti **esimesena mobiilivaadetega**. Hiljem on lihtsast keerulisemaks kergem üle minna kui vastupidi.

</blockquote>

Tasapisi olemegi liikumas nüüd tavaliste nimekirjade juurest spetsiifilisemate kasutajaliideste kavandamise rakenduste juurde:

<f-next-button title="Järgmiseks: Prototüübid" />

-

<f-image src="./img/views.gif" style="--image-height:70vh" />

---











| section: Prototüübid
| cols: 1fr 1fr

## Proto&shy;tüüp?

Wikipedia ütleb:

<blockquote>
    
<var>Prototüüp</var> 
on kontseptsiooni või protsessi testimiseks ehitatud esialgne proovtoode, mudel või versioon.

</blockquote>

Niisiis, mudel või prooviversioon - midagi, mis oleks juba kasutatav, aga mille loomiseks ei kulu sama palju aega, raha, jne kui valmis rakenduse tegemiseks. Kõrval pildil on näiteks varajase Macintoshi prototüüp.

#### Miks?

Sellest on eespool juttu ja vahepeal pole midagi muutunud: **et meie planeeritud head ja vead võimalikult vara üles leida.**

#### Kuidas?

Esialgu ikka samamoodi - pliiatsi ja paberiga.

&nbsp;

<f-next-button title="Järgmine: Paberprototüübid" />

-

<f-image src="https://upload.wikimedia.org/wikipedia/commons/5/5c/Early_Macintosh_Prototype_Computer_History_Museum_Mountain_View_California_2013-04-11_23-45.jpg" style="--image-height:80vh; --image-position:center center; --image-size:cover;" />

<small>Pilt: <a href="https://commons.wikimedia.org/wiki/File:Early_Macintosh_Prototype_Computer_History_Museum_Mountain_View_California_2013-04-11_23-45.jpg" title="via Wikimedia Commons">User:Victorgrigas</a> / <a href="https://creativecommons.org/licenses/by-sa/3.0">CC BY-SA</a></small>

---







| section: Paberprototüüp
| 1 1
| 2 4
| 3 4
| 5 6

## Paber&shy;prototüüp

&nbsp;

-

Jälle Wikipediast:

<blockquote>

<var>Paberprototüüp</var> on tarkvaratoote kasutajaliidese trükitud või käsitsi joonistatud kujundus. Selliseid prototüüpe kasutatakse tavaliselt tarkvara disaini varaseks testimiseks ning see võib olla osa tarkvara loomisel disainilahenduste otsuste kinnitamiseks enne kõige kulukamate projekteerimisetappide läbimist.

</blockquote>

-

"Ok, aga seda paberi asja me just ju tegime?!?" ütled sa. Mitte päris. Või noh, enamvähem... Käiks siiski veel läbi mõne lisanipi, mis meid päris prototüübini juhataksid.


#### 1. Abivahendid

Esmalt võiks mainida välja prinditavaid seadmete raame, mis annaksid nüüd meile juba selgemad proportsioonid kui niisama käsitsi tõmmatud kastikesed. Neid leiab veebist. Mõned näited:

<f-link to="https://www.sketchize.com/">Sketchize</f-link>
<f-link to="https://sneakpeekit.com/">Sneakpeekit</f-link>
<f-link to="https://sketchsheets.com/">Sketchsheets</f-link>

-

<f-image src="./img/paper-template.png" style="--image-size:contain" />

-

&nbsp;

#### 2. Modulaarsus

Kas mäletad, mis vahe oli pikal nimekirjal ja mõttekaardil? 

Mõttekaart koosnes mugavamalt muudetavatest osadest - <var>moodulitest</var> või <var>komponentidest</var> (need postIT-id ja muu mudru). Me saame **sama teha ka prototüübi puhul** kui joonistame oma **kasutajaliidese komponendid** (menüüd, nupud, pildid, teated jne) õiges suuruses paberile ja **lõikame välja**. Nii saame me kokku kombineerida ja proovida erinevaid vaateid ilma neid pidevalt ümber joonistamata. 👍

-

<f-image src="./img/paper-prototype.gif" style="--image-height:60vh" />

<small><a href="https://commons.wikimedia.org/wiki/File:Paperbasedprototype5.jpg" title="via Wikimedia Commons">Samuel.mann at English Wikibooks</a> / <a href="https://creativecommons.org/licenses/by-sa/3.0">CC BY-SA</a></small>

---








| section: Paber ärkab ellu!
| cols: 2fr 3fr
| 1 1
| 2 3
| 4 5

## Interaktiivsus

&nbsp;

-

Lihtsalt pildist eristab korralikku prototüüpi <var>interaktiivsus</var> - reageerimine kasutaja tegevustele (klikk, tap, swipe, häälkäsklus vms). Enamasti **vahetub kasutaja käsu peale üks vaade teisega** või **muutub mingi omadus** (näiteks heli läheb valjemaks). Kuidas seda teha paberile joonistatud piltidega? 

Kõrval on video, kust on näha korralikku paberprototüübi <var>kasutajatesti</var> - kasutaja püüab täita talle ette öeldud toiminguid ja keegi abiline tekitab "interaktiivsuse", st liigutab erinevaid väljalõigatud komponente ja vaateid edasi-tagasi vastavalt kasutaja toimingutele. Kõik see filmitakse üles ja analüüsitakse hoolega läbi - kus kasutaja jäi hätta, kus ta kõhkles, aga ka seda, mis hästi läks.

Siis tehakse muudatused ja testitakse uuesti. 🤯

-

<div class="video-responsive">
    <iframe src="https://www.youtube.com/embed/Car4IlhY3_0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen ></iframe>
</div>

-

&nbsp;

### Kas lihtsamini ei saa?

<img alt="POP logo" src="data:image/png;base64,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" style="max-width:300px; margin:3vh 0">

Saab küll. Lihtsamate prototüüpide puhul tasub alustuseks proovida mobiiliäppi Marvel POP, mille <f-link to="https://marvelapp.com/pop">leiab siit</f-link>

Asi töötab väga lihtsalt: me saame selle rakendusega oma paberprototüübi vaated üles pildistada ja lisada sinna nö "nupud", millele vajutades erinevad vaated ja komponendid vahetuvad. Peaaegu nagu päris juba.

-

<div class="video-responsive">
    <iframe src="https://www.youtube.com/embed/m3tNSZZgAwM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen ></iframe>
</div>

---








| chapter: HI-FI prototüübid
| section: Prototüüpimiskeskkonnad

Siit läheb ehk kunagi edasi...

---



<!--  

section: Figma

Siin hakkame Figmaga pihta...

---





chapter: Disainiteooria
section: Kompositsioon

kompa (joondus ka?)

---




section: Grid

Grid

---





section: Värv

Värv

---




section: Tekstid

Veebitüpost

---






chapter: Graafilised jubinad
section: Pikselgraafika

failitüübid, pilditöötluse alused

---





section: Vektorgraafika

svg, vektorgraafika alused

---

-->
