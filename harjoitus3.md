# Harjoitus 3, Versionhallinta ja MarkDown

**Kurssi:** (http://terokarvinen.com/2020/configuration-managment-systems-palvelinten-hallinta-ict4tn022-spring-2020/

**a) MarkDown. Tee tämän tehtävän raportti MarkDownina. Helpointa on tehdä raportti GitHub-varastoon, jolloin md-päätteiset tiedostot muotoillaan automaattisesti. Tyhjä rivi tekee kappalejaon, risuaita ‘#’ tekee otsikon, sisennys merkitsee koodinpätkän.**

Käyttämiäni ohjeita MarkDownin opetteluun: 
(https://www.markdownguide.org/basic-syntax/)
(https://guides.github.com/features/mastering-markdown/)

Aloitin harjoituksen asentamalla itselleni Gedit-tekstieditorin, jolla päätin kirjoittaa raportin.

’sudo apt-get -y install gedit’

Aloitin raportin kirjoittamisen komennolla ’gedit harjoitus3.md’.

Tämän jälkeen menin GitHubiin (Github.com) tekemään harjoitusta varten uuden repositorion

Uuden repon nimeksi laitoin "harjoitus3ph".Tein repositoriosta julkisen sekä valitsin "Initialize this repository with a README" ja lisenssiksi GNU General Public License.

![1](1.xcf)

Luomisen jälkeen kloonasin uuden repositorioni omalle koneelleni:

’git clone https://github.com/HuoAks/harjoitus3ph’

Komento kopioi koko repositorion käyttäjäni kotihakemistoon.

’cd harjoitus3ph/’

Tässä vaiheessa siirsin raporttini uuteen hakemistooni:

’mv harjoitus3.md harjoitus3ph’

Käytin komentoja’git add .’ ja ’git commit’ tallentaakseni repoon tekemäni muutokset. Tämän jälkeen komennolla ’git push’ lisäsin commitin GitHubiin



