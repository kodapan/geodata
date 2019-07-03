All geografisk rådata länkat till från denna sida är allmän egendom i enighet med licensen CC0, skapad och samanställd av Kodapan.

# Bakgrundsinformation


Lagringsformatet är s.k. OSM XML, den standard som tagits fram för OpenStreetMap. All metadata följer eller är snarlik de standarder som tagits fram av OpenStreetMap. Fel existerar helt säkert i datamängden och metadatstrukturen komer troligen därför genomgå framtida förändringar. Entitetsidentiteter kommer med all säkerhet ändras i framtida datasläpp, så förlita er i stället på unika nycklar som exempelvis tätortskoder.

Datasamlingen senaste uppdaterad: 2015-06-25

# Filer
Territorial-, län- och kommungränser som OSM-XML: graenser.osm.xml 
Alla namngivna platser, inklusive tätorter som OSM-XML: osm.xml 
Enbart tätorter som OSM-XML: taetorter.osm.xml 

# GeoJSON-derivat
Kommuner (polygoner och kontaktinformation) som GeoJSON: kommuner.geo.json 
Kommuner (polygoner och kontaktinformation) klippta längst kustlinjer som GeoJSON: kommuner-kustlinjer.geo.json 
Län (polygoner och kontaktinformation) som GeoJSON: laen.geo.json 
Län (polygoner och kontaktinformation) klippta längst kustlinjer som GeoJSON: laen-kustlinjer.geo.json 

# Innehåll

* Territorialgränser
* Länsgränser
* Kommungränser
* Ungefärliga mittpunkten till knappt 11 500 namngivna platser:
* Alla SCBs 1956 tätorter
* 1058 av SCBs 2920 småorter
* 3000 ytterligare orter
* 1357 församlingskyrkor
* 434 slott och herrgårdar
* 856 berg och lokala höjder
* 1513 sjöar och vattendrag
* 309 öar och halvöar
* Ytterligare drygt 500 namngivna punkter av diverse slag

Datamängden är primärt kalkerad efter Lantmäteriets översiktskarta i 1:700 000-1:350 000 från 1994, dvs information som sedan 2009 räknas till allmän egendom enligt det s.k. katalogskyddet 49§ i lag 1960:729.

Koordinaterna är uträknade från en manuell rektifiering av ovan nämnda karta och är därför på inget sätt exakta. Det är således möjligt, även om mindre sannolikt, att enstaka koordinater sitter flera kilometer fel.

Delmängder data härstammar från eller är förädlingar av samkörning mot EUs vattenterritorialgränser, Statistiska centralbyrån, Postnummeruppror, WikiData, manuellt utmätta från äldre kartböcker, samt ett antal uppslag mot andra helt licensfria eller CC0-licensierade datakällor.

Datasamlingen släpps under den öppna och fria CC0 i CreativeCommons-familjen av licenser, dvs helt utan restriktioner.

Till skillnad från s.k. BY-licenser är det inga krav på källhänvisning och till skillnad från s.k. SA-licenser är det ingen begränsning på hur du får återpublicera rådatan eller förädlade produkter.

För att ta extremfallet är det tillåtet att sälja denna datasamling till tredje part utan att på något sätt referera till orginalkällan och dessutom ställa krav på hur den tredje parten använder eller återpublicerar data.

# Varför?
Man kan ganska enkelt tänka sig att det skulle bli besvärligt för företagare i Sverige om Trafikverket ställde krav på att varor märks med vilka vägar de fraktats längst, samt alla vägar där man fraktat de saker och personer som på något sätt ligger bakom produktionen av varorna.

Mjölkkartonger skulle inte vara stora nog för få plats med all information om vilka vägar mjölkpaket fraktats till butiker, vägar mjölktankbilen åkt mellan stall och mejeri, vägar kornas mat kom till stallet, vägar mjölktankarna i stallet fraktats dit på från gjuteriet, vägar metallen till mjölktankarna åkte från gruvan till gjuteriet, vägar dynamiten i gruvan fraktades på från kemiföretaget, vägar alla anställda på kemiföretaget körde bil till jobbet, vägar alla bilproducenternas anställda körde till jobbet för att kunna bygga kemiföretagets anställdas bilar, och så vidare i all oändlighet.

Det är naturligtvis fullständigt orimligt att ställa sådana krav.

Tyvärr är det precis så orimliga krav man ställer för dem som vill förädla stora datamängder från många källor vid släpp av öppna data med BY- och SA-licenser. Komplexiteten för att skriva mjukvara och hantera datamänger blir ohanterlig.

Om Sveriges företagare skall fortsätta vara duktiga och innovativa inom informationsteknologi kan vi inte ställa så kontraproduktiva krav på öppna data. Sanningen är att vi redan ligger långt efter på den här fronten. Det är därför som denna datasamling släpps.

De i behov av geodata men som inte har några problem med BY- och SA-licenser hänvisas till OpenStreetMap, vars data är mycket mer precis, detaljerad och uppdaterad.

För mer information kontakta banan@kodapan.se.


Prova gärna Kodapans öppna (ASL2) Java GIS-API för OpenStreetMap vid arbete med datasamlingen. https://github.com/kodapan/osm-common

Ytterligare ramverk och verktyg återfinnes på OpenStreetMaps hemsida. http://wiki.openstreetmap.org/wiki/Frameworks

# Exempelutdrag från datasamlingen

    …
    <tag k='admin_level' v='2' />
    <tag k='name' v='Sverige' />
    <tag k='type' v='multipolygon' />
  </relation>

    …
    <tag k='admin_level' v='4' />
    <tag k='boundary' v='administrative' />
    <tag k='name' v='Skåne län' />
    <tag k='ref:se:län:bokstav' v='M' />
    <tag k='ref:se:län:nummer' v='12' />
    <tag k='type' v='multipolygon' />
  </relation>

    …
    <tag k='admin_level' v='7' />
    <tag k='area:land:km2' v='153.7' />
    <tag k='area:land:km2:source' v='Statistiska centralbyrån' />
    <tag k='boundary' v='administrative' />
    <tag k='name' v='Malmö kommun' />
    <tag k='population' v='245699' />
    <tag k='population:source' v='Statistiska centralbyrån' />
    <tag k='population:source:date' v='1996' />
    <tag k='ref:se:kommun:kod' v='1280' />
    <tag k='ref:se:kommun:kod:1977-1979' v='1280' />
    <tag k='ref:se:kommun:kod:1980-1982' v='1280' />
    <tag k='ref:se:kommun:kod:1983-1991' v='1280' />
    <tag k='ref:se:kommun:kod:1992-1994' v='1280' />
    <tag k='ref:se:kommun:kod:1995-1996' v='1280' />
    <tag k='ref:se:kommun:kod:1997' v='1280' />
    <tag k='ref:se:kommun:kod:1998' v='1280' />
    <tag k='short_name' v='Malmö' />
    <tag k='type' v='multipolygon' />
  </relation>

  <node id='-10047' lat='55.59029766127' lon='13.00766274703' >
    <tag k='name' v='Malmö' />
    <tag k='place' v='city' />
    <tag k='ref:se:kommun:centralort' v='yes' />
    <tag k='ref:se:scb:tätort:kod' v='T3604' />
    <tag k='population' v='270214' />
    <tag k='population:source' v='Statistiska centralbyrån' />
    <tag k='population:source:date' v='2010-12-31' />
  </node>
  
  <node id='-11296' lat='55.54037598237' lon='13.04697644572' >
    <tag k='name' v='Lockarp' />
    <tag k='place' v='hamlet' />
    <tag k='ref:se:scb:småort:kod' v='S3541' />
    <tag k='population' v='54' />
    <tag k='population:source' v='Statistiska centralbyrån' />
    <tag k='population:source:date' v='2010-12-31' />
    <tag k='area:land:km2' v='0.13' />
    <tag k='area:land:km2:source' v='Statistiska centralbyrån' />
    <tag k='area:land:km2:source:date' v='2010-12-31' />
  </node>

  <node id='-8856' lat='67.89960152553' lon='18.43996756825' >
    <tag k='ele' v='2111' />
    <tag k='name' v='Kebnekaise' />
    <tag k='natural' v='peak' />
    <tag k='reg_name' v='Giebnegaisi' />
  </node>

  <node id='-3806' lat='58.95171219559' lon='13.61183054168' >
    <tag k='name' v='Vänern' />
    <tag k='natural' v='water' />
  </node>

  <node id='-5174' lat='61.15550537346' lon='13.12195900406' >
    <tag k='building' v='church' />
    <tag k='name' v='Sälens fjällkyrka' />
  </node>

  <node id='-10586' lat='59.65296800975' lon='17.93262322615' >
    <tag k='aeroway' v='aerodrome' />
    <tag k='name' v='Arlanda' />
  </node>

  <node id='-4917' lat='62.2185728507' lon='12.5053349643' >
    <tag k='name' v='Storrödtjämstugan' />
    <tag k='tourism' v='alpine_hut' />
  </node>


