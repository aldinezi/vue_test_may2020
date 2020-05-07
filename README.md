# Izlazni test, Vue.js

# Ime i prezime:

# Pravila:

- vrijeme izrade testa je 2h
- dopušteno je korištenje interneta i slajdova s predavanja
- bilo kakav pokušaj varanja, uključujući prepisivanje od drugih, rezultirat će najstrožim sankcijama
- u folderu mockups se nalaze preporučeni izgled aplikacije kojeg se potrebno strogo držati.
- kvalitetna vizuelna implementacija može donijeti dodatne bodove.

# Zadatak 1.:

Napravite Vue.js aplikaciju koja će sadržati 3 osnovne komponente:

> **Lines komponenta** - komponenta prikazuje listu autobusnih  linija, koje su prethodno dohvaćene i spremljene u store. Klikom na jednu od linija iz liste, naziv linije mora biti označen svijetlo plavom pozadinom i bijelim slovima, a detalji linije prikazani u sljedećoj komponenti.
Listi linija također prikazuje i jedinstvene brojeve linija.


> **Details komponenta** - komponenta prikazuje detalje linije, sve satnice polazaka autobusa uredno prikazane.

Podatke za linije i detalje dohvatiti sa
[https://limitless-chamber-46546.herokuapp.com/]
U Vuex store spremite dohvaćene podatke i koristite u komponentama.
Tip - dohvaćene podatke možete struktuirati, preformatirati, parsirati kako vam najbolje odgovara za implementaciju aplikacije.

(20 bodova)

# Zadatak 2.:

> **Header komponenta**
Komponenta sadrži polje za pretragu liste linija.
Filtriranje linija moguće je u najboljem slučaju da se dešava dok korisnik unosi slova u polje ili tek nakon klika na dugme 'Traži'.

(20 bodova)

# Zadatak 3.:

U header komponenti prikažite select polje u kojem će vrijednosti biti sve moguće satnice polazaka autobusa. Odabirom jedne od satnica, lista linija bi trebala biti prefiltirana, i prikazivati samo one linije koje sadrže odabranu satnicu.

(30 bodova)

# Zadatak 4.:

- U header komponenti dodati checkbox polja kojima je moguće odabrati šta se prikazuje u listi linija i to:
        **stanice polaska,**
        **stanice između polaska i odredišta linije,**
        **odredišne stanice.**
U nazivu stanice prikazati podatke ovisno o označenim checkbox poljima.
Defaultno, svi checkboxi trebaju biti uključeni.

- Omogućiti pretragu samo po polaznoj, stanici između ili odredišnoj stanici, ovisno o uključenom checkboxu.

(30 bodova)
