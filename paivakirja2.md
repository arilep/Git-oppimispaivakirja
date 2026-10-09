# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

## Hajautettu Git
Harjoituksessa 5 ei ollut juurikaan ongelmia. Haarojen hallinnointi oli itselleni kokonaan uutta asiaa. Githubissa minulla onkin entuudestaan liuta repositorioita aiemmilta kursseilta, joten tässä tuli paljon uutta sekä vanhan kertausta. Tehtävän vaiheet olivat selkeitä ja havainnollistivat mitä missäkin tapahtui matkan varrella todella hyvin. 

## Git projektissa
Vaikea osuus tuli harjoituksessa 6, kun ilmeni ongelmia index-sivun näkymässä. Git pull -pyynnöistä huolimatta näkymä ei päivittynyt viimeisimpään versioon (analoginen kello + päivitetty tausta) ja bash kertoi haaran olevan up-to-date. Viimeisintä päivitystä lukuunottamatta kaikki sujui kuitenkin melko jouhevasti. Harjoitus 7 oli suoraviivainen ja käytännönläheinen.

## Osiossa käyttämäni Git-komennot

Täydensin edellistä listaa muutamilla komennoilla joita tuli käytettyä tässä osiossa.

| Komento | Kuvaus |
| --------| ------ |
| git add | Merkitään tiedosto(t) commitia varten | 
| git branch | Näytetään olemassa olevat haarat tai luodaan parametrina annettu uusi haara |
| git clone | Kopioidaan etärepositorio ja sen versionhallintahistoria paikalliseksi repositorioksi |
| git commit | Tallennetaan staging-alueelle tehdyt muutokset paikalliseen repositorioon |
| git fetch | Ladataan tiedot etärepositoriosta paikalliseen repositorioon |
| git init | Alustetaan nykyinen hakemisto Git-versionhallintaan |
| git log | Haetaan commit -talletusten historia |
| git merge | Yhdistetään haara nykyiseen aktiiviseen haaraan |
| git mv | Nimeää tai siirtää tiedoston ja lisää tiedon Git-hallintaan |
| git pull | Suoritetaan 'git fetch' ja 'git merge' |
| git push | Synkronoidaan paikallisen repositorion tiedot etärepositorioon |
| git remote add | Määritetään uusi etärepositorio |
| git reset | Poistetaan git add -komennolla merkitty tiedosto staging-alueelta |
| git restore | Perutaan työtilassa tehdyt muutokset, joita ei ole viety staging-alueelle |
| git revert | Perutaan parametrina annetun commitin muutokset |
| git rm | Poistaa tiedoston työhakemistosta ja Git-hallinnasta |
| git status | Haetaan nykyisen repositorion Git-tila |
| git switch | Vaihdetaan haaraa, -c <uusi-haaran-nimi> luo uuden haaran ja siirtyy siihen |
| git tag | Lisää tag-tunnisteen nykyiseen commitiin |