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


Prova gärna Kodapans öppna (ASL2) Java GIS-API för OpenStreetMap vid arbete med datasamlingen.
Ytterligare ramverk och verktyg återfinnes på OpenStreetMaps hemsida.

Exempelutdrag från datasamlingen

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


