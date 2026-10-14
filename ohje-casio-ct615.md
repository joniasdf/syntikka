# Ohje: Casio CT-615 ja Syntikkapeli

## Tietoa soittimesta
- Casio CT-615 (Tone Bank, n. 1990): **61 täysikokoista kosketinta**, ei kosketusherkkyyttä, 210 soundia, 20 rytmiä, 10-ääninen polyfonia, yksi kaiutin.
- Alue: C–C, 5 oktaavia. Pelissä vastaa MIDI-nuotteja **C2–C7** (keski-C = C4 on 25. kosketin vasemmalta).
- **Ei MIDI-liitäntää** (ei MIDI OUT -DIN-liitintä eikä USB:tä). Siksi soitettuja nuotteja ei voi lukea kaapelilla.
- Koskettimiston leveys (koskettimien alue, ei koko kotelo): **835 mm (mitattu)**, 36 valkoista kosketinta × n. 23,5 mm. Koko soittimen leveys on myyjien mukaan n. 91 cm (36″). **Mittaa oma soittimesi**: alimman C:n vasen reuna → ylimmän C:n oikea reuna.
- Transponointi: en löytänyt varmaa tietoa – katso soittimen paneelista. Jos käytät transponointia, aseta se pois (0), jotta nuotit vastaavat ruutua.

## 1. Yhdistäminen tietokoneeseen
Koska MIDI:ä ei ole, vaihtoehtoja on kolme:
1. **Mikrofoni (suositus)**: Syöte → *Mikrofoni* → *Käynnistä mikrofoni*. Selain kysyy luvan. Peli tunnistaa soitetun nuotin äänestä.
   - Toimii parhaiten **yksittäisillä nuoteilla** (melodia). Sointutunnistus on kokeellinen.
   - Käytä **odotustilaa**: peli odottaa kunnes oikea nuotti kuuluu.
   - Säädä *Herkkyys (kohinaportti)*: nosta, jos taustamelu laukaisee nuotteja; laske, jos soitto ei rekisteröidy.
   - *Viiveen kompensointi* (n. 80–150 ms) korjaa mikrofonin ja tunnistuksen viiveen pisteytyksessä.
   - Parempi tulos: kytke CT-615:n **kuuloke-/PHONES-lähtö** kaapelilla tietokoneen mikrofoni- tai linjatuloon (3,5 mm tai 6,3 mm → 3,5 mm -kaapeli, tai USB-äänikortti). Silloin ympäristön melu ei häiritse.
   - Valitse CT-615:ssä selkeä soundi (esim. piano tai urut); efektit ja rytmit pois.
2. **Ilman tunnistusta**: tila *Kuuntele* (peli soittaa ja näyttää) tai *Odotustila* tietokoneen näppäimistöllä.
3. **Tietokoneen näppäimistö**: Syöte → *Näppäimistö*.

(Jos myöhemmin hankit MIDI-soittimen: USB-MIDI toimii suoraan; pelkkä DIN MIDI OUT vaatii USB-MIDI-sovittimen. MIDI-kanava: peli kuuntelee kaikkia kanavia.)

## 1b. Tunnistustesti
Paina asetusten yläosassa **🎯 Tunnistustesti** ennen soittamista:
1. **Hiljaisuus** – 2 s taustamelun mittaus, ehdottaa kohinaportin.
2. **Vapaa testi** – näyttää tunnistetun nuotin, taajuuden, virityksen (senttiä) ja äänitason ("Ei ääntä" / "Liian hiljaa" / "Tunnistettu: X").
3. **Ohjattu testi** – soita korostetut nuotit yksi kerrallaan; tulokset oikein / väärin / oktaavivirhe.
4. **Rytmitesti** – soita kun ympyrä välähtää; mittaa viiveen.
5. **Yhteenveto** – tarkkuus %, viive ja **Käytä suositusasetuksia** (kohinaportti, viiveen kompensointi, sointutunnistus pois).

## 2. Selain
- Käytä **Chromea tai Edgeä**. Avaa `index.html` ja salli **mikrofoni** (tai MIDI) kun selain kysyy.
- Paina **⛶ Koko näyttö** – mittojen laskenta on tarkin koko näytön tilassa.

## 3. Sijoittelu
- Aseta näyttö/TV **suoraan syntikan taakse/yläpuolelle**, niin että ruudun alareuna on mahdollisimman lähellä koskettimia. Jos näyttö on syntikan alla (esim. pöydällä tabletti), valitse *Koskettimisto ylhäällä (nuotit nousevat)*.
- Näytön ja koskettimien tulee olla samansuuntaiset, ja katso ruutua suoraan edestä.

## 4. Pika-asetus
1. **Näytön koko**: lävistäjä tuumina + kuvasuhde (yleensä 16:9) tai mittaa näkyvän kuva-alan leveys.
2. **Syntikka**: valitse *Casio CT-615*. Tämä asettaa 61 kosketinta, alueen C2–C7, leveyden 83,5 cm (mitattu) ja mikrofonisyötteen. Korjaa leveys omalla mittauksellasi.
3. **Siirtymä**: mittaa etäisyys **näytön kuva-alan vasemmasta reunasta** syntikan **alimman koskettimen vasempaan reunaan** (negatiivinen, jos kosketin on kuvan vasemman reunan vasemmalla puolella).
4. Varmista, että *Käytä fyysisiä mittoja* on päällä.

## 5. Hienosäätö
- Avaa *Hienosäätö (kalibrointi)* → *Kalibrointitila*. Raahaa koskettimistoa (vaaka = siirto, Shift+raahaus = leveys) kunnes ruudun koskettimet ovat oikeiden kohdalla. Huom: Pika-asetuksen muuttaminen laskee arvot uudelleen.

## 5b. Kuvakalibrointi (vaihtoehto mittaamiselle)
1. Paina *Kuvakalibrointi → Näytä kuvio*: ruudulle tulee neljä värillistä kulmamerkkiä.
2. Ota puhelimella kuva edestä niin, että koko näyttö ja koko syntikka näkyvät.
3. Lataa kuva (*Lataa kuva*). Peli etsii merkit ja koskettimiston ja näyttää sinisen esikatseluviivan.
4. Jos tunnistus menee pieleen, paina *Klikkaa reunat itse* ja klikkaa alimman koskettimen vasen ja ylimmän oikea reuna. Sitten *Hyväksy*.
- Toimii parhaiten kun kuva otetaan suoraan edestä ja koskettimisto on lähellä näytön alareunaa. Kirkkaat heijastukset näytössä haittaavat tunnistusta.

## 6. Suositellut ääniasetukset
- **Selaimen ääni pois**: Äänenvoimakkuus 0 – käytä CT-615:n omaa ääntä. Mikrofonia käytettäessä tämä on välttämätöntä, muuten peli kuulee omat äänensä.
- *Toista toinen käsi automaattisesti* kannattaa ottaa pois mikrofonin kanssa (tai pidä äänenvoimakkuus 0).
- Aloita helpoista kappaleista (★) ja hitaalla tempolla (0,5–0,7).

## Lähteet
- Wikipedia: List of Casio keyboards (CT-615, 1990, 61 kosketinta, 210 soundia, ei MIDI-merkintää)
- pianoandsynth.com – Casio CT615 (61 full size keys, ei kosketusherkkyyttä, 10 ääntä polyfoniaa)
- Gearspace-keskustelu "Who knows the Casio CT615/640?" (CT-640:ssä on MIDI, CT-615:ssä ei)
- WorthPoint-myynti-ilmoitus (61 kosketinta, yksi kaiutin, n. 36″ pitkä)
